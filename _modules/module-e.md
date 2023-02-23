---
title: "E Step: Evaluate the Overall Data Package"
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
  &nbsp;&nbsp;1. Evaluate the results of the curation process.
  <br>
  &nbsp;&nbsp;2. Assess the impact/value of data curation by considering the relationships between the depositor/repository/curator.
  <br>
  &nbsp;&nbsp;3. Assess a dataset using measures of FAIRness.
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

<button class="collapsible">FAIR</button>

<div class="content">
  <p><br> The FAIR Principles were developed by a set of diverse stakeholders that outline how scientific data should be shared. They stand for Findable, Accessible, Interoperable, and Reusable. </p>
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

<h2>Summary of the Evaluate Step</h2>
<p>
In this step you will evaluate the overall data package to determine if data curation by the repository adds value to the data sharing process and that the resulting data package is findable, accessible, interoperable, reusable or FAIR*. 
<br>
<br>
*Read more about FAIR: <a href="https://www.force11.org/fairprinciples" target="_blank">https://www.force11.org/fairprinciples</a>
</p>

<br>

<h2> What do we mean by Evaluate?  </h2>

<p>
Curation is a partnership between:
</p>

<ul style = "padding-left: 5%" >
  <li> the curator and the researcher </li>
  <li> the researcher and the repository system</li>
  <li> the curator and the repository system
</li>
</ul>
<br>

<p>
The diagram below shows the relationship and key considerations between the curator, researcher, and repository platform and how we work together to make data more FAIR. 
</p>
<img src="../../images/DCN_ModuleE_Figure.png">
<br>

<h2>&nbsp;E Step Actions</h2>
<p>
  As we consider each stakeholder connection, ask yourself:
  &nbsp;&nbsp;&nbsp;1.  Did curation result in stronger relationships with the depositor? (Researcher<-->Curator)
   <br>
  One way to assess this is to survey authors that deposit data to your repository and ask them about their experience. Read this case study...

<blockquote class = "highlighted-text">
<h2> Researcher<-->Curator Case Study </h2>

<p>
Case Study: How satisfied are depositors with our curation services? We asked them! 

<br>
Members of the Data Curation Network, representing academic and non-profit data repositories, wanted to better understand how satisfied depositors were with the data curation services their data received from curation staff during the data sharing process (deposit, ingest, appraisal, curation, and publication). 

<br>
In spring 2021, we surveyed 568 researchers who had recently deposited data into one of 6 data repositories and asked them to consider their most recent data curation experience. Our 11-question survey received a 42% response rate with 239 valid responses. Of these:

<br>
<li>87% strongly agreed that they were satisfied with their curation experience </li>
<li>75% reported that due to the curation process, changes were made to their data. For the remainder who said no changes were made, almost all said it was because no changes were needed </li>
<li>81% strongly agreed that Data curation by their repository added value to the data sharing process </li>
<li>98% said they would recommend this repository to a colleague </li>
<li>The most value-add action cited by many researchers was simply having a curator take time and review the dataset, as one respondent sums up: “Feedback from someone who comes to the data/documents with fresh eyes is simply invaluable…” </li>


  Download a <a href="https://hdl.handle.net/11299/224733" target = "_blank"> copy of the survey instrument </a> to use for your repository! 
</p>

</blockquote>
<p>

<b>Materials Needed</b><br>

For this activity you will assess a dataset for FAIRness and then recommend ways to increase the FAIRness.

<br>

   <br>
</p>
<br>

<blockquote class = "highlighted-text">
<h2> Activity: Evaluate for FAIRNess </h2>

<p>

<b>Materials Needed</b><br>

For this activity you will assess a dataset for FAIRness and then recommend ways to increase the FAIRness.

<br>

<h4>Directions</h4>

<p>
&nbsp;&nbsp;1. Please identify a dataset to use for this activity. Options:
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;a. <a href="https://ecommons.cornell.edu/handle/1813/43783" target="_blank"> Our example dataset </a> (final version in the repository)
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;b. A dataset in your data repository
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;c. One from another repository (e.g., FigShare, ICPSR, etc.)
<br>
&nbsp;&nbsp;2. Use the curator checklist above to assess the dataset for key FAIR features. 
<br>
&nbsp;&nbsp;3. Determine suggestions for potentially improving the FAIRness of the selected dataset.
</p>
</p>
</blockquote>

<br>

<h2>E Step Checklist</h2>

<div class="flex-contianer">
     <a class="button button-primary" href="https://docs.google.com/document/d/1RWt2obXOOeJRRFmVo9VAkl4h41cL33Zm5YYny3hbPZ8/edit" target = "_blank"> Access Curation Checklist</a>
</div>

<br>

<h4> Findable - </h4>
&nbsp;&nbsp;<input type="checkbox" id="1" name="1" >
<label for="1"> &nbsp;Metadata exceeds author/ title/ date.</label><br>
&nbsp;&nbsp;<input type="checkbox" id="2" name="2">
<label for="2"> &nbsp;Unique PID (DOI, Handle, PURL, etc.).</label><br>
&nbsp;&nbsp;<input type="checkbox" id="3" name="3">
<label for="3"> &nbsp;Discoverable via web search engines.</label><br>
<h4> Accessible - </h4>
&nbsp;&nbsp;<input type="checkbox" id="4" name="4" >
<label for="4"> &nbsp;Retrievable via a standard protocol (e.g., HTTP).</label><br>
&nbsp;&nbsp;<input type="checkbox" id="5" name="5" >
<label for="5"> &nbsp;Free, open (e.g., download link). </label><br>
<h4> Interoperable - </h4>
&nbsp;&nbsp;<input type="checkbox" id="6" name="6" >
<label for="6"> &nbsp;Metadata formatted in a standard schema (e.g., Dublin Core). </label><br>
&nbsp;&nbsp;<input type="checkbox" id="7" name="7" >
<label for="7"> &nbsp;Metadata provided in machine-readable format (OAI feed).</label><br>
<h4> Reusable - </h4>
&nbsp;&nbsp;<input type="checkbox" id="8" name="8" >
<label for="8"> &nbsp;Data include sufficient metadata about the data characteristics to reuse. </label><br>
&nbsp;&nbsp;<input type="checkbox" id="9" name="9" >
<label for="9"> &nbsp;Contact info displayed if the direct assistance of the author needed.</label><br>
&nbsp;&nbsp;<input type="checkbox" id="10" name="10" >
<label for="10"> &nbsp;Clear indicators of who created, owns, and stewards the data.</label><br>
&nbsp;&nbsp;<input type="checkbox" id="11" name="11" >
<label for="11"> &nbsp;Data are released with clear data usage terms (e.g., a CC License).</label><br>

<br>

<h2> Key Ethical Considerations </h2>

<ul style="padding-top: 2%; padding-bottom: 2%; padding-left: 5%;">
<li> Final review--remember it is not too late to surface any ethical concerns. </li>
<li> Verify the words/language being used are not racist/harmful. </li>
<li> Remind the submitter of their responsibility, if they choose to ignore requests for de-identification or similar concerns. 
</li>
</ul>

<br>

<h2>Additional Resources</h2>

<p>There are numerous other tools and metrics being created by the community to evaluate FAIRness: 
</p>

<ul style=" padding-top: 1%; padding-bottom: 1%;padding-left: 5%;">

<li> Original principles published by FORCE11: <a href="https://www.force11.org/fairprinciples" target = "_blank"> https://www.force11.org/fairprinciples </a> and original article: <a href="https://doi.org/10.1038/sdata.2016.18" target = "_blank"> https://doi.org/10.1038/sdata.2016.18 </a>
    <ul style=" padding-top: 1%; padding-bottom: 1%;padding-left: 7%;">
    <li> The FAIR Data Principles feature 15 facets corresponding to the four letters of FAIR - Findable, Accessible, Interoperable, Reusable. </li>
    <li> FAIR metrics developed by the original research group: <a href="https://github.com/FAIRMetrics/Metrics" target = "_blank">https://github.com/FAIRMetrics/Metrics </a></li>
    </ul>
</li>
<li>FAIR <a href="https://doi.org/10.2218/ijdc.v12i2.567" target = "_blank">scoring rubric </a> used in the activity</li>
<li> <a href="https://zenodo.org/record/4081213#.YVS9YMZOnBI" target = "_blank"> FAIRsFAIR Data Object Assessment Metrics </a> (v0.4) Contains 17 core metrics to assess the FAIRness of a dataset. 
    <ul  style=" padding-top: 1%; padding-bottom: 1%;padding-left: 7%;">
    <li>This work builds on an RDA working group called FAIR Data Maturity Model (RDA) which published the <a href="https://www.rd-alliance.org/system/files/FAIR%20Data%20Maturity%20Model_%20specification%20and%20guidelines_v1.00.pdf" target = "_blank"> FAIR Data Maturity Model Specification and Guidelines </a> (2020):<a href="https://doi.org/10.15497/rda00050" target = "_blank"> https://doi.org/10.15497/rda00050
    </a> </li>
    <li>This group also released a beta tool in 2021 called that <a href="https://www.fairsfair.eu/f-uji-automated-fair-data-assessment-tool" target = "_blank"> F-UJI Automated FAIR Data Assessment Tool </a> which aims to computationally assess FAIRness by entering a DOI or URL for a dataset. </li>
    </ul>
</li>
<li>Australian Research Data Commons provides a self-guided question-based <a href="https://ardc.edu.au/resources/working-with-data/fair-data/fair-self-assessment-tool/" target = "_blank"> FAIR data assessment tool </a> </li>
</ul>
<br>
<br>

<style>
.flex-contianer {
  display: flex;
  justify-content: space-between;
}
</style>

<br>

<div class="flex-contianer">
     <a class="button button-primary" href="/CURATED/modules/module-t"> < Previous</a>
     <a class="button button-primary" href="/CURATED/modules/module-d"> Next > </a>
</div>
