=================
Portfolio Webpage 
=================

Author: Tarun Savita Date:18 June 2025 

--Project Overview 
This project is a personal portfolio webpage designed to showcase my skills, education, 
experience, and projects. The webpage includes a structured navigation system, informative 
sections, and an interactive contact form. The goal is to create an engaging, user-friendly, and 
professional online presence. 


--Important HTML Elements & Their Roles 
The webpage is built using structured HTML elements: 

1. Head Section (<head>) 
• <meta> Tags: Ensures compatibility and responsiveness. 
• <title>: Defines the title displayed on the browser tab. 
• <link>: Associates the webpage with an external CSS file for styling.

2. Navigation (<nav>) 
• Contains a <table> layout organizing page links. 
• Dropdown navigation on the Contact page provides direct access to sections. 

3. Main Content (<main>) 
• Skills List (<ul>): Displays technical skills in bullet points. 
• Education Timeline (<ol>): Presents academic qualifications in sequential order. 
• Project Showcase (<table>): Tabular format highlighting project details. 
• Profile Image (<img>): Displays a professional avatar. 

4. Contact Form (<form>) 
• Text Inputs (<input type="text">,<input type="email">`) for user details. 
• Checkboxes (<input type="checkbox">) for preferred contact methods. 
• Radio Buttons (<input type="radio">) for inquiry type selection. 
• Date Picker (<input type="date">) for scheduling contact. 
• Range Slider (<input type="range">) for urgency level selection. 
• Submit Button (<button>) sends the form data.

5. Footer (<footer>) 
• Displays copyright details and professional title for branding. 


--Navigation System 
navigation system is implemented in two ways:  

1. Table-Based Navigation  
organizes navigation links ( elements) in a structured layout.  Clicking a link redirects users to 
different pages. 

2. Dropdown Navigation (Contact Page)  
creates a dropdown menu with page options. The onchange event automatically redirects 
users upon selection.


--Why Specific Input Types Were Chosen? 
Text Inputs: Allows users to enter names, emails, and messages.

Phone Input: Ensures a valid 10-digit format using a validation pattern.

Checkboxes: Provides multiple contact preferences to accommodate user choices.

Radio Buttons: Restricts selection to one inquiry type, avoiding conflicting choices. 

Date Picker: Facilitates scheduled user interaction without confusion.  

Range Slider: Makes urgency selection more interactive rather than manual entry. 