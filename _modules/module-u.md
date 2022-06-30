---
title: "U Step: Understand the Data Deposit"
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

<blockquote class = "highlighted-text">
<h2>Learning Outcomes</h2>
<br>
<p>
<b>Curators will be able to:</b><br>
  &nbsp;&nbsp;&nbsp;1. Identify different terms and processes associated with the Understand step of the CURATED model.
   <br>
  &nbsp;&nbsp;&nbsp;2. Assess a dataset and its component files as a complete package.
   <br>
  &nbsp;&nbsp;&nbsp;3. Engage in an activity to practice the Understand step on the dataset identified in the previous <a href= "/CURATED/modules/module-c" target="_blank"> Check step. </a>
    <br>
  &nbsp;&nbsp;&nbsp;4. Reflect on what might be necessary to enhance understanding of the data package in preparation for the <a href= "/CURATED/modules/module-r" target="_blank">Request step:</a> Request missing information.

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

<button class="collapsible">Absolute/Relative path</button>

<div class="content">
  <br>
  <p>The path refers to the location of a file in the directory structure of where it is stored. </p>
  <p>
  &nbsp;&nbsp;&nbsp;&nbsp; a. Absolute paths provide a full list of all of the folders from the beginning (or “root”) of the storage unit. On most unix based systems, the root directory is “\.” On Windows systems, the root directory usually begins with a drive letter such as “C:\”.
  </p>
  <p>
  &nbsp;&nbsp;&nbsp;&nbsp; b. Relative paths provide a list of folders that begin at a designated folder (usually the initial folder of a project). In the case of curating for secondary use, relative paths are preferred for long term preservation since it is generally easier to share and preserve the initial project folder and all subsequent folders.</p>
</div>
<button class="collapsible">Codebook</button>
<div class="content">
  <p><br>A codebook provides a description of all the items contained in the data collection with information about individual files, measures, and codes used to represent those files. A codebook will often provide additional context about the data collection process, assumptions, requirements, and descriptive statistics that enable a secondary user to understand the context for the collection while also validating the integrity of the data collection.</p>
</div>
<button class="collapsible">Commented Code</button>
<div class="content">
  <p><br>Documentation embedded in the computer programming code that is ignored by the interpreter or compiler when the computer program executes.</p>
</div>
<button class="collapsible">Data Dictionary</button>
<div class="content">
  <p><br>A list of the elements contained in a dataset and their position in the data file. Each file in a data submission may have its own data dictionary.</p>
</div>
<button class="collapsible">Delimited file</button>
<div class="content">
  <p><br>A data file in which each data element is separated by a common character. Comma separated values (.csv) files are very popular, but tab separated values (.tsv) files and pipe delimited (|) files are also used in many data projects.</p>
</div>
<button class="collapsible">File dependency (or dependency)</button>
<div class="content">
  <p><br>Software code that requires the presence of certain files (file dependency) or software libraries for the program to execute. Some dependencies may require a particular version of a software code for execution.</p>
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

<h2>Summary of the U Step: Understand the Data Deposit</h2>
<p>
After Checking the contents of the data deposit, the Understand step of the curation process requires a deeper dive into the individual items submitted for curation. The curator should review whether these items form a cohesive package that would allow someone other than the original researcher to be able to understand what is being presented. Perhaps the most important information to look for during this process is the presence of contextual and content-specific documentation, file dependencies, and potential ethical issues that could prohibit publishing openly in a repository.

</p>

<br>
<br>

<h2>U Step Actions</h2>
Below are some actions you might perform during the Understand step. Actions will vary depending on the subject matter and data type you are curating. The <a href= "http://hdl.handle.net/11299/202810" target="_blank"> Data Curation Network’s Data Curation Primers </a> provide a helpful resource for better understanding new data types and formats. Primer topics cover a wide range of formats, software platforms, and data types.

<br>

<table frames=hsides rules=rows>
<th style="color:#44729B;" ><h4>Check for:</h4></th>
<th style="color:#44729B;  padding-left: 4%;" ><h4>Questions to ask:</h4></th>

<tr>
<td style="color:#44729B; padding-top: 2%; padding-bottom: 2%;"><b>Overall Quality Assurance</b></td>
<td ><ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 5%;"><li>Are there missing data?</li>
<li>Could a user with similar qualifications to the author’s understand and reuse these data?</li>
<li>Does the provided code execute without errors?</li>
<li>Are the data, documentation, and/or metadata presented in a way that aids in interpretation?</li></ul></td>
</tr>
<tr>
<td style="color:#44729B; padding-top: 2%; padding-bottom: 2%;"><b>Documentation Depth</b></td>
<td><ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 5%;"><li>Is the context of the data explained? (Methodology information, relevant citations, file relationships, etc.)</li>
<li>Is the content of the data explained? (variable and value labels, units of measurement, etc.)</li>
<li>Is there additional documentation that may be helpful based on the data type? (e.g a codebook, data dictionary, study protocol, survey questionnaire(s) etc.)</li>
<li>If code is present, is it commented (e.g. explains what each chunk of code is supposed to produce)?</li></ul></td>
</tr>
<tr>
<td style="color:#44729B; padding-top: 2%; padding-bottom: 2%;"><b>Data Structure</b></td>
<td><ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 5%;"><li>If spreadsheet data are present, are there multiple sheets? The data on multiple sheets should be documented and stored as a separate delimited file (to ensure usability of each sheet rather than relying on the original software platform, which could become obsolete).</li>
<li>Are there embedded calculations or other software dependencies?</li>
<li>Are there file references/links to other files in the package (are all the files there? correctly referenced?)</li>
<li>If code is present, are referenced file paths relative (easy to change based on where the data is located once downloaded)?</li></ul></td>
</tr>
<tr>

<td style="color:#44729B; padding-top: 2%; padding-bottom: 2%;"><b>Ethical Issues Assessment
</b></td>

<td><ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 5%;">

<li>If human subject data are included:

  <ul style="padding-top: 1%; padding-bottom: 1%; padding-left: 5%;">
    <li> Is a consent form present that allows for data sharing? </li>
    <li> Are there any direct or indirect identifiers that could reveal the identities of those involved in the data project? If unsure, this should be a question for the data provider in the <a href= "/CURATED/modules/module-r" target="_blank"> Request step.</a> </li>
  </ul>

</li>

<li>If there are geographic data included:
  <ul style=" padding-top: 1%; padding-bottom: 1%; padding-left: 5%;">
    <li> Are there direct location identifiers (addresses, geographic coordinates, placenames, etc.) that could pose a risk to persons or places that could pose a risk to research participants, endangered species, sensitive archeology sites, etc.?
    </li>
  </ul>
</li>

<li>If data were obtained from another source, is permission listed to redistribute/republish?
</li>
</ul></td>
</tr>
</table>

<br>

<h2> U Step Checklist </h2>
<div class="flex-contianer">
     <a class="button button-primary" href= "https://docs.google.com/document/d/1RWt2obXOOeJRRFmVo9VAkl4h41cL33Zm5YYny3hbPZ8/edit" target = "_blank"> Access CURATE(D) Checklist</a>
</div>

<br>

<h2> Key Ethical Considerations </h2>

<ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 5%;">
<li> If working with human data, is this research done with and not on communities and populations involved? (You may wish to review data sources, researchers, and their connections to the communities and subjects they are serving to facilitate further conversation with researcher(s).)
  <ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 7%;">
  <li> Are there authoritative group representatives who should be contacted in the next (request) step? </li>
  </ul>
</li>
<li>Are there labels or other descriptive indicators that could be applied to better represent or protect an identified group of people impacted by this data deposit? (Example: <a href= "https://localcontexts.org/labels/traditional-knowledge-labels/" target="_blank"> TK labels</a>)</li>
</ul>

<br>

<blockquote class = "highlighted-text">
<h2>Activity</h2>
<br>
<h4>Activity option A:</h4>
<p>
Use the example <a href= "https://drive.google.com/drive/folders/1aWTQYpEQ4GBzh4KnUK5u6uEKjqKrPVTv?usp=sharing" target="_blank"> data deposit </a>. These files are in Microsoft Excel and Word format.
</p>
<h4>Activity option B:</h4>
<p>
Download a dataset from <a href="https://figshare.com/category" target="_blank"> Figshare </a> that aligns with your own subject area expertise. Look over the dataset and determine if you, or someone with skills similar to the researcher, would have enough information to understand what is presented.
</p>
<h4>Materials Needed (both A and B):</h4>
<p>
Software available to open your chosen dataset and accompanying files (or ability to convert to a readable format)
</p>
<h4>Directions (both A and B):</h4>
<p>
&nbsp;&nbsp; 1. Open the files and assess what you see using the “U Step Actions” described above.
</p>

<h4>Active Reflection:</h4>
<p>
&nbsp;&nbsp;1. How “understandable” do you think this dataset is?
<br>
&nbsp;&nbsp;2. What would make this dataset more understandable? The answers you provide here will be helpful for the next step in the CURATED process.
<br>
&nbsp;&nbsp;3. How do you see yourself using what you learned in your own practice?
</p>
</blockquote>

<br>
<h2>Additional Resources</h2>

<h4>Types of Documentation: </h4>

<p>
<h5>README file</h5>
<img src="../../images/UStep_README.PNG" vspace="25">

<br>

<h5>Codebook</h5>
<img src="../../images/UStep_Codebook.PNG" vspace="25">

<br>

<h5>Commented Code</h5>
<img src="../../images/UStep_Code.PNG" vspace="25">
</p>

<h4>
Working With Various File Formats: </h4>
<p>
When curating data for a repository that accepts all types of data, you can receive many different types of files. As a result, you might not always have the requisite software needed to open and view the files. When this occurs, there are a few different ways to still be able to read the files using common, readily available software.
</p>
<p>
Common proprietary formats you might encounter include (but are not limited to) MATLAB (.mat, .m), Stata (.dta, .dct, .do), SAS (.sas, .sas7bdat), SPSS (.sav, .sps), ESRI/ArcGIS (.shp, .dbf, .gdb).
</p>
<p>
For some proprietary formats, there are open source, freely available software packages that can work with them. For example, QGIS can be used to work with files created in ESRI’s ArcGIS platform. For others, you may have to convert the files. A useful tool for conversion is called <a href= "https://stattransfer.com/overview/" target="_blank"> Stat/Transfer </a>. It is not freely available, but can be worth the investment given that it also helps with older legacy file formats.
</p>

<p>
 <a href= "https://notepad-plus-plus.org/" target="_blank"> Notepad++ </a> is a free source code and text editor. It is an exceptionally helpful tool when working with text files that appear unstructured when opened with regular Notepad or Wordpad. It can also often be used to open code files such as .m, .r, .do, .sas. Notepad++ is also worth trying when a file appears to not have any extension.
</p>
<p>
Curating human participant data can be challenging. The Data Curation Network has a Primer on <a href= "https://notepad-plus-plus.org/" target="_blank"> Human Participants Data Essentials  </a>that can help inform that process. </p>

<br>
<br>

<style>
.flex-contianer {
  display: flex;
  justify-content: space-between;
}
</style>

<div class="flex-contianer">
     <a class="button button-primary" href="/CURATED/modules/module-c"> < Previous</a>
     <a class="button button-primary" href="/CURATED/modules/module-r"> Next ></a>
</div>
