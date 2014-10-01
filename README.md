Client/Server Application Development
=====================================

Members: <br> 
Jonathon Huston <br>
Matthew Campbell <br>
Kyle Harvey <br>
William McCulla <br>

Scenario: <br>
A film studio wants to celebrate their 120th anniversary with the launch of a new website, allowing registered users to suggest, rate and dowload clips from their favourite releases from the studio.  The studio wants users to be able to select/add/download movies based on Film name, Director or Cast member.

Part 1: Plan and Design
=======================

Project Specification: <br>
You are to submit a Project proposal document based on the selected scenario, addressing the following topics: <br>
• Group membership and project idea <br>
• Project aims and objectives (Details of what the system will achieve) <br>
• Requirements specification (Your system MUST cover all the requirements specified below as a bare minimum. Additional requirements are expected based on the scenario) <br>
• System Design. <br>
• Testing and Evaluation Plan. <br>
• Workload distribution (How the project will be distributed amongst the group members) <br><br>
This document should not be longer than 15 A4 pages.

Requirements: <br>
Your proposal should cover the following requirements as a bare minimum: <br>
• A database (Including Database Design and sample data) tailored to your specific scenario. <br>
• A public area to describe your application’s purpose <br>
• A registration area for new users, including a section on security <br>
• Secure area for registered users <br>
• Custom content in the secure area, tailored to the user logged in and the specific scenario.

Part 2: Implementation
======================

You must submit a Zip file named with your GroupNumber. This file must contain: <br>
• An exported database sql-file with Group Number (e.g. Group10.sql) <br>
• All files necessary for the correct function of the website (HTML, PHP, INC, etc) <br>
• A written report containing:
  o Design details (relationship justifications/assumptions, ER Diagram, Linked Relational Schema, any necessary details about the system) highlighting any alterations from the Project proposal document submitted in Semester I <br>
  o A valid username & password for your system <br>
  o Bibliographical reference of any code taken from another resource (e.g. URL of webpage) along with details of how you have adapted this code (use Harvard Standard) <br>
  o A statement from individual members of the group regarding group work load share and participation. <br>
  
  
The following is a general breakdown of marks for the final submission of the project: <br><br>
1. Database Design & Creation (10%)<br>
You will need to design and create a database for your allocated scenario. As a refresher these are the steps you should follow when creating your database: <br>
• Create an ER Diagram (see notes COM147 for ER Diagram notation). <br>
• Justify each relationship in BOTH directions. <br>
• For each entity type choose a sensible primary key plus at least 3 other appropriate attributes. <br>
• Use the relational mapping rules to create a set of linked tables <br>
• Implement the database in MySQL (through phpmyadmin) using appropriate data types, with primary and foreign keys specified <br>
• Add a reasonable number of records ensuring that the relationships are expressed through the data.<br><br>
2. Website basics (30%) <br>
You are expected to provide a simple hierarchy of pages (representing a small website) with: <br>
• A welcome page and public section of the website. This can include things like news section, quick links, FAQ, About Us pages, etc. These can be any mixture of dynamic and static pages. The welcome page must include a login/password form leading to a member area, and a link to a registration page for new members.<br>
• A registration page with the following checks and appropriate error messages: <br>
  o Existing Username <br>
  o Password length (minimum 8 characters) <br>
  o Password strength (Passwords should have at least a capital letter, a number and a symbol or punctuation mark) <br>
• Sessions set on login to ensure that pages are not accessible unless logged in as a valid user<br>
• A login page implemented with login check and appropriate error messages <br>
• A logout link that destroys sessions & returns to the welcome page <br>
• Your website must use a consistant style across all pages. <br><br>
3. Advanced features (50%) <br>
The group will decide on the added functionality to provide on the website according to the scenario described. The advanced features will be marked according to: <br>
• Level of overall effort evident <br>
• Code layout, structure, elegance, suitability, naming convention and comments <br>
• Data validation <br>
• Usability and accessibility <br>
• Evidence of enthusiasm and interest both in the project and the written report. <br><br>
4. Oral demonstration (5%) <br>
The group will showcase the software produced to the teaching team. It is expected that all group members be present during the demo and anyone may be questioned about any aspect of the development.

tl;dr lets fuck shit up <br>
<img src=https://raw.githubusercontent.com/group12mofos/GroupProject/master/dealwithit.gif>
