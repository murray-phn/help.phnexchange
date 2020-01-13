# PHN Admin Introduction

**PHN Admin** is a control panel for managing your PHN within the PHN Exchange.

Once you have signed into the PHN Exchange with a valid account, the **PHN Admin** button will appear on the left navigation menu.

## **PHN Details**

Top level details for your PHN like contact phone number, email address and website.

PHN Description will show a large description and or message on the front page of your PHN.

## **Reports**

The Reports section of the **PHN Admin** dashboard contains aggregated global reports for PHNs. 

### **PIP QI Report**

Information for the **PIP QI Report** comes from each practices **Practice Profile** and also from their extracted data submissions.

It is crucial that this information is correct, Partner PHNs may need to work with their General practices ensure that their **Practice Profile** information is correct.

**Features:**

- Displays a list of practices which are compliant or non-compliant for selected quarters.
- An exportable CSV file which can be given to Department of Health as a PIP QI submission.
- An exportable CSV file containing a list of PIP QI compliant practices.
- An exportable CSV file containing a list of Non PIP compliant practices and listings of reasons why.

## **Practice Datasource**

This is where you enter your PATCAT database details with a read only database user to connect the PHN Exchange to your PATCAT database.

Please note that in most cases the **driver** text field in most cases will be: `sqlsrv`

## **Practices**

A list of all practices within the PHN.

To allow a user access to view practice data they must be added as a **Practice Member**.

### **Practice Members**

**Practice Members** are PHN Exchange **Members** that have permission to General Practice features and data through a dashboard named the **GP Hub**.

**PHN Admins** can gives practice staff access to the **GP Hub** through either an automatic or manual process.

### How to add a **Practice Member**

- Login to the PHN Exchange.
- Click Admin on the left menu and navigate to your PHN.
- Open the Practices section and find the relevant practice.
- Scroll to the bottom of the practice page and find the Practice Members section.
- Click "Create" and a popup will appear, supply an email address of a registered account on the PHN Exchange and toggle the flag "Is Practice Manager" to YES and click the CREATE button.

### Using PATCAT to automatically setup Practice account permissions

If the email address in PATCAT against a practice is the same email address that they have registered with, they are automatically assigned as a practice member.

To confirm if a practice has the correct email address assigned in PATCAT:

- Login to your PHN PATCAT portal, for Murray PHN it is [https://patcat.murrayphn.org.au/](https://patcat.murrayphn.org.au/)
- In the top right of the page after login click `Practices`.
- Select a practice and confirm the associated email address is correct.
- After updating the email address in PATCAT PHN Exchange should take 1 minute to reflect the new changes.
- After PHN Exchange has detected the email change, the practice member using the email address needs to sign out and sign in again to now see the **GP Hub** button.

## **Priority Areas**

### How to create a **Priority Area**

  1. <a href="../../user-guide/members/#sign-in-to-the-phn-exchange" target="_blank">Sign In</a> to your PHN Admin account.
  2. Click **PHN Admin** on the left navigation menu.
  3. Select your PHN by clicking `CONTINUE`.
  4. On the **PHN Admin** page, scoll down to the section named **Priority Areas** and expand the section by clicking on it.  
  ![Button GP Hub](../../images/btn-card-priority-areas.png)  
  5. In the bottom right of the **Priority Areas** section, click the `CREATE` button.
  6. In the **Create Priority Area** popup window, enter a priority area name and click `CREATE`
  7. Success! you have finished **How to create a Priority Area**

## **Regions**

Groups of LGA's within a PHN.

## **Licenses**

Electronic license agreements between a PHN and it's practices.

## **PHN Members**

**PHN Members** are members who have access to view or edit PHN data.

There are two **PHN Member** roles:

- Admin  
    Have full access to change any details about a PHN.
- PracticeCoordinator  
    Only have access to view all of the practices for a PHN.