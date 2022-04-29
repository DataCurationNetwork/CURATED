---
title: "U Step: Understand the Data"
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
<b>&nbsp;Curators will be able to:</b><br>
  &nbsp;&nbsp;1. Identify different terms and processes associated with the Understand step of the CURATED model.
   <br>
  &nbsp;&nbsp;2. Assess a dataset and its component files as a complete package.
   <br>
  &nbsp;&nbsp;3. Engage in an activity to practice the U step on the dataset identified in the previous step (Check).
    <br>
  &nbsp;&nbsp;4. Reflect on what might be necessary to enhance understanding of the data package in preparation for the R(equest) step: Request missing information.
 
</p>
</blockquote>

<br>
<br>

<h2>Terms to Know</h2>


<p>
 <b>&nbsp;&nbsp;1. Absolute path/relative path</b> - The path refers to the location of a file in the directory structure of where it is stored. <b><i>Absolute paths</i></b> provide a full list of all of the folders from the beginning (or “root”) of the storage unit. On most unix based systems, the root directory is “\.” On Windows systems, the root directory usually begins with a drive letter such as “C:\”. <b><i>Relative paths</i></b> provide a list of folders that begin at a designated folder (usually the initial folder of a project). In the case of curating for secondary use, relative paths are preferred for long term preservation since it is generally easier to share and preserve the initial project folder and all subsequent folders.


   <br>
   <br>
 <b>&nbsp;&nbsp;2. Codebook</b> -  a codebook provides a description of all the items contained in the data collection with information about individual files, measures, and codes used to represent those files. A codebook will often provide additional context about the data collection process, assumptions, requirements, and descriptive statistics that enable a secondary user to understand the context for the collection while also validating the integrity of the data collection.</li>


   <br>
   <br>
 <b>&nbsp;&nbsp;3. Commented Code</b> - Documentation embedded in the computer programming code that is ignored by the interpreter or compiler when the computer program executes.
   <br>
   <br>
 <b>&nbsp;&nbsp;4. Data Dictionary </b> - a list of the elements contained in a dataset and their position in the data file. Each file in a data submission may have its own data dictionary.
   <br>
   <br>
 <b>&nbsp;&nbsp;5. Delimited file</b> - a data file in which each data element is separated by a common character.  Comma separated values (.csv) files are very popular, but tab separated values (.tsv) files and pipe delimited (|) files are also used in many data projects.

   <br>
   <br>
 <b>&nbsp;&nbsp;6. File dependency (or dependency)</b> - software code that requires the presence of certain files (file dependency) or software libraries for the program to execute. Some dependencies may require a particular version of a software code for execution.
 </p>

<br>
<br>



<h2>Summary of the Understand Step (U Step)</h2>
<p>
After <b>C</b>hecking the contents of the data deposit, the <b>U</b>nderstand step of the curation process requires a deeper dive into the individual items submitted for curation. The curator should review whether these items form a cohesive package that would allow someone other than the original researcher to be able to understand what is being presented. Perhaps the most important information to look for during this process is the presence of contextual and content-specific documentation, file dependencies, and potential ethical issues that could prohibit publishing openly in a repository.

</p>

<br>
<br>

<h2>U Step Actions</h2>
Below are some actions you might perform during the Understand step. Actions will vary depending on the subject matter and data type you are curating. The <a href="http://hdl.handle.net/11299/202810" target="_blank"> Data Curation Network’s Data Curation Primers </a> provide a helpful resource for better understanding new data types and formats. Primer topics cover a wide range of formats and software platforms and data types.

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
    <li> Are there any direct or indirect identifiers that could reveal the identities of those involved in the data project? If unsure, this should be a question for the data provider in the <b>R</b>equest step.  </li>
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

<blockquote class = "highlighted-text">
<h2>Activity</h2>
<br>
<h4>Activity option A:</h4>
<p>
Use this link to access a <a href= " https://drive.google.com/drive/folders/1aWTQYpEQ4GBzh4KnUK5u6uEKjqKrPVTv?usp=sharing" target="_blank"> dataset </a>  and its associated files. These files are in Microsoft Excel and Word format.
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
