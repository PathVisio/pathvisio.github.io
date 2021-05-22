<html>
<head>
<title>GPML Schema 2013a Documentation</title>
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
var xiBoxes = new Array('attributeGroup_FontAttributes_xibox', 'attributeGroup_RectAttributes_xibox', 'attributeGroup_ShapeStyleAttributes_xibox', 'type_RotationType_xibox', 'type_ColorType_xibox', 'type_StyleType_xibox', 'type_Dimension_xibox', 'group_CommentGroup_xibox', 'element_Pathway_xibox', 'element_DataNode_xibox', 'element_State_xibox', 'element_GraphicalLine_xibox', 'element_Interaction_xibox', 'element_Label_xibox', 'element_Shape_xibox', 'element_Group_xibox', 'element_InfoBox_xibox', 'element_Legend_xibox', 'element_Biopax_xibox');
/* IDs of Schema Component Representation boxes */
var scBoxes = new Array('schema_scbox', 'attributeGroup_FontAttributes_scbox', 'attributeGroup_RectAttributes_scbox', 'attributeGroup_ShapeStyleAttributes_scbox', 'type_RotationType_scbox', 'type_ColorType_scbox', 'type_StyleType_scbox', 'type_Dimension_scbox', 'group_CommentGroup_scbox', 'element_Pathway_scbox', 'element_DataNode_scbox', 'element_State_scbox', 'element_GraphicalLine_scbox', 'element_Interaction_scbox', 'element_Label_scbox', 'element_Shape_scbox', 'element_Group_scbox', 'element_InfoBox_scbox', 'element_Legend_scbox', 'element_Biopax_scbox');

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
<h1><a name="top">GPML Schema Documentation</a></h1>
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
<a href="#element_DataNode">Element: <strong>DataNode</strong>
</a>
</li>
<li>
<a href="#element_State">Element: <strong>State</strong>
</a>
</li>
<li>
<a href="#element_GraphicalLine">Element: <strong>GraphicalLine</strong>
</a>
</li>
<li>
<a href="#element_Interaction">Element: <strong>Interaction</strong>
</a>
</li>
<li>
<a href="#element_Label">Element: <strong>Label</strong>
</a>
</li>
<li>
<a href="#element_Shape">Element: <strong>Shape</strong>
</a>
</li>
<li>
<a href="#element_Group">Element: <strong>Group</strong>
</a>
</li>
<li>
<a href="#element_InfoBox">Element: <strong>InfoBox</strong>
</a>
</li>
<li>
<a href="#element_Legend">Element: <strong>Legend</strong>
</a>
</li>
<li>
<a href="#element_Biopax">Element: <strong>Biopax</strong>
</a>
</li>
</ul>
</li>
<li><a href="#SchemaDefinitions">Global Definitions</a>
<ul>
<li>
<a href="#attributeGroup_FontAttributes">Attribute Group: <strong>FontAttributes</strong>
</a>
</li>
<li>
<a href="#attributeGroup_RectAttributes">Attribute Group: <strong>RectAttributes</strong>
</a>
</li>
<li>
<a href="#attributeGroup_ShapeStyleAttributes">Attribute Group: <strong>ShapeStyleAttributes</strong>
</a>
</li>
<li>
<a href="#type_RotationType">Simple Type: <strong>RotationType</strong>
</a>
</li>
<li>
<a href="#type_ColorType">Simple Type: <strong>ColorType</strong>
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
<span class="targetNS">http://pathvisio.org/GPML/2013a</span>
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
<span class="targetNS">http://pathvisio.org/GPML/2013a</span>
</td>
</tr>
</table>
<div class="schemaComponent box">
<div>
<input type="button" id="schema_scbox_button" class="control" onclick="switchState('schema_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="schema_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:schema</span> <span class="scTag">targetNamespace</span>="<span class="scContent">http://pathvisio.org/GPML/2013a</span>" <span class="scTag">elementFormDefault</span>="<span class="scContent">qualified</span>"&gt;<div class="scContent" style="margin-left: 1.5em">...</div>&lt;/<span class="scTag">xsd:schema</span>&gt;</div>
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
<td>
				A graph diagram representing a biological process as a set of interactions
				and relationships among genes, proteins, metabolites, and other factors in
				the context of cellular compartments, tissues and organisms.
			</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Pathway_xibox_button" class="control" onclick="switchState('element_Pathway_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Pathway_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Pathway<br /><span style="margin-left: 0.5em"> Name="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The name of a pathway.'); viewDocumentation('Attribute', 'Name', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Organism="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The scientific name (e.g., Homo sapiens) of the species being described by the pathway.'); viewDocumentation('Attribute', 'Organism', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Data-Source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> Version="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The version of a Pathway (currently not used in WP).'); viewDocumentation('Attribute', 'Version', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Author="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The people who created/edited the pathway in question.'); viewDocumentation('Attribute', 'Author', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Maintainer="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The people who edited/maintained the pathway in question.'); viewDocumentation('Attribute', 'Maintainer', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Email="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> License="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The license of a pathway.'); viewDocumentation('Attribute', 'License', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Last-Modified="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Last modification date, in the form of YYYYMMDD'); viewDocumentation('Attribute', 'Last-Modified', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> BiopaxRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> Source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Elements used to provide descriptions and arbitrary notes for a given object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:PublicationXref<br /><span style="margin-left: 0.5em"> ID="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Database="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Attribute<br /><span style="margin-left: 0.5em"> Key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics<br /><span style="margin-left: 0.5em"> BoardWidth="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> BoardHeight="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;DataNode&quot; element declaration." href="#element_DataNode">DataNode</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;DataNode&quot; element declaration." href="#element_DataNode">DataNode</a>&gt; <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;State&quot; element declaration." href="#element_State">State</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;State&quot; element declaration." href="#element_State">State</a>&gt; <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Interaction&quot; element declaration." href="#element_Interaction">Interaction</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Interaction&quot; element declaration." href="#element_Interaction">Interaction</a>&gt; <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;GraphicalLine&quot; element declaration." href="#element_GraphicalLine">GraphicalLine</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;GraphicalLine&quot; element declaration." href="#element_GraphicalLine">GraphicalLine</a>&gt; <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Label&quot; element declaration." href="#element_Label">Label</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Label&quot; element declaration." href="#element_Label">Label</a>&gt; <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Shape&quot; element declaration." href="#element_Shape">Shape</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Shape&quot; element declaration." href="#element_Shape">Shape</a>&gt; <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Group&quot; element declaration." href="#element_Group">Group</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Group&quot; element declaration." href="#element_Group">Group</a>&gt; <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;InfoBox&quot; element declaration." href="#element_InfoBox">InfoBox</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;InfoBox&quot; element declaration." href="#element_InfoBox">InfoBox</a>&gt; <span class="occurs">[1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Legend&quot; element declaration." href="#element_Legend">Legend</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Legend&quot; element declaration." href="#element_Legend">Legend</a>&gt; <span class="occurs">[0..1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Biopax&quot; element declaration." href="#element_Biopax">Biopax</a>&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Biopax&quot; element declaration." href="#element_Biopax">Biopax</a>&gt; <span class="occurs">[0..1]</span></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Pathway&gt;</div>
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
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Pathway</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CommentGroup&quot; group definition." href="#group_CommentGroup">CommentGroup</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Graphics</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">BoardWidth</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">BoardHeight</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;DataNode&quot; element declaration." href="#element_DataNode">DataNode</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;State&quot; element declaration." href="#element_State">State</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Interaction&quot; element declaration." href="#element_Interaction">Interaction</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;GraphicalLine&quot; element declaration." href="#element_GraphicalLine">GraphicalLine</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Label&quot; element declaration." href="#element_Label">Label</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Shape&quot; element declaration." href="#element_Shape">Shape</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Group&quot; element declaration." href="#element_Group">Group</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;InfoBox&quot; element declaration." href="#element_InfoBox">InfoBox</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Legend&quot; element declaration." href="#element_Legend">Legend</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Biopax&quot; element declaration." href="#element_Biopax">Biopax</a></span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Name</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"&gt;<div class="comment" style="margin-left: 1.5em">&lt;--  GenMAPP Pathway Title --&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Organism</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- Organism is not a field in the
						GenMAPP database at this time, but we want to preserve this
						information when importing maps, and also when exporting maps.
						GenMAPP maps have the organism implied from the
						filename. --&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Data-Source</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- On import to GenMAPP,
						Data-Source value could be 'KEGG', 'Cytoscape', etc.  On export
						from GenMAPP, value should be 'GenMAPP' with version
						number. 
					Deprecated in 2017 version
				--&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Version</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- GenMAPP version, use for export
					of maps from GenMAPP only. --&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Author</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Maintainer</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Email</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">License</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Last-Modified</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">BiopaxRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Pathway_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_DataNode" class="name">DataNode</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>DataNode</td>
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
<td>
				Denotes a biological entity that forms a node in a pathway and
				has some biological meaning associated with it. For a list of
				the gpml:DataNode types supported at WikiPathways, see subclasses
				of wp:DataNode or the wpTypes vocabulary defined for use in applications.
			</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_DataNode_xibox_button" class="control" onclick="switchState('element_DataNode_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_DataNode_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:DataNode<br /><span style="margin-left: 0.5em"> BiopaxRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> GraphId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> GroupRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> TextLabel="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Type="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Basic GPML types are:\&quot;Protein\&quot;, \&quot;Rna\&quot;, \&quot;Complex\&quot;, \&quot;GeneProduct\&quot;, \&quot;Metabolite\&quot; and \&quot;Unknown\&quot;.'); viewDocumentation('Attribute', 'Type', docArray);">?</a>"</span>&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> Source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Elements used to provide descriptions and arbitrary notes for a given object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:PublicationXref<br /><span style="margin-left: 0.5em"> ID="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Database="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Attribute<br /><span style="margin-left: 0.5em"> Key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics<br /><span style="margin-left: 0.5em"> CenterX="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Middle of a pathway element in the x-direction.'); viewDocumentation('Attribute', 'CenterX', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> CenterY="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Middle of a pathway element in the y-direction.'); viewDocumentation('Attribute', 'CenterY', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Width="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the x-dimensional length of a pathway element.'); viewDocumentation('Attribute', 'Width', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Height="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the y-dimensional length of a pathway element.'); viewDocumentation('Attribute', 'Height', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontName="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The name of the set of printable text characters to be used for visualization.'); viewDocumentation('Attribute', 'FontName', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontStyle="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Italic'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style or font face applied to displayed text, e.g., Arial.'); viewDocumentation('Attribute', 'FontStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontDecoration="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Underline'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for underline or normal.'); viewDocumentation('Attribute', 'FontDecoration', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontStrikethru="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Strikethru'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for strikethru or normal.'); viewDocumentation('Attribute', 'FontStrikethru', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontWeight="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Bold'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Thickness of the font used, e.g a bold font would have more weight. Used for DataNodes, Labels and Shapes.'); viewDocumentation('Attribute', 'FontWeight', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontSize="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:nonNegativeInteger</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The point value for the size of the font.'); viewDocumentation('Attribute', 'FontSize', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Align="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Left'|'Center'|'Right'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Horizontal alignment of displayed text, e.g., Left, Center, Right.'); viewDocumentation('Attribute', 'Align', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Valign="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Top'|'Middle'|'Bottom'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Vertical alignment of displayed text, e.g., Top, Middle, Bottom.'); viewDocumentation('Attribute', 'Valign', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Color="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The color to be used for visualization.'); viewDocumentation('Attribute', 'Color', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> LineStyle="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a line or border, e.g., Solid or Broken.'); viewDocumentation('Attribute', 'LineStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> LineThickness="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the width of a given line, interaction or border.'); viewDocumentation('Attribute', 'LineThickness', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FillColor="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> ShapeType="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> ZOrder="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span> <span class="occurs">[0..1]</span>"</span>/&gt;  <span class="occurs">[1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Xref<br /><span style="margin-left: 0.5em"> Database="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> ID="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[1]</span></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:DataNode&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_DataNode_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_DataNode_scbox_button" class="control" onclick="switchState('element_DataNode_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_DataNode_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">DataNode</span>"&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- 
			DataNode is the old GeneProduct, a gene in GenMAPP terminology. 
			DataNode represents all possible biological entities in a pathway
				like GeneProduct, Metabolite, Pathway, Protein, RNA, Unknown.
		--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CommentGroup&quot; group definition." href="#group_CommentGroup">CommentGroup</a></span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Graphics</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;RectAttributes&quot; attribute group definition." href="#attributeGroup_RectAttributes">RectAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;FontAttributes&quot; attribute group definition." href="#attributeGroup_FontAttributes">FontAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ShapeStyleAttributes&quot; attribute group definition." href="#attributeGroup_ShapeStyleAttributes">ShapeStyleAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">FillColor</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span></span>" <span class="scTag">default</span>="<span class="scContent">White</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ShapeType</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">default</span>="<span class="scContent">Rectangle</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ZOrder</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Xref</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Database</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ID</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">BiopaxRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GraphId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GroupRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">TextLabel</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Type</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">default</span>="<span class="scContent">Unknown</span>"&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- Old versions of GPML only allowed these values for Type: 
				It's recommended that you use these values as often as possible. --&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_DataNode_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_State" class="name">State</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>State</td>
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
<td>
				Always linked to a DataNode representing a specific state of the biological 
				entity (e.g. phosphorylation, genetic variants, etc)
			</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_State_xibox_button" class="control" onclick="switchState('element_State_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_State_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:State<br /><span style="margin-left: 0.5em"> BiopaxRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> GraphId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> GraphRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> TextLabel="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> StateType="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> Source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Elements used to provide descriptions and arbitrary notes for a given object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:PublicationXref<br /><span style="margin-left: 0.5em"> ID="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Database="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Attribute<br /><span style="margin-left: 0.5em"> Key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics<br /><span style="margin-left: 0.5em"> RelX="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> RelY="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Width="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Height="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Color="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The color to be used for visualization.'); viewDocumentation('Attribute', 'Color', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> LineStyle="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a line or border, e.g., Solid or Broken.'); viewDocumentation('Attribute', 'LineStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> LineThickness="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the width of a given line, interaction or border.'); viewDocumentation('Attribute', 'LineThickness', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FillColor="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> ShapeType="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> ZOrder="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span> <span class="occurs">[0..1]</span>"</span>/&gt;  <span class="occurs">[1]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Xref<br /><span style="margin-left: 0.5em"> Database="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> ID="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..1]</span></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:State&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_State_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_State_scbox_button" class="control" onclick="switchState('element_State_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_State_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">State</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CommentGroup&quot; group definition." href="#group_CommentGroup">CommentGroup</a></span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Graphics</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">RelX</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">RelY</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Width</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Height</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ShapeStyleAttributes&quot; attribute group definition." href="#attributeGroup_ShapeStyleAttributes">ShapeStyleAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">FillColor</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span></span>" <span class="scTag">default</span>="<span class="scContent">White</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ShapeType</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">default</span>="<span class="scContent">Rectangle</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ZOrder</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Xref</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Database</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ID</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">BiopaxRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GraphId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GraphRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">TextLabel</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">StateType</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">default</span>="<span class="scContent">Unknown</span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- Biological modification type. suggested values: Phosphorylated, Glycosylated, Activated, ... !--&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_State_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_GraphicalLine" class="name">GraphicalLine</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>GraphicalLine</td>
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
<td>
				A visual annotation, often used to partition space or connect other annotation,
				e.g., Shapes. GrapicalLine are graphical annotations without semantic meaning
				An Xref cannot be specified for GraphicalLines (in contrast to Interactions).
			</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_GraphicalLine_xibox_button" class="control" onclick="switchState('element_GraphicalLine_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_GraphicalLine_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:GraphicalLine<br /><span style="margin-left: 0.5em"> GroupRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> BiopaxRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> GraphId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> Type="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> Source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Elements used to provide descriptions and arbitrary notes for a given object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:PublicationXref<br /><span style="margin-left: 0.5em"> ID="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Database="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Attribute<br /><span style="margin-left: 0.5em"> Key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics<br /><span style="margin-left: 0.5em"> Color="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> LineThickness="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> LineStyle="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> ConnectorType="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> ZOrder="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span> <span class="occurs">[0..1]</span>"</span>&gt;  <span class="occurs">[1]</span> <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Point<br /><span style="margin-left: 0.5em"> X="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Y="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> RelX="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> RelY="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> GraphRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> GraphId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> ArrowHead="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>/&gt;  <span class="occurs">[2..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Anchor<br /><span style="margin-left: 0.5em"> Position="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> GraphId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> Shape="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics&gt;</div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:GraphicalLine&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_GraphicalLine_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_GraphicalLine_scbox_button" class="control" onclick="switchState('element_GraphicalLine_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_GraphicalLine_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">GraphicalLine</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CommentGroup&quot; group definition." href="#group_CommentGroup">CommentGroup</a></span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Graphics</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Point</span>" <span class="scTag">minOccurs</span>="<span class="scContent">2</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">X</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Y</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- relX and relY are the coordinates used when
	                                a point is linked to another object (when GraphRef
	                                is defined). They represent he coordinates of the
	                                point relative to the object that it's linked to, where
	                                0,0 lies at the center of the object and 1,1 at the bottom-right
	                                corner --&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">RelX</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">RelY</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GraphRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GraphId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- Note: only the ArrowHead attribute on first and last points are used, the rest is ignored. !--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ArrowHead</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">default</span>="<span class="scContent">Line</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Anchor</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Position</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GraphId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Shape</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">default</span>="<span class="scContent">ReceptorRound</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Color</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span></span>" <span class="scTag">default</span>="<span class="scContent">Black</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">LineThickness</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">LineStyle</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span></span>" <span class="scTag">default</span>="<span class="scContent">Solid</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ConnectorType</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>" <span class="scTag">default</span>="<span class="scContent">Straight</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ZOrder</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End Graphics related attributes--&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GroupRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">BiopaxRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GraphId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Type</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_GraphicalLine_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Interaction" class="name">Interaction</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Interaction</td>
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
<td>
				Defines the biochemical relationship between DataNodes
				or with Anchors on other Interactions. An Xref can be
				specified for Interactions (in contrast to GraphicalLines).
			</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Interaction_xibox_button" class="control" onclick="switchState('element_Interaction_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Interaction_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Interaction<br /><span style="margin-left: 0.5em"> GroupRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> BiopaxRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> GraphId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> Type="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> Source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Elements used to provide descriptions and arbitrary notes for a given object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:PublicationXref<br /><span style="margin-left: 0.5em"> ID="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Database="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Attribute<br /><span style="margin-left: 0.5em"> Key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics<br /><span style="margin-left: 0.5em"> Color="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> LineThickness="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> LineStyle="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> ConnectorType="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> ZOrder="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span> <span class="occurs">[0..1]</span>"</span>&gt;  <span class="occurs">[1]</span> <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Point<br /><span style="margin-left: 0.5em"> X="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Y="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> RelX="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> RelY="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> GraphRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> GraphId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> ArrowHead="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>/&gt;  <span class="occurs">[2..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Anchor<br /><span style="margin-left: 0.5em"> Position="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> GraphId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> Shape="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Xref<br /><span style="margin-left: 0.5em"> Database="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> ID="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[1]</span></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Interaction&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Interaction_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Interaction_scbox_button" class="control" onclick="switchState('element_Interaction_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Interaction_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Interaction</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CommentGroup&quot; group definition." href="#group_CommentGroup">CommentGroup</a></span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Graphics</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Point</span>" <span class="scTag">minOccurs</span>="<span class="scContent">2</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">X</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Y</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- relX and relY are the coordinates used when
	                                a point is linked to another object (when GraphRef
	                                is defined). They represent he coordinates of the
	                                point relative to the object that it's linked to, where
	                                0,0 lies at the center of the object and 1,1 at the bottom-right
	                                corner --&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">RelX</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">RelY</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GraphRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:IDREF</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GraphId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- Note: only the ArrowHead attribute on first and last points are used, the rest is ignored. !--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ArrowHead</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">default</span>="<span class="scContent">Line</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Anchor</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Position</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GraphId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Shape</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">default</span>="<span class="scContent">ReceptorRound</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Color</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span></span>" <span class="scTag">default</span>="<span class="scContent">Black</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">LineThickness</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">LineStyle</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span></span>" <span class="scTag">default</span>="<span class="scContent">Solid</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ConnectorType</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>" <span class="scTag">default</span>="<span class="scContent">Straight</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ZOrder</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Xref</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Database</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ID</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GroupRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">BiopaxRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GraphId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Type</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Interaction_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Label" class="name">Label</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Label</td>
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
<td>
				A text field which can be used to annotate any aspect of a pathway.
			</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Label_xibox_button" class="control" onclick="switchState('element_Label_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Label_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Label<br /><span style="margin-left: 0.5em"> Href="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The hyperlink optionally specified in a Label for a reference to a url.'); viewDocumentation('Attribute', 'Href', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> BiopaxRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> GraphId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> GroupRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> TextLabel="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> Source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Elements used to provide descriptions and arbitrary notes for a given object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:PublicationXref<br /><span style="margin-left: 0.5em"> ID="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Database="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Attribute<br /><span style="margin-left: 0.5em"> Key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics<br /><span style="margin-left: 0.5em"> CenterX="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Middle of a pathway element in the x-direction.'); viewDocumentation('Attribute', 'CenterX', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> CenterY="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Middle of a pathway element in the y-direction.'); viewDocumentation('Attribute', 'CenterY', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Width="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the x-dimensional length of a pathway element.'); viewDocumentation('Attribute', 'Width', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Height="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the y-dimensional length of a pathway element.'); viewDocumentation('Attribute', 'Height', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontName="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The name of the set of printable text characters to be used for visualization.'); viewDocumentation('Attribute', 'FontName', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontStyle="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Italic'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style or font face applied to displayed text, e.g., Arial.'); viewDocumentation('Attribute', 'FontStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontDecoration="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Underline'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for underline or normal.'); viewDocumentation('Attribute', 'FontDecoration', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontStrikethru="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Strikethru'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for strikethru or normal.'); viewDocumentation('Attribute', 'FontStrikethru', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontWeight="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Bold'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Thickness of the font used, e.g a bold font would have more weight. Used for DataNodes, Labels and Shapes.'); viewDocumentation('Attribute', 'FontWeight', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontSize="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:nonNegativeInteger</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The point value for the size of the font.'); viewDocumentation('Attribute', 'FontSize', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Align="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Left'|'Center'|'Right'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Horizontal alignment of displayed text, e.g., Left, Center, Right.'); viewDocumentation('Attribute', 'Align', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Valign="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Top'|'Middle'|'Bottom'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Vertical alignment of displayed text, e.g., Top, Middle, Bottom.'); viewDocumentation('Attribute', 'Valign', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Color="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The color to be used for visualization.'); viewDocumentation('Attribute', 'Color', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> LineStyle="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a line or border, e.g., Solid or Broken.'); viewDocumentation('Attribute', 'LineStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> LineThickness="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the width of a given line, interaction or border.'); viewDocumentation('Attribute', 'LineThickness', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FillColor="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> ShapeType="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> ZOrder="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span> <span class="occurs">[0..1]</span>"</span>/&gt;  <span class="occurs">[1]</span></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Label&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Label_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Label_scbox_button" class="control" onclick="switchState('element_Label_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Label_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Label</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div class="comment" style="margin-left: 1.5em">&lt;--  This is text on a GenMAPP map that
				can have associated comments. --&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CommentGroup&quot; group definition." href="#group_CommentGroup">CommentGroup</a></span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Graphics</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;RectAttributes&quot; attribute group definition." href="#attributeGroup_RectAttributes">RectAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;FontAttributes&quot; attribute group definition." href="#attributeGroup_FontAttributes">FontAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ShapeStyleAttributes&quot; attribute group definition." href="#attributeGroup_ShapeStyleAttributes">ShapeStyleAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">FillColor</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span></span>" <span class="scTag">default</span>="<span class="scContent">Transparent</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ShapeType</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">default</span>="<span class="scContent">None</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ZOrder</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End Graphics related attributes--&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Href</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">BiopaxRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GraphId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GroupRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">TextLabel</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Label_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Shape" class="name">Shape</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Shape</td>
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
<td>
				Shape can refer to two different things in GPML,
				both of which are associated with graphical elements.
			</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Shape_xibox_button" class="control" onclick="switchState('element_Shape_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Shape_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Shape<br /><span style="margin-left: 0.5em"> BiopaxRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> GraphId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> GroupRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> TextLabel="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> Source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Elements used to provide descriptions and arbitrary notes for a given object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:PublicationXref<br /><span style="margin-left: 0.5em"> ID="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Database="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Attribute<br /><span style="margin-left: 0.5em"> Key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Graphics<br /><span style="margin-left: 0.5em"> CenterX="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Middle of a pathway element in the x-direction.'); viewDocumentation('Attribute', 'CenterX', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> CenterY="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Middle of a pathway element in the y-direction.'); viewDocumentation('Attribute', 'CenterY', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Width="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the x-dimensional length of a pathway element.'); viewDocumentation('Attribute', 'Width', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Height="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the y-dimensional length of a pathway element.'); viewDocumentation('Attribute', 'Height', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontName="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The name of the set of printable text characters to be used for visualization.'); viewDocumentation('Attribute', 'FontName', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontStyle="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Italic'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style or font face applied to displayed text, e.g., Arial.'); viewDocumentation('Attribute', 'FontStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontDecoration="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Underline'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for underline or normal.'); viewDocumentation('Attribute', 'FontDecoration', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontStrikethru="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Strikethru'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for strikethru or normal.'); viewDocumentation('Attribute', 'FontStrikethru', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontWeight="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Bold'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Thickness of the font used, e.g a bold font would have more weight. Used for DataNodes, Labels and Shapes.'); viewDocumentation('Attribute', 'FontWeight', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FontSize="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:nonNegativeInteger</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The point value for the size of the font.'); viewDocumentation('Attribute', 'FontSize', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Align="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Left'|'Center'|'Right'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Horizontal alignment of displayed text, e.g., Left, Center, Right.'); viewDocumentation('Attribute', 'Align', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Valign="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Top'|'Middle'|'Bottom'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Vertical alignment of displayed text, e.g., Top, Middle, Bottom.'); viewDocumentation('Attribute', 'Valign', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> Color="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The color to be used for visualization.'); viewDocumentation('Attribute', 'Color', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> LineStyle="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a line or border, e.g., Solid or Broken.'); viewDocumentation('Attribute', 'LineStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> LineThickness="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the width of a given line, interaction or border.'); viewDocumentation('Attribute', 'LineThickness', docArray);">?</a>"</span><br /><span style="margin-left: 0.5em"> FillColor="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> ShapeType="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> ZOrder="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> Rotation="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;RotationType&quot; type definition." href="#type_RotationType">RotationType</a></span> <span class="occurs">[0..1]</span>"</span>/&gt;  <span class="occurs">[1]</span></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Shape&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Shape_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Shape_scbox_button" class="control" onclick="switchState('element_Shape_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Shape_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Shape</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CommentGroup&quot; group definition." href="#group_CommentGroup">CommentGroup</a></span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- Graphics related attributes--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Graphics</span>" <span class="scTag">minOccurs</span>="<span class="scContent">1</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">1</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;RectAttributes&quot; attribute group definition." href="#attributeGroup_RectAttributes">RectAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;FontAttributes&quot; attribute group definition." href="#attributeGroup_FontAttributes">FontAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ShapeStyleAttributes&quot; attribute group definition." href="#attributeGroup_ShapeStyleAttributes">ShapeStyleAttributes</a></span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">FillColor</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span></span>" <span class="scTag">default</span>="<span class="scContent">Transparent</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ShapeType</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ZOrder</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:integer</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Rotation</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;RotationType&quot; type definition." href="#type_RotationType">RotationType</a></span></span>" <span class="scTag">default</span>="<span class="scContent">Top</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- End Graphics related attributes--&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">BiopaxRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GraphId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GroupRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">TextLabel</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Shape_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Group" class="name">Group</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Group</td>
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
<td>
				A collection of structurally or functionally similar or related pathway elements.
			</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Group_xibox_button" class="control" onclick="switchState('element_Group_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Group_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Group<br /><span style="margin-left: 0.5em"> BiopaxRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> GroupId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> GroupRef="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> Style="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> TextLabel="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span><br /><span style="margin-left: 0.5em"> GraphId="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span> <span class="occurs">[0..1]</span>"</span>&gt; <br /><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> Source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Elements used to provide descriptions and arbitrary notes for a given object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:PublicationXref<br /><span style="margin-left: 0.5em"> ID="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Database="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; <span class="occurs">[0..*]</span></div><div style="margin-left: 1.5em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Attribute<br /><span style="margin-left: 0.5em"> Key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Group&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Group_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Group_scbox_button" class="control" onclick="switchState('element_Group_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Group_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Group</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">ref</span>="<span class="scContent"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;CommentGroup&quot; group definition." href="#group_CommentGroup">CommentGroup</a></span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">BiopaxRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GroupId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GroupRef</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Style</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">default</span>="<span class="scContent">None</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">TextLabel</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">GraphId</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:ID</span></span>" <span class="scTag">use</span>="<span class="scContent">optional</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Group_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_InfoBox" class="name">InfoBox</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>InfoBox</td>
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
<td>
				InfoBox element holds the coordinates on the GenMAPP layout where the 
				Information kept in the	Info table will be displayed in the mapp.
			</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_InfoBox_xibox_button" class="control" onclick="switchState('element_InfoBox_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_InfoBox_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:InfoBox<br /><span style="margin-left: 0.5em"> CenterX="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> CenterY="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span>"</span>/&gt; </div>
</div>
<script type="text/javascript">
<!--
setState('element_InfoBox_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_InfoBox_scbox_button" class="control" onclick="switchState('element_InfoBox_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_InfoBox_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">InfoBox</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">CenterX</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">CenterY</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_InfoBox_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Legend" class="name">Legend</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Legend</td>
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
<td>
				An explanatory list of the colors used for visualizing data on the pathway. 
				Not currently used.
			</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Legend_xibox_button" class="control" onclick="switchState('element_Legend_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Legend_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Legend<br /><span style="margin-left: 0.5em"> CenterX="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> CenterY="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span>"</span>/&gt; </div>
</div>
<script type="text/javascript">
<!--
setState('element_Legend_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Legend_scbox_button" class="control" onclick="switchState('element_Legend_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Legend_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Legend</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">CenterX</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">CenterY</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Legend_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Element: <a name="element_Biopax" class="name">Biopax</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>Biopax</td>
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
<td>
				Integration of annotation, references, and ontology from Biopax. 
			</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="element_Biopax_xibox_button" class="control" onclick="switchState('element_Biopax_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="element_Biopax_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Biopax&gt; <br /><div class="other" style="margin-left: 1.5em">Allow any elements from the following namespace(s): http://www.biopax.org/release/biopax-level3.owl# (skip validation). <span class="occurs">[0..*]</span></div>&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Biopax&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Biopax_xibox', true);
// -->
</script>
</div>
<div class="schemaComponent box">
<div>
<input type="button" id="element_Biopax_scbox_button" class="control" onclick="switchState('element_Biopax_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="element_Biopax_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Biopax</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:any</span> <span class="scTag">namespace</span>="<span class="scContent">http://www.biopax.org/release/biopax-level3.owl#</span>" <span class="scTag">processContents</span>="<span class="scContent">skip</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('element_Biopax_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h2><a name="SchemaDefinitions">Global Definitions</a></h2>
<h3>Attribute Group: <a name="attributeGroup_FontAttributes" class="name">FontAttributes</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>FontAttributes</td>
</tr>
<tr>
<th>Documentation</th>
<td>
				Common font properties. 
			</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="attributeGroup_FontAttributes_xibox_button" class="control" onclick="switchState('attributeGroup_FontAttributes_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="attributeGroup_FontAttributes_xibox" class="contents">
<span style="margin-left: 0em"> FontName="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The name of the set of printable text characters to be used for visualization.'); viewDocumentation('Attribute', 'FontName', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> FontStyle="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Italic'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style or font face applied to displayed text, e.g., Arial.'); viewDocumentation('Attribute', 'FontStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> FontDecoration="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Underline'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for underline or normal.'); viewDocumentation('Attribute', 'FontDecoration', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> FontStrikethru="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Strikethru'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The typographic style for strikethru or normal.'); viewDocumentation('Attribute', 'FontStrikethru', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> FontWeight="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Normal'|'Bold'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Thickness of the font used, e.g a bold font would have more weight. Used for DataNodes, Labels and Shapes.'); viewDocumentation('Attribute', 'FontWeight', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> FontSize="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:nonNegativeInteger</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The point value for the size of the font.'); viewDocumentation('Attribute', 'FontSize', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> Align="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Left'|'Center'|'Right'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Horizontal alignment of displayed text, e.g., Left, Center, Right.'); viewDocumentation('Attribute', 'Align', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> Valign="<span class="constraint"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> (<em>value</em> comes from list: {'Top'|'Middle'|'Bottom'})</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Vertical alignment of displayed text, e.g., Top, Middle, Bottom.'); viewDocumentation('Attribute', 'Valign', docArray);">?</a>"</span>
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
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">name</span>="<span class="scContent">FontAttributes</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">FontName</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">default</span>="<span class="scContent">Arial</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">FontStyle</span>" <span class="scTag">default</span>="<span class="scContent">Normal</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Normal</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Italic</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">FontDecoration</span>" <span class="scTag">default</span>="<span class="scContent">Normal</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Normal</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Underline</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">FontStrikethru</span>" <span class="scTag">default</span>="<span class="scContent">Normal</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Normal</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Strikethru</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">FontWeight</span>" <span class="scTag">default</span>="<span class="scContent">Normal</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Normal</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Bold</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">FontSize</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:nonNegativeInteger</span></span>" <span class="scTag">default</span>="<span class="scContent">12</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Align</span>" <span class="scTag">default</span>="<span class="scContent">Center</span>"&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- Horizontal alignment --&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Left</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Center</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Right</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Valign</span>" <span class="scTag">default</span>="<span class="scContent">Top</span>"&gt;<div class="comment" style="margin-left: 1.5em">&lt;-- Vertical alignment --&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Top</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Middle</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Bottom</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:attribute</span>&gt;</div>&lt;/<span class="scTag">xsd:attributeGroup</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('attributeGroup_FontAttributes_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Attribute Group: <a name="attributeGroup_RectAttributes" class="name">RectAttributes</a>
</h3>
<table class="properties">
<tr>
<th>Name</th>
<td>RectAttributes</td>
</tr>
<tr>
<th>Documentation</th>
<td>
				Group of attributes for a pathway element, e.g. rectangular node.  
			</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="attributeGroup_RectAttributes_xibox_button" class="control" onclick="switchState('attributeGroup_RectAttributes_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="attributeGroup_RectAttributes_xibox" class="contents">
<span style="margin-left: 0em"> CenterX="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Middle of a pathway element in the x-direction.'); viewDocumentation('Attribute', 'CenterX', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> CenterY="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Middle of a pathway element in the y-direction.'); viewDocumentation('Attribute', 'CenterY', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> Width="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the x-dimensional length of a pathway element.'); viewDocumentation('Attribute', 'Width', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> Height="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span> <span class="occurs">[1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the y-dimensional length of a pathway element.'); viewDocumentation('Attribute', 'Height', docArray);">?</a>"</span>
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
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">name</span>="<span class="scContent">RectAttributes</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">CenterX</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">CenterY</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Width</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Height</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;Dimension&quot; type definition." href="#type_Dimension">Dimension</a></span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:attributeGroup</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('attributeGroup_RectAttributes_scbox', false);
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
<td>
				Group of attributes defining the style (e.g. color, line style) of a pathway element.   
			</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="attributeGroup_ShapeStyleAttributes_xibox_button" class="control" onclick="switchState('attributeGroup_ShapeStyleAttributes_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="attributeGroup_ShapeStyleAttributes_xibox" class="contents">
<span style="margin-left: 0em"> Color="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The color to be used for visualization.'); viewDocumentation('Attribute', 'Color', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> LineStyle="<span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The visual appearance of a line or border, e.g., Solid or Broken.'); viewDocumentation('Attribute', 'LineStyle', docArray);">?</a>"</span><br /><span style="margin-left: 0em"> LineThickness="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span> <span class="occurs">[0..1]</span> <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('The pixel value for the width of a given line, interaction or border.'); viewDocumentation('Attribute', 'LineThickness', docArray);">?</a>"</span>
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
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:attributeGroup</span> <span class="scTag">name</span>="<span class="scContent">ShapeStyleAttributes</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Color</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;ColorType&quot; type definition." href="#type_ColorType">ColorType</a></span></span>" <span class="scTag">default</span>="<span class="scContent">Black</span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- 2017 adds fillColor attribute --&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">LineStyle</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:<a title="Jump to &quot;StyleType&quot; type definition." href="#type_StyleType">StyleType</a></span></span>" <span class="scTag">default</span>="<span class="scContent">Solid</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">LineThickness</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>" <span class="scTag">default</span>="<span class="scContent">1.0</span>"/&gt;</div>&lt;/<span class="scTag">xsd:attributeGroup</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('attributeGroup_ShapeStyleAttributes_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Simple Type: <a name="type_RotationType" class="name">RotationType</a>
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
<td>RotationType</td>
</tr>
<tr>
<th>Content</th>
<td>
<ul><li>Union of following types: <ul>
<li>Locally defined type:<ul><li>Base XSD Type: string</li></ul>
<ul>
<li>
<em>value</em> comes from list: {'Top'|'Right'|'Bottom'|'Left'}</li>
</ul>
</li>
<li>Locally defined type:<ul><li>Base XSD Type: float</li></ul>
</li>
</ul>
</li></ul>
</td>
</tr>
<tr>
<th>Documentation</th>
<td>
				 A float value (rotation in radians) or a string (Top, Right, Bottom, Left) 
				 for each of the four right angles.
			</td>
</tr>
</table>
<div class="schemaComponent box">
<div>
<input type="button" id="type_RotationType_scbox_button" class="control" onclick="switchState('type_RotationType_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="type_RotationType_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:simpleType</span> <span class="scTag">name</span>="<span class="scContent">RotationType</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:union</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Top</span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- rotation of 0.0 !--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Right</span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- rotation of 1/2 pi !--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Bottom</span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- rotation of 1 pi !--&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Left</span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- rotation of 3/2 pi !--&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:float</span></span>"/&gt;</div><div class="comment" style="margin-left: 1.5em">&lt;-- rotation is always measured in radians !--&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:union</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('type_RotationType_scbox', false);
// -->
</script>
</div>
<div style="text-align: right; clear: both;"><a href="#top">top</a></div>
<hr />
<h3>Simple Type: <a name="type_ColorType" class="name">ColorType</a>
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
<td>ColorType</td>
</tr>
<tr>
<th>Content</th>
<td>
<ul><li>Union of following types: <ul>
<li>Locally defined type:<ul><li>Base XSD Type: hexBinary</li></ul>
</li>
<li>Locally defined type:<ul><li>Base XSD Type: string</li></ul>
<ul>
<li>
<em>value</em> comes from list: {'Aqua'|'Black'|'Blue'|'Fuchsia'|'Gray'|'Green'|'Lime'|'Maroon'|'Navy'|'Olive'|'Purple'|'Red'|'Silver'|'Teal'|'White'|'Yellow'|'Transparent'}</li>
</ul>
</li>
</ul>
</li></ul>
</td>
</tr>
<tr>
<th>Documentation</th>
<td>
				Color as a hexadecimal number, binary code, or string (enumerated colors).
			</td>
</tr>
</table>
<div class="schemaComponent box">
<div>
<input type="button" id="type_ColorType_scbox_button" class="control" onclick="switchState('type_ColorType_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="type_ColorType_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:simpleType</span> <span class="scTag">name</span>="<span class="scContent">ColorType</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:union</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:hexBinary</span></span>"/&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Aqua</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Black</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Blue</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Fuchsia</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Gray</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Green</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Lime</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Maroon</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Navy</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Olive</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Purple</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Red</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Silver</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Teal</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">White</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Yellow</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Transparent</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>&lt;/<span class="scTag">xsd:union</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>
</div>
<script type="text/javascript">
<!--
setState('type_ColorType_scbox', false);
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
<td>
<span class="type">
<a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> &lt; <strong>StyleType</strong> (by restriction)</td>
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
<ul><li>Base XSD Type: string</li></ul>
<ul>
<li>
<em>value</em> comes from list: {'Solid'|'Broken'}</li>
</ul>
</td>
</tr>
</table>
<div class="schemaComponent box">
<div>
<input type="button" id="type_StyleType_scbox_button" class="control" onclick="switchState('type_StyleType_scbox'); return false;" style="display: none" /> <span class="caption">Schema Component Representation</span>
</div>
<div id="type_StyleType_scbox" class="contents">
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:simpleType</span> <span class="scTag">name</span>="<span class="scContent">StyleType</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:restriction</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Solid</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:enumeration</span> <span class="scTag">value</span>="<span class="scContent">Broken</span>"/&gt;</div>&lt;/<span class="scTag">xsd:restriction</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleType</span>&gt;</div>
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
<td>
				Dimension for width and height. Cannot be negative values. 
			</td>
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
<td>
				One or more comments, references, and key value attributes.  
			</td>
</tr>
</table>
<div class="sample box">
<div>
<input type="button" id="group_CommentGroup_xibox_button" class="control" onclick="switchState('group_CommentGroup_xibox'); return false;" style="display: none" /> <span class="caption">XML Instance Representation</span>
</div>
<div id="group_CommentGroup_xibox" class="contents">
<div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment<br /><span style="margin-left: 0.5em"> Source="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[0..1]</span>"</span>&gt;  <span class="occurs">[0..*]</span>  <a href="javascript:void(0)" title="View Documentation" class="documentation" onclick="docArray = new Array('Elements used to provide descriptions and arbitrary notes for a given object.'); viewDocumentation('Element', 'Comment', docArray);">?</a><br /><span style="margin-left: 1.5em"> <span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> </span><br />&lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Comment&gt;</div><div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:PublicationXref<br /><span style="margin-left: 0.5em"> ID="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Database="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div><div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; ... &lt;/<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:BiopaxRef&gt; <span class="occurs">[0..*]</span></div><div style="margin-left: 0em">&lt;<a href="#ns_gpml" title="Find out namespace of 'gpml' prefix">gpml</a>:Attribute<br /><span style="margin-left: 0.5em"> Key="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span><br /><span style="margin-left: 0.5em"> Value="<span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span> <span class="occurs">[1]</span>"</span>/&gt;  <span class="occurs">[0..*]</span></div>
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
<div style="margin-left: 0em">&lt;<span class="scTag">xsd:group</span> <span class="scTag">name</span>="<span class="scContent">CommentGroup</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:sequence</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Comment</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:simpleContent</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:extension</span> <span class="scTag">base</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Source</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>"/&gt;</div>&lt;/<span class="scTag">xsd:extension</span>&gt;</div>&lt;/<span class="scTag">xsd:simpleContent</span>&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">PublicationXref</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">ID</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Database</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">BiopaxRef</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:element</span> <span class="scTag">name</span>="<span class="scContent">Attribute</span>" <span class="scTag">minOccurs</span>="<span class="scContent">0</span>" <span class="scTag">maxOccurs</span>="<span class="scContent">unbounded</span>"&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:complexType</span>&gt;<div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Key</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div><div style="margin-left: 1.5em">&lt;<span class="scTag">xsd:attribute</span> <span class="scTag">name</span>="<span class="scContent">Value</span>" <span class="scTag">type</span>="<span class="scContent"><span class="type"><a href="#ns_xsd" title="Find out namespace of 'xsd' prefix">xsd</a>:string</span></span>" <span class="scTag">use</span>="<span class="scContent">required</span>"/&gt;</div>&lt;/<span class="scTag">xsd:complexType</span>&gt;</div>&lt;/<span class="scTag">xsd:element</span>&gt;</div>&lt;/<span class="scTag">xsd:sequence</span>&gt;</div>&lt;/<span class="scTag">xsd:group</span>&gt;</div>
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
