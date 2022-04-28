---
title: "T Step: Transform File Formats"
layout: module
---

<h4>Learning Outcomes</h4>
Curators will be able to:
<ol>
<li>Describe what transformation is, and why it is important.</li>
<li>Identify common file formats to maximize long-term access and preservation.</li>
<li>Use different tools available to help with file transformation.</li>
<li>Identify challenges and benefits to file transformation.</li>
</ol>
<br>
<h2>Terms to know</h2>
<ol>
<li><b>Access</b> -The act of making information available. To increase ease of access, data should be made available in a convenient and modifiable form.</li>
<li><b>Accessibility</b> - Content that is accessible is designed and developed so that people with disabilities can use it. For data curators, accessibility can include technical requirements that facilitate access for people with a diverse range of hearing, movement, sight, and cognitive ability (e.g. formatting that is compatible with screen readers), as well as requirements that facilitate user interactions (e.g. understandable instructions remove barriers to access, understanding and reuse of the data). Curating with accessibility in mind can improve data for all future users.</li>
<li><b>Conversion or Transformation</b> - The migration of information from one file format to another, usually for purposes of preservation or access.</li>
<li><b>Interoperability</b> - Data formatted using a disciplinary standard for better integration with other datasets and/or systems.</li>
<li><b>Preservation</b> - Ensuring that data remain intact, accessible and understandable over time. This requires preserving the integrity of digital files themselves, and can be very complicated. Preservation actions may include preserving the software required to interact with the data or emulating older systems, migrating data to new formats and new media, and ensuring there is sufficient metadata to understand, interpret, manage and preserve the data.</li>
<li><b>Proprietary Format</b> - A proprietary format is a file format of a company, organization, or individual that contains data that is ordered and stored according to a particular encoding-scheme, designed by the company or organization to be secret, such that the decoding and interpretation of this stored data is easily accomplished only with particular software or hardware that the company itself has developed. (Wikipedia)</li>
</ol>
<br>
<h2>Summary of the Transform Step</h2>
<b>Transformation</b> is the process of converting data from one format to another (e.g. from a <b>proprietary format</b> like Microsoft Excel to a non-proprietary format like csv). Transformation may be recommended for several reasons including increasing <b>access</b>, <b>interoperability</b>, and likelihood of long term <b>preservation</b>. Curators may convert files themselves or request that the depositor convert files. Sometimes both original and converted files should be deposited, (e.g. some file types may be good for long-term preservation, but functionality is lost, so it’s recommended to deposit both versions).
<h4>T Step Actions</h4>
<ol>
<li>Decide if current formats meet access and preservation requirements.<br>
&emsp; a. (See examples of common proprietary formats and suggested formats for preservation in Table 1: Common Transformations below).</li>
<li>Convert or ask depositor to convert files to formats that increase access, interoperability, and likelihood for long-term preservation.</li>
<li>Decide if both original and converted files will be part of the upload.</li>
<li>Update documentation to reflect transformation notes, as necessary.</li>
</ol>
<br>
<b>Table 1: Common Transformations</b>
<table border=1 frames=hsides rules=rows>
<th>Native Software or Format</th>
<th>Suggested Formats
or Transformations</th>
<th>Transformation Tools and Notes</th>
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
<h4>T Step Checklist</h4>
<input type="checkbox" id="1" name="1" >
<label for="1">Preferred File Formats in Use?</label><br>
&emsp;<input type="checkbox" id="2" name="2">
<label for="2">Check for proprietary formats</label><br>
&emsp;<input type="checkbox" id="3" name="3">
<label for="3">Check for software availability and version*</label><br>
<input type="checkbox" id="4" name="4" >
<label for="4">Recommend conversion</label><br>
<input type="checkbox" id="5" name="5" >
<label for="5">Retain original formats and/or inclulde both formats in deposit</label><br>
<input type="checkbox" id="6" name="6" >
<label for="6">Document file transformations/conversions, tools used, notes</label><br>

<style>
.flex-contianer {
  display: flex;
  justify-content: space-between;
}
</style>

<div class="flex-contianer">
     <a class="button button-primary" href="/modules/module-a">Previous</a>
     <a class="button button-primary" href="/modules/module-e"> Next</a>
</div>
