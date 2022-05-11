---
title: "T Step: Transform File Formats"
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

img {
  max-width: 100%;
  height: auto;
}
</style>

<br>

<blockquote class = "highlighted-text">
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
<button class="collapsible">Accessibility</button>
<div class="content">
  <p><br>Content that is accessible is designed and developed so that people with disabilities can use it. For data curators, accessibility can include technical requirements that facilitate access for people with a diverse range of hearing, movement, sight, and cognitive ability (e.g. formatting that is compatible with screen readers), as well as requirements that facilitate user interactions (e.g. understandable instructions remove barriers to access, understanding and reuse of the data). Curating with accessibility in mind can improve data for all future users.
</p>
</div>
<button class="collapsible">Conversion or Transformation</button>
<div class="content">
  <p><br>The migration of information from one file format to another, usually for purposes of preservation or access.
</p>
</div>
<button class="collapsible">Interoperability </button>
<div class="content">
  <p><br>Data formatted using a disciplinary standard for better integration with other datasets and/or systems. </p>
</div>
<button class="collapsible">Preservation</button>
<div class="content">
  <p><br>Ensuring that data remain intact, accessible and understandable over time. This requires preserving the integrity of digital files themselves, and can be very complicated. Preservation actions may include preserving the software required to interact with the data or emulating older systems, migrating data to new formats and new media, and ensuring there is sufficient metadata to understand, interpret, manage and preserve the data.</p>
</div>
<button class="collapsible">Proprietary Format</button>
<div class="content">
  <p><br>A proprietary format is a file format of a company, organization, or individual that contains data that is ordered and stored according to a particular encoding-scheme, designed by the company or organization to be secret, such that the decoding and interpretation of this stored data is easily accomplished only with particular software or hardware that the company itself has developed.

<a href="https://en.wikipedia.org/wiki/Proprietary_format" target="_blank"> (Wikipedia) </a> </p>

</div>

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
     <a class="button button-primary" href="https://docs.google.com/document/d/1RWt2obXOOeJRRFmVo9VAkl4h41cL33Zm5YYny3hbPZ8/edit" target = "_blank"> Access Curation Checklist</a>
</div>

<br>

&nbsp;&nbsp;<input type="checkbox" id="1" name="1" >
<label for="1"> &nbsp;Preferred File Formats in Use?</label><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="checkbox" id="2" name="2">
<label for="2"> &nbsp;Check for proprietary formats</label><br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<input type="checkbox" id="3" name="3">
<label for="3"> &nbsp;Check for software availability and version\*</label><br>
&nbsp;&nbsp;<input type="checkbox" id="4" name="4" >
<label for="4"> &nbsp;Recommend conversion</label><br>
&nbsp;&nbsp;<input type="checkbox" id="5" name="5" >
<label for="5"> &nbsp;Retain original formats and/or inclulde both formats in deposit</label><br>
&nbsp;&nbsp;<input type="checkbox" id="6" name="6" >
<label for="6"> &nbsp;Document file transformations/conversions, tools used, notes</label>

<br>
<br>

<h2> Key Ethical Considerations </h2>

<ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 5%;">
<li>Consider how best to navigate researcher bandwidth limitations and ownership of data with repository commitments to reducing barriers to reuse.</li>
<li>Decide how to balance the potential benefits of transformation with the risks of mistakes and loss of content/context, especially if curator or repository will be performing transformation. Document the decision.
</li>
</ul>

<br>

<blockquote class = "highlighted-text">

<h2>Activity: Excel Archival Tool </h2>
<p>
The <a href="https://github.com/mcgrory/ExcelArchivalTool" target = "_blank"> Excel Archival Tool</a> programmatically converts Excel files to open source formats (specifically, CSV and PNG) in preparation for archiving. You will download, install, and use the Excel Archival Tool (EAT) to transform a Microsoft Excel file to archival CSV and PNG files. The Excel Archival Tool is only available for Windows platforms; other platforms will either have to perform the file transformations manually or obtain a Windows machine to do this exercise.
</p>

<p>The Excel Archival Tool:
</p>

<ul style = "padding-left: 5%" >
  <li>Automated conversion process for Microsoft Excel → CSVs but also captures
  <ul style = "padding-left: 7%">
      <li>Charts and figures exported as PNGs</li>
      <li>Formulas exported as text files</li>
      <li>Cell formatting and style preserved as html snapshot of spreadsheet </li>
  </ul>
  </li>
  <li>
  Generates a report on the archival outputs
  <img src="../../images/Tstep_EATool.png" >
  </li>
</ul>
<br>

<h4>Activity Materials:</h4>

<p>The Excel Archival Tool requires a Windows environment to run (Windows XP, 7). The GUI version (WithUI) requires Internet Explorer. You may want to perform the file transformations manually or borrow a Windows machine to do this exercise if you use a non-Windows machine.
</p>

<ol style = "padding-left: 5%">

<li>Download Excel Archival Tool  from GitHub: <a href="http://z.umn.edu/exceltool" target = "_blank"> http://z.umn.edu/exceltool</a>
    <ol type = "a" style = "padding-left: 7%">
    <li>We suggest that you use the WithUI version of the tool for this exercise.
        <ol type = "i" style = "padding-left: 10%"><li>After downloading the ZIP, extract the WithUI folder.</li></ol>
   </li>
   <li>Remember where you extract these files, so you can access the tool during the exercise.</li>
   </ol>

</li>
<li>Download excel file “Microsoft Excel data file, all figures [Microsoft Excel]” from <a href="https://hdl.handle.net/1813/43783" target = "_blank"> https://hdl.handle.net/1813/43783</a>.
</li>
<li>Create a folder for your EAT output; this is not a requirement, but will simplify the process.
</li>
</ol>
<br>

<h4>Directions:</h4>
<ol style = "padding-left: 5%">
<li>Make sure Excel is not running on your computer.</li>
<li>Launch EAT by double clicking the ExcelAchivalTool.HTA from within the WithUI program folder. </li>
<li>Select the location of the input (Ostwald_etal_WaterHomeostatis2016_Data.xls) file.</li>
<li>Select the output location (created during setup).</li>
<li>Select desired outputs. Suggested outputs for this exercise:
    <ol type = "a" style = "padding-left: 7%">
    <li>Raw Spreadsheet Data (csv)</li>
    <li>Cell Formulas (txt)</li>
    <li>Charts and Figures (png)</li>
    </ol>
</li>
<li>Review your outputs. What should you have? EAT should have created:
    <ol type = "a" style = "padding-left: 7%">
    <li>One CSV file for each of the worksheets in the workbook. In this example, it should have created 10 CSV files.</li>
    <li>One Folder named “Formulas”; inside there should be one folder for each file. Each file folder will have one TXT file for each worksheet that had formulas in it. In this example, it should have created two TXT files.</li>
    <li>One “Output Report.txt” file containing a summary of the output for that EAT run.</li>
    </ol>
</li>
<li>Bundle as Archival File for repository upload (zip, tar, etc., according to repository policy).
</li>
</ol>
<br>
</blockquote>

<br>
<br>

<blockquote class = "highlighted-text">

<h2>Activity: Transformation Actions </h2>

<h4>Activity Materials </h4>
<p>
Dataset, either the same one you used for the EAT activity, or one of your choosing.
</p>
<h4> Directions </h4>
<ol style = "padding-left: 5%">
<li>List possible format transformations for your datasets </li>
<li>Put yourself in the role of different dataset stakeholders (researcher, curator, archivist, consumer, publisher). <br>
Consider how any transformation benefits different stakeholders <br>
List some of the challenges to any particular format transformations or stakeholder perspectives.</li>
</ol>
<br>
<p>
Bonus question: At what level has your institution promised to “preserve” the data, and what are the implications of that policy in practice?
</p>

</blockquote>

<br>
<br>

<button class="collapsible">Suggested Answers</button>

<div class="content">
  <br>
  <ol>
  <li>List possible format transformations for your datasets. <br>
  Answer: excel file should be converted to csv, figures to jpg, and formulas and other information preserved as a txt file.
</li>
  <li>
    Put yourself in the role of different dataset stakeholders (researcher, curator, archivist, consumer, publisher).
      <ol type = "a">
          <li>Consider how any transformation benefits different stakeholders. <br>
The researcher may benefit from increased accessibility for future re-users, resulting in increased re-use and more citations. Future consumers benefit by getting the data in a format that can easily be imported into multiple different tools. Curators and archivists benefit by having the data in a format that is more likely to be preserved in the long-term.
</li>
          <li>List some of the challenges to any particular format transformations or stakeholder perspectives. <br>
The researcher may not want to take the time to perform transformations. Future consumers may not understand how to use preservation formats, making it important to consider also including analysis-friendly formats in the deposit. For some proprietary file formats, no other format is available.
          </li>
      </ol>
  </li>
  </ol>
<br>

<p>
Bonus question: At what level has your institution promised to “preserve” the data, and what are the implications of that policy in practice? <br>
Read over your preservation support policy (or <a href="https://guides.library.cornell.edu/ecommons/preservation" target = "_blank"> this example</a> from Cornell’s eCommons digital repository) and consider what effect file transformations, or the lack thereof might have on the repository’s ability to preserve the data. Are files that are only able to be opened by a proprietary software that is no longer maintained or available preserved?
  </p>
  <br>
</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.maxHeight){
      content.style.maxHeight = null;
    } else {
      content.style.maxHeight = content.scrollHeight + "px";
    }
  });
}
</script>

</body>
</html>

<br>
<br>
<h2>Additional Resources</h2>

<p>
Excel Archival Tool  from GitHub:   <a href="http://z.umn.edu/exceltool" target = "_blank"> http://z.umn.edu/exceltool</a>  - The Excel Archival Tool programmatically converts Excel files to open source formats (specifically, CSV and PNG).
</p>
<p>
McGrory, John. (2015). Poster for "Excel Archival Tool: Automating the Spreadsheet Conversion Process". Retrieved from the University of Minnesota Digital Conservancy, <a href="http://hdl.handle.net/11299/171966" target = "_blank"> http://hdl.handle.net/11299/171966</a>.
</p>
<p>
Module 3 Understand: more information about proprietary file formats, software version documentation, and other important actions for understanding the data.
</p>
<p>
Janée, Greg; Sawchuk, Sandra; Yoo, Ho Jung. (2019). Microsoft Excel Data Curation Primer. Data Curation Network GitHub Repository.
</p>
<p>
Smithsonian Institution Archives. Smithsonian Recommended Preservation Formats for Electronic Records. <a href="https://siarchives.si.edu/what-we-do/digital-curation/recommended-preservation-formats-electronic-records" target = "_blank"> https://siarchives.si.edu/what-we-do/digital-curation/recommended-preservation-formats-electronic-records</a>.
</p>
<p>
Cornell University Library. File formats for digital content: Probability for full long-term preservation, in Recommended File Formats. <a href="https://guides.library.cornell.edu/ecommons/formats <" target = "_blank"> https://guides.library.cornell.edu/ecommons/formats </a>
</p>

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
