# Changelog

All notable changes to the PHN Exchange will be documented in this file.

Partner PHNs are invited to review and test new versions prior to release and publishing on the live site.

Each partner PHN will:

- Be notified when a new major version is available for testing
- Be provided access to the test site
- Have 5 working days to complete their testing and provide feedback
- Be able to send feedback via [support@phnexchange.com.au](mailto:support@phnexchange.com.au)

After the test period has ended, the new version will usually be released and published on the live site within two working days.


### 3.16 - 29/09/2020

Fixed

- **Mapping functionality**

Resolved issue with maps being used in PHN Exchange not loading correctly.

- **Priority area import**

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
