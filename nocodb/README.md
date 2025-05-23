# NoCoDB Directory

Website: https://www.nocodb.com/
Github: https://github.com/nocodb/nocodb
Docker Hub: https://hub.docker.com/r/nocodb/nocodb

> [!WARNING] Local Use Only
> 
> This repository contains scripts for installing the application in a Docker container. These scripts are intended for **local development and testing purposes only**. They have not been secured or optimized for production environments.
> 
> - Do not use these scripts in a production environment without proper security auditing and hardening.
> - Ensure all sensitive information, such as passwords and API keys, are removed or properly secured before deploying online.
> - Review and modify the scripts to follow security best practices before using them in any public or production setting.
> 
> Users are responsible for implementing appropriate security measures before deploying this application online or in a production environment.

This directory contains the necessary files and configurations for deploying the Child Care Management System (CCMS) using NoCoDB, an open-source platform that transforms your database into a smart, collaborative, no-code application. With NoCoDB, you can create tailored applications and workflows effortlessly.

## About NoCoDB
NoCoDB is a robust and versatile open-source platform that turns any SQL database (MySQL, PostgreSQL, SQLite, etc.) into an interactive spreadsheet-style interface. It enables users to create, customize, and share applications without writing any code, making it perfect for managing complex datasets and workflows.

## Key features include:
Collaborative grid view for database management.
Intuitive form builder for collecting and updating data.
Advanced relationship mapping for database tables.
Support for workflows, automations, and integrations via APIs and third-party tools.
Learn more at: https://www.nocodb.com

## Getting Started
To set up CCMS using NoCoDB, follow these steps:

## Install NoCoDB:
Deploy NoCoDB using Docker, npm, or other installation methods (detailed in the official documentation).

**Connect Your Database:** Link NoCoDB to your preferred SQL database (MySQL, PostgreSQL, SQLite, etc.).

**Import the CCMS Schema:** Use the provided schema files:

- Activities.csv
- Inscription.csv

set up tables for managing child records functionalities.

```mermaid
erDiagram
    Activities {
        int id PK
        text Title
        attachment Image
        date Date_Event
        text Note
    }
    Inscription {
        int id PK
        text Child_Last_Name
        text Child_First_Name       
        date Child_Birthday
        singleselect Child_Gender
        singleselect Service_Year
        text Child_Address
        text Child_lives_with
        text Parent_Name
        phoneAddress Parent_Work_Phone
        phoneAddress Parent_Home_Phone
        text Parent_Name
        phoneAddress Parent_Work_Phone
        phoneAddress Parents_Home_Phone
        text Emergency_contact
        phoneAddress Emergency_contact_Phone
        text Child_Doctor
        text Child_Doctor_Phone
        text Allergies
        text Medications
        text Care_Card_number
        attachment Picture_of_Child
        text Signature_of_Parent_Guardian
        text Witness
        datetime Signature_Date
    }
```


**Customize Your Application:** Configure relationships between tables, define user permissions, and design forms for data entry.
Use NoCoDB's spreadsheet-like interface and form builder to adapt CCMS to your specific needs.

**Automate Workflows:** Set up workflows to automate repetitive tasks like attendance tracking or generating invoices.

**Launch and Manage:** Once configured, your CCMS is ready to manage your child care center efficiently with NoCoDB.

**Compatibility:** CCMS is compatible with the latest stable versions of NoCoDB and supports various SQL databases. Make sure your environment meets the system requirements for optimal performance.

## Contributing
Contributions to the CCMS for NoCoDB are welcome! If you encounter bugs, have feature suggestions, or want to contribute improvements, please use the issue tracker or submit a pull request on the repository.

## License
The Child Care Management System (CCMS) for NoCoDB is released under the MIT License.

<details>
<summary>Timeline</summary>

Please note that this timeline is subject to change as the project progresses. 

### Database Design and Calendar Activities
- [x] Basic database design for children registration
- [x] Implement calendar activities functionality

### Staff Management and Billing
- [ ] Develop staff management features (roles, schedules, certifications)
    - [ ] Reports
    - [ ] Employee time report
- [ ] Implement billing and payment functionality

### Enrollment and Waitlist
- [ ] Streamline the enrollment process
- [ ] Manage waitlists and availability

### Attendance Tracking and Reporting
- [ ] Track attendance for children and staff
- [ ] Generate reports and analytics

### Communication and Notifications
- [ ] Enable seamless communication between parents, staff, and administrators
- [ ] Implement notification system and announcements

### Integration and Customization
- [ ] Integrate with other systems or platforms for data synchronization
- [ ] Allow customization options for tailored implementations

### Documentation and Testing
- [ ] Create comprehensive documentation for installation and usage
- [ ] Perform thorough testing and bug fixing

</details>