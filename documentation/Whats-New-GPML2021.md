# About GPML2021

### What's new? 
* [Streamlined Annotations and Citations &#9312;](#annotation)
* [New Evidence Code &#9313;](#evidence)
* [Updated Extensible Type Definitions &#9450;](#type)
* [New Interaction Panel &#9314;](#interaction-panel)
* [DataNode Type Alias and Attribute ElementRef &#9315;](#type)
* [States Nested in DataNodes &#9316;](#state)
* [Pathway Author Element &#9317;](#author)
* [Graphics Customization &#9450;](#graphics)
* [Xref DataSource as Compact Identifier Prefix &#9318;](#datasource)
* [Merged Group GroupId and GraphId &#9319;](#groupid)
* [Removed Unused Elements and Attributes &#9450;](#removed)
* [Modified Schema Format and Structure &#9450;](#structure)

<div>
<p align="center">
  <img name ="map" width="95%" src="gpml2021_schema_diagram.svg">
  <br>
  <em>Figure 1: GPML2021 Schema Diagram</em>
</p>
</div>

<div>
<h3 name="annotation">Streamlined Annotations and Citations <a href="map">&#9312;</a></h3>
</div>

In GPML2021, Annotation and Citation replaces Biopax OpenControlledVocabulary and PublicationXref respectively. An Annotation has elementId, value, type (e.g. Ontology). Annotation optionally contains Xref and url. Citation has elementId, Xref, and optionally url. From a Citation Xref all information about a publication can be found. Therefore, publication details (e.g. author, title) are not written in GPML2021. 

*Example of GPML2013a OpenControlledVocabulary compared with GPML2021 Annotation:* 

GPML2013a OpenControlledVocabulary
```
<Biopax>
    <bp:openControlledVocabulary xmlns:bp="http://www.biopax.org/release/biopax-level3.owl#">
        <bp:TERM xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#" rdf:datatype="http://www.w3.org/2001/XMLSchema#string">thyroid cancer</bp:TERM>
        <bp:ID xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#" rdf:datatype="http://www.w3.org/2001/XMLSchema#string">DOID:1781</bp:ID>
        <bp:Ontology xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#" rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Disease</bp:Ontology>
    </bp:openControlledVocabulary>
    ...
</Biopax>
```
GPML2021 Annotation and AnnotationRef
```
<Annotations>
    </Annotation>
        <Annotation elementId="a2" name="thyroid cancer" url="https://identifiers.org/DOID:1781" type="Disease">
        <Xref identifier="1781" dataSource="DOID"/>
    </Annotation>
</Annotations>

<AnnotationRef elementRef="a2"/>	
```
*Example of GPML2013a PublicationXref compared with GPML2021 Citation:* 

GPML2013a PublicationXref and BiopaxRef
```
<Biopax>
    <bp:PublicationXref xmlns:bp="http://www.biopax.org/release/biopax-level3.owl#" 
        xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#" rdf:id="cbc">
        <bp:ID rdf:datatype="http://www.w3.org/2001/XMLSchema#string">7730304</bp:ID>
        <bp:DB rdf:datatype="http://www.w3.org/2001/XMLSchema#string">PubMed</bp:DB>
        <bp:TITLE rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Isotopomer analysis of citric acid cycle and 
        gluconeogenesis in rat liver. Reversibility of isocitrate dehydrogenase and involvement of ATP-citrate lyase in 
        gluconeogenesis.</bp:TITLE>
        <bp:SOURCE rdf:datatype="http://www.w3.org/2001/XMLSchema#string">J Biol Chem</bp:SOURCE>
        <bp:YEAR rdf:datatype="http://www.w3.org/2001/XMLSchema#string">1995</bp:YEAR>
        <bp:AUTHORS rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Des Rosiers C</bp:AUTHORS>
        <bp:AUTHORS rdf:datatype="http://www.w3.org/2001/XMLSchema#string">Di Donato L</bp:AUTHORS>
        <bp:AUTHORS... 
    </bp:PublicationXref>
    ...
</Biopax>

<BiopaxRef>cbc</BiopaxRef>
```
GPML2021 Citation and CitationRef
```
<Citations>
    <Citation elementId="cbc" url="https://identifiers.org/pubmed:7730304">
        <Xref identifier="7730304" dataSource="pubmed"/>
    </Citation>
    ...
</Citations>

<CitationRef elementRef="cbc"/>
```
AnnotationRef has elementRef which refers to the elementId of its parent Annotation. AnnotationRef can optionally have CitationRefs and EvidenceRefs which refer to Citations and Evidences which support the Annotation. CitationRef has elementRef which refers to the elementId of its parent Citation. AnnotationRef and CitationRef are grouped in CommentGroup along with Comment, Property, and [EvidenceRef](#evidence). DataNodes, States, Interactions, GraphicalLines, Labels, Shapes, and Groups all have CommentGroup. Therefore, in GPML2021, individual Pathway Elements can have AnnotationRefs and CitationRefs.  This improves upon GPML2013a in which Annotations/OpenControlledVocabulary could only be linked to the pathway and not to individual pathway elements.   


<h3 name="evidence">New Evidence Code <a href=#map>&#9313;</a></h3>


New elements Evidence and EvidenceRef (reference to an Evidence) are introduced for the annotation of Evidence Codes. An Evidence will have elementId and Xref for the [Evidence Code Ontology](https://evidenceontology.org/). Evidence can also optional have a term/text value and an url link. EvidenceRef has elementRef which refers to the elementId of its parent Evidence. The Pathway can have a list of Evidences. Pathway, DataNode, State, Interaction, and Group can have EvidenceRef. EvidenceRef can also be nested in an AnnotationRef element. 

*Example for Evidences*
```
<Evidences>
    <Evidence elementId="evd" value="experimental evidence" url="https://identifiers.org/ECO:0000006">
        <Xref identifier="0000006" dataSource="ECO"/>
    </Evidence>
    ...
</Evidences>
```
<h3 name="type">Updated Extensible Type Definitions <a href=#map>&#9450;</a></h3>

New categories for DataNode (Molecules vs. Concepts), State, Group, and Annotation types are defined. As well as enumeration types for connectorType, StyleType, and Anchor shapeType. All Types are extensible with type string.  

| DataNode type       |              |State type              | Group type      | Annotation type     |
| :---                | :---         |:---                    | :---            |:---                 |
| Undefined (default) |              |Undefined (default)     | Group (default) | Undefined (default) |
| ***Molecules:***    | ***Concepts:***|Protein modification  | Complex       | Ontology            |
| GeneProduct         | Pathway      |Genetic variant         | Pathway         | Taxonomy            |
| DNA                 | Disease      |Epigenetic modification | Analog          | Interaction type    |
| RNA                 | Phenotype    |                        | Paralog         |                     |
| Protein             | Alias        |                        |                 |                     |
| Complex             | Event        |                        |                 |                     |
| Metabolite          |              |                        |                 |                     |


| ConnectorType      | Line/BorderStyle) |  Anchor shapeType  |
| :---               | :---              | :---               |
| Straight (default) | Solid (default)   | Square (default)   |
| Elbow		           | Dashed            | Circle             |
| Curved             | Double            | None               |
| Segmented          |                   |                    |

Additionally, LineStyle "Double" and CellularComponent shapeTypes enumeration types are cleaned up so that such information no longer needs to be stored in key-value pair Property.  


<h3 name="interaction-panel">New Interaction Panel <a href=#map>&#9314;</a></h3>


A new Interaction Panel (Interaction or Line arrowHead type) is introduced. ArrowHead type is extensible and plugins will be available for: 
* Molecular Interaction Map (MIM) 
* Systems Biology Graphical Notation (SBGN)


| ArrowHead type|
|:---|
|Undirected relationship(default)|
|Directed relationship|
|Conversion|
|Inhibition|
|Catalysis|
|Stimulation|
|Binding|
|Translocation|
|Transcription-translation|


<h3 name="elementref">DataNode Type Alias and Attribute ElementRef <a href=#map>&#9315;</a></h3>

An Alias for a Group can be represented by a DataNode with type="Alias" and elementRef referring to the elementId of the parent Group. 

*Example of a Group and DataNode Alias:* 
```
<DataNode elementId="c27d1" elementRef="d4107" textLabel="Alias_for_abc" .../>

<DataNode elementId="ed3f8" textLabel="DataNode" type="GeneProduct" groupRef="d4107"  .../ >

<Label elementId="e180c"  textLabel="group_abc" groupRef="d4107".../>

<Group elementId="d4107" style="Complex".../>

```
Nested Groups are also possible by utilizing DataNode as Aliases.  

*Example of Nested Groups and DataNode Aliases:* 
```
  <DataNode elementId="a1" elementRef="efg" textLabel="Alias_for_efg" />
  <DataNode elementId="a2" elementRef="abc" groupRef="efg" textLabel="Alias_for_abc" />
  <DataNode elementId="a3" elementRef="abc" textLabel="Alias_for_abc" />

  <DataNode elementId="n1" groupRef="abc" textLabel="DataNode;" type="GeneProduct" .../>
  <DataNode elementId="n2" groupRef="efg" textLabel="DataNode;" type="GeneProduct" .../>
  <Label elementId="n3" groupRef="abc" textLabel="group_abc" .../>
  <Label elementId="n4" groupRef="efg" textLabel="group_efg".../>

  <Group elementId="abc" Style="Complex" textLabel="GroupABC" groupRef="efg" />
  <Group elementId="efg" Style="Complex" textLabel="GroupEFG" />
```


<h3 name="state">States Nested in DataNodes <a href=#map>&#9316;</a></h3>


Given that a State is always linked to a DataNode, States are moved to be nested inside of DataNodes in GPML2021. 

*Example for DataNode with States:* 
```
<DataNodes>
    <DataNode elementId="b4d99" textLabel="ERBB2" type="GeneProduct">
        <Xref identifier="ENSG00000141736" dataSource="ensembl" />
        <States>
            <State elementId="c0d56" textLabel="+" type="Undefined">
              <Graphics ... />
            </State>
            ...
      </DataNode>
</DataNodes>
```


<h3 name="author">Pathway Author Element <a href=#map>&#9317;</a></h3>


The Author elements nested in Authors allows the storing of pathway author information, including: 
* name
* username
* order (authorship order)
* Xref (e.g. ORCID iD).

*Example for Authors:* 
```
<Authors>
    <Author name="Mkutmon" fullName="Martina Kutmon" email="xxx@xxx.com"/>
    <Author name="Egonw" fullName="Egon Willighagen" email="xxx@xxx.com"/>
    ...
</Authors>
```


<h3 name="graphics">Graphics Customization <a href=#map>&#9450;</a></h3>


Additional customization of graphics (e.g. color, shape) is now possible. 
* Different colors can be specified for borderColor and textColor 
* New shapeTypes 
* Background color can be defined for pathway 
* Group has added graphics properties (RectAttributes, FontAttributes, ShapeStyleAttributes) 
* State has added font properties (FontAttributes)


<h3 name="datasource">Xref DataSource as Compact Identifier Prefix <a href=#map>&#9318;</a></h3>


Xref dataSource(s) will be retrieved from [BridgeDb](https://bridgedb.github.io/), and it is also possible to register new data sources. The DataSource compact identifier prefix is given priority and written for by default GPML2021 format (in contrast, DataSource full name is written by default for GPML2013a).  See registered BridgeDB [datasources](https://github.com/bridgedb/datasources/blob/main/datasources.tsv). Additionally, Xref is added for the Pathway. 

*Example Pathway Xref:* 
```
  <Xref identifier="WP1_r1" dataSource="wikipathways"/>
```


*For Example:* 

| identifier| compact identifier prefix | full name | system code |
| :--- | :--- | :--- | :--- |
|ENSG00000139618| ensembl | Ensembl | En | 

<h3 name="groupid">Merged Group GroupId and GraphId <a href=#map>&#9319;</a></h3>

Group Element previously had both GroupId and GraphId, identification of Groups are merged into just elementId.  

<h3 name="removed">Removed Unused Elements and Attributes <a href=#map>&#9450;</a></h3>

Unimplemented elements and attributes of GPML2013a are removed in GPML2021.  
For Example: 
* Legend Element
* Interaction and GraphicalLine “Type” Attribute 
* Pathway Attributes Author, Maintainer, Email, LastModified...

<h3 name="structure">Modified Schema Format and Structure <a href=#map>&#9450;</a></h3>

* Conformed to naming convention
    * camelCase for Attributes
    * Upper camelCase for Elements
* Standardization and simplification of color type and simplification of rotation type
    * Color type is defined as type hexBinary
    * Rotation type is defined as float (radians)
    * Enumerated string values defined in ColorType and RotationType (GPML2013a) no longer used   
* Renamed properties for clarity and consistency 
    
     *For Example:*
    * GraphId and GraphRef renamed elementId and elementRef respectively 
    * Xref Database renamed to dataSource
    * Align and Valign renamed to, hAlign and vAlign. 
* Improved modularity 
    * Reused elements globally defined (e.g. Point and Anchor)
    * Reused attributes grouped and globally declared 
* Elements nested for organization
