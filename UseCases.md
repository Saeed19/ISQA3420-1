USE CASE 1
Title: Determine License and Vulnerability data by pulling up software policy to compare with software license.
Primary Actor: Manager 
Goal in Context: The Manager is able to determine license and vulnerability information from provided package information.
Stakeholders:a> Manger b.> Developer 
Manager: To get relevant OSS license and vulnerability data. 
Developer: To provide the relevant file/package level information
Preconditions: 
Software package policies are stored in the policy database. Relevant file/package information is in the NIST Vulnerability database Scanner provides proper OSS license data License and Vulnerability database is current and up to date
Main Success Scenario: Manager receives accurate and valid license and vulnerability data for the requested software packages and receives the policy data from the policy database.
Failed End Conditions: Manager receives inaccurate or invalid license and vulnerability information for the requested project packages and also does not receive the policy from the policy database.
Trigger: Manager requests project policy data to which license and vulnerability data is provided.
USE CASE 2
Title: Retrieve and update policy for software project
Primary Actor: Manager
Goal in Context: The manager is able to pull up and update policy documents for the software package.
Stakeholders: Manager
Manager: To provide updated software policy data. 
Preconditions: Relevant file data is in Software Package Vulnerability and License Information Database and is up to-date.
Main Success Scenario: The Manager receives software policy data and updates the policy for the software package.
Failed End Conditions: Manager receives inaccurate or corrupt policy information from the Software Package Vulnerability and License Information Database. 
The NIST Vulnerability database gives a license number associated with a vulnerable data.
Software Package License and Vulnerability Policy is not up and running.
Trigger: Corporate manager sends request to Software Package Vulnerability and License Information Database
USE CASE 3
Title: To find Policies for Corresponding Software Packages
Primary Actor: Manager
Goal in Context: The Manager is able to determine Open Source Software Package Policies from provided package data. The Corporate Manager can receive and update current policy documents.
Stakeholders: Manager
Manager: To retrieve and update software package policy data. 
Developer: To request and retrieve associated software policies.
Preconditions:
Relevant file data is in the Software Package Vulnerability and License Information database, Policy Database, and NIST Vulnerability Database is up-to-date.
Main Success Scenario: Manager receives associated policy for corresponding software based on corresponding request.
Failed End Conditions: Manager receives incorrect or corrupt software package policy.
Trigger: Corporate Manager request and receives accurate policy data.
