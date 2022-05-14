---
title: "D Step: Document for Curation"
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
&nbsp;&nbsp;1. identify main goals of having a documentation plan for one’s archive
   <br>
  &nbsp;&nbsp;2. review typical features of a documentation and digital archiving workflow plan, with a nod to digital preservation principles, illustrated by examples from other DCN institutions.
   <br>
  &nbsp;&nbsp;3. create a documentation report for their institution, on a “features” form.

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

<button class="collapsible">Accession</button>

<div class="content">
  <p>The record of deposit made upon addition to the repository collection with relevant cataloging details such as dates and depositor names.</p>
</div>
<button class="collapsible">Catalog</button>
<div class="content">
  <p>The descriptive metadata associated with the deposited files and dataset covering accession, findability, contributors, and content overviews.</p>
</div>
<button class="collapsible">Provenance</button>
<div class="content">
  <p>In the context of digital preservation, refers to the history of a digital object including its origins (e.g. depositor name) and any transformations applied to that original object before release.</p>
</div>
<button class="collapsible">Archival Information Package </button>
<div class="content">
  <p>In the context of digital preservation, refers to the inclusion of all files related to dataset preservation, including documentation, in a single bundled format such as .TAR or .Zip, often including checksum metadata for fixity checks, such as MD5 files. 
</p>
</div>
<button class="collapsible">Checksum</button>
<div class="content">
  <p>a unique digital code with a separate reference copy applied to, and preserved with, a given digital object or bundle. Any change in bits checked periodically against the reference copy indicates corruption of the preserved original files, signaling the need to replace it with a backup.
</p>
</div>
<button class="collapsible">Terms of use</button>
<div class="content">
  <p>generally a set of metadata fields covering user’s obligations when downloading files, including licensing, such as Creative Commons, citation requirements, confidentiality declarations, and other conditions.</p>
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
Throughout the deposit and curation process we are recording the significant treatments or actions applied to the submission. This is distinct from documentation the depositors created to accompany their own datasets. Archives and repositories should document records of the collection’s accession, progress as a project, changes made by curators from the original data submission, and preservation documentation.
<br>
<br>

<h2>&nbsp;D Step Actions</h2>
<br>
<h4>What is curation documentation?</h4>
<p>
The goal for dataset documentation is to support the long-term preservation of the data collection by recording curation activities and treatments. At minimum this involves: <br>
  &nbsp;&nbsp;&nbsp;1.  Accessioning and deposit records
   <br>
  &nbsp;&nbsp;&nbsp;2.  Repository dataset record metadata
   <br>
   &nbsp;&nbsp;&nbsp;3. Provenance/change logs
   <br>
   &nbsp;&nbsp;&nbsp;4. Service workflow
   <br>
   &nbsp;&nbsp;&nbsp;5. Preservation packaging metadata
</p>
<br>

Such documentation could be bundled with a preservation copy of the dataset and when using packaging software such as BagIT. This module will illustrate these types of documentation for dataset curation.
{start accordion here}
<br>
<br>

<h4>Accessioning and deposit records</h4>
<p>
Every data repository service needs minimal tracking of deposited data collections. The traditional archival term “accessioning” can refer to the receiving and processing of digital deposits with accompanying recordkeeping.

Most repository platforms like Dataverse or DSpace maintain some accessioning information such as deposit dates, but they do not necessarily maintain everything your repository service may wish to track, nor provide summary reports for internal administration.</p>
<br>
<br>
[Dataverse minimal accessioning information]
<br>

<img src="../../images/Dstep-1a.png">
<img src="../../images/Dstep-1b.png">
<br>
<br>
<p>For example, ArchiveMatica as a general digital archiving platform supports fairly extensive workflow and accessioning information to track the deposit process; however, currently this platform is not readily adaptable to user-facing research data repositories.</p>
<p>[Define image 1] ArchiveMatica accessioning record view</p>
<img src="../../images/Dstep-2.png">
<br>
<br>
<p>Repository services may have to set up external systems of tracking on databases or spreadsheets, usually with some manual data entry. Johns Hopkins University Data Services, for example, maintains a spreadsheet, with unique accession numbers and “package name” for datasets, as well as dates and contact information.</p>
<p>[Define image 2] Accessioning spreadsheet</p>
<img src="../../images/Dstep-3.png">
<br>
<br>
<p>Other ticket-based project management tools such as JIRA can be used to capture some of the accessioning metadata while also tracking steps in the curation workflow. Examples of JIRA will be shown in the section on Service Workflow Documentation.</p>
<h4>Checklist of metadata for accessioning and depositing records.</h4>
<table frames=hsides rules=rows>
<tr>
<td  style="padding-top: 1%; padding-bottom: 1%;">Deposit ID</td>
<td  style="padding-top: 1%; padding-bottom: 1%;">A unique identifier for the collection deposit (usually different than the DOI.)</td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">Preservation filename</td>
<td style="padding-top: 1%; padding-bottom: 1%;"> If the repository creates separate preservation copies or bundles, such filenames are often generated following a naming convention.</td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">Collection title</td>
<td style="padding-top: 1%; padding-bottom: 1%;">Supplied by the depositor, sometimes with modification suggested by the curator.</td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">DOI</td>
<td style="padding-top: 1%; padding-bottom: 1%;">Digital Object Identifier registered with DataCite unique to the citable dataset, sometimes generated for individual files.</td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">Depositor</td>
<td style="padding-top: 1%; padding-bottom: 1%;">Usually the contributing creator of the dataset, but additional fields might designate a person responsible for the dataset over time (such as a project PI) if there are separate depositors as the corresponding contact (such as a student.)</td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">Affiliation</td>
<td style="padding-top: 1%; padding-bottom: 1%;">Institution and often a department or research group.</td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">Date deposited</td>
<td style="padding-top: 1%; padding-bottom: 1%;">Date officially received by the repository</td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">Date distributed</td>
<td style="padding-top: 1%; padding-bottom: 1%;">Generally the date publicly available</td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">Date preserved</td>
<td style="padding-top: 1%; padding-bottom: 1%;">May be a separate later date when prepared for preservation.</td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">Curator</td>
<td style="padding-top: 1%; padding-bottom: 1%;">One or more repository staff who managed the deposit and any file transformations and/or correspondence with the depositor.</td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">IRB documentation</td>
<td style="padding-top: 1%; padding-bottom: 1%;">For datasets from human subject research, fields indicating whether depositors provided consent form sample or other IRB approval and privacy disclosure screening conducted.</td>
</tr>
</table>
<br>
<h4>Repository dataset record metadata</h4>
<p>Much of the crucial metadata about a deposited dataset is captured in the repository collection record itself. Beyond the accessioning information (deposit date) this includes the collection title, citation, DOI, descriptions, authors and other details.  For most platforms, this information cataloging the deposit record is visible online to any visitor to the site. Additional metadata may only be visible to repository administrators or staff.

Is it a best practice to keep all of that collection metadata locked within that single repository platform? In addition to the platform’s own backup, it may be prudent to export that record metadata for internal administration as well as a reference for users.

For administering the repository, exporting and preserving record metadata as a separate file can serve as a backup independent of the platform, and can also be packaged along with preservation copies of the data files themselves. Dataverse, for example, allows export of metadata in several formats, such as DDI, which could potentially be used to reconstitute all deposit records on another platform.

[Image - Repository metadata export, Dataverse]

</p>
<img src="../../images/Dstep-4.png">
<br>
<br>
<p>Cornell builds a curation log for internal use partly from platform-supplied information but manually adds additional curation details, and adds the file to the download collection. This approach blends the user-facing information and administrative documentation for preservation.
[image alt-text ] Cornell README that includes record metadata.
</p>
<img src="../../images/Dstep-6.png">
<br>
<br>
<p>For repository visitors, the files they download may not necessarily include a “README” document that includes that record information, especially the crucial citation, description, authors, and terms of use. Users would not have those details as a “take away” kept with the downloaded files if they never return to the original repository collection. Depending on the repository’s deposit methods, curators may rely on researchers to supply a README. If it is feasible to supply that record summary to the depositor as a README starter, the depositor may be encouraged to add additional details about the datasets and their use. Alternatively, curators might also add such details to a README, and create one when not supplied by the depositor.

Some platforms generate a deposit record summary automatically to be included with all download files.

U. Michigan’s Deep Blue data repository generates README-style record documentation automatically included with the downloaded files.
[Alt-text: U. Michigan record documentation accompanying dataset downloads.]

</p>
<img src="../../images/Dstep-5.png">
<br>
<br>
<h4>Checklist for documenting repository record metadata</h4>
If a README metadata record is generated for repository users to download with data files, essential “take away” information could include:
<ul style="padding-left: 3%;">
<li style="padding-top: 1%; padding-bottom: 0.5%;">Data citation (Title, authors, date, publishing repository, DOI link)</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">DOI or link to deposit</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Depositor contact information</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Date published</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Description of dataset (or associated publication abstract.)</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Associated publication citation and link</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Rights license and terms of use</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">File list with additional description</li>
</ul>
<br>
<h4>Provenance/change logs</h4>
<p>Provenance is another term adapted from traditional archiving. It refers to documenting the history of a digital object including its origins (e.g. depositor name) and logging any transformations applied to that original object before release. Subsequent version changes as well as ownership or location changes (e.g. moving to another repository) should also be documented with the data collection provenance.

Such change logs provide another layer of context to the preservation package for a collection, with version tracking being especially important for collection management.

Again, few repository platforms automatically capture all aspects of provenance, so repositories may have to devise external workflows for documentation, either automated or manual.
Cornell’s repository system includes fields for recording each change during the curation process, that can be included in the record metadata README document included with the data file downloads.

Image: Cornell provenance change logs.

</p>
<img src="../../images/Dstep-7.png">
<br>
<br>
<p>Johns Hopkins creates a simple table in MS Word that is included with the preservation copy of the data files.</p>
<img src="../../images/Dstep-8.png">
<br>
<br>
<h4>Checklist for provenance log</h4>
Checklist of essential or minimal elements to capture for the various types of metadata.
<ul style="padding-left: 3%;">
<li style="padding-top: 1%; padding-bottom: 0.5%;">Deposit identifier/record name</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Change date</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Curator</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Action taken (description)</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Versioning naming convention (post publication)</li>
</ul>
<br>
<h4>Service workflow</h4>
<p>The service workflow refers more generally to the overall handling of a dataset as a project or task, from initial inquiries from a depositor and subsequent email exchanges, to the deposit and curation steps, to publication and maintenance. Some repository institutions take a “project management” approach to deposits following deposits “received,” “in process,” and “completed” with dates, curators assigned, and other tracking details.

Workflow documentation is mainly useful for repository management but it may be relevant to capture some workflow elements for the dataset deposit record and provenance for preservation.
Some digital archiving platforms such as Archivematica have built-in service workflow tracking, but often repositories may need to adapt general purpose project management software and build customized workflows. Request tracking and ticketing systems such as JIRA, ORTS or Request Tracker could be adapted from their typical IT helpdesk or code development functions.

For example, the Data Curation Network uses JIRA to track curation help requests.

</p>
<img src="../../images/Dstep-9.png">
<br>
<br>
<p>Tickets or “Issues” for JIRA can be customized with fields relevant to data deposits, such as U. Michigan’s:
</p>
<img src="../../images/Dstep-10.png">
<br>
<br>
<p>U. Illinois’ system also captures email exchanges:</p>
<img src="../../images/Dstep-11.png">
<br>
<br>
<p>Service workflow ticketing systems may not be sufficient in themselves for tracking the deposit and accessioning records of completed projects. A “distributed” approach might use JIRA in combination with other records in multiple locations, such as spreadsheets and archived Outlook email exchanges. JHU, for example, is supplementing their spreadsheet system, mentioned earlier, with JIRA tracking for in-process deposits.
[JHU image]
</p>
<h4>Checklist for service workflow</h4>
Service workflow focuses on tracking the stage in the process from accession to publication/preservation. A given deposit’s “ticket” might include all or part of the deposit record metadata and accessioning information but should have relevant “at-a-glance” information which could include:
<ul style="padding-left: 3%;">
<li style="padding-top: 1%; padding-bottom: 0.5%;">Deposit ID/filename</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Depositor</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Status (e.g., Intake, curating, publishing, closed)</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Curator (assigned to)</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Relevant activity dates (deposit, curate, publish)</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Last activity/modification date</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Notes</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Work time log (optionally)</li>
</ul>
<br>
<h4>Preservation packaging metadata</h4>
<p>A final step of documentation can occur at the preservation stage of dataset archiving. Data files can be bundled with all relevant documentation to form a “package” ready for long-term storage ideally capable of restoring the full data collection. Certain digital archiving software produces self-contained packages bundling files, descriptive metadata, and preservation metadata such as md5 checksum files for fixity checks.

<a href="https://github.com/LibraryOfCongress/bagit-java" target="_blank">BagIt</a> is a leading digital archiving protocol that, in addition to preservation metadata, allows additional descriptive metadata files that could include accessioning and deposit records. The <a href="https://github.com/DataConservancy/dcs-packaging-tool" target="_blank">Data Conservancy Package Tool</a> developed by Johns Hopkins, for example, uses the BagIT protocol to generate a “bag-info” file packaged with data into a single TAR file for their preservation system.

</p>
<img src="../../images/Dstep-12.png">
<br>
<img src="../../images/Dstep-13.png">
<br>
<br>
<p>Other programs like <b>ArchiveMatica</b> leverage this ability to add preservation metadata to the BagIt package. Even without such systems, it is a best practice to keep as much documentation together with preserved files, including provenance and preservation metadata, to create a more complete backup of the archive and curation process.</p>
<h4>Checklist for preservation packaging </h4>
Much of the deposit metadata and accessioning documentation discussed so far could be preserved with the files as part of the package.
Documentation that might be included as part of the preservation package could include:
<ul style="padding-bottom: 1%; padding-left: 3%;">
<li style="padding-top: 1%; padding-bottom: 0.5%;">Accessioning records</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Deposit metadata</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Provenance records</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Depositor correspondence/emails (optional)</li>
</ul>
Special preservation metadata might include:
<ul style="padding-left: 3%;">
<li style="padding-top: 1%; padding-bottom: 0.5%;">Bagit info files</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Md5 checksum manifest files for fixity checks</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Special record IDs and/or file naming for preservation packages (not used elsewhere)</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Versioning information for updated files.</li>
</ul>
<br>
<br>
<h2>Key Ethical Considerations</h2>
<ul style="padding-left: 3%;">
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Document that disclosure risk review has taken place. State if changes from original data have been made, but do not give enough detail on changes to reverse-engineer any anonymization.</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Include consent (or waiver) and/or IRB approval of sharing with administrative documentation.</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Consider collecting contributor demographics.</li>
</ul>
<br>
<blockquote class = "highlighted-text">
<h2> Activity </h2>

<p>

This module covered several aspects of documentation recommended for administering an institutional data repository.

</p>
<h3>Activity Materials</h3>
<h4>Directions</h4>
<p>This exercise is about articulating your current local institutional repository documentation strategy, or desired approach if you do not currently have a data archive or curation program.

Using the checklist below, draft answers to how you are currently, or would like to, in a future state document your curation, preservation, and data related activities.

</p>
<h4>Activity Checklist</h4>
<br>
<table frames=hsides rules=rows>
<th>Documentation Type</th>
<th>Description</th>
<th>Questions to Address</th>
<tr>
<td  style="padding-top: 1%; padding-bottom: 1%;">Accessioning and deposit records</td>
<td  style="padding-top: 1%; padding-bottom: 1%;">Accessioning here refers to documentation of data deposits and processing. Minimal information may include deposit IDs or filenames following a naming convention, relevant dates, depositor names and curator names. Other deposit record metadata might be captured, but of relevance here is your method of assembling and viewing the lists of deposits’ essential information, their history and status.</td>
<td  style="padding-top: 1%; padding-bottom: 1%;">Are such tracking and reporting features in your repository platform (or ideal system) or via spreadsheets or other means?</td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">Repository dataset cataloging metadata</td>
<td style="padding-top: 1%; padding-bottom: 1%;"> “Cataloging” metadata refers here to the information about each dataset record, including metadata visible to viewers of the repository and internal administrative metadata.
</td>
<td style="padding-top: 1%; padding-bottom: 1%;">The accessioning records may track some of this metadata, but does your repository export and preserve all or part of the catalog record outside of the platform itself? (Dataverse, for example, exports metadata in several formats.)  Do you have, or plan, a version of the catalog record for users that exports along with the data as a README?</td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">Provenance/change logs</td>
<td style="padding-top: 1%; padding-bottom: 1%;">The provenance of a digital object can refer to its record of changes from original deposit to transformations during curation before release. Subsequent version changes, location changes, can also be relevant to the collection’s long term preservation in addition to accessioning metadata.</td>
<td style="padding-top: 1%; padding-bottom: 1%;">How does (or would) your repository capture the history of transformations during curation and/or updates after publication?</td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">Service workflow</td>
<td style="padding-top: 1%; padding-bottom: 1%;">Archive deposits follow a workflow from requests, deposits, curation, publication that can be tracked like a project management task. All repositories document this workflow in some form. Sometimes this is done manually such as through spreadsheets or calendars. Some repository platforms track at least part of a workflow, such as deposit dates and release status. Project management or request ticketing systems such as JIRA can also be adapted to much of the workflow documentation</td>
<td style="padding-top: 1%; padding-bottom: 1%;">How does your repository track workflow? What software do you use, or would explore using?</td>
</tr>
<tr>
<td style="padding-top: 1%; padding-bottom: 1%;">Preservation packaging metadata</td>
<td style="padding-top: 1%; padding-bottom: 1%;"></td>
<td style="padding-top: 1%; padding-bottom: 1%;">What is your repository’s method or planned method, for preserving archived files and associated metadata?<br>
<br>
Do you/will you have a separate preservation copy of files from user-facing files in the platform?<br>
<br>
Do you/will you package files and relevant documentation together using protocols such as <a href="https://en.wikipedia.org/wiki/BagIt" target="_blank">BagIt</a>? Describe, and also mention the preservation format (e.g.,.TAR or .ZIP)
Is the correspondence/email with depositors preserved, and how?<br>
<br>
Does your preservation package include special preservation metadata such as MD5 records for fixity checks, special preservation IDs or filename conventions, or other descriptive metadata besides the catalog and accessioning metadata?</td>

</tr>
</table>

</blockquote>

<br>

<h2>Review of the Document Step (D Step)</h2>
This module discussed several aspects of documentation beyond what depositors provide, that help with administration and workflow of an institutional data repository. Traditional archiving and project management supplies some relevant terminology for what documentation to collect and preserve, including:
<ul style="padding-left: 3%;">
<li style="padding-top: 1%; padding-bottom: 0.5%;">Accessioning records for the receiving and processing of deposits.</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Deposit record metadata exported from the platform.</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Provenance of all changes from the original dataset and post-publication updates.</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Workflow tracking of ongoing deposits, and optionally, correspondence, with a ticketing system or a similar project management approach.</li>
<li style="padding-top: 0.5%; padding-bottom: 1%;">A preservation package of files and documentation including metadata specific to preservation, such as md5 fixity checksum data.</li>
</ul>
<p>The exercise is an opportunity to record, develop, and potentially share documentation plans for your institutional repository.

These five types of documentation could ideally be sufficient to reproduce the archive apart from its platform, as a best practice for long-term digital preservation.

</p>
<br>
<h2>Additional Resources</h2>
Resources referenced in this guide and related to dataset documentation:
<ul style="padding-left: 3%;">
<li style="padding-top: 1%; padding-bottom: 0.5%;">Archivematica: open-source digital preservation system [WWW Document], n.d. URL <a href="https://www.archivematica.org/en/" target="_blank">https://www.archivematica.org/en/</a> (accessed 1.13.22).
</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Atlassian, n.d. Jira | Issue & Project Tracking Software [WWW Document]. Atlassian. URL <a href="https://www.atlassian.com/software/jira" target="_blank">https://www.atlassian.com/software/jira</a> (accessed 1.13.22).</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Deep Blue Repositories, Univ. of Michigan Library [WWW Document], n.d. URL <a href="https://www.lib.umich.edu/collections/deep-blue-repositories" target="_blank">https://www.lib.umich.edu/collections/deep-blue-repositories</a>(accessed 1.13.22).</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Digital Content Transfer Tools - Digital Preservation (Library of Congress) [WWW Document], n.d. URL <a href="https://www.digitalpreservation.gov/series/challenge/data-transfer-tools.html" target="_blank">https://www.digitalpreservation.gov/series/challenge/data-transfer-tools.html</a> (accessed 1.13.22).
</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Guide to writing “README” style metadata | Cornell Research Data Management Service Group [WWW Document], n.d. URL <a href="https://data.research.cornell.edu/content/README" target="_blank">https://data.research.cornell.edu/content/README</a> (accessed 1.13.22).</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Kunze, J.A., 2021. Bagitspec. URL <a href="https://github.com/jkunze/bagitspec" target="_blank">https://github.com/jkunze/bagitspec</a></li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Jones, S., Pryor, G. & Whyte, A. (2013). ‘How to Develop Research Data Management Services - a guide for HEIs’. DCC How-to Guides. Edinburgh: Digital Curation Centre. <a href="https://www.dcc.ac.uk/guidance/how-guides/how-develop-rdm-services" target="_blank">https://www.dcc.ac.uk/guidance/how-guides/how-develop-rdm-services</a> (see section on data catalogs and repositories.) </li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">The Dataverse Project - Dataverse.org [WWW Document], n.d. URL <a href="https://dataverse.org/home" target="_blank">https://dataverse.org/home</a> (accessed 1.13.22).</li>
<li style="padding-top: 0.5%; padding-bottom: 0.5%;">Packaging Tool | Data Conservancy, n.d. URL <a href="https://dataconservancy.org/software/" target="_blank">https://dataconservancy.org/software/</a> (accessed 1.13.22).</li>
</ul>
<br>
<br>
<div class="flex-contianer">
     <a class="button button-primary" href="/CURATED/modules/module-e"> < Previous</a>
</div>
