<html>
<head>
<title>GPML2021 Schema Documentation</title>
<meta http-equiv="Content-Type" content="text/xml; charset=iso-8859-1" />
<style type="text/css">
/* ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ */
/* More-configurable styles */

/******** General ********/

/* Document body */
body {
   color: Black;
   background-color: White;
   font-family: Arial, sans-serif;
   font-size: 10pt;
}
/* Horizontal rules */
hr {
   color: black;
}
/* Document title */
h1 {
   font-size: 18pt;
   letter-spacing: 2px;
   border-bottom: 1px #ccc solid;
   padding-top: 5px;
   padding-bottom: 5px;
}
/* Main section headers */
h2 {
   font-size: 14pt;
   letter-spacing: 1px;
}
/* Sub-section headers */
h3, h3 a, h3 span {
   font-size: 12pt;
   font-weight: bold;
   color: black;
}
/* Table displaying the properties of the schema components or the
   schema document itself */
table.properties th, table.properties th a {
   color: black;
   background-color: #8AD; /* Pink */
}
table.properties td {
   background-color: #eee; /* Gray */
}


/******** Table of Contents Section ********/

/* Controls for switching between printing and viewing modes */
div#printerControls {
   color: #963; /* Orange-brown */
}
/* Controls that can collapse or expand all XML Instance
   Representation and Schema Component Representation boxes */
div#globalControls {
   border: 2px solid #999;
}


/******** Schema Document Properties Section ********/

/* Table displaying the namespaces declared in the schema */
table.namespaces th {
   background-color: #ccc;
}
table.namespaces td {
   background-color: #eee;
}
/* Target namespace of the schema */
span.targetNS {
   color: #06C;
   font-weight: bold;
}


/******** Schema Components' Sections ********/

/* Name of schema component */
.name {
   color: #F93; /* Orange */
}

/* Hierarchy table */
table.hierarchy {
   border: 2px solid #999; /* Gray */
}

/* XML Instance Representation table */
div.sample div.contents {
   border: 2px dashed black;
}

/* Schema Component Representation table */
div.schemaComponent div.contents {
   border: 2px black solid;
}


/******** Glossary Section ********/

/* Glossary Terms */
.glossaryTerm {
   color: #036; /* Blue */
}


/* ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ */
/* Printer-version styles */

@media print {

/* Ensures that controls are hidden when printing */
div#printerControls {
   visibility: hidden;
}
div#globalControls {
   visibility: hidden;
}
#legend {
   display: none;
}
#legendTOC {
   display: none;
}
#glossary {
   display: none;
}
#glossaryTOC {
   display: none;
}

}

/* ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ */
/* Base styles */

/******** General ********/

/* Unordered lists */
ul {
   margin-left: 1.5em;
   margin-bottom: 0em;
}
/* Tables */
table {
   margin-top: 10px;
   margin-bottom: 10px;
   margin-left: 2px;
   margin-right: 2px;
}
table th, table td {
   font-size: 10pt;
   vertical-align: top;
   padding-top: 3px;
   padding-bottom: 3px;
   padding-left: 10px;
   padding-right: 10px;
}
table th {
   font-weight: bold;
   text-align: left;
}
/* Table displaying the properties of the schema components or the
   schema document itself */
table.properties {
   width: 90%;
}
table.properties th {
   width: 30%;
}
/* Boxes that can make its content appear and disappear*/
div.box {
   margin: 1em;
}
   /* Box caption */
div.box span.caption {
   font-weight: bold;
}
   /* Button to open and close the box */
div.box input.control {
   width: 1.4em;
   height: 1.4em;
   text-align: center;
   vertical-align: middle;
   font-size: 11pt;
}
   /* Box contents */
div.box div.contents {
   margin-top: 3px;
}


/******** Table of Contents Section ********/

/* Controls for switching between printing and viewing modes */
div#printerControls {
   white-space: nowrap;
   font-weight: bold;
   padding: 5px;
   margin: 5px;
}
/* Controls that can collapse or expand all XML Instance
   Representation and Schema Component Representation boxes */
div#globalControls {
   padding: 10px;
   margin: 5px;
}


/******** Schema Document Properties Section ********/

/* Table displaying the namespaces declared in the schema */
table.namespaces th {
}
table.namespaces td {
}
/* Target namespace of the schema */
span.targetNS {
}


/******** Schema Components' Sections ********/

/* Name of schema component */
.name {
}

/* Hierarchy table */
table.hierarchy {
   width: 90%;
}
table.hierarchy th {
   font-weight: normal;
   font-style: italic;
   width: 20%;
}
table.hierarchy th, table.hierarchy td {
   padding: 5px;
}

/* XML Instance Representation table */
div.sample {
   width: 90%;
}
div.sample div.contents {
   padding: 5px;
   font-family: Courier New, sans-serif;
   font-size: 10pt;
}
   /* Normal elements and attributes */
div.sample div.contents, div.sample div.contents a {
   color: black;
}
   /* Group Headers */
div.sample div.contents .group, div.sample div.contents .group a {
   color: #999; /* Light gray */
}
   /* Type Information */
div.sample div.contents .type, div.sample div.contents .type a {
   color: #999; /* Light gray */
}
   /* Occurrence Information */
div.sample div.contents .occurs, div.sample div.contents .occurs a {
   color: #999; /* Light gray */
}
   /* Fixed values */
div.sample div.contents .fixed {
   color: #063; /* Green */
   font-weight: bold;
}
   /* Simple type constraints */
div.sample div.contents .constraint, div.sample div.contents .constraint a {
   color: #999; /* Light gray */
}
   /* Elements and attributes inherited from base type */
div.sample div.contents .inherited, div.sample div.contents .inherited a {
   color: #666; /* Dark gray */
}
   /* Elements and attributes added to or changed from base type */
div.sample div.contents .newFields {
   font-weight: bold;
}
   /* Other type of information */
div.sample div.contents .other, div.sample div.contents .other a {
   color: #369; /* Blue */
   font-style: italic;
}
   /* Link to open up window displaying documentation */
div.sample div.contents a.documentation {
   text-decoration: none;
   padding-left: 3px;
   padding-right: 3px;
   padding-top: 0px;
   padding-bottom: 0px;
   font-weight: bold;
   font-size: 11pt;
   background-color: #FFD;
   color: #069;
}
   /* Invert colors when hovering over link to open up window 
      displaying documentation */
div.sample div.contents a.documentation:hover {
   color: #FFD;
   background-color: #069;
}

/* Schema Component Representation table */
div.schemaComponent {
   width: 90%;
}
div.schemaComponent div.contents {
   font-family: Courier New, sans-serif;
   font-size: 10pt;
   padding: 5px;
}
   /* Syntax characters */
div.schemaComponent div.contents {
   color: #00f; /* blue */
}
   /* Element and attribute tags */
div.schemaComponent div.contents .scTag {
   color: #933; /* maroon */
}
   /* Element and attribute content */
div.schemaComponent div.contents .scContent, div.schemaComponent div.contents .scContent a {
   color: black;
   font-weight: bold;
}
   /* Comments */
div.schemaComponent div.contents .comment {
   color: #999; /* Light gray */
}

/******** Legend Section ********/

div#legend table, div#legend div {
   margin-bottom: 3px;
}
div#legend div.hint {
   color: #999; /* Light gray */
   width: 90%;
   margin-left: 1em;
   margin-bottom: 2em;
}


/******** Glossary Section ********/

/* Glossary Terms */
.glossaryTerm {
   font-weight: bold;
}


/******** Footer ********/

.footer {
   font-size: 8pt;
}
</style>
<script type="text/javascript">
<!--
/* IDs of XML Instance Representation boxes */
var xiBoxes = new Array('attributeGroup_RectAttributes_xibox', 'attributeGroup_FontAttributes_xibox', 'attributeGroup_ShapeStyleAttributes_xibox', 'attributeGroup_LineStyleAttributes_xibox', 'type_StyleType_xibox', 'type_Dimension_xibox', 'group_CommentGroup_xibox', 'element_Pathway_xibox', 'element_DataNodes_xibox', 'element_States_xibox', 'element_Interactions_xibox', 'element_GraphicalLines_xibox', 'element_Labels_xibox', 'element_Shapes_xibox', 'element_Groups_xibox', 'element_Annotations_xibox', 'element_AnnotationRef_xibox', 'element_Citations_xibox', 'element_CitationRef_xibox', 'element_Evidences_xibox', 'element_EvidenceRef_xibox', 'element_Xref_xibox', 'element_Url_xibox', 'element_Point_xibox', 'element_Anchor_xibox');
/* IDs of Schema Component Representation boxes */
var scBoxes = new Array('schema_scbox', 'attributeGroup_RectAttributes_scbox', 'attributeGroup_FontAttributes_scbox', 'attributeGroup_ShapeStyleAttributes_scbox', 'attributeGroup_LineStyleAttributes_scbox', 'type_StyleType_scbox', 'type_Dimension_scbox', 'group_CommentGroup_scbox', 'element_Pathway_scbox', 'element_DataNodes_scbox', 'element_States_scbox', 'element_Interactions_scbox', 'element_GraphicalLines_scbox', 'element_Labels_scbox', 'element_Shapes_scbox', 'element_Groups_scbox', 'element_Annotations_scbox', 'element_AnnotationRef_scbox', 'element_Citations_scbox', 'element_CitationRef_scbox', 'element_Evidences_scbox', 'element_EvidenceRef_scbox', 'element_Xref_scbox', 'element_Url_scbox', 'element_Point_scbox', 'element_Anchor_scbox');

/**
 * Can get the ID of the button controlling
 * a collapseable box by concatenating
 * this string onto the ID of the box itself.
 */
var B_SFIX = "_button";

/**
 * Counter of documentation windows
 * Used to give each window a unique name
 */
var windowCount = 0;

/**
 * Returns an element in the current HTML document.
 * 
 * @param elementID Identifier of HTML element
 * @return               HTML element object
 */
function getElementObject(elementID) {
    var elemObj = null;
    if (document.getElementById) {
        elemObj = document.getElementById(elementID);
    }
    return elemObj;
}             

/**
 * Closes a collapseable box.
 * 
 * @param boxObj       Collapseable box
 * @param buttonObj Button controlling box
 */
function closeBox(boxObj, buttonObj) {
  if (boxObj == null || buttonObj == null) {
     // Box or button not found
  } else {
     // Change 'display' CSS property of box
     boxObj.style.display="none";

     // Change text of button 
     if (boxObj.style.display=="none") {
        buttonObj.value=" + ";
     }
  }
}

/**
 * Opens a collapseable box.
 * 
 * @param boxObj       Collapseable box
 * @param buttonObj Button controlling box
 */
function openBox(boxObj, buttonObj) {
  if (boxObj == null || buttonObj == null) {
     // Box or button not found
  } else {
     // Change 'display' CSS property of box
     boxObj.style.display="block";

     // Change text of button
     if (boxObj.style.display=="block") {
        buttonObj.value=" - ";
     }
  }
}

/**
 * Sets the state of a collapseable box.
 * 
 * @param boxID Identifier of box
 * @param open If true, box is "opened",
 *             Otherwise, box is "closed".
 */
function setState(boxID, open) {
  var boxObj = getElementObject(boxID);
  var buttonObj = getElementObject(boxID+B_SFIX);
  if (boxObj == null || buttonObj == null) {
     // Box or button not found
  } else if (open) {
     openBox(boxObj, buttonObj);
     // Make button visible
     buttonObj.style.display="inline";
  } else {
     closeBox(boxObj, buttonObj);
     // Make button visible
     buttonObj.style.display="inline";
  }
}

/**
 * Switches the state of a collapseable box, e.g.
 * if it's opened, it'll be closed, and vice versa.
 * 
 * @param boxID Identifier of box
 */
function switchState(boxID) {
  var boxObj = getElementObject(boxID);
  var buttonObj = getElementObject(boxID+B_SFIX);
  if (boxObj == null || buttonObj == null) {
     // Box or button not found
  } else if (boxObj.style.display=="none") {
     // Box is closed, so open it
     openBox(boxObj, buttonObj);
  } else if (boxObj.style.display=="block") {
     // Box is opened, so close it
     closeBox(boxObj, buttonObj);
  }
}

/**
 * Closes all boxes in a given list.
 * 
 * @param boxList Array of box IDs
 */
function collapseAll(boxList) {
  var idx;
  for (idx = 0; idx < boxList.length; idx++) {
     var boxObj = getElementObject(boxList[idx]);
     var buttonObj = getElementObject(boxList[idx]+B_SFIX);
     closeBox(boxObj, buttonObj);
  }
}

/**
 * Open all boxes in a given list.
 * 
 * @param boxList Array of box IDs
 */
function expandAll(boxList) {
  var idx;
  for (idx = 0; idx < boxList.length; idx++) {
     var boxObj = getElementObject(boxList[idx]);
     var buttonObj = getElementObject(boxList[idx]+B_SFIX);
     openBox(boxObj, buttonObj);
  }
}

/**
 * Makes all the control buttons of boxes appear.
 * 
 * @param boxList Array of box IDs
 */
function viewControlButtons(boxList) {
    var idx;
    for (idx = 0; idx < boxList.length; idx++) {
        buttonObj = getElementObject(boxList[idx]+B_SFIX);
        if (buttonObj != null) {
            buttonObj.style.display = "inline";
        }
    }
}

/**
 * Makes all the control buttons of boxes disappear.
 * 
 * @param boxList Array of box IDs
 */
function hideControlButtons(boxList) {
    var idx;
    for (idx = 0; idx < boxList.length; idx++) {
        buttonObj = getElementObject(boxList[idx]+B_SFIX);
        if (buttonObj != null) {
            buttonObj.style.display = "none";
        }
    }
}

/**
 * Sets the page for either printing mode
 * or viewing mode. In printing mode, the page
 * is made to be more readable when printing it out.
 * In viewing mode, the page is more browsable.
 *
 * @param isPrinterVersion If true, display in
 *                                 printing mode; otherwise, 
 *                                 in viewing mode
 */
function displayMode(isPrinterVersion) {
    var obj;
    if (isPrinterVersion) {
        // Hide global control buttons
        obj = getElementObject("globalControls");
        if (obj != null) {
            obj.style.visibility = "hidden";
        }
        // Hide Legend
        obj = getElementObject("legend");
        if (obj != null) {
            obj.style.display = "none";
        }
        obj = getElementObject("legendTOC");
        if (obj != null) {
            obj.style.display = "none";
        }
        // Hide Glossary
        obj = getElementObject("glossary");
        if (obj != null) {
            obj.style.display = "none";
        }
        obj = getElementObject("glossaryTOC");
        if (obj != null) {
            obj.style.display = "none";
        }

        // Expand all XML Instance Representation tables
        expandAll(xiBoxes);
        // Expand all Schema Component Representation tables
        expandAll(scBoxes);

        // Hide Control buttons
        hideControlButtons(xiBoxes);
        hideControlButtons(scBoxes);
    } else {
        // View global control buttons
        obj = getElementObject("globalControls");
        if (obj != null) {
            obj.style.visibility = "visible";
        }
        // View Legend
        obj = getElementObject("legend");
        if (obj != null) {
            obj.style.display = "block";
        }
        obj = getElementObject("legendTOC");
        if (obj != null) {
            obj.style.display = "block";
        }
        // View Glossary
        obj = getElementObject("glossary");
        if (obj != null) {
            obj.style.display = "block";
        }
        obj = getElementObject("glossaryTOC");
        if (obj != null) {
            obj.style.display = "block";
        }

        // Expand all XML Instance Representation tables
        expandAll(xiBoxes);
        // Collapse all Schema Component Representation tables
        collapseAll(scBoxes);

        // View Control buttons
        viewControlButtons(xiBoxes);
        viewControlButtons(scBoxes);
    }
}

/**
 * Opens up a window displaying the documentation
 * of a schema component in the XML Instance
 * Representation table.
 * 
 * @param compDesc      Description of schema component 
 * @param compName      Name of schema component 
 * @param docTextArray Array containing the paragraphs 
 *                           of the new document
 */
function viewDocumentation(compDesc, compName, docTextArray) {
  var width = 400;
  var height = 200;
  var locX = 100;
  var locY = 200;

  /* Generate content */
  var actualText = "<html>";
  actualText += "<head><title>";
  actualText += compDesc;
  if (compName != '') {
     actualText += ": " + compName;
  }
  actualText += "</title></head>";
  actualText += "<body bgcolor=\"#FFFFEE\">";
  // Title
  actualText += "<p style=\"font-family: Arial, sans-serif; font-size: 12pt; font-weight: bold; letter-spacing:1px;\">";
  actualText += compDesc;
  if (compName != '') {
     actualText += ": <span style=\"color:#006699\">" + compName + "</span>";
  }
  actualText += "</p>";
  // Documentation
  var idx;
  for (idx = 0; idx < docTextArray.length; idx++) {
     actualText += "<p style=\"font-family: Arial, sans-serif; font-size: 10pt;\">" + docTextArray[idx] + "</p>";
  }
  // Link to close window
  actualText += "<a href=\"javascript:void(0)\" onclick=\"window.close();\" style=\"font-family: Arial, sans-serif; font-size: 8pt;\">Close</a>";
  actualText += "</body></html>";

  /* Display window */
  windowCount++;
  var docWindow = window.open("", "documentation"+windowCount, "toolbar=no,location=no,status=no,menubar=no,scrollbars=yes,resizable,alwaysRaised,dependent,titlebar=no,width="+width+",height="+height+",screenX="+locX+",left="+locX+",screenY="+locY+",top="+locY);
  docWindow.document.write(actualText);
}

// -->
</script>
</head>
<body>
<h1><a name="top">GPML2021 Schema Documentation</a></h1>
<div style="float: right;">
<div id="printerControls" style="display:none;">
<input type="checkbox" onclick="displayMode(this.checked)" />Printer-friendly Version</div>
<script type="text/javascript">
<!--

var pc = getElementObject("printerControls");
if (pc != null) {
   pc.style.display="block";
}
               
// -->
</script>
<div id="globalControls" style="display:none">
<strong>XML Instance Representation:</strong><br />
<span style="margin-left: 1em; white-space: nowrap">[ <a href="javascript:void(0)" onclick="expandAll(xiBoxes)">Expand All</a> | <a href="javascript:void(0)" onclick="collapseAll(xiBoxes)">Collapse All</a> ]</span><br /><br />
<strong>Schema Component Representation:</strong><br />
<span style="margin-left: 1em; white-space: nowrap">[ <a href="javascript:void(0)" onclick="expandAll(scBoxes)">Expand All</a> | <a href="javascript:void(0)" onclick="collapseAll(scBoxes)">Collapse All</a> ]</span>
</div>
<script type="text/javascript">
<!--

var gc = getElementObject("globalControls");
if (gc != null) {
   gc.style.display="block";
}
               
// -->
</script>
</div>
<h2>Table of Contents</h2>
<ul>
<li>
<a href="#SchemaProperties">Schema Document Properties</a>
</li>
<li><a href="#SchemaDeclarations">Global Declarations</a>
<ul>
<li>
<a href="#element_Pathway">Element: <strong>Pathway</strong>
</a>
</li>
<li>
<a href="#element_DataNodes">Element: <strong>DataNodes</strong>
</a>
</li>
<li>
<a href="#element_States">Element: <strong>States</strong>
</a>
</li>
<li>
<a href="#element_Interactions">Element: <strong>Interactions</strong>
</a>
</li>
<li>
<a href="#element_GraphicalLines">Element: <strong>GraphicalLines</strong>
</a>
</li>
<li>
<a href="#element_Labels">Element: <strong>Labels</strong>
</a>
</li>
<li>
<a href="#element_Shapes">Element: <strong>Shapes</strong>
</a>
</li>
<li>
<a href="#element_Groups">Element: <strong>Groups</strong>
</a>
</li>
<li>
<a href="#element_Annotations">Element: <strong>Annotations</strong>
</a>
</li>
<li>
<a href="#element_AnnotationRef">Element: <strong>AnnotationRef</strong>
</a>
</li>
<li>
<a href="#element_Citations">Element: <strong>Citations</strong>
</a>
</li>
<li>
<a href="#element_CitationRef">Element: <strong>CitationRef</strong>
</a>
</li>
<li>
<a href="#element_Evidences">Element: <strong>Evidences</strong>
</a>
</li>
<li>
<a href="#element_EvidenceRef">Element: <strong>EvidenceRef</strong>
</a>
</li>
<li>
<a href="#element_Xref">Element: <strong>Xref</strong>
</a>
</li>
<li>
<a href="#element_Url">Element: <strong>Url</strong>
</a>
</li>
<li>
<a href="#element_Point">Element: <strong>Point</strong>
</a>
</li>
<li>
<a href="#element_Anchor">Element: <strong>Anchor</strong>
</a>
</li>
</ul>
</li>
<li><a href="#SchemaDefinitions">Global Definitions</a>
<ul>
<li>
<a href="#attributeGroup_RectAttributes">Attribute Group: <strong>RectAttributes</strong>
</a>
</li>
<li>
<a href="#attributeGroup_FontAttributes">Attribute Group: <strong>FontAttributes</strong>
</a>
</li>
<li>
<a href="#attributeGroup_ShapeStyleAttributes">Attribute Group: <strong>ShapeStyleAttributes</strong>
</a>
</li>
<li>
<a href="#attributeGroup_LineStyleAttributes">Attribute Group: <strong>LineStyleAttributes</strong>
</a>
</li>
<li>
<a href="#type_StyleType">Simple Type: <strong>StyleType</strong>
</a>
</li>
<li>
<a href="#type_Dimension">Simple Type: <strong>Dimension</strong>
</a>
</li>
<li>
<a href="#group_CommentGroup">Model Group: <strong>CommentGroup</strong>
</a>
</li>
</ul>
</li>
</ul>
<ul id="legendTOC" style="margin-top: 0em">
<li><a href="#Legend">Legend</a></li>
</ul>
<ul id="glossaryTOC" style="margin-top: 0em">
<li><a href="#Glossary">Glossary</a></li>
</ul>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h2><a name="SchemaProperties">Schema Document Properties</a></h2>
<table class="properties">
<tr>
<th>
<a title="Look up 'Target Namespace' in glossary" href="#term_TargetNS">Target Namespace</a>
</th>
<td>
<span class="targetNS">http://pathvisio.org/GPML/2021</span>
</td>
</tr>
<tr>
<th>Element and Attribute Namespaces</th>
<td>
<ul>
<li>Global element and attribute declarations belong to this schema's target namespace.</li>
<li>By default, local element declarations belong to this schema's target namespace.</li>
<li>By default, local attribute declarations have no namespace.</li>
</ul>
</td>
</tr>
</table>
<h3>Declared Namespaces</h3>
<table class="namespaces">
<tr>
<th>Prefix</th>
<th>Namespace</th>
</tr>
<tr>
<td>
<a name="ns_xml">xml</a>
</td>
<td>http://www.w3.org/XML/1998/namespace</td>
</tr>
<tr>
<td>
<a name="ns_xsd">xsd</a>
</td>
<td>http://www.w3.org/2001/XMLSchema</td>
</tr>
<tr>
<td>
<a name="ns_gpml">gpml</a>
</td>
<td>
<span class="targetNS">http://pathvisio.org/GPML/2021</span>
</td>
</tr>
</table>
<div class="schemaComponent box">
<div>
<input type="button" id="schema_scbox_button" class="control" onclick="switchState('schema_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="schema_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:schema</span> <span class="scTag">targetNamespace</span>="<span class="scContent">http://pathvisio.org/GPML/2021</span>" <span class="scTag">elementFormDefault</span>="<span class="scContent">qualified</span>"&gt;<div class="scContent" style="margin-left: 1.5em">...</div>&lt;/<span class="scTag">xsd:schema</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('schema_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h2><a name="SchemaDeclarations">Global Declarations</a></h2>
<h3>Element: <a name="element_Pathway" class="name">Pathway</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Pathway</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>A graph diagram representing a biological process as a set of interactions and relationships among genes, proteins, metabolites, and other factors in the context of cellular compartments, tissues and organisms.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Pathway_xibox_button" class="control" onclick="switchState('element_Pathway_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Pathway_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Pathway<br /><span style="margin-left: 0.5em"> title="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The title of a pathway.'); viewDocumentation('Attribute', 'title', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> organism="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The scientific name of the species being described by a pathway, e.g. Homo sapiens...'); viewDocumentation('Attribute', 'organism', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The source of a pathway, e.g. WikiPathways, KEGG...'); viewDocumentation('Attribute', 'source', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> version="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The version of a pathway.'); viewDocumentation('Attribute', 'version', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> license="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The license of a pathway.'); viewDocumentation('Attribute', 'license', docArray);">?</a>"</span>&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; <span class="occurs">[0..1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Description&gt; <span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span> &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Description&gt; <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Textual description of the pathway.'); viewDocumentation('Element', 'Description', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Authors&gt;  <span class="occurs">[0..1]</span> <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Author<br /><span style="margin-left: 0.5em"> name="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The name of an author.'); viewDocumentation('Attribute', 'name', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> username="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The username of an author.'); viewDocumentation('Attribute', 'username', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> order="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The authorship order of an author.'); viewDocumentation('Attribute', 'order', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The people who created or edited a pathway.'); viewDocumentation('Element', 'Author', docArray);">?</a><br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a database entry for an author, e.g. ORCID.'); viewDocumentation('Element', 'Xref', docArray);">?</a></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Author&gt;</div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Authors&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The source for a comment.'); viewDocumentation('Attribute', 'source', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Descriptions or arbitrary notes for an object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Property<br /><span style="margin-left: 0.5em"> key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The key of a key-value pair.'); viewDocumentation('Attribute', 'key', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The value of a key-value pair.'); viewDocumentation('Attribute', 'value', docArray);">?</a>"</span>/&gt;  <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Key-value pair information for an object.'); viewDocumentation('Element', 'Property', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Annotation.'); viewDocumentation('Element', 'AnnotationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Citation.'); viewDocumentation('Element', 'CitationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Evidence.'); viewDocumentation('Element', 'EvidenceRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics<br /><span style="margin-left: 0.5em"> boardWidth="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The width of a pathway.'); viewDocumentation('Attribute', 'boardWidth', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> boardHeight="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The height of a pathway.'); viewDocumentation('Attribute', 'boardHeight', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> backgroundColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color for the background of a pathway, default white.'); viewDocumentation('Attribute', 'backgroundColor', docArray);">?</a>"</span>/&gt;  <span class="occurs">[0..1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;DataNodes&quot; element declaration." href="#element_DataNodes">DataNodes</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;DataNodes&quot; element declaration." href="#element_DataNodes">DataNodes</a>&gt; <span class="occurs">[0..1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Interactions&quot; element declaration." href="#element_Interactions">Interactions</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Interactions&quot; element declaration." href="#element_Interactions">Interactions</a>&gt; <span class="occurs">[0..1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;GraphicalLines&quot; element declaration." href="#element_GraphicalLines">GraphicalLines</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;GraphicalLines&quot; element declaration." href="#element_GraphicalLines">GraphicalLines</a>&gt; <span class="occurs">[0..1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Labels&quot; element declaration." href="#element_Labels">Labels</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Labels&quot; element declaration." href="#element_Labels">Labels</a>&gt; <span class="occurs">[0..1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Shapes&quot; element declaration." href="#element_Shapes">Shapes</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Shapes&quot; element declaration." href="#element_Shapes">Shapes</a>&gt; <span class="occurs">[0..1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Groups&quot; element declaration." href="#element_Groups">Groups</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Groups&quot; element declaration." href="#element_Groups">Groups</a>&gt; <span class="occurs">[0..1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Annotations&quot; element declaration." href="#element_Annotations">Annotations</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Annotations&quot; element declaration." href="#element_Annotations">Annotations</a>&gt; <span class="occurs">[0..1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Citations&quot; element declaration." href="#element_Citations">Citations</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Citations&quot; element declaration." href="#element_Citations">Citations</a>&gt; <span class="occurs">[0..1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Evidences&quot; element declaration." href="#element_Evidences">Evidences</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Evidences&quot; element declaration." href="#element_Evidences">Evidences</a>&gt; <span class="occurs">[0..1]</span></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Pathway&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Pathway_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Pathway_scbox_button" class="control" onclick="switchState('element_Pathway_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Pathway_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Pathway</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Description</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"/&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Authors</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Author</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">name</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">username</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">order</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CommentGroup&quot; group definition." href="#group_CommentGroup">CommentGroup</a></span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Graphics</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">boardWidth</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">boardHeight</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">backgroundColor</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span></span>" <span class="scTag">default</span>="<span class="scContent">ffffff</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;DataNodes&quot; element declaration." href="#element_DataNodes">DataNodes</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Interactions&quot; element declaration." href="#element_Interactions">Interactions</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;GraphicalLines&quot; element declaration." href="#element_GraphicalLines">GraphicalLines</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Labels&quot; element declaration." href="#element_Labels">Labels</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Shapes&quot; element declaration." href="#element_Shapes">Shapes</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Groups&quot; element declaration." href="#element_Groups">Groups</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Annotations&quot; element declaration." href="#element_Annotations">Annotations</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Citations&quot; element declaration." href="#element_Citations">Citations</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Evidences&quot; element declaration." href="#element_Evidences">Evidences</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">title</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">organism</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">source</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">version</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">license</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Pathway_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_DataNodes" class="name">DataNodes</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>DataNodes</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>List of Data nodes. A data node denotes a biological entity that forms a node in a pathway.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_DataNodes_xibox_button" class="control" onclick="switchState('element_DataNodes_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_DataNodes_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:DataNodes&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:DataNode<br /><span style="margin-left: 0.5em"> elementId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The internal gpml unique identifier for an element.'); viewDocumentation('Attribute', 'elementId', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> textLabel="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The text label for a data node.'); viewDocumentation('Attribute', 'textLabel', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> type="<span class="constraint">union of: [ [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Undefined'|'GeneProduct'|'DNA'|'RNA'|'Protein'|'Complex'|'Metabolite'|'Pathway'|'Disease'|'Phenotype'|'Alias'|'Event'}) ], [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> ] ]</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The data node type, e.g. Undefined (default), GeneProduct, Metabolite, Alias...'); viewDocumentation('Attribute', 'type', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> groupRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('When a pathway element is part of a gpml:Group, groupRef refers to the elementId of the parent group.'); viewDocumentation('Attribute', 'groupRef', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> aliasRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('An aliasRef indicates a child/parent relationship between objects. A DataNode can have type \&quot;Alias\&quot; and refer to a gpml:Group.'); viewDocumentation('Attribute', 'aliasRef', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Denotes a biological entity that forms a node in a pathway.'); viewDocumentation('Element', 'DataNode', docArray);">?</a><br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; <span class="occurs">[0..1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;States&quot; element declaration." href="#element_States">States</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;States&quot; element declaration." href="#element_States">States</a>&gt; <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The states linked to this data node.'); viewDocumentation('Element', 'States', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics<br /><span style="margin-left: 0.5em"> centerX="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The middle of an object in the x-direction.'); viewDocumentation('Attribute', 'centerX', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> centerY="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The middle of an object in the y-direction.'); viewDocumentation('Attribute', 'centerY', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> width="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the x-dimensional length of an object.'); viewDocumentation('Attribute', 'width', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> height="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the y-dimensional length of an object.'); viewDocumentation('Attribute', 'height', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> textColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color of text, default black.'); viewDocumentation('Attribute', 'textColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontName="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The name of the collection of characters with a similar design, e.g. Arial (default)...'); viewDocumentation('Attribute', 'fontName', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontWeight="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Bold'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The thickness of the font used, e.g Normal (default) or Bold. A bold font has more weight.'); viewDocumentation('Attribute', 'fontWeight', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontStyle="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Italic'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Italic or Normal (default).'); viewDocumentation('Attribute', 'fontStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontDecoration="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Underline'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Underline or Normal (default).'); viewDocumentation('Attribute', 'fontDecoration', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontStrikethru="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Strikethru'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Strikethru or Normal (default).'); viewDocumentation('Attribute', 'fontStrikethru', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontSize="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:nonNegativeInteger</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The point value for the size of the font.'); viewDocumentation('Attribute', 'fontSize', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> hAlign="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Left'|'Center'|'Right'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The horizontal alignment of displayed text: Left, Center (default), or Right.'); viewDocumentation('Attribute', 'hAlign', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> vAlign="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Top'|'Middle'|'Bottom'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The vertical alignment of displayed text: Top, Middle (default), or Bottom.'); viewDocumentation('Attribute', 'vAlign', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> borderColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color of a border, default black.'); viewDocumentation('Attribute', 'borderColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> borderStyle="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a line, e.g. Solid (default), Dashed...'); viewDocumentation('Attribute', 'borderStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> borderWidth="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the width of a given border.'); viewDocumentation('Attribute', 'borderWidth', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fillColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color contained within the line or border of an object, default white.'); viewDocumentation('Attribute', 'fillColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> shapeType="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a two dimensional object, e.g. Rectangle (default), Nucleus...'); viewDocumentation('Attribute', 'shapeType', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> zOrder="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The order of an object along the z-axis.'); viewDocumentation('Attribute', 'zOrder', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> rotation="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('A float value (rotation in radians).'); viewDocumentation('Attribute', 'rotation', docArray);">?</a>"</span>/&gt;  <span class="occurs">[1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The source for a comment.'); viewDocumentation('Attribute', 'source', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Descriptions or arbitrary notes for an object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Property<br /><span style="margin-left: 0.5em"> key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The key of a key-value pair.'); viewDocumentation('Attribute', 'key', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The value of a key-value pair.'); viewDocumentation('Attribute', 'value', docArray);">?</a>"</span>/&gt;  <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Key-value pair information for an object.'); viewDocumentation('Element', 'Property', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Annotation.'); viewDocumentation('Element', 'AnnotationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Citation.'); viewDocumentation('Element', 'CitationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Evidence.'); viewDocumentation('Element', 'EvidenceRef', docArray);">?</a></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:DataNode&gt;</div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:DataNodes&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_DataNodes_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_DataNodes_scbox_button" class="control" onclick="switchState('element_DataNodes_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_DataNodes_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">DataNodes</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- DataNode --&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">DataNode</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;States&quot; element declaration." href="#element_States">States</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Graphics</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;RectAttributes&quot; attribute group definition." href="#attributeGroup_RectAttributes">RectAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;FontAttributes&quot; attribute group definition." href="#attributeGroup_FontAttributes">FontAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ShapeStyleAttributes&quot; attribute group definition." href="#attributeGroup_ShapeStyleAttributes">ShapeStyleAttributes</a></span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CommentGroup&quot; group definition." href="#group_CommentGroup">CommentGroup</a></span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">elementId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">textLabel</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">type</span>" <span class="scTag">default</span>="<span class="scContent">Undefined</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:union</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Undefined</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">GeneProduct</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">DNA</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">RNA</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Protein</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Complex</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Metabolite</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Pathway</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Disease</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Phenotype</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Alias</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Event</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"/&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:union</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">groupRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">aliasRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End: DataNode --&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_DataNodes_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_States" class="name">States</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>States</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>List of States. A state represents a specific state of the biological entity (e.g. phosphorylation, genetic variants, etc). A state is linked to a data node.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_States_xibox_button" class="control" onclick="switchState('element_States_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_States_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:States&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:State<br /><span style="margin-left: 0.5em"> elementId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The internal gpml unique identifier for an element.'); viewDocumentation('Attribute', 'elementId', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> textLabel="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The text label for a state.'); viewDocumentation('Attribute', 'textLabel', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> type="<span class="constraint">union of: [ [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Undefined'|'ProteinModification'|'GeneticVariant'|'EpigeneticModification'}) ], [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> ] ]</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The state type, e.g. Undefined (default), Protein modification, Genetic variant...'); viewDocumentation('Attribute', 'type', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The state of a biological entity (e.g. Undefined (default), Protein modification...) linked to a parent gpml:DataNode.'); viewDocumentation('Element', 'State', docArray);">?</a><br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; <span class="occurs">[0..1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics<br /><span style="margin-left: 0.5em"> relX="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The relative x coordinates on the parent gpml:DataNode, where 0,0 is at the center and 1,1 is at the bottom-right corner of the data node.'); viewDocumentation('Attribute', 'relX', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> relY="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The relative y coordinates on the parent gpml:DataNode, where 0,0 is at the center and 1,1 is at the bottom-right corner of the data node.'); viewDocumentation('Attribute', 'relY', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> width="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the x-dimensional length of a state.'); viewDocumentation('Attribute', 'width', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> height="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the y-dimensional length of a state.'); viewDocumentation('Attribute', 'height', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> textColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color of text, default black.'); viewDocumentation('Attribute', 'textColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontName="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The name of the collection of characters with a similar design, e.g. Arial (default)...'); viewDocumentation('Attribute', 'fontName', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontWeight="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Bold'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The thickness of the font used, e.g Normal (default) or Bold. A bold font has more weight.'); viewDocumentation('Attribute', 'fontWeight', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontStyle="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Italic'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Italic or Normal (default).'); viewDocumentation('Attribute', 'fontStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontDecoration="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Underline'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Underline or Normal (default).'); viewDocumentation('Attribute', 'fontDecoration', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontStrikethru="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Strikethru'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Strikethru or Normal (default).'); viewDocumentation('Attribute', 'fontStrikethru', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontSize="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:nonNegativeInteger</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The point value for the size of the font.'); viewDocumentation('Attribute', 'fontSize', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> hAlign="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Left'|'Center'|'Right'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The horizontal alignment of displayed text: Left, Center (default), or Right.'); viewDocumentation('Attribute', 'hAlign', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> vAlign="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Top'|'Middle'|'Bottom'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The vertical alignment of displayed text: Top, Middle (default), or Bottom.'); viewDocumentation('Attribute', 'vAlign', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> borderColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color of a border, default black.'); viewDocumentation('Attribute', 'borderColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> borderStyle="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a line, e.g. Solid (default), Dashed...'); viewDocumentation('Attribute', 'borderStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> borderWidth="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the width of a given border.'); viewDocumentation('Attribute', 'borderWidth', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fillColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color contained within the line or border of an object, default white.'); viewDocumentation('Attribute', 'fillColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> shapeType="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a two dimensional object, e.g. Rectangle (default), Nucleus...'); viewDocumentation('Attribute', 'shapeType', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> zOrder="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The order of an object along the z-axis.'); viewDocumentation('Attribute', 'zOrder', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> rotation="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('A float value (rotation in radians).'); viewDocumentation('Attribute', 'rotation', docArray);">?</a>"</span>/&gt;  <span class="occurs">[1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The source for a comment.'); viewDocumentation('Attribute', 'source', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Descriptions or arbitrary notes for an object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Property<br /><span style="margin-left: 0.5em"> key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The key of a key-value pair.'); viewDocumentation('Attribute', 'key', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The value of a key-value pair.'); viewDocumentation('Attribute', 'value', docArray);">?</a>"</span>/&gt;  <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Key-value pair information for an object.'); viewDocumentation('Element', 'Property', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Annotation.'); viewDocumentation('Element', 'AnnotationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Citation.'); viewDocumentation('Element', 'CitationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Evidence.'); viewDocumentation('Element', 'EvidenceRef', docArray);">?</a></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:State&gt;</div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:States&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_States_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_States_scbox_button" class="control" onclick="switchState('element_States_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_States_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">States</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- State --&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">State</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Graphics</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">relX</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">relY</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">width</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">height</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;FontAttributes&quot; attribute group definition." href="#attributeGroup_FontAttributes">FontAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ShapeStyleAttributes&quot; attribute group definition." href="#attributeGroup_ShapeStyleAttributes">ShapeStyleAttributes</a></span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CommentGroup&quot; group definition." href="#group_CommentGroup">CommentGroup</a></span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">elementId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">textLabel</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">type</span>" <span class="scTag">default</span>="<span class="scContent">Undefined</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:union</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Undefined</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">ProteinModification</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">GeneticVariant</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">EpigeneticModification</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"/&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:union</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End: State --&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_States_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Interactions" class="name">Interactions</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Interactions</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>List of Interactions. An interaction represents the biological relation between entities. An Xref can be specified for Interactions (in contrast to GraphicalLines).</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Interactions_xibox_button" class="control" onclick="switchState('element_Interactions_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Interactions_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Interactions&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Interaction<br /><span style="margin-left: 0.5em"> elementId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The internal gpml unique identifier for an element.'); viewDocumentation('Attribute', 'elementId', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> groupRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('When a pathway element is part of a gpml:Group, groupRef refers to the elementId of the parent group.'); viewDocumentation('Attribute', 'groupRef', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Interactions represent biological relation between entities. An Xref can be specified for Interactions (in contrast to GraphicalLines).'); viewDocumentation('Element', 'Interaction', docArray);">?</a><br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; <span class="occurs">[0..1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Waypoints&gt;  <span class="occurs">[1]</span> <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Point&quot; element declaration." href="#element_Point">Point</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Point&quot; element declaration." href="#element_Point">Point</a>&gt; <span class="occurs">[2..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Anchor&quot; element declaration." href="#element_Anchor">Anchor</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Anchor&quot; element declaration." href="#element_Anchor">Anchor</a>&gt; <span class="occurs">[0..*]</span></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Waypoints&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics<br /><span style="margin-left: 0.5em"> lineColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color of a line, default black.'); viewDocumentation('Attribute', 'lineColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> lineStyle="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a line, e.g. Solid (default), Dashed...'); viewDocumentation('Attribute', 'lineStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> lineWidth="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the width of a given line.'); viewDocumentation('Attribute', 'lineWidth', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> connectorType="<span class="constraint">union of: [ [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Straight'|'Elbow'|'Curved'|'Segmented'}) ], [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> ] ]</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Specifies a set of rules to govern layout of lines, e.g. Straight (default), Elbow...'); viewDocumentation('Attribute', 'connectorType', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> zOrder="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The order of an object along the z-axis.'); viewDocumentation('Attribute', 'zOrder', docArray);">?</a>"</span>/&gt;  <span class="occurs">[1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The source for a comment.'); viewDocumentation('Attribute', 'source', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Descriptions or arbitrary notes for an object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Property<br /><span style="margin-left: 0.5em"> key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The key of a key-value pair.'); viewDocumentation('Attribute', 'key', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The value of a key-value pair.'); viewDocumentation('Attribute', 'value', docArray);">?</a>"</span>/&gt;  <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Key-value pair information for an object.'); viewDocumentation('Element', 'Property', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Annotation.'); viewDocumentation('Element', 'AnnotationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Citation.'); viewDocumentation('Element', 'CitationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Evidence.'); viewDocumentation('Element', 'EvidenceRef', docArray);">?</a></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Interaction&gt;</div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Interactions&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Interactions_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Interactions_scbox_button" class="control" onclick="switchState('element_Interactions_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Interactions_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Interactions</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- Interaction --&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Interaction</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Waypoints</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Point&quot; element declaration." href="#element_Point">Point</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">2</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Anchor&quot; element declaration." href="#element_Anchor">Anchor</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Graphics</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;LineStyleAttributes&quot; attribute group definition." href="#attributeGroup_LineStyleAttributes">LineStyleAttributes</a></span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CommentGroup&quot; group definition." href="#group_CommentGroup">CommentGroup</a></span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">elementId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">groupRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End: Interaction --&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Interactions_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_GraphicalLines" class="name">GraphicalLines</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>GraphicalLines</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>List of Graphical lines. A graphical line is a visual annotation without semantic meaning. It is often used to partition space or connect other pathway elements. An Xref cannot be specified for GraphicalLines (in contrast to Interactions).</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_GraphicalLines_xibox_button" class="control" onclick="switchState('element_GraphicalLines_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_GraphicalLines_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:GraphicalLines&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:GraphicalLine<br /><span style="margin-left: 0.5em"> elementId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The internal gpml unique identifier for an element.'); viewDocumentation('Attribute', 'elementId', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> groupRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('When a pathway element is part of a gpml:Group, groupRef refers to the elementId of the parent group.'); viewDocumentation('Attribute', 'groupRef', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Graphical line are visual annotations without semantic meaning. An Xref cannot be specified for GraphicalLines (in contrast to Interactions).'); viewDocumentation('Element', 'GraphicalLine', docArray);">?</a><br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Waypoints&gt;  <span class="occurs">[1]</span> <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Point&quot; element declaration." href="#element_Point">Point</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Point&quot; element declaration." href="#element_Point">Point</a>&gt; <span class="occurs">[2..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Anchor&quot; element declaration." href="#element_Anchor">Anchor</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Anchor&quot; element declaration." href="#element_Anchor">Anchor</a>&gt; <span class="occurs">[0..*]</span></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Waypoints&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics<br /><span style="margin-left: 0.5em"> lineColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color of a line, default black.'); viewDocumentation('Attribute', 'lineColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> lineStyle="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a line, e.g. Solid (default), Dashed...'); viewDocumentation('Attribute', 'lineStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> lineWidth="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the width of a given line.'); viewDocumentation('Attribute', 'lineWidth', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> connectorType="<span class="constraint">union of: [ [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Straight'|'Elbow'|'Curved'|'Segmented'}) ], [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> ] ]</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Specifies a set of rules to govern layout of lines, e.g. Straight (default), Elbow...'); viewDocumentation('Attribute', 'connectorType', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> zOrder="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The order of an object along the z-axis.'); viewDocumentation('Attribute', 'zOrder', docArray);">?</a>"</span>/&gt;  <span class="occurs">[1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The source for a comment.'); viewDocumentation('Attribute', 'source', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Descriptions or arbitrary notes for an object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Property<br /><span style="margin-left: 0.5em"> key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The key of a key-value pair.'); viewDocumentation('Attribute', 'key', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The value of a key-value pair.'); viewDocumentation('Attribute', 'value', docArray);">?</a>"</span>/&gt;  <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Key-value pair information for an object.'); viewDocumentation('Element', 'Property', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Annotation.'); viewDocumentation('Element', 'AnnotationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Citation.'); viewDocumentation('Element', 'CitationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Evidence.'); viewDocumentation('Element', 'EvidenceRef', docArray);">?</a></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:GraphicalLine&gt;</div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:GraphicalLines&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_GraphicalLines_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_GraphicalLines_scbox_button" class="control" onclick="switchState('element_GraphicalLines_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_GraphicalLines_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">GraphicalLines</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- GraphicalLine --&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">GraphicalLine</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Waypoints</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Point&quot; element declaration." href="#element_Point">Point</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">2</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Anchor&quot; element declaration." href="#element_Anchor">Anchor</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Graphics</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;LineStyleAttributes&quot; attribute group definition." href="#attributeGroup_LineStyleAttributes">LineStyleAttributes</a></span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CommentGroup&quot; group definition." href="#group_CommentGroup">CommentGroup</a></span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End Graphics related attributes--&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">elementId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">groupRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End: GraphicalLine --&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_GraphicalLines_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Labels" class="name">Labels</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Labels</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>List of Labels. A label is a text field which can be used to annotate any aspect of a pathway.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Labels_xibox_button" class="control" onclick="switchState('element_Labels_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Labels_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Labels&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Label<br /><span style="margin-left: 0.5em"> elementId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The internal gpml unique identifier for an element.'); viewDocumentation('Attribute', 'elementId', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> textLabel="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The text for a label.'); viewDocumentation('Attribute', 'textLabel', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> groupRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('When a pathway element is part of a gpml:Group, groupRef refers to the elementId of the parent group.'); viewDocumentation('Attribute', 'groupRef', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> href="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hyperlink for a reference to an url.'); viewDocumentation('Attribute', 'href', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('A text field which can be used to annotate any aspect of a pathway.'); viewDocumentation('Element', 'Label', docArray);">?</a><br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics<br /><span style="margin-left: 0.5em"> centerX="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The middle of an object in the x-direction.'); viewDocumentation('Attribute', 'centerX', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> centerY="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The middle of an object in the y-direction.'); viewDocumentation('Attribute', 'centerY', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> width="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the x-dimensional length of an object.'); viewDocumentation('Attribute', 'width', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> height="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the y-dimensional length of an object.'); viewDocumentation('Attribute', 'height', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> textColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color of text, default black.'); viewDocumentation('Attribute', 'textColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontName="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The name of the collection of characters with a similar design, e.g. Arial (default)...'); viewDocumentation('Attribute', 'fontName', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontWeight="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Bold'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The thickness of the font used, e.g Normal (default) or Bold. A bold font has more weight.'); viewDocumentation('Attribute', 'fontWeight', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontStyle="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Italic'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Italic or Normal (default).'); viewDocumentation('Attribute', 'fontStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontDecoration="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Underline'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Underline or Normal (default).'); viewDocumentation('Attribute', 'fontDecoration', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontStrikethru="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Strikethru'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Strikethru or Normal (default).'); viewDocumentation('Attribute', 'fontStrikethru', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontSize="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:nonNegativeInteger</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The point value for the size of the font.'); viewDocumentation('Attribute', 'fontSize', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> hAlign="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Left'|'Center'|'Right'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The horizontal alignment of displayed text: Left, Center (default), or Right.'); viewDocumentation('Attribute', 'hAlign', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> vAlign="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Top'|'Middle'|'Bottom'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The vertical alignment of displayed text: Top, Middle (default), or Bottom.'); viewDocumentation('Attribute', 'vAlign', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> borderColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color of a border, default black.'); viewDocumentation('Attribute', 'borderColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> borderStyle="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a line, e.g. Solid (default), Dashed...'); viewDocumentation('Attribute', 'borderStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> borderWidth="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the width of a given border.'); viewDocumentation('Attribute', 'borderWidth', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fillColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color contained within the line or border of an object, default white.'); viewDocumentation('Attribute', 'fillColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> shapeType="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a two dimensional object, e.g. Rectangle (default), Nucleus...'); viewDocumentation('Attribute', 'shapeType', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> zOrder="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The order of an object along the z-axis.'); viewDocumentation('Attribute', 'zOrder', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> rotation="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('A float value (rotation in radians).'); viewDocumentation('Attribute', 'rotation', docArray);">?</a>"</span>/&gt;  <span class="occurs">[1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The source for a comment.'); viewDocumentation('Attribute', 'source', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Descriptions or arbitrary notes for an object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Property<br /><span style="margin-left: 0.5em"> key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The key of a key-value pair.'); viewDocumentation('Attribute', 'key', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The value of a key-value pair.'); viewDocumentation('Attribute', 'value', docArray);">?</a>"</span>/&gt;  <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Key-value pair information for an object.'); viewDocumentation('Element', 'Property', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Annotation.'); viewDocumentation('Element', 'AnnotationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Citation.'); viewDocumentation('Element', 'CitationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Evidence.'); viewDocumentation('Element', 'EvidenceRef', docArray);">?</a></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Label&gt;</div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Labels&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Labels_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Labels_scbox_button" class="control" onclick="switchState('element_Labels_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Labels_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Labels</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- Label --&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Label</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Graphics</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;RectAttributes&quot; attribute group definition." href="#attributeGroup_RectAttributes">RectAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;FontAttributes&quot; attribute group definition." href="#attributeGroup_FontAttributes">FontAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ShapeStyleAttributes&quot; attribute group definition." href="#attributeGroup_ShapeStyleAttributes">ShapeStyleAttributes</a></span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CommentGroup&quot; group definition." href="#group_CommentGroup">CommentGroup</a></span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">elementId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">textLabel</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">groupRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">href</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End: Label --&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Labels_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Shapes" class="name">Shapes</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Shapes</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>List of Shapes. A shape is a visual annotation or graphical element.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Shapes_xibox_button" class="control" onclick="switchState('element_Shapes_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Shapes_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Shapes&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Shape<br /><span style="margin-left: 0.5em"> elementId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The internal gpml unique identifier for an element.'); viewDocumentation('Attribute', 'elementId', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> textLabel="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The text label for a shape.'); viewDocumentation('Attribute', 'textLabel', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> groupRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('When a pathway element is part of a gpml:Group, groupRef refers to the elementId of the parent group.'); viewDocumentation('Attribute', 'groupRef', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('A visual annotation or graphical element.'); viewDocumentation('Element', 'Shape', docArray);">?</a><br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics<br /><span style="margin-left: 0.5em"> centerX="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The middle of an object in the x-direction.'); viewDocumentation('Attribute', 'centerX', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> centerY="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The middle of an object in the y-direction.'); viewDocumentation('Attribute', 'centerY', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> width="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the x-dimensional length of an object.'); viewDocumentation('Attribute', 'width', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> height="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the y-dimensional length of an object.'); viewDocumentation('Attribute', 'height', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> textColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color of text, default black.'); viewDocumentation('Attribute', 'textColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontName="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The name of the collection of characters with a similar design, e.g. Arial (default)...'); viewDocumentation('Attribute', 'fontName', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontWeight="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Bold'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The thickness of the font used, e.g Normal (default) or Bold. A bold font has more weight.'); viewDocumentation('Attribute', 'fontWeight', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontStyle="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Italic'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Italic or Normal (default).'); viewDocumentation('Attribute', 'fontStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontDecoration="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Underline'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Underline or Normal (default).'); viewDocumentation('Attribute', 'fontDecoration', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontStrikethru="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Strikethru'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Strikethru or Normal (default).'); viewDocumentation('Attribute', 'fontStrikethru', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontSize="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:nonNegativeInteger</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The point value for the size of the font.'); viewDocumentation('Attribute', 'fontSize', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> hAlign="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Left'|'Center'|'Right'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The horizontal alignment of displayed text: Left, Center (default), or Right.'); viewDocumentation('Attribute', 'hAlign', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> vAlign="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Top'|'Middle'|'Bottom'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The vertical alignment of displayed text: Top, Middle (default), or Bottom.'); viewDocumentation('Attribute', 'vAlign', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> borderColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color of a border, default black.'); viewDocumentation('Attribute', 'borderColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> borderStyle="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a line, e.g. Solid (default), Dashed...'); viewDocumentation('Attribute', 'borderStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> borderWidth="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the width of a given border.'); viewDocumentation('Attribute', 'borderWidth', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fillColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color contained within the line or border of an object, default white.'); viewDocumentation('Attribute', 'fillColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> shapeType="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a two dimensional object, e.g. Rectangle (default), Nucleus...'); viewDocumentation('Attribute', 'shapeType', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> zOrder="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The order of an object along the z-axis.'); viewDocumentation('Attribute', 'zOrder', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> rotation="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('A float value (rotation in radians).'); viewDocumentation('Attribute', 'rotation', docArray);">?</a>"</span>/&gt;  <span class="occurs">[1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The source for a comment.'); viewDocumentation('Attribute', 'source', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Descriptions or arbitrary notes for an object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Property<br /><span style="margin-left: 0.5em"> key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The key of a key-value pair.'); viewDocumentation('Attribute', 'key', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The value of a key-value pair.'); viewDocumentation('Attribute', 'value', docArray);">?</a>"</span>/&gt;  <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Key-value pair information for an object.'); viewDocumentation('Element', 'Property', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Annotation.'); viewDocumentation('Element', 'AnnotationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Citation.'); viewDocumentation('Element', 'CitationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Evidence.'); viewDocumentation('Element', 'EvidenceRef', docArray);">?</a></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Shape&gt;</div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Shapes&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Shapes_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Shapes_scbox_button" class="control" onclick="switchState('element_Shapes_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Shapes_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Shapes</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- Shapes --&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Shape</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Graphics</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;RectAttributes&quot; attribute group definition." href="#attributeGroup_RectAttributes">RectAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;FontAttributes&quot; attribute group definition." href="#attributeGroup_FontAttributes">FontAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ShapeStyleAttributes&quot; attribute group definition." href="#attributeGroup_ShapeStyleAttributes">ShapeStyleAttributes</a></span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CommentGroup&quot; group definition." href="#group_CommentGroup">CommentGroup</a></span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End Graphics related attributes--&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">elementId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">textLabel</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">groupRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End: Shape --&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Shapes_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Groups" class="name">Groups</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Groups</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>List of Groups. A group is a collection of structurally or functionally similar or related pathway elements.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Groups_xibox_button" class="control" onclick="switchState('element_Groups_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Groups_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Groups&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Group<br /><span style="margin-left: 0.5em"> elementId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The internal gpml unique identifier for an element.'); viewDocumentation('Attribute', 'elementId', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> textLabel="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The text label for a group.'); viewDocumentation('Attribute', 'textLabel', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> type="<span class="constraint">union of: [ [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Group'|'Complex'|'Pathway'|'Analog'|'Paralog'}) ], [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> ] ]</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The group type, e.g. Group (default), Complex, Pathway...'); viewDocumentation('Attribute', 'type', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> groupRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('When a pathway element is part of a gpml:Group, groupRef refers to the elementId of the parent group.'); viewDocumentation('Attribute', 'groupRef', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('A collection of structurally or functionally similar or related pathway elements.'); viewDocumentation('Element', 'Group', docArray);">?</a><br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; <span class="occurs">[0..1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics<br /><span style="margin-left: 0.5em"> centerX="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The middle of an object in the x-direction.'); viewDocumentation('Attribute', 'centerX', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> centerY="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The middle of an object in the y-direction.'); viewDocumentation('Attribute', 'centerY', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> width="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the x-dimensional length of an object.'); viewDocumentation('Attribute', 'width', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> height="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the y-dimensional length of an object.'); viewDocumentation('Attribute', 'height', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> textColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color of text, default black.'); viewDocumentation('Attribute', 'textColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontName="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The name of the collection of characters with a similar design, e.g. Arial (default)...'); viewDocumentation('Attribute', 'fontName', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontWeight="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Bold'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The thickness of the font used, e.g Normal (default) or Bold. A bold font has more weight.'); viewDocumentation('Attribute', 'fontWeight', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontStyle="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Italic'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Italic or Normal (default).'); viewDocumentation('Attribute', 'fontStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontDecoration="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Underline'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Underline or Normal (default).'); viewDocumentation('Attribute', 'fontDecoration', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontStrikethru="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Strikethru'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Strikethru or Normal (default).'); viewDocumentation('Attribute', 'fontStrikethru', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fontSize="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:nonNegativeInteger</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The point value for the size of the font.'); viewDocumentation('Attribute', 'fontSize', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> hAlign="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Left'|'Center'|'Right'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The horizontal alignment of displayed text: Left, Center (default), or Right.'); viewDocumentation('Attribute', 'hAlign', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> vAlign="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Top'|'Middle'|'Bottom'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The vertical alignment of displayed text: Top, Middle (default), or Bottom.'); viewDocumentation('Attribute', 'vAlign', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> borderColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color of a border, default black.'); viewDocumentation('Attribute', 'borderColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> borderStyle="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a line, e.g. Solid (default), Dashed...'); viewDocumentation('Attribute', 'borderStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> borderWidth="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the width of a given border.'); viewDocumentation('Attribute', 'borderWidth', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> fillColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color contained within the line or border of an object, default white.'); viewDocumentation('Attribute', 'fillColor', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> shapeType="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a two dimensional object, e.g. Rectangle (default), Nucleus...'); viewDocumentation('Attribute', 'shapeType', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> zOrder="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The order of an object along the z-axis.'); viewDocumentation('Attribute', 'zOrder', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> rotation="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('A float value (rotation in radians).'); viewDocumentation('Attribute', 'rotation', docArray);">?</a>"</span>/&gt;  <span class="occurs">[1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The source for a comment.'); viewDocumentation('Attribute', 'source', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Descriptions or arbitrary notes for an object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Property<br /><span style="margin-left: 0.5em"> key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The key of a key-value pair.'); viewDocumentation('Attribute', 'key', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The value of a key-value pair.'); viewDocumentation('Attribute', 'value', docArray);">?</a>"</span>/&gt;  <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Key-value pair information for an object.'); viewDocumentation('Element', 'Property', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Annotation.'); viewDocumentation('Element', 'AnnotationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Citation.'); viewDocumentation('Element', 'CitationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Evidence.'); viewDocumentation('Element', 'EvidenceRef', docArray);">?</a></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Group&gt;</div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Groups&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Groups_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Groups_scbox_button" class="control" onclick="switchState('element_Groups_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Groups_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Groups</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- Group --&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Group</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Graphics</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;RectAttributes&quot; attribute group definition." href="#attributeGroup_RectAttributes">RectAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;FontAttributes&quot; attribute group definition." href="#attributeGroup_FontAttributes">FontAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ShapeStyleAttributes&quot; attribute group definition." href="#attributeGroup_ShapeStyleAttributes">ShapeStyleAttributes</a></span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CommentGroup&quot; group definition." href="#group_CommentGroup">CommentGroup</a></span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">elementId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">textLabel</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">type</span>" <span class="scTag">default</span>="<span class="scContent">Group</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:union</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Group</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Complex</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Pathway</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Analog</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Paralog</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"/&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:union</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">groupRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End: Group --&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Groups_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Annotations" class="name">Annotations</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Annotations</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>List of Annotations. An annotation is a reference with additional information, e.g. some Ontology.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Annotations_xibox_button" class="control" onclick="switchState('element_Annotations_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Annotations_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Annotations&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Annotation<br /><span style="margin-left: 0.5em"> elementId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The internal gpml unique identifier for an element.'); viewDocumentation('Attribute', 'elementId', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The name, term, or text of an annotation. An Annotation must have a value and type.'); viewDocumentation('Attribute', 'value', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> type="<span class="constraint">union of: [ [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Undefined'|'Ontology'|'Taxonomy'}) ], [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> ] ]</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The type of an annotation, e.g. Undefined (default), Ontology, Taxonomy...'); viewDocumentation('Attribute', 'type', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('An annotation reference, e.g. Ontology (e.g.subcellular location), Taxonomy (e.g.organism)...'); viewDocumentation('Element', 'Annotation', docArray);">?</a><br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a database entry. An Annotation can have an Xref.'); viewDocumentation('Element', 'Xref', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Url&quot; element declaration." href="#element_Url">Url</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Url&quot; element declaration." href="#element_Url">Url</a>&gt; <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Link to a web address. An Annotation can have an Url.'); viewDocumentation('Element', 'Url', docArray);">?</a></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Annotation&gt;</div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Annotations&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Annotations_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Annotations_scbox_button" class="control" onclick="switchState('element_Annotations_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Annotations_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Annotations</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- Annotation --&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Annotation</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Url&quot; element declaration." href="#element_Url">Url</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">elementId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">value</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">type</span>" <span class="scTag">default</span>="<span class="scContent">Undefined</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:union</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Undefined</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Ontology</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Taxonomy</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"/&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:union</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End: Annotation --&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Annotations_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_AnnotationRef" class="name">AnnotationRef</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>AnnotationRef</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>Reference to a gpml:Annotation.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_AnnotationRef_xibox_button" class="control" onclick="switchState('element_AnnotationRef_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_AnnotationRef_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:AnnotationRef<br /><span style="margin-left: 0.5em"> elementRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('A elementRef indicates a child/parent relationship between objects. The elementRef of the child refers to the elementId of the parent.'); viewDocumentation('Attribute', 'elementRef', docArray);">?</a>"</span>&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a citation for an annotation.'); viewDocumentation('Element', 'CitationRef', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to an evidence for an annotation.'); viewDocumentation('Element', 'EvidenceRef', docArray);">?</a></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:AnnotationRef&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_AnnotationRef_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_AnnotationRef_scbox_button" class="control" onclick="switchState('element_AnnotationRef_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_AnnotationRef_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">AnnotationRef</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">elementRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_AnnotationRef_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Citations" class="name">Citations</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Citations</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>List of Citations. A citation is a reference to a source of information.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Citations_xibox_button" class="control" onclick="switchState('element_Citations_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Citations_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Citations&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Citation<br /><span style="margin-left: 0.5em"> elementId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The internal gpml unique identifier for an element.'); viewDocumentation('Attribute', 'elementId', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('A literature reference, citation, or work.'); viewDocumentation('Element', 'Citation', docArray);">?</a><br /><span class="group" style="margin-left: 1.5em">Start <a title="Look up 'Choice' in glossary" href="#term_Choice">Choice</a> <span class="occurs">[1]</span></span><br /><div style="margin-left: 3em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a database entry. A Citation must have either an Xref or Url, or both.'); viewDocumentation('Element', 'Xref', docArray);">?</a></div><div style="margin-left: 3em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Url&quot; element declaration." href="#element_Url">Url</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Url&quot; element declaration." href="#element_Url">Url</a>&gt; <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Link to a web address. A Citation must have either an Xref or Url, or both.'); viewDocumentation('Element', 'Url', docArray);">?</a></div><div style="margin-left: 3em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Url&quot; element declaration." href="#element_Url">Url</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Url&quot; element declaration." href="#element_Url">Url</a>&gt; <span class="occurs">[1]</span></div><span class="group" style="margin-left: 1.5em">End Choice</span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Citation&gt;</div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Citations&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Citations_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Citations_scbox_button" class="control" onclick="switchState('element_Citations_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Citations_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Citations</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- Citation --&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Citation</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:choice</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Url&quot; element declaration." href="#element_Url">Url</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Url&quot; element declaration." href="#element_Url">Url</a></span>"/&gt;</div>&lt;/<span class="scTag">xsd:choice</span>&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">elementId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End: Citation --&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Citations_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_CitationRef" class="name">CitationRef</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>CitationRef</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>Reference to a gpml:Citation.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_CitationRef_xibox_button" class="control" onclick="switchState('element_CitationRef_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_CitationRef_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:CitationRef<br /><span style="margin-left: 0.5em"> elementRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('A elementRef indicates a child/parent relationship between objects. The elementRef of the child refers to the elementId of the parent.'); viewDocumentation('Attribute', 'elementRef', docArray);">?</a>"</span>&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to an annotation for a citation.'); viewDocumentation('Element', 'AnnotationRef', docArray);">?</a></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:CitationRef&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_CitationRef_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_CitationRef_scbox_button" class="control" onclick="switchState('element_CitationRef_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_CitationRef_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">CitationRef</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">elementRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_CitationRef_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Evidences" class="name">Evidences</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Evidences</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>List of Evidence. An evidence provides information on type of scientific evidence.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Evidences_xibox_button" class="control" onclick="switchState('element_Evidences_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Evidences_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Evidences&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Evidence<br /><span style="margin-left: 0.5em"> elementId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The internal gpml unique identifier for an element.'); viewDocumentation('Attribute', 'elementId', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The name, term, or text of an evidence.'); viewDocumentation('Attribute', 'value', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Evidence in biological research.'); viewDocumentation('Element', 'Evidence', docArray);">?</a><br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a>&gt; <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a database entry. An Evidence must have an Xref.'); viewDocumentation('Element', 'Xref', docArray);">?</a></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Url&quot; element declaration." href="#element_Url">Url</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Url&quot; element declaration." href="#element_Url">Url</a>&gt; <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Link to a web address. An Evidence can have an Url.'); viewDocumentation('Element', 'Url', docArray);">?</a></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Evidence&gt;</div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Evidences&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Evidences_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Evidences_scbox_button" class="control" onclick="switchState('element_Evidences_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Evidences_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Evidences</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- Evidence --&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Evidence</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Xref&quot; element declaration." href="#element_Xref">Xref</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Url&quot; element declaration." href="#element_Url">Url</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">elementId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">value</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End: Evidence --&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Evidences_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_EvidenceRef" class="name">EvidenceRef</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>EvidenceRef</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>Reference to a gpml:Evidence.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_EvidenceRef_xibox_button" class="control" onclick="switchState('element_EvidenceRef_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_EvidenceRef_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:EvidenceRef<br /><span style="margin-left: 0.5em"> elementRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('A elementRef indicates a child/parent relationship between objects. The elementRef of the child refers to the elementId of the parent.'); viewDocumentation('Attribute', 'elementRef', docArray);">?</a>"</span>/&gt; </div>
</div>
<script type="text/javascript">
<!--
setState('element_EvidenceRef_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_EvidenceRef_scbox_button" class="control" onclick="switchState('element_EvidenceRef_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_EvidenceRef_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">EvidenceRef</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">elementRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_EvidenceRef_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Xref" class="name">Xref</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Xref</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>Reference to a database entry.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Xref_xibox_button" class="control" onclick="switchState('element_Xref_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Xref_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Xref<br /><span style="margin-left: 0.5em"> identifier="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The identifier of a PublicationXref or Xref object.'); viewDocumentation('Attribute', 'identifier', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> dataSource="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Specifies the datasource prefix (see BridgeDb DataSource Ontology at https://github.com/bridgedb/datasources/blob/main/datasources.tsv) for the identifier provided as an Xref.'); viewDocumentation('Attribute', 'dataSource', docArray);">?</a>"</span>/&gt; </div>
</div>
<script type="text/javascript">
<!--
setState('element_Xref_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Xref_scbox_button" class="control" onclick="switchState('element_Xref_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Xref_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Xref</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">identifier</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">dataSource</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Xref_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Url" class="name">Url</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Url</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>Link to a web address.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Url_xibox_button" class="control" onclick="switchState('element_Url_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Url_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Url<br /><span style="margin-left: 0.5em"> link="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The link to a web address.'); viewDocumentation('Attribute', 'link', docArray);">?</a>"</span>/&gt; </div>
</div>
<script type="text/javascript">
<!--
setState('element_Url_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Url_scbox_button" class="control" onclick="switchState('element_Url_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Url_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Url</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">link</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Url_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Point" class="name">Point</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Point</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>A location in 2-dimensional space defined by x and y coordinates.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Point_xibox_button" class="control" onclick="switchState('element_Point_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Point_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Point<br /><span style="margin-left: 0.5em"> elementId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The internal gpml unique identifier for an element.'); viewDocumentation('Attribute', 'elementId', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> arrowHead="<span class="constraint">union of: [ [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Undirected'|'Directed'|'Conversion'|'Inhibition'|'Catalysis'|'Stimulation'|'Binding'|'Translocation'|'TranscriptionTranslation'}) ], [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> ] ]</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The glyph at the ends of lines and interactions.'); viewDocumentation('Attribute', 'arrowHead', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> x="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The x coordinate of a point.'); viewDocumentation('Attribute', 'x', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> y="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The y coordinate of a point.'); viewDocumentation('Attribute', 'y', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> elementRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('An elementRef indicates a child/parent relationship between objects. The elementRef of the child refers to the elementId of the parent.'); viewDocumentation('Attribute', 'elementRef', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> relX="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('When a point is linked to an object, relX and relY are the relative coordinates on the object, where 0,0 is at the center and 1,1 at the bottom-right corner of the object.'); viewDocumentation('Attribute', 'relX', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> relY="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('When a point is linked to an object, relX and relY are the relative coordinates on the object, where 0,0 is at the center and 1,1 at the bottom-right corner of the object.'); viewDocumentation('Attribute', 'relY', docArray);">?</a>"</span>/&gt; </div>
</div>
<script type="text/javascript">
<!--
setState('element_Point_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Point_scbox_button" class="control" onclick="switchState('element_Point_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Point_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Point</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">elementId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">arrowHead</span>" <span class="scTag">default</span>="<span class="scContent">Undirected</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:union</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Undirected</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Directed</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Conversion</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Inhibition</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Catalysis</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Stimulation</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Binding</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Translocation</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">TranscriptionTranslation</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"/&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:union</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">x</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">y</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">elementRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">relX</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">relY</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Point_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Anchor" class="name">Anchor</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Anchor</td>
</tr>
<tr>
<th>Type</th>
<td>Locally-defined complex type</td>
</tr>
<tr>
<th>
<a title="Look up 'Nillable' in glossary" href="#term_Nillable">Nillable</a>
</th>
<td>no</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
<tr>
<th>Documentation</th>
<td>A connection point on a graphical line or an interaction, where another graphical line or interaction can be connected.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Anchor_xibox_button" class="control" onclick="switchState('element_Anchor_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Anchor_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Anchor<br /><span style="margin-left: 0.5em"> elementId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> position="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Proportional distance of an anchor along the line it belongs to, between 0 and 1.'); viewDocumentation('Attribute', 'position', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> shapeType="<span class="constraint">union of: [ [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Square'|'Circle'|'None'}) ], [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> ] ]</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual representation of an anchor, e.g. Square (default), Circle, None...'); viewDocumentation('Attribute', 'shapeType', docArray);">?</a>"</span>/&gt; </div>
</div>
<script type="text/javascript">
<!--
setState('element_Anchor_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Anchor_scbox_button" class="control" onclick="switchState('element_Anchor_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Anchor_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Anchor</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">elementId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">position</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">shapeType</span>" <span class="scTag">default</span>="<span class="scContent">Square</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:union</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Square</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Circle</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">None</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"/&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:union</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Anchor_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h2><a name="SchemaDefinitions">Global Definitions</a></h2>
<h3>Attribute Group: <a name="attributeGroup_RectAttributes" class="name">RectAttributes</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>RectAttributes</td>
</tr>
<tr>
<th>Documentation</th>
<td>Centering (position) and dimension properties for an object.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="attributeGroup_RectAttributes_xibox_button" class="control" onclick="switchState('attributeGroup_RectAttributes_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="attributeGroup_RectAttributes_xibox" class="contents">
<span style="margin-left: 0em"> centerX="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The middle of an object in the x-direction.'); viewDocumentation('Attribute', 'centerX', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> centerY="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The middle of an object in the y-direction.'); viewDocumentation('Attribute', 'centerY', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> width="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the x-dimensional length of an object.'); viewDocumentation('Attribute', 'width', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> height="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the y-dimensional length of an object.'); viewDocumentation('Attribute', 'height', docArray);">?</a>"</span>
</div>
<script type="text/javascript">
<!--
setState('attributeGroup_RectAttributes_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="attributeGroup_RectAttributes_scbox_button" class="control" onclick="switchState('attributeGroup_RectAttributes_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="attributeGroup_RectAttributes_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">name</span>="<span class="scContent">RectAttributes</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">centerX</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">centerY</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">width</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">height</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:attributeGroup</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('attributeGroup_RectAttributes_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Attribute Group: <a name="attributeGroup_FontAttributes" class="name">FontAttributes</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>FontAttributes</td>
</tr>
<tr>
<th>Documentation</th>
<td>Common font properties.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="attributeGroup_FontAttributes_xibox_button" class="control" onclick="switchState('attributeGroup_FontAttributes_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="attributeGroup_FontAttributes_xibox" class="contents">
<span style="margin-left: 0em"> textColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color of text, default black.'); viewDocumentation('Attribute', 'textColor', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> fontName="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The name of the collection of characters with a similar design, e.g. Arial (default)...'); viewDocumentation('Attribute', 'fontName', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> fontWeight="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Bold'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The thickness of the font used, e.g Normal (default) or Bold. A bold font has more weight.'); viewDocumentation('Attribute', 'fontWeight', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> fontStyle="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Italic'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Italic or Normal (default).'); viewDocumentation('Attribute', 'fontStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> fontDecoration="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Underline'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Underline or Normal (default).'); viewDocumentation('Attribute', 'fontDecoration', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> fontStrikethru="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Strikethru'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for Strikethru or Normal (default).'); viewDocumentation('Attribute', 'fontStrikethru', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> fontSize="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:nonNegativeInteger</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The point value for the size of the font.'); viewDocumentation('Attribute', 'fontSize', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> hAlign="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Left'|'Center'|'Right'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The horizontal alignment of displayed text: Left, Center (default), or Right.'); viewDocumentation('Attribute', 'hAlign', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> vAlign="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Top'|'Middle'|'Bottom'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The vertical alignment of displayed text: Top, Middle (default), or Bottom.'); viewDocumentation('Attribute', 'vAlign', docArray);">?</a>"</span>
</div>
<script type="text/javascript">
<!--
setState('attributeGroup_FontAttributes_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="attributeGroup_FontAttributes_scbox_button" class="control" onclick="switchState('attributeGroup_FontAttributes_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="attributeGroup_FontAttributes_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">name</span>="<span class="scContent">FontAttributes</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">textColor</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span></span>" <span class="scTag">default</span>="<span class="scContent">000000</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">fontName</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">default</span>="<span class="scContent">Arial</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">fontWeight</span>" <span class="scTag">default</span>="<span class="scContent">Normal</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Normal</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Bold</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">fontStyle</span>" <span class="scTag">default</span>="<span class="scContent">Normal</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Normal</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Italic</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">fontDecoration</span>" <span class="scTag">default</span>="<span class="scContent">Normal</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Normal</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Underline</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">fontStrikethru</span>" <span class="scTag">default</span>="<span class="scContent">Normal</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Normal</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Strikethru</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">fontSize</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:nonNegativeInteger</span></span>" <span class="scTag">default</span>="<span class="scContent">12</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">hAlign</span>" <span class="scTag">default</span>="<span class="scContent">Center</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Left</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Center</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Right</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">vAlign</span>" <span class="scTag">default</span>="<span class="scContent">Middle</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Top</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Middle</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Bottom</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div>&lt;/<span class="scTag">xsd:attributeGroup</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('attributeGroup_FontAttributes_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Attribute Group: <a name="attributeGroup_ShapeStyleAttributes" class="name">ShapeStyleAttributes</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>ShapeStyleAttributes</td>
</tr>
<tr>
<th>Documentation</th>
<td>Visual appearance of a two-dimensional object.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="attributeGroup_ShapeStyleAttributes_xibox_button" class="control" onclick="switchState('attributeGroup_ShapeStyleAttributes_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="attributeGroup_ShapeStyleAttributes_xibox" class="contents">
<span style="margin-left: 0em"> borderColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color of a border, default black.'); viewDocumentation('Attribute', 'borderColor', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> borderStyle="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a line, e.g. Solid (default), Dashed...'); viewDocumentation('Attribute', 'borderStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> borderWidth="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the width of a given border.'); viewDocumentation('Attribute', 'borderWidth', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> fillColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color contained within the line or border of an object, default white.'); viewDocumentation('Attribute', 'fillColor', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> shapeType="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a two dimensional object, e.g. Rectangle (default), Nucleus...'); viewDocumentation('Attribute', 'shapeType', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> zOrder="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The order of an object along the z-axis.'); viewDocumentation('Attribute', 'zOrder', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> rotation="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('A float value (rotation in radians).'); viewDocumentation('Attribute', 'rotation', docArray);">?</a>"</span>
</div>
<script type="text/javascript">
<!--
setState('attributeGroup_ShapeStyleAttributes_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="attributeGroup_ShapeStyleAttributes_scbox_button" class="control" onclick="switchState('attributeGroup_ShapeStyleAttributes_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="attributeGroup_ShapeStyleAttributes_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">name</span>="<span class="scContent">ShapeStyleAttributes</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">borderColor</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span></span>" <span class="scTag">default</span>="<span class="scContent">000000</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">borderStyle</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span></span>" <span class="scTag">default</span>="<span class="scContent">Solid</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">borderWidth</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">default</span>="<span class="scContent">1.0</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">fillColor</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span></span>" <span class="scTag">default</span>="<span class="scContent">ffffff</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">shapeType</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">default</span>="<span class="scContent">Rectangle</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">zOrder</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">rotation</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:attributeGroup</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('attributeGroup_ShapeStyleAttributes_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Attribute Group: <a name="attributeGroup_LineStyleAttributes" class="name">LineStyleAttributes</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>LineStyleAttributes</td>
</tr>
<tr>
<th>Documentation</th>
<td>Visual appearance of a line.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="attributeGroup_LineStyleAttributes_xibox_button" class="control" onclick="switchState('attributeGroup_LineStyleAttributes_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="attributeGroup_LineStyleAttributes_xibox" class="contents">
<span style="margin-left: 0em"> lineColor="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hexadecimal color of a line, default black.'); viewDocumentation('Attribute', 'lineColor', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> lineStyle="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a line, e.g. Solid (default), Dashed...'); viewDocumentation('Attribute', 'lineStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> lineWidth="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the width of a given line.'); viewDocumentation('Attribute', 'lineWidth', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> connectorType="<span class="constraint">union of: [ [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Straight'|'Elbow'|'Curved'|'Segmented'}) ], [ <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> ] ]</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Specifies a set of rules to govern layout of lines, e.g. Straight (default), Elbow...'); viewDocumentation('Attribute', 'connectorType', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> zOrder="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The order of an object along the z-axis.'); viewDocumentation('Attribute', 'zOrder', docArray);">?</a>"</span>
</div>
<script type="text/javascript">
<!--
setState('attributeGroup_LineStyleAttributes_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="attributeGroup_LineStyleAttributes_scbox_button" class="control" onclick="switchState('attributeGroup_LineStyleAttributes_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="attributeGroup_LineStyleAttributes_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">name</span>="<span class="scContent">LineStyleAttributes</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">lineColor</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span></span>" <span class="scTag">default</span>="<span class="scContent">000000</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">lineStyle</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span></span>" <span class="scTag">default</span>="<span class="scContent">Solid</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">lineWidth</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">default</span>="<span class="scContent">1.0</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">connectorType</span>" <span class="scTag">default</span>="<span class="scContent">Straight</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:union</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Straight</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Elbow</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Curved</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Segmented</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"/&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:union</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">zOrder</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:attributeGroup</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('attributeGroup_LineStyleAttributes_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Simple Type: <a name="type_StyleType" class="name">StyleType</a>
</h3>
<table class="hierarchy">
<tr>
<th>Super-types:</th>
<td>None</td>
</tr>
<tr>
<th>Sub-types:</th>
<td>None</td>
</tr>
</table>
<table class="properties">
<tr>
<th>Name</th>
<td>StyleType</td>
</tr>
<tr>
<th>Content</th>
<td>
<ul><li>Union of following types: <ul>
<li>Locally defined type:<ul><li>Base XSD Type: string</li></ul>
<ul>
<li>
<em>value</em> comes from list: {'Solid'|'Dashed'|'Double'}</li>
</ul>
</li>
<li>Locally defined type:<ul><li>Base XSD Type: string</li></ul>
</li>
</ul>
</li></ul>
</td>
</tr>
<tr>
<th>Documentation</th>
<td>Style type for a line or border, e.g. Solid, Dashed...</td>
</tr>
</table>
<div class="schemaComponent box">
<div>
<input type="button" id="type_StyleType_scbox_button" class="control" onclick="switchState('type_StyleType_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="type_StyleType_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:simpleType</span> <span class="scTag">name</span>="<span class="scContent">StyleType</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:union</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Solid</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Dashed</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Double</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"/&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:union</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('type_StyleType_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Simple Type: <a name="type_Dimension" class="name">Dimension</a>
</h3>
<table class="hierarchy">
<tr>
<th>Super-types:</th>
<td>
<span class="type">
<a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> &lt; <strong>Dimension</strong> (by restriction)</td>
</tr>
<tr>
<th>Sub-types:</th>
<td>None</td>
</tr>
</table>
<table class="properties">
<tr>
<th>Name</th>
<td>Dimension</td>
</tr>
<tr>
<th>Content</th>
<td>
<ul><li>Base XSD Type: float</li></ul>
<ul>
<li>
<em>value</em> &gt;= 0</li>
</ul>
</td>
</tr>
<tr>
<th>Documentation</th>
<td>Dimension for width or height. Cannot be a negative value.</td>
</tr>
</table>
<div class="schemaComponent box">
<div>
<input type="button" id="type_Dimension_scbox_button" class="control" onclick="switchState('type_Dimension_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="type_Dimension_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:simpleType</span> <span class="scTag">name</span>="<span class="scContent">Dimension</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:minInclusive</span> <span class="scTag">value</span>="<span class="scContent">0</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('type_Dimension_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Model Group: <a name="group_CommentGroup" class="name">CommentGroup</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>CommentGroup</td>
</tr>
<tr>
<th>Documentation</th>
<td>One or more comments, properties, or references.</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="group_CommentGroup_xibox_button" class="control" onclick="switchState('group_CommentGroup_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="group_CommentGroup_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The source for a comment.'); viewDocumentation('Attribute', 'source', docArray);">?</a>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Descriptions or arbitrary notes for an object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Property<br /><span style="margin-left: 0.5em"> key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The key of a key-value pair.'); viewDocumentation('Attribute', 'key', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The value of a key-value pair.'); viewDocumentation('Attribute', 'value', docArray);">?</a>"</span>/&gt;  <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Key-value pair information for an object.'); viewDocumentation('Element', 'Property', docArray);">?</a></div><div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Annotation.'); viewDocumentation('Element', 'AnnotationRef', docArray);">?</a></div><div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Citation.'); viewDocumentation('Element', 'CitationRef', docArray);">?</a></div><div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a>&gt; <span class="occurs">[0..*]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Reference to a gpml:Evidence.'); viewDocumentation('Element', 'EvidenceRef', docArray);">?</a></div>
</div>
<script type="text/javascript">
<!--
setState('group_CommentGroup_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="group_CommentGroup_scbox_button" class="control" onclick="switchState('group_CommentGroup_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="group_CommentGroup_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">name</span>="<span class="scContent">CommentGroup</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Comment</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleContent</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:extension</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">source</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"/&gt;</div>&lt;/<span class="scTag">xsd:extension</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleContent</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Property</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">key</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">value</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;AnnotationRef&quot; element declaration." href="#element_AnnotationRef">AnnotationRef</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CitationRef&quot; element declaration." href="#element_CitationRef">CitationRef</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;EvidenceRef&quot; element declaration." href="#element_EvidenceRef">EvidenceRef</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div>&lt;/<span class="scTag">xsd:group</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('group_CommentGroup_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<div id="legend">
<h2><a name="Legend">Legend</a></h2>
<div style="float: left; width: 15em;">
<h3 style="margin-bottom: 0px;">Complex Type:</h3>
<div class="hint" style="margin-left: 0em;">Schema Component Type</div>
</div>
<div style="float: left; width: 15em;">
<h3 style="margin-bottom: 0px;"><span class="name">AusAddress</span></h3>
<div class="hint" style="margin-left: 0em;">Schema Component Name</div>
</div>
<table class="hierarchy" style="clear : both">
<tr>
<th>Super-types:</th>
<td>
<span class="type" style="color: #0000FF; text-decoration:underline;">Address</span> &lt; <span class="current">AusAddress</span> (by extension)</td>
</tr>
<tr>
<th>Sub-types:</th>
<td>
<ul>
<li>
<span class="type" style="color: #0000FF; text-decoration:underline;">QLDAddress</span> (by restriction)</li>
</ul>
</td>
</tr>
</table>
<div class="hint">If this schema component is a type definition, its type hierarchy is shown in a gray-bordered box.</div>
<table class="properties">
<tr>
<th>Name</th>
<td>AusAddress</td>
</tr>
<tr>
<th>
<a title="Look up 'Abstract' in glossary" href="#term_Abstract">Abstract</a>
</th>
<td>no</td>
</tr>
</table>
<div class="hint">The table above displays the properties of this schema component.</div>
<div class="sample box">
<div>
<span class="caption">XML Instance Representation</span>
</div>
<div class="contents">
<span style="margin-left: 0em">&lt;...</span>
<span class="newFields">
<span> country="<span class="fixed">Australia</span>"</span>
</span>&gt; <br />
<span style="margin-left: 1.5em" class="inherited">&lt;unitNo&gt; <span class="type">string</span> &lt;/unitNo&gt; <span class="occurs">[0..1]</span></span><br />
<span style="margin-left: 1.5em" class="inherited">&lt;houseNo&gt; <span class="type">string</span> &lt;/houseNo&gt; <span class="occurs">[1]</span></span><br />
<span style="margin-left: 1.5em" class="inherited">&lt;street&gt; <span class="type">string</span> &lt;/street&gt; <span class="occurs">[1]</span></span><br />
<span class="group" style="margin-left: 1.5em">Start <a title="Look up 'Choice' in glossary" href="#term_Choice">Choice</a>
<span class="occurs">[1]</span></span><br />
<span style="margin-left: 3em" class="inherited">&lt;city&gt; <span class="type">string</span> &lt;/city&gt; <span class="occurs">[1]</span></span><br />
<span style="margin-left: 3em" class="inherited">&lt;town&gt; <span class="type">string</span> &lt;/town&gt; <span class="occurs">[1]</span></span><br />
<span class="group" style="margin-left: 1.5em">End Choice</span><br />
<span class="newFields">
<span style="margin-left: 1.5em">&lt;state&gt; <span class="type" style="text-decoration:underline;">AusStates</span> &lt;/state&gt; <span class="occurs">[1]</span></span><br />
<span style="margin-left: 1.5em">&lt;postcode&gt; <span class="constraint">string &lt;&lt;<em>pattern</em> = [1-9][0-9]{3}&gt;&gt;</span> &lt;/postcode&gt; <span class="occurs">[1]</span>
<a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Post code must be a four-digit number.'); viewDocumentation('Element', 'postcode', docArray);">?</a>
</span><br />
</span>
<span style="margin-left: 0em">&lt;/...&gt;</span><br />
</div>
</div>
<div class="hint">
<p>The XML Instance Representation table above shows the schema component's content as an XML instance.</p>
<ul>
<li>The minimum and maximum occurrence of elements and attributes are provided in square brackets, e.g. [0..1].</li>
<li>Model group information are shown in gray, e.g. Start Choice ... End Choice.</li>
<li>For type derivations, the elements and attributes that have been added to or changed from the base type's content are shown in <span style="font-weight: bold">bold</span>.</li>
<li>If an element/attribute has a fixed value, the fixed value is shown in green, e.g. country="Australia".</li>
<li>Otherwise, the type of the element/attribute is displayed.
               <ul>
<li>If the element/attribute's type is in the schema, a link is provided to it.</li>
<li>For local simple type definitions, the constraints are displayed in angle brackets, e.g. &lt;&lt;<em>pattern</em> = [1-9][0-9]{3}&gt;&gt;.</li>
</ul>
</li>
<li>If a local element/attribute has documentation, it will be displayed in a window that pops up when the question mark inside the attribute or next to the element is clicked, e.g. &lt;postcode&gt;.</li>
</ul>
</div>
<div class="schemaComponent box">
<div>
<span class="caption">Schema Component Representation</span>
</div>
<div class="contents">
<span style="margin-left: 0em">&lt;<span class="scTag">complexType</span>
<span class="scTag">name</span>="<span class="scContent">AusAddress</span>"&gt;</span><br />
<span style="margin-left: 1.5em">&lt;<span class="scTag">complexContent</span>&gt;</span><br />
<span style="margin-left: 3em">&lt;<span class="scTag">extension</span>
<span class="scTag">base</span>="<span class="scContent"><span class="type" style="text-decoration:underline;">Address</span></span>"&gt;</span><br />
<span style="margin-left: 4.5em">&lt;<span class="scTag">sequence</span>&gt;</span><br />
<span style="margin-left: 6em">&lt;<span class="scTag">element</span>
<span class="scTag">name</span>="<span class="scContent">state</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type" style="text-decoration:underline;">AusStates</span></span>"/&gt;</span><br />
<span style="margin-left: 6em">&lt;<span class="scTag">element</span>
<span class="scTag">name</span>="<span class="scContent">postcode</span>"&gt;</span><br />
<span style="margin-left: 7.5em">&lt;<span class="scTag">simpleType</span>&gt;</span><br />
<span style="margin-left: 9em">&lt;<span class="scTag">restriction</span>
<span class="scTag">base</span>="<span class="scContent"><span class="type">string</span></span>"&gt;</span><br />
<span style="margin-left: 10.5em">&lt;<span class="scTag">pattern</span>
<span class="scTag">value</span>="<span class="scContent">[1-9][0-9]{3}</span>"/&gt;</span><br />
<span style="margin-left: 9em">&lt;/<span class="scTag">restriction</span>&gt;</span><br />
<span style="margin-left: 7.5em">&lt;/<span class="scTag">simpleType</span>&gt;</span><br />
<span style="margin-left: 6em">&lt;/<span class="scTag">element</span>&gt;</span><br />
<span style="margin-left: 4.5em">&lt;/<span class="scTag">sequence</span>&gt;</span><br />
<span style="margin-left: 4.5em">&lt;<span class="scTag">attribute</span>
<span class="scTag">name</span>="<span class="scContent">country</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type">string</span></span>" <span class="scTag">fixed</span>="<span class="scContent">Australia</span>"/&gt;</span><br />
<span style="margin-left: 3em">&lt;/<span class="scTag">extension</span>&gt;</span><br />
<span style="margin-left: 1.5em">&lt;/<span class="scTag">complexContent</span>&gt;</span><br />
<span style="margin-left: 0em">&lt;/<span class="scTag">complexType</span>&gt;</span><br />
</div>
</div>
<div class="hint">The Schema Component Representation table above displays the underlying XML representation of the schema component. (Annotations are not shown.)</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
</div>
<div id="glossary">
<h2><a name="Glossary">Glossary</a></h2>
<p>
<span class="glossaryTerm">
<a name="term_Abstract">Abstract</a> </span>(Applies to complex type definitions and element declarations). An abstract element or complex type cannot used to validate an element instance. If there is a reference to an abstract element, only element declarations that can substitute the abstract element can be used to validate the instance. For references to abstract type definitions, only derived types can be used.</p>
<p>
<span class="glossaryTerm">
<a name="term_All">All Model Group</a> </span>Child elements can be provided <em>in any order</em> in instances. See: <a title="http://www.w3.org/TR/xmlschema-1/#element-all" href="http://www.w3.org/TR/xmlschema-1/#element-all">http://www.w3.org/TR/xmlschema-1/#element-all</a>.</p>
<p>
<span class="glossaryTerm">
<a name="term_Choice">Choice Model Group</a> </span>
<em>Only one</em> from the list of child elements and model groups can be provided in instances. See: <a title="http://www.w3.org/TR/xmlschema-1/#element-choice" href="http://www.w3.org/TR/xmlschema-1/#element-choice">http://www.w3.org/TR/xmlschema-1/#element-choice</a>.</p>
<p>
<span class="glossaryTerm">
<a name="term_CollapseWS">Collapse Whitespace Policy</a> </span>Replace tab, line feed, and carriage return characters with space character (Unicode character 32). Then, collapse contiguous sequences of space characters into single space character, and remove leading and trailing space characters.</p>
<p>
<span class="glossaryTerm">
<a name="term_ElemBlock">Disallowed Substitutions</a> </span>(Applies to element declarations). If <em>substitution</em> is specified, then <a title="Look up 'substitution group' in glossary" href="#term_SubGroup">substitution group</a> members cannot be used in place of the given element declaration to validate element instances. If <em>derivation methods</em>, e.g. extension, restriction, are specified, then the given element declaration will not validate element instances that have types derived from the element declaration's type using the specified derivation methods. Normally, element instances can override their declaration's type by specifying an <code>xsi:type</code> attribute.</p>
<p>
<span class="glossaryTerm">
<a name="term_Key">Key Constraint</a> </span>Like <a title="Look up 'Uniqueness Constraint' in glossary" href="#term_Unique">Uniqueness Constraint</a>, but additionally requires that the specified value(s) must be provided. See: <a title="http://www.w3.org/TR/xmlschema-1/#cIdentity-constraint_Definitions" href="http://www.w3.org/TR/xmlschema-1/#cIdentity-constraint_Definitions">http://www.w3.org/TR/xmlschema-1/#cIdentity-constraint_Definitions</a>.</p>
<p>
<span class="glossaryTerm">
<a name="term_KeyRef">Key Reference Constraint</a> </span>Ensures that the specified value(s) must match value(s) from a <a title="Look up 'Key Constraint' in glossary" href="#term_Key">Key Constraint</a> or <a title="Look up 'Uniqueness Constraint' in glossary" href="#term_Unique">Uniqueness Constraint</a>. See: <a title="http://www.w3.org/TR/xmlschema-1/#cIdentity-constraint_Definitions" href="http://www.w3.org/TR/xmlschema-1/#cIdentity-constraint_Definitions">http://www.w3.org/TR/xmlschema-1/#cIdentity-constraint_Definitions</a>.</p>
<p>
<span class="glossaryTerm">
<a name="term_ModelGroup">Model Group</a> </span>Groups together element content, specifying the order in which the element content can occur and the number of times the group of element content may be repeated. See: <a title="http://www.w3.org/TR/xmlschema-1/#Model_Groups" href="http://www.w3.org/TR/xmlschema-1/#Model_Groups">http://www.w3.org/TR/xmlschema-1/#Model_Groups</a>.</p>
<p>
<span class="glossaryTerm">
<a name="term_Nillable">Nillable</a> </span>(Applies to element declarations). If an element declaration is nillable, instances can use the <code>xsi:nil</code> attribute. The <code>xsi:nil</code> attribute is the boolean attribute, <em>nil</em>, from the <em>http://www.w3.org/2001/XMLSchema-instance</em> namespace. If an element instance has an <code>xsi:nil</code> attribute set to true, it can be left empty, even though its element declaration may have required content.</p>
<p>
<span class="glossaryTerm">
<a name="term_Notation">Notation</a> </span>A notation is used to identify the format of a piece of data. Values of elements and attributes that are of type, NOTATION, must come from the names of declared notations. See: <a title="http://www.w3.org/TR/xmlschema-1/#cNotation_Declarations" href="http://www.w3.org/TR/xmlschema-1/#cNotation_Declarations">http://www.w3.org/TR/xmlschema-1/#cNotation_Declarations</a>.</p>
<p>
<span class="glossaryTerm">
<a name="term_PreserveWS">Preserve Whitespace Policy</a> </span>Preserve whitespaces exactly as they appear in instances.</p>
<p>
<span class="glossaryTerm">
<a name="term_TypeFinal">Prohibited Derivations</a> </span>(Applies to type definitions). Derivation methods that cannot be used to create sub-types from a given type definition.</p>
<p>
<span class="glossaryTerm">
<a name="term_TypeBlock">Prohibited Substitutions</a> </span>(Applies to complex type definitions). Prevents sub-types that have been derived using the specified derivation methods from validating element instances in place of the given type definition.</p>
<p>
<span class="glossaryTerm">
<a name="term_ReplaceWS">Replace Whitespace Policy</a> </span>Replace tab, line feed, and carriage return characters with space character (Unicode character 32).</p>
<p>
<span class="glossaryTerm">
<a name="term_Sequence">Sequence Model Group</a> </span>Child elements and model groups must be provided <em>in the specified order</em> in instances. See: <a title="http://www.w3.org/TR/xmlschema-1/#element-sequence" href="http://www.w3.org/TR/xmlschema-1/#element-sequence">http://www.w3.org/TR/xmlschema-1/#element-sequence</a>.</p>
<p>
<span class="glossaryTerm">
<a name="term_SubGroup">Substitution Group</a> </span>Elements that are <em>members</em> of a substitution group can be used wherever the <em>head</em> element of the substitution group is referenced.</p>
<p>
<span class="glossaryTerm">
<a name="term_ElemFinal">Substitution Group Exclusions</a> </span>(Applies to element declarations). Prohibits element declarations from nominating themselves as being able to substitute a given element declaration, if they have types that are derived from the original element's type using the specified derivation methods.</p>
<p>
<span class="glossaryTerm">
<a name="term_TargetNS">Target Namespace</a> </span>The target namespace identifies the namespace that components in this schema belongs to. If no target namespace is provided, then the schema components do not belong to any namespace.</p>
<p>
<span class="glossaryTerm">
<a name="term_Unique">Uniqueness Constraint</a> </span>Ensures uniqueness of an element/attribute value, or a combination of values, within a specified scope. See: <a title="http://www.w3.org/TR/xmlschema-1/#cIdentity-constraint_Definitions" href="http://www.w3.org/TR/xmlschema-1/#cIdentity-constraint_Definitions">http://www.w3.org/TR/xmlschema-1/#cIdentity-constraint_Definitions</a>.</p>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
</div>
<p class="footer">Generated by <a href="http://xml.fiforms.org/xs3p/">xs3p</a> (<a href="http://titanium.dstc.edu.au/xml/xs3p">old link</a>)
               . Last modified: <script type="text/javascript">
<!--
document.write(document.lastModified);
// -->
</script>
</p>
</body>
</html>
