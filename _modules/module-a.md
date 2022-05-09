---
title: "A Step: Augment the Data Deposit"
layout: module
---

<style>

.highlighted-text {
    padding: 0 0 5px 5px;
    border: 1px solid;
    border-color: #ffffff;
    border-radius: 4px;
    margin: 15px 5px 10px 0;
    background-color: rgba(68, 114, 155, 0.1);
    padding-top: 10px;
    padding-left: 8px;

}
</style>


<br>

<blockquote class = "highlighted-text">
<h2>Learning Outcomes</h2>
<b> Curators will be able to: </b>


<p>
  &nbsp;&nbsp;1. Evaluate metadata profiles and README documentation for discovery, access, and linkages.
   <br>
  &nbsp;&nbsp;2. Complete metadata profiles and README documentation to enhance discovery, access, and linkages.
   <br>
  &nbsp;&nbsp;3. Add or replace files supplemented by the depositor from the Request step and any inforamtion gathered in the Understand step.
    <br>

</p>
</blockquote>

<br>
<br>

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
.collapsible {
  background-color: #44729B;
  color: white;
  cursor: pointer;
  padding-bottom: 30px;
  padding-top: 30px;
  padding-left: 20px;
  width: 100%;
  border: none;
  border-bottom: 3px solid white;
  text-align: left;
  outline: none;
}
.active, .collapsible:hover {
  background-color: #345878;
}
.content {
  padding: 0 20px;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
  background-color: rgb(68,114,155,0.2);
}
.collapsible:after {
  color: #ffffff;
  content: "+";
  font-size: 20px;
  float: right;
  margin-left: 5px;
  padding-right: 10px;
}
.active:after {
  content: "-";
  color: #ffffff;
  font-size: 20px;
  padding-right: 10px;
}
</style>
</head>

<body>

<h2>Terms to know</h2>

<br>
<br>

<button class="collapsible">Access</button>
<div class="content">
  <p><br>The act of making information available. To increase ease of access, data should be made available in a convenient and modifiable form.
</p>
</div>


<br>
<br>

<h2>Summary of the Augment Step</h2>
<p>
The <b>A</b>ugment step in the CURATE(D) model applies to the dataset, the information gathered in the <b>U</b>nderstand step, and the feedback you've received from the <b>R</b>equest step.

There are two specific ways you may Augment the dataset and it's documentation with:
<p>
  &nbsp;&nbsp;1. Machine-readable metadata
   <br>
  &nbsp;&nbsp;2. README files or other documentation
   <br>

</p>
</blockquote>

<br>

<h2>A Step Actions</h2>
<p>
When Augmenting a dataset there are a number of areas for the curator to consider enhancing: these include strategies to improve the datasets discoverability, accessibility, and linkages through metadata and related documentation.

<h4>Metadata</h4>
<p>
Essential metadata elements - <a href="https://schema.datacite.org/meta/kernel-4.4/" target="_blank"> DataCite Metadata Schema .</a>

<br>

<style>

  td, th{
  padding-top: 10px;
  padding-bottom: 10px;
  padding-left: 15px;
  padding-right: 15px;
  border-style:solid;
  border-color: #44729B;
  }

  tr{
  border-style:solid;
  border-color: #44729B;

  }

</style>


<b>Table 1: <a href="https://schema.datacite.org/meta/kernel-4.4/doc/DataCite-MetadataKernel_v4.4.pdf" target="_blank"> DataCite Metadata Profile 4.4 .</a> Recommended and Optional Properties</b>
<table>
<th bgcolor="#44729B"><h4 style = "color:#FFFFFF;"> Property </h4></th>
<th bgcolor="#44729B"><h4 style = "color:#FFFFFF;">Obligation</h4></th>
<tr>
<td>Identifier</td>
<td>Mandatory</td>
</tr>
<tr>
<td>Creator (with optional given name, family name, name identifier and affiliation sub-properties)</td>
<td>Mandatory</td>
</tr>
<tr>
<td>Title (with optional type sub-properties)</td>
<td>Mandatory</td>
</tr>
<tr>
<td>Publisher</td>
<td>Mandatory</td>
</tr>
<tr>
<td>PublicationYear</td>
<td>Mandatory</td>
</tr>
<tr>
<td>ResourceType (with mandatory general type description subproperty)</td>
<td>Mandatory</td>
</tr>
<tr>
<td>Subject (with scheme sub-property)</td>
<td>Recommended</td>
</tr>
<tr>
<td>Contributor (with optional given name, family name, name identifier, and affiliation sub-properties)</td>
<td>Recommended</td>
</tr>
<tr>
<td>Date (with type sub-property)</td>
<td>Recommended</td>
</tr>
<tr>
<td>Language</td>
<td>Optional</td>
</tr>
<tr>
<td>AlternateIdentifier (with type sub-property)</td>
<td>Optional</td>
</tr>
<tr>
<td>RelatedIdentifier (with type and relation type sub-properties)</td>
<td>Recommended</td>
</tr>
<tr>
<td>Size</td>
<td>Optional</td>
</tr>
<tr>
<td>Format</td>
<td>Optional</td>
</tr>
<tr>
<td>Version</td>
<td>Optional</td>
</tr>
<tr>
<td>Rights</td>
<td>Optional</td>
</tr>
<tr>
<td>Description (with type sub-property)</td>
<td>Recommended</td>
</tr>
<tr>
<td>GeoLocation (with point, box, place, and polygon sub-properties)</td>
<td>Recommended</td>
</tr>
<tr>
<td>FundingReference (with name, identifier, and award related sub-properties)</td>
<td>Optional</td>
</tr>
<tr>
<td>RelatedItem (With identifier, creator, title, publication year, volume, issue, number, page, publisher, edition, and contributor sub-properties)</td>
<td>Optional</td>
</tr>
</table>
<br>
<br>

<h4>README and other Documentation</h4>
<p>
Example README Forms
<a href="https://github.com/psu-libraries/scholarsphere/wiki/README-Guide" target="_blank"> Penn State README.</a>
<a href="https://cornell.app.box.com/v/ReadmeTemplate" target="_blank"> Cornell README.</a>



<h2>A Step Checklist</h2>

<div class="flex-contianer">
     <a class="button button-primary" href="https://docs.google.com/document/d/1RWt2obXOOeJRRFmVo9VAkl4h41cL33Zm5YYny3hbPZ8/edit" target = "_blank"> Access CURATE(D) Checklist</a>
</div>



<h2> Key Ethical Considerations </h2>

<ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 5%;">
<li>Make sure bibliographic information reflects correct author attribution</li>
<li>Ensure any augmentation by the depositor to resolve ethical questions from previous
steps is completed</li>
</ul>

<br>



<blockquote class = "highlighted-text">

<h2>Activity</h2>
<p>



<h4>Activity Materials:</h4>
&nbsp;1.   <a href="https://drive.google.com/drive/folders/1ow_IJ8Gh1Ska5Ck837D5JRFogd646FMy" target="_blank">Updated README obtained from the Request step</a>.
 <br>
 <br>

 <b>Directions</b><br>
    Now that you've <b>C</b>hecked and <b>U</b>ndstand the dataset, as well as <b>R</b>equested some inforamtion from the depositor - it is time to <b>A</b>ugment the data with gathered information. Assume that after you requested more information, the depositor sent an updated README file. Augment the dataset above - augmenting both the README and the metadata form.

 <br>
 </p>
 </blockquote>

 <br>

 <b>Active Reflection</b><br>
    After completing this step, take a few minutes and see what else may be missing that you want to go back to the depositor and ask for additional information about. What's incomplete or still required for reuse?

 <br>
 </p>
 </blockquote>

 <br>



<style>
.flex-contianer {
  display: flex;
  justify-content: space-between;
}
</style>
<div class="flex-contianer">
     <a class="button button-primary" href="/CURATED/modules/module-a"> < Previous</a>
     <a class="button button-primary" href="/CURATED/modules/module-e"> Next > </a>
</div>
