---
title: "T Step: Transform File Formats"
layout: module
---

<br>

<h2>Learning Outcomes</h2>
<b> Curators will be able to: </b>


<p>
  &nbsp;&nbsp;1. Describe what transformation is, and why it is important.
   <br>
  &nbsp;&nbsp;2. Identify common file formats to maximize long-term access and preservation.
   <br>
  &nbsp;&nbsp;3. Use different tools available to help with file transformation.
    <br>
  &nbsp;&nbsp;4. Identify challenges and benefits to file transformation.
 
</p>

<br>
<br>

<h2>Terms to know</h2>



<p>
 <b>&nbsp;&nbsp;1. Access</b> - The act of making information available. To increase ease of access, data should be made available in a convenient and modifiable form.
   <br>
   <br>
 <b>&nbsp;&nbsp;2. Accessibility</b> - Content that is accessible is designed and developed so that people with disabilities can use it. For data curators, accessibility can include technical requirements that facilitate access for people with a diverse range of hearing, movement, sight, and cognitive ability (e.g. formatting that is compatible with screen readers), as well as requirements that facilitate user interactions (e.g. understandable instructions remove barriers to access, understanding and reuse of the data). Curating with accessibility in mind can improve data for all future users.
   <br>
   <br>

<b>&nbsp;&nbsp;3. Conversion or Transformation </b>  - The migration of information from one file format to another, usually for purposes of preservation or access.
  <br>
  <br>


 <b>&nbsp;&nbsp;4. Interoperability</b> - Data formatted using a disciplinary standard for better integration with other datasets and/or systems.
   <br>
   <br>
 <b>&nbsp;&nbsp;5. Preservation</b> - Ensuring that data remain intact, accessible and understandable over time. This requires preserving the integrity of digital files themselves, and can be very complicated. Preservation actions may include preserving the software required to interact with the data or emulating older systems, migrating data to new formats and new media, and ensuring there is sufficient metadata to understand, interpret, manage and preserve the data.
   <br>
   <br>
 <b>&nbsp;&nbsp;6. Proprietary Format</b> - A proprietary format is a file format of a company, organization, or individual that contains data that is ordered and stored according to a particular encoding-scheme, designed by the company or organization to be secret, such that the decoding and interpretation of this stored data is easily accomplished only with particular software or hardware that the company itself has developed. 
 
 <a href="https://en.wikipedia.org/wiki/Proprietary_format" target="_blank"> (Wikipedia) </a> 
 </p>

<br>
<br>

<h2>Summary of the Transform Step</h2>
<p>
<b>Transformation</b> is the process of converting data from one format to another (e.g. from a <b>proprietary format</b> like Microsoft Excel to a non-proprietary format like csv). Transformation may be recommended for several reasons including increasing <b>access</b>, <b>interoperability</b>, and likelihood of long term <b>preservation</b>. Curators may convert files themselves or request that the depositor convert files. Sometimes both original and converted files should be deposited, (e.g. some file types may be good for long-term preservation, but functionality is lost, so it’s recommended to deposit both versions).
</p>

<br>

<h2>T Step Actions</h2>


<p>
  &nbsp;&nbsp;1. Decide if current formats meet access and preservation requirements.
   <br>
   &emsp;&nbsp;&nbsp; a. (See examples of common proprietary formats and suggested formats for preservation in Table 1: Common Transformations below).
   <br>
  &nbsp;&nbsp;2. Convert or ask depositor to convert files to formats that increase access, interoperability, and likelihood for long-term preservation.
   <br>
  &nbsp;&nbsp;3. Decide if both original and converted files will be part of the upload.
    <br>
  &nbsp;&nbsp;4. Update documentation to reflect transformation notes, as necessary.
 
</p>

<br>
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


<b>Table 1: Common Transformations</b>
<table>
<th bgcolor="#44729B"><h4 style = "color:#FFFFFF;"> Native Software or Format </h4></th>
<th bgcolor="#44729B"><h4 style = "color:#FFFFFF;">Suggested Formats
or Transformations</h4></th>
<th bgcolor="#44729B"><h4 style = "color:#FFFFFF;">Transformation Tools and Notes</h4></th>
<tr>
<td>CZI (microscope images), Photoshop</td>
<td>TIFF, JPG, FITS</td>
<td>Use “export”; Omero, Bioformats; WikiData tracks software and file formats for preservation</td>
</tr>
<tr>
<td>Microsoft Word</td>
<td>PDF, TXT, HTML</td>
<td>Use “save as”; use accessibility checker to maximize accessibility.</td>
</tr>
<tr>
<td>Microsoft Excel / XLS, XLS</td>
<td>CSV, TSV</td>
<td>Use “save as”; Use Excel Archival Tool to preserve formulas</td>
</tr>
<tr>
<td>Microsoft Access</td>
<td>DBF</td>
<td>Use “save as”; retain original to ensure full functionality.</td>
</tr>
<tr>
<td>Chemdraw / CDX</td>
<td>CDXML, MOL, JPG, 001, OPJ, TRI</td>
<td>Retain original. Some conversions will result in loss of information.</td>
</tr>
<tr>
<td>PDF</td>
<td>PDF-A</td>
<td>Use “save as”</td>
</tr>
<tr>
<td>MP4, MOV, WMV</td>
<td>Uncompressed AVI or MOV + captions</td>
<td>No information is gained going from a “lower” resolution image to a “higher” one, but long-term access may be improved. Use YouTube, Vimeo, Kaltura or other tools for captioning.</td>
</tr>
<tr>
<td>Windows Media (audio, music files)</td>
<td>WAV, MP3</td>
<td>Free audio converters are available, or use iTunes or Windows Media Player to convert files.</td>
</tr>
<tr>
<td>.SHP (geocoded xls)</td>
<td>CSV + extracted metadata</td>
<td>Retain .SHP. Use FME Tool or ArcGIS</td>
</tr>
<tr>
<td>Webpages</td>
<td>WARC, TIFF</td>
<td>[Link to Internet Archive.] Provide screen shots.</td>
</tr>
</table>
<br>
<br>





<h2>T Step Checklist</h2>

<div class="flex-contianer">
     <a class="button button-primary" href="https://docs.google.com/document/d/1RWt2obXOOeJRRFmVo9VAkl4h41cL33Zm5YYny3hbPZ8/edit" target = "_blank"> Access checklist here</a>
</div>

<br>

&nbsp;&nbsp;<input type="checkbox" id="1" name="1" >
<label for="1"> &nbsp;Preferred File Formats in Use?</label><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="checkbox" id="2" name="2">
<label for="2"> &nbsp;Check for proprietary formats</label><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="checkbox" id="3" name="3">
<label for="3"> &nbsp;Check for software availability and version*</label><br>
&nbsp;&nbsp;<input type="checkbox" id="4" name="4" >
<label for="4"> &nbsp;Recommend conversion</label><br>
&nbsp;&nbsp;<input type="checkbox" id="5" name="5" >
<label for="5"> &nbsp;Retain original formats and/or inclulde both formats in deposit</label><br>
&nbsp;&nbsp;<input type="checkbox" id="6" name="6" >
<label for="6"> &nbsp;Document file transformations/conversions, tools used, notes</label>


<br>

<h2>Additional Resources</h2>

<div class="flex-contianer">
     <a class="button button-primary" href="#" target="_blank"> CLICK HERE</a>
</div>


<br>
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
