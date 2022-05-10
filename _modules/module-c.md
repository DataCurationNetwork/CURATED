---
title: "C Step: Check the Data Deposit"
layout: module
---

<br>

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


<blockquote class = "highlighted-text">
  <h2>Learning Outcomes</h2>
  <br>
  <p>
<b>Curators will be able to:</b><br>
&nbsp;&nbsp;1. Perform curation actions such as conducting a file inventory and opening the files.
   <br>
  &nbsp;&nbsp;2. Check the submission for completeness based on a predefined criteria.
   <br>
  &nbsp;&nbsp;3. Develop preliminary recommendations to be used for the “Understand” step.

</p>
</blockquote>


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
<br>
<br>


<h2>Terms to know</h2>

<br>
<br>

<button class="collapsible">Submission information package (SIP)</button>
<div class="content">
  <p><br>Items that have been submitted by the depositor.</p>
</div>
<button class="collapsible">Archival Information Package (AIP)</button>
<div class="content">
  <p><br>A package that contains data that will be stored within a digital archive.</p>
</div>
<button class="collapsible">Dissemination Information Package (DIP)</button>
<div class="content">
  <p><br>A package created from the Archival Information Package (AIP) to distribute digital content to users.</p>
</div>
<button class="collapsible">File inventory </button>
<div class="content">
  <p><br>The list of files in the submission information package (SIP).</p>
</div>
<button class="collapsible">File organization</button>
<div class="content">
  <p><br>The act of structuring files in a hierarchical way to ensure findability.</p>
</div>
<button class="collapsible">README file</button>
<div class="content">
  <p><br>A file that is usually a text file (.txt) or a rich text format file (.rtf) or markdown (.md) that gives information about the creators of the data, where the data was created, methods used to produce the data, sharing privileges, and so on.</p>
</div>
<button class="collapsible">Metadata</button>
<div class="content">
  <p><br>Data about data. Metadata can include the author, file size, the date the document was created and keywords to describe the document.</p>
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



<h2>Summary of the Check Step</h2>
<p>
The check step is the first step of the CURATED process. In this step, we take an inventory of the contents that have been submitted by the depositor, known in the <a href="https://www.oclc.org/research/publications/2000/lavoie-oais.html" target="_blank"> Open Archival Information System (OAIS) </a>  model as the<b> submission information package (SIP)</b>. The SIP will become an <b>archival information package (AIP)</b>through the process of curation and a <b>dissemination information package (DIP) </b>through its retrieval by a user. Examples of the contents for SIPs may include: data files, code files, supporting documents, and metadata. At this step we are inventorying what has been submitted and noting our initial thoughts. We’ll examine the content more closely in the U (understand) Step. However, to prepare for the next step, we can start opening or downloading software that will allow us to examine submission components and obtaining any resources we’ll need to help with the next step.

<br>
<br>
Common things to look for during this step are the record level <b> metadata, file inventory, file organization</b>, the <b>README file</b>, and whether the file(s) can open or not:
</p>

<br>

<table frames=hsides rules=rows>
<th style="color:#44729B;" ><h4>Check for:</h4></th>
<th style="color:#44729B;  padding-left: 4%;" ><h4>Questions to ask:</h4></th>
<tr>
<td style="color:#44729B; padding-top: 2%; padding-bottom: 2%;"><b>Completeness</b></td>
<td ><ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 5%;"><li> Is the submission complete based on any predefined criteria for your repository? An example of predefined criteria is the <a href="https://datadryad.org/stash/faq#files" target="_blank"> Dryad repository guidelines </a>.</li></ul></td>
</tr>
<tr>
<td style = "color:#44729B; padding-top: 2%; padding-bottom: 2%;"><b>Record Level Metadata</b></td>
<td><ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 5%;"><li> Does the description have sufficient detail?</li>
<li>Are all required fields filled out? (e.g., title, author/creator, licensing) </li></ul></td>
</tr>
<tr>
<td style = "color:#44729B; padding-top: 2%; padding-bottom: 2%;"><b>File inventory</b></td>
<td ><ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 5%;"><li> What files are included? </li>
<li> Are files missing? </li></ul></td>
</tr>
<tr>
<td style = "color:#44729B; padding-top: 2%; padding-bottom: 2%;"><b>File organization</b></td>
<td><ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 5%;"><li> Are there unwanted spaces or special characters?</li>
<li> Is there a file naming convention? </li>
<li> Order and description (if many files) </li>
<li> File hierarchy in terms you can clearly see the relationships in the naming of the files on the top level and the files below them in terms of how they are named (ex. School_data as a top level folder and school_data_ny as a folder in the school_data folder referring to school data from New York) . </li></ul></td>
</tr>
<tr>
<td style = "color:#44729B; padding-top: 2%; padding-bottom: 2%;"><b>README</b></td>
<td><ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 5%;"><li> Is there a documentation file, like a README?</li>
<li>Example:  <a href="https://cornell.app.box.com/v/ReadmeTemplate" target="_blank"> Cornell ReadMe Template </a> </li></ul></td>
</tr>
<tr>
<td style = "color:#44729B; padding-top: 2%; padding-bottom: 2%;" ><b>Brief file diagnostic</b></td>
<td><ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 5%;"><li> (software) Does this open? </li>
<li> (code) Does this run? </li>
<li> What version? </li></ul></td>
</tr>
</table>

<br>
<br>

<h2> C Step Actions</h2>
<p>
  &nbsp;&nbsp;&nbsp;1.  Check data files.
   <br>
  &nbsp;&nbsp;&nbsp;2.  Verify all metadata provided by the author and review the available documentation.

   <br>
</p>
<br>




<h2> Key Ethical Considerations </h2>

<ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 5%;">
<li> Review participant agreement and data use agreements; examine potential impacts of sharing this data. Consider:
  <ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 7%;">
  <li> Individuals and communities represented</li>
  <li> Representativeness of diverse human populations</li>
  <li> Protection or endangerment status of species </li>
  <li> Geographic locations (e.g., contested boundaries, historical and current political situations) </li>
  <li> Animal research ethics and approval </li>
  </ul>
</li>
<li>Is it possible that the data deposit may impact a specific group?</li>
<li>Does this data deposit follow compliance and institutional policy?</li>
</ul>

<br>


<blockquote class = "highlighted-text">
<h2> Activity </h2>


<p>

<b>Materials Needed</b><br>

  &nbsp;1.   <a href="https://drive.google.com/drive/folders/1aWTQYpEQ4GBzh4KnUK5u6uEKjqKrPVTv?usp=sharing" target="_blank">Data deposit</a>.
   <br>
   <br>


<b>Directions</b><br>
    In this activity, using the checklist below, you will perform the C check on the <a href="https://drive.google.com/drive/folders/1aWTQYpEQ4GBzh4KnUK5u6uEKjqKrPVTv?usp=sharing" target="_blank">data depositt</a>. Once you have completed this activity, feel free to run the C step on another dataset of your choosing.

<br>
</p>
</blockquote>

<br>

<h2>C Step Checklist</h2>

<div class="flex-contianer">
     <a class="button button-primary" href="https://docs.google.com/document/d/1RWt2obXOOeJRRFmVo9VAkl4h41cL33Zm5YYny3hbPZ8/edit" target = "_blank"> Access CURATE(D) Checklist</a>
</div>
<br>
<table frames=hsides rules=rows>

<th>C Step Number</th>
<th>C Step</th>
<th>Yes/No/NA</th>
<tr>
<td  style="padding-top: 1%; padding-bottom: 1%;">C1</td>
<td  style="padding-top: 1%; padding-bottom: 1%;">Files open as expected?</td>
<td style="padding-top: 1%; padding-bottom: 1%;"><input type="checkbox">&nbsp;&nbsp;&nbsp; <input type="checkbox">&nbsp;&nbsp;&nbsp; <input type="checkbox"></td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">C2</td>
<td style="padding-top: 1%; padding-bottom: 1%;">Code runs as expected?</td>
<td style="padding-top: 1%; padding-bottom: 1%;"><input type="checkbox">&nbsp;&nbsp;&nbsp; <input type="checkbox">&nbsp;&nbsp;&nbsp; <input type="checkbox"></td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">C3</td>
<td style="padding-top: 1%; padding-bottom: 1%;">Metadata has all required fields filled out such as the title, author, and licensing information.</td>
<td style="padding-top: 1%; padding-bottom: 1%;"><input type="checkbox">&nbsp;&nbsp;&nbsp; <input type="checkbox">&nbsp;&nbsp;&nbsp; <input type="checkbox"></td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">C4</td>
<td style="padding-top: 1%; padding-bottom: 1%;">Is there any documentation?</td>
<td style="padding-top: 1%; padding-bottom: 1%;"><input type="checkbox">&nbsp;&nbsp;&nbsp; <input type="checkbox">&nbsp;&nbsp;&nbsp; <input type="checkbox"></td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">C5</td>
<td style="padding-top: 1%; padding-bottom: 1%;">Are there human participant data present?</td>
<td style="padding-top: 1%; padding-bottom: 1%;"><input type="checkbox">&nbsp;&nbsp;&nbsp; <input type="checkbox">&nbsp;&nbsp;&nbsp; <input type="checkbox"></td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">C6</td>
<td style="padding-top: 1%; padding-bottom: 1%;">Do the file names have unwanted spaces or characters?</td>
<td style="padding-top: 1%; padding-bottom: 1%;"><input type="checkbox">&nbsp;&nbsp;&nbsp; <input type="checkbox">&nbsp;&nbsp;&nbsp; <input type="checkbox"></td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">C7</td>
<td style="padding-top: 1%; padding-bottom: 1%;">Is there a file hierarchy in place?</td>
<td style="padding-top: 1%; padding-bottom: 1%;"><input type="checkbox">&nbsp;&nbsp;&nbsp; <input type="checkbox">&nbsp;&nbsp;&nbsp; <input type="checkbox"></td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">C8</td>
<td style="padding-top: 1%; padding-bottom: 1%;">Is there a file naming convention?</td>
<td style="padding-top: 1%; padding-bottom: 1%;"><input type="checkbox">&nbsp;&nbsp;&nbsp; <input type="checkbox">&nbsp;&nbsp;&nbsp; <input type="checkbox"></td>
</tr>
</table>

<br>
<h2>Additional Resources</h2>

<h4>Tools </h4>
<p>
<br>
<a href="https://docs.google.com/spreadsheets/d/1Xu2TlLePQ2jZ-ox3Ym7QBkeWPRCGX6mz7YjjKrkLyQY/edit#gid=0" target="_blank">View some selected tools that can open a variety of data types .</a>
</p>

<style>
.flex-contianer {
  display: flex;
  justify-content: space-between;
}
</style>

<br>

<div class="flex-contianer">
     <a class="button button-primary" href="/CURATED/data"> < Previous</a>
     <a class="button button-primary" href="/CURATED/modules/module-u"> Next > </a>
</div>
