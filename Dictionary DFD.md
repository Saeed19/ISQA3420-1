
<h1>Entities</h1>
<p><b>Developer</b> The Corporate Person responsible for all the coding and the main software packages and preparing for the license scan.</p>
<p><b>Manager</b> Advising Authority to the software packages.</p>
<h1>Data stores</h1>
<p><b>NIST Vulnerability DB</b> Database that contains all known vulnerabilities in the software package.</p>
<p><b>Policy DB</b> Database that stores Policy documents for the relevant, associated software packages.</p>
<p><b>Software Package Vulnerability & License Information DB</b> Database that stores software package, license and vulnerability information.</p>
<h1>Processes</h1>
<p><b>Manage Software Package</b> Process that pulls up the policy request data for corresponding software projects based on Developer’s and Manager's request.</p>
<p><b>Retrieve Policy</b> Pull all data polices requested by manager or developer from policy database.</p>
<p><b>Edit Policy</b> Process where Manager submits or modifies policy documents.</p>
<p><b>Scanner License</b> Process that scans for any licenses that can be found in the program.</p>
<p><b>Request Lic&Vul Information</b> Consolidate and integrate the software project License Vulnerability Information came from the manger and developer.</p>
<p><b>Create policy</b> Process the data flow which would come came from the manager and send to policy data store to create/ Update and Upload the policy.</p>
<h1>Data Flows</h1>
<p><b>Software Package</b> Multiple code files that make up a software.</p>
<p><b>Software Package License Result</b> Open Source Software Licenses. These include Open source, MIT, Apache licenses, etc.</p>
<p><b>License & Vulnerability Result</b> Sends vulnerability data if any to be paired with the license data to store vulnerable data associated with the licenses.</p>
<p><b>Package Name</b> Name of software package/collection of files.</p>
<p><b>Vulnerability Result</b> Documented Open Source Software Package vulnerabilities.</p>
<p><b>License & Vulnerability Result</b> Process where manager or developer requests package for corresponding license info.</p>
<p><b>Policy Info</b> Response to manager for package, license & vulnerability information.</p>
<p><b>Policy Request</b> Request from manager for package policy, license & vulnerability information.</p>
<p><b>New Policy</b> Creation of policy that is requested by the manager to be sent to the Policy DB for storage.</p>
<p><b>Retrieve policy</b> Acknowledgement by Policy DB that the request has been processed and stored.</p>
<p><b>Software Policies request</b> Software policies that correspond with their respective software projects.</p>
<p><b>Software Project Policy Request</b> Request associated policy information for respective software projects.</p>
<p><b>Policy Update</b> Most up to date policy document approved by Manager.</p>

