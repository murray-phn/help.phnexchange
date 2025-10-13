# Changelog

All notable changes to the PHN Exchange will be documented in this file.

<!-- Partner PHNs are invited to review and test new versions prior to release and publishing on the live site.

Each partner PHN will:

- Be notified when a new major version is available for testing
- Be provided access to the test site
- Have 5 working days to complete their testing and provide feedback
- Be able to send feedback via [support@phnexchange.com.au](mailto:support@phnexchange.com.au)

After the test period has ended, the new version will usually be released and published on the live site within two working days. -->

### 6.80 - 26/08/2024

New features

- **GP Data Report Upgrade**

The GP Data Report has been internally remade to support each PHN customizing the data report to their own requirements.

This includes strong performance improvments to GP Data report load times.

- **Security and performance improvments**

- **Internal database improvments**

### 6.18 - 28/03/2024

New features

- **PHN Admin**

> Practices Visual Reformulated to Incorporated Primary Sense and Polar databases support
> - PHN Exchange team is now providing support for PHNs that uses the Primary Sense clinical decision support tool, most of the Practices Reports are already being generated in the Practice Hub.

- **GP Hub**

> Now users can print all the reports at once, using the button on the right floating menu.
> PHNs with Primary Sense can now view reports from their practices data.

Adjusts

 - **PHN Exchange**
 
 > User Interface3 adjustments.
 > Backend proccesses improved, to achieve better performance overall.

- **Home Page**

> LGAs map demarcation adjusted to the latest (2023) published by the Australian Bureau of Statistics (ABS) website.

- **Priority Areas**

> Removed the mouse scroll to zoom in and out maps, so users dont zoom in/out maps while trying to scroll down the page.

- **GP Hub**

> Practice Snapshots were updated, before it was showing Snapshots of the most current month, and Practices that didnt submit their extraction on time, were seeing blank values. Updated to get the Snapshot of the latest data evr submitted.
> Print Report button is now located on the top section of each group of reports, to improve user experience.
> Some reports were renamed, to reduce confusion and redundancy.
> Removed Redundant charts and extra PIP QIs reports (a, b and cs).
> Removed the button to view a video about each of the reports as it was outdated and was not being visualized by users.

- **PHN Admin**

> Reports
> - Adjusted the Department of Health Report.

- **PHN at a Glance**

> Page reformulated, with graphs reorganized/aggrouped.


### 5.78 - 14/07/2023

New features

- **PHN Admin**

> Reports > Power Bi 
> - Users can use PHN Exchange platform to share Power BI reports. After providing the hyperlink, the user can link it to one or more practices, or to all the practices on that PHN. The practice members will be able to access them through their practice page, on GP Hub. PHN's are responsible for adding row level permissions based on practice email address. For more information contact support.

> Practices > Practice Groups
> - PHN Admins and Practice Coordinators can now aggroup practices. There will be extra functionalities soon that will reflect on how Practice Members experience the website.

- **PHN at a Glance**

> PHN Admins can use the Practice Groups (as mentioned above) functionality in the PHN at a glance page! In the Practices Overview section, you can see the top and bottom 5 practices of a group only, as well as the entire PHN practices, for the PIP QI measures.

- **Two-factor Authentication**

> To increase the security of the data and to conform with the latest policies, users must now enter a 6-digit number code sent to their e-mail, when attempting to log in and access the website content. Users registered using their Microsoft Account, are exempted, as they have their own multi factor authentication.

- **GP Hub**

> Data Reports
> - New graphs added to the “Diabetes Trend” section of the page

Adjusts

- **Practices' Members (PHN admins, PHN practice coordinators and practice managers only)**

> PHN Admins, PHN practice coordinators and practice managers can now also assign other users to the practices and even register new PHN Exchange users themselves, assigning them to the respective Practice.
> The new practice members and managers registered will receive an email that they only have to confirm, and they will be able to see their practice’s reports right away (they will set their own passwords, so no need of a pre-set password anymore!)

- **GP Hub**

> Data Reports
> - The Practice Snapshot (Standard and Advanced) are being generated way faster than before.

- **PHP Version**

> Now using version 8.2 of the PHP language.

- **Minor fixes**

> - ABS Atlas > The link is opening a new tab with the Australian Bureau of Statistics (ABS) page.
> - Priority Areas > When you click on an LGA, a new tab will be open with the address of their Census Community Profiles on the ABS page.
> - PHN Admin > Priority Areas > When a new document is uploaded, if there is any error on the file, the user will know exactly what the error is they need to fix so they can upload the data.
> - GP Reports without data > If data is non-existent (due to lack of extractions or different database architectures between different PHNs), a new message will appear in the graph to inform this.
> - Other bugs

### 5.30 - 16/11/2022

New features

- **GP Data Report**

> Users can toggle between 'Practice and PHN' and 'Practice numbers only'. After accessing a Practice's Data Reports, there is a new option on the right side floating menu, at the bottom. The 'graphs option' and select 'Practice and PHN' or 'Practice numbers only' visualization.

> - If 'Practice and PHN' is selected: The page will reload and you can select the report to see the percentage numbers of patients for that graphic and measure against the practice's PHN average.
Example: Demographics - Active Pensioners > The graph will show the Practice's percentage of Active pensioners (dark blue) and Practice's PHN average of Active pensioners (light blue).
>
> - <b>(NEW)</b> If 'Practice numbers only' is selected: The page will reload and you can select the report to see the total numbers of patients for that graphic and measure.
Example: Demographics - Active Pensioners > The graph will show the Practice's total numbers of Active pensioners (dark blue) and total number of Active patients (light blue).

> New Graphs:

> - Chronic Conditions Management Trend – Active patients with a GPMP with 10997, last result in 12 months.

> - ATSI Health Trend – Active Aboriginal and/or Torres Strait Islander patients with a GPMP with 10987, last result in 12 months.

- **Practices' Members (PHN admins only)**

> - PHN Admins can now use the GP Admin area, and click to edit a Practice and Register a User to PHN Exchange (before, they could only assign an existing user to a practice).

- **Update password (users not registered with Microsoft Account)**

> - PHN Exchange users that have not registered using their Microsoft Account login method to register, can update their registered password. After loging in, they can use the My Account page to update their password.

Adjusts

- **PHN Admin - Reports**

> - The new DOH Reports for PIP QI specifications file was adjusted to capitalize all the practices’ names and LGAs, so when submitted, the user won’t receive warnings about this.

### 5.16 - 27/07/2022

New Features

- **GP Data Report**

> - See the name of the current Practice on the Navigation Menu.
>
> - When hovering the mouse for a couple seconds, you can now see a simple formula to understand what they are being compared against.
>
> - Since yellow, red and light green graphs can mean different things in agraph, the graphs were re-coloured. Now its used only blue, pink, purple and dark green pallete colors.
>
> - Name pattern, all the measures and graphs have now the same naming convention.

Added

- **GP Data Report – Practice Snapshot - Advanced**

> Medication Review: "Active patients on 8 or more medications"

- **GP Data Report – Demographic Profile**

> "Active patients on 5 or more medications"
>
> "Active patients aged 65 years and over, with no visit recorded in last 6 months"
>
> "Active patients with Mental Health Diagnosis"
>
> "Active patients with Shared health Summary (SHS) Upload during last month"
>
> "Active Aboriginal and Torres Strait Islander patients with Chronic Disease"

- **GP Data Report – Data Quality Trend**

> "Active patients with Indigenous status"
>
> "Patients with no visit over 36 months"
>
> "Active patients with Diagnoses not Coded"

- **GP Data Report – Chronic Conditions Management Trend**

> New section
>
> "Active patients with GPMP/TCA, last result in 12 months"
>
> "Active patients with GPMP/TCA review, last result in 3 months"
>
> "Active patients with GPMP/TCA review, last result in 6 months"
>
> "Active patients on 5 or more medications with MMR, last result in 12 months"

- **GP Data Report – Mental Health Trend**

> "Active patients with MHTP, last result in 12 months"
>
> "Active patients with MHTP Review, last result in 3 months"
>
> "Active patients with MHTP review, last result in 6 months"
>
> "Active patients with a MH condition on 5 or more medications with MMR, last result in 12 months"

- **GP Data Report – Health Assessments Trends**

> "Active patients with Heart Health Assessment"

- **GP Data Report - Aboriginal and Torres Strait Islander Health Trends**

> "Active Aboriginal and/or Torres Strait Islander patients with GPMP/TCA, last result in 12 months"
>
> "Active Aboriginal and/or Torres Strait Islander patients GPMP/TCA Review, last result in 3 months"
>
> "Active Aboriginal and/or Torres Strait Islander patients with GPMP/TCA Review, last result in 6 months"
>
> "Active Aboriginal and/or Torres Strait Islander patients on 5 or more medications with MMR, last result in 12 months"

- **GP Data Report – Immunisation**

> "COVID - Doses applied in the last month"

Updated

- **GP Data Report – Practice Snapshot - Advanced**

> Chronic Disease Management: "Active patients with GPMP/TCA, last result in 12 months"
>
> - It was 24 months. Plus, the formula has been updated, its now divided by the "total of active patients with chronic disease", not just "total of active patients".
>
> Chronic Disease Management: "Active patients with GPMP/TCA Review, last result in 3 months"
>
> - It was 6 months. Plus, the formula has been updated, its now divided by the "total of active patients with GPMP", not just "total of active patients".
>
> Medication Review: "Patients on 5 or more medications (Active pattients) with Medication Management Review (<12mths)"
>
> - Updated to "Active chronic patients on 5 or more medications with MMR, last result in 12 months".

- **GP Data Report – Data Quality Trend**

> "Active patients aged 15 years and over with smoking status recorded"
>
> - It was over 18 years old before.

- **GP Data Report – Screening Trend**

> "Active patients aged between 50 to 74 years old with bowel screens in last 2 years"
>
> -Updated to only count patients between 50 and 74 years old.
>
> "Participation in Breast Screen Australia program, women aged 50–74"
>
> -Updated to only count patients between 50 and 74 years old, not 18-70 anymore.
>
> "Participation in the National Cervical Screening Program, people aged 25–74"
>
> -Updated to only count patients between 25 and 74 years old, not 18-70 anymore.

- **GP Data Report – Health Assessments Trends**

> "Active patients aged 75 years and over with Health Assessment, last result in 12 Months"
>
> - Updated to only count the ones made in the last 12 months.

- **GP Data Report - Aboriginal and Torres Strait Islander Health Trends**

> "Active Aboriginal and/or Torres Strait Islander patients Health Assessments, last result in 12 months"
>
> - Added the condition of last result in 12 months.


Removed

- **GP Data Report – Practice Snapshot - Advanced**

> Chronic Disease Management: "Active Aoriginal and/or Torres Strait Islander patients with GMPM/TCA last result <24 months"
>
> - Moved to the "Aboriginal and Torres Strait Islander Health Trends" section, in graphic form, and not it is 12 months.
>
> Chronic Disease Management: "Active Aoriginal and/or Torres Strait Islander patients with GMPM/TCA Review last result <6 months"
>
> - Moved to the "Aboriginal and Torres Strait Islander Health Trends" section, in graphic form, and not it is 3 months.
>
> Mental Health: "Mental health diagnosis (Active Patients) with Mental Health Treatment Plan (<12months)"

- **GP Data Report – Mental Health Trend**

> "Proportion of active mental health patients with GP-MHTP Review"

- **GP Data Report – Immunisation**

> "Adult Pneumococcal"
>
> - To be added back in the next release.

Adjusted

- **GP Data Report – PIP QI**

> Fixed the error that was not printing the titles of graphs 2b and 3b's, when trying to print this report.

### 4.9 - 11/08/2021

New Features

- **GP Data Report – PIP QI**

> Now users can export the reports in a .pdf format;
> 
> Added date information, to indicate which extraction the report was generated from.

Updated

- **GP Data Report – Practice Snapshot**

> Adjusted the calculus of "Indigenous Status recorded (Active patients)", and "HbA1c Recorded" for "Patients with Diabetes".


### 4.8 - 11/06/2021

New Features

- **Priority Areas - New Data Columns "PHN" and "AUS"**

> Previously the PHN column was auto-calculated, while this worked to some degree it did not always present the correct information, this has changed to be defined by PHN's directly.
> The addition of AUS column offers the ability to compare data against Australian statistics.
> 
> Please note! Your Import file for Priority Areas will have to be updated! Example file downloaded in (PHN Admin > Priority Areas > Download Template).
> Or you can update your import file columns to be the following:
> Priority Area, Subject, Measure, Source, Bias, Description, Data Source Link, <b>PHN</b>, State, <b>AUS</b>
> If you need any assistance with Priority Area import files, please contact us at: support@phnexchange.com.au

- **Priority Areas - Visual Improvements**

> Priority Areas has been updated to fit much more data.

- **PHN Listing**

> A searchable list of all PHN's are now shown on the home page as an alternative option from the map.

### 4.5 - 12/03/2021

Added

- **Priority Area data export from Admin Panel**


Changed

- **GP Data Report - MBS Item services - Past 12 months**

> Changed previous (Count of Patients by MBS Item) table to (MBS Item services - Past 12 months).
This change come as advice to make the chart more useful for practices wishing to see MBS Items given within minimum claiming periods.

- **Priority areas - Show population default to OFF**

> Population numbers are now hidden by default until turned back on with the settings cog in the top right of the priority areas page. This change is to save confusion and let PHN's show their own population numbers in priority areas. This feature is now only intended to give a reference to previous census population numbers if needed.

Upgraded

- **Backend upgraded to PHP 8**

Fixed

- **PIP QI Charts were incorrect by a margin of 1%-2% in some cases**

- **Coronary Heart Disease Trend Charts not calculating correctly**

### 4.4 - 18/12/2020

Added

- **Additional description field to measures in Priority Areas**

### 4.3 - 4/12/2020

Added

- **New PIP QI GP data report graphs**

All new set of 12 graphs that pull directly from PAT BI to report on the 12 quality improvement measures.

### 4.2 - 26/11/2020

Fixed

- **Error with GP Data report graphs**

### 4.1 - 30/10/2020

Changed

- **Updated priority area interface**

Simplified the priority area interace to better use the screen space to show data.


### 4.0 - 13/10/2020

Added

- **Priority area import completed**

Completed priority area import feature.

### 3.16 - 29/09/2020

Fixed

- **Mapping functionality**

Resolved issue with maps being used in PHN Exchange not loading correctly.

- **Priority area import first implementation**

Resolved additional use cases and data types for importing the priority area template data.


### 3.15 - 25/08/2020

Fixed

- **Priority area import**

Resolved several issues related to importing Priority Areas template files.


### 3.14 - 31/07/2020

Added

- **Practice engagement report**

Option to export engagement practices have with PHN Exchange.

- **License assigned practices report**

Option to export practices that have been assigned to a specific license.

### 3.13 - 16/07/2020

Added

- **Finished practice resources functionality**

PHNs can now create "Practice Resources" through the PHN Admin dashboard, these are urls or web addresses that practices may find useful.

These resources can be made exclusive to specific practices.

Practices can access through the GP Hub.

### 3.12 - 18/06/2020

Added

- **Ability to print receipt of accepted license agreement.**
- **Ability to upload priority area data from csv template file.**

Changed

- **PHN's front page can now list more than 10 regions.**
- **Accepted license export list now includes accepted date and duration of license.**

### 3.11 - 14/05/2020

Added

- **Ability to search list of accepted license agreements by practice.**
- **Ability to export list of accepted license agreements.**
- **Ability to remove unpublished license versions.**
- **Ability to revoke existing license agreements if required by PHN Admins.**
- **Ability to print licenses from admin panel.**

Fixed

- **Fixed some buttons still being clickable while they were still processing**
- **The table under the PIP QI Report was listing all practices, now only list practices related to PIP QI.**
- **Added cleansing process to data coming from PATCAT like email addresses coming with spaces in them.**
- **PHN Admin attempts to load Practice Datasource and Reports even if no database details have yet been given.**
- **Priority areas maps not working.**

### 3.10 - 30/04/2020

Added 

- **Ability to mark Priority Area Measures as not being able to average into a PHN total.**
- **Ability to review all Practice Member accounts on the PHN Admin page.**

Fixed

- **Priority area related bugs.**

### 3.9 - 22/04/2020

Added

- **LGA name tooltip when hovering over LGAs with mouse on any PHN's home page.**

Changed

- **Non PIP Compliant practices list only counts practices that have supplied a PIP ID.**

Fixed

- **PIP QI Report PHN Name not being generated correctly.**
- **Error on PHN home page related to LGA's.**
- **Last 4 reports on GP Data Report not showing.**
- **Printing not presenting correctly for GP Data Report.**

### 3.8 - 14/04/2020

Added

- **Capacity for PHN's to select their connected LGA's within the PHN Admin portal.**

Changed

- **Redirected Help Centre link to new help centre address.**

Fixed

- **Internet Explorer bug that caused practice profile to redirect forever.**
- **Slight change to PIP QI calculation.**

### 3.7 - 12/03/2020

Fixed

- **PIP QI Report generation.**

### 3.6 - 21/02/2020

Upgraded

- **ABS Atlas now has increased performance and functionality.**

Fixed

- **Fixed Priority Areas showing incorrect population numbers on some older browsers.**
- **Several fixes to user interface and browser compatibility.**
  
### 3.5 - 13/02/2020

Added

- **Added footer to GP Data report with usefull controls.**
- **Added ability to print sections of GP Data Report.**
- **Added 1 minute explanation video per section of the GP Data Report.**

Fixed

- **Fixed spelling in proportion of active patients with IMI Record to IHI Record.**
- **Fixed latest data submission in practice summary showing incorrect months and data.**
- **Fixed error related to duplicate practice member and not being able to login.**
- **Fixed front page not displaying properly on some devices.**

### 3.4 - 28/01/2020

Upgraded

- **Backend software - php 7.3 to php 7.4**

### 3.3 - 16/01/2020

Fixed

- **Added some Missing fields to immunisation graphs like 'Not Recorded'**
- **Added missing bipolar record on Mental Health graphs**
- **Typos in health conditions**
- **Wording on some graphs from 'completed' to 'recorded by practice'**
- **Error with exclusive licenses**
- **Fixed some pages not automatically getting new updates**

### 3.2 - 14/01/2020

Upgraded

- **Emails now sent more quickly**  
  Email system upgraded to send emails in realtime

Fixed

- **Priority Area Export incorrectly listing LGA names**
- **PIP QI Registration Date not being loaded for PIP QI Report**
- **Incorrect Naming of PHN Member Role**
- **Visual Bug related to perpetual license agreements**
- **Colour of buttons in priority areas for saving/updating content**

Known Issues

- **Some pages not updating with new fixeds**  
  Need to press left control + F5 to hard refresh pages, fixed in next version.

### 3.1 - 9/01/2020

Added

- **Ongoing license agreement types**

<p>
    The ability to have ongoing or perpetual practice license agreements between PHNs and General Practices.
</p>

- **UI Upgrade to tables**

<p>
    Added refresh button and total items count to table lists.
</p>

Fixed

- **CSV PIP QI report to DOH handle PHN names with spaces**
- **CSV PIP QI report to DOH fixed incorrect name mentioning hour instead of day**

### 3.0 - 12/12/2019

- **Home**
<p>
    Resources on the hompage for each PHN now link to the Australian Institute of Health and Welfare dashboard.
</p>

- **GP Hub**
<p>
    A centralized dashboard of all the features a practice will need to access.
</p>

- **Priority Area**
<p>
    In priority areas, the names of local government areas's now link to an ABS Statistics website.
</p>

- **Practice specific licenses**
<p>
    Licenses created by PHNs can now be assigned to only be seen and accepted by specific practices.
</p>

- **GP Data Report**
<p>
    Option for practices to sign required license agreements to access GP Data Report.
    Licenses created by PHNs can be toggled to block the GP Data Report until they have been accepted.
    Time series graphs display as percentages, solid colour represents the PHN percentage while the line represents the Practice percentage.
    Graphs have been reordered showing time series graphs at the top of the GP Data Report while instant time graphs have moved to the bottom.
</p>
    
- **Option for practices to sign required license agreements to access GP Data Report**
<p>
    Licenses created by PHNs can be toggled to block the GP Data Report until they have been accepted.
</p>

- **Practice required to review their details every 3 months**
<p>
    Practices that login and view the GP Hub are now redirected automatically to update their practice details if the practice has not reviewed them within 3 months.
</p>

- **Interface cleanup and organization**
<p>
    Previously users had to click the row on lists to open them, on all tables there will now be an "Edit" or "Continue" button on the far right of each row.
    This change facilitates accessibility requirements and allows for copying of information from rows without being interrupted.
</p>

- **Help Center**
<p>
    The Help Center is a website repository of information about the PHN Exchange and PHN in a Box.
    The Help Center is available through the navigation bar on PHN Exchange.
</p>

- **Security Upgrades**
<p>
    Several internal upgrades to the backend of PHN Exchange to support security.
</p>
