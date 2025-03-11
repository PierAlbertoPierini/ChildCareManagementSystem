# Child Care Management System

> [!WARNING] Local Use Only
> 
> This repository contains scripts for installing the application in a Docker container. These scripts are intended for **local development and testing purposes only**. They have not been secured or optimized for production environments.
> 
> - Do not use these scripts in a production environment without proper security auditing and hardening.
> - Ensure all sensitive information, such as passwords and API keys, are removed or properly secured before deploying online.
> - Review and modify the scripts to follow security best practices before using them in any public or production setting.
> 
> Users are responsible for implementing appropriate security measures before deploying this application online or in a production environment.

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

![ccms - Child Care Management System - logo](ccms-logo.svg)

## ccms Version
|          | **Seatable** | **Reis3** | **Directus** | **NocoDB** |  **NocoBase**  |  **Saltcorn**  |  **Teable**  |  **UnDB**  | **Grist** |
| -------- |    :---:     |   :---:   |     :---:    |    :---:   |      :---:     |      :---:     |     :---:    |    :---:   |   :---:   |
| Version  |     0.2      |           |              |     0.1    |                |                |              |            |    0.1    |

### News

Added NEWS.md file where I will report some news on the project.


# Child Care Management System

The Child Care Management System or short "CCMS" is an open-source project aimed at providing a comprehensive and efficient solution for managing child care centers, daycares, and similar childcare facilities. This system is built on top of no-code or low-code applications, leveraging their simplicity and flexibility to enable easy customization and seamless integration.

## Features

Child Management: Effortlessly manage child records, including personal details, emergency contacts, medical information, and attendance records.
Staff Management: Keep track of staff members, their roles, schedules, certifications, and important documents.
Billing and Payments: Simplify the billing process, generate invoices, track payments, and manage financial transactions.
Enrollment and Waitlist: Streamline the enrollment process, maintain waitlists, and manage availability.
Attendance Tracking: Track attendance for children and staff, generate reports, and monitor attendance patterns.
Communication: Enable seamless communication between parents, staff, and administrators through notifications, messages, and announcements.
Reporting and Analytics: Generate insightful reports and analytics to gain valuable insights into the operations of the child care center.
Integration: Easily integrate with other systems or platforms for data synchronization and enhanced functionality.


| APPS Features          | **Seatable** | **Reis3** | **Directus** | **NocoDB** | **NocoBase** | **Saltcorn** | **Teable** | **UnDB** | **Grist** |
| ---                    |     :---:    |    :---:  |    :---:     |    :---:   |     :---:    |     :---:    |   :---:    |   :---:  |   :---:   |
| Sign up                |              |           |              |            |      Yes     |      Yes     |            |          |           |
| Forms                  |     Yes      |    Yes    |     Yes      |    Yes     |      Yes     |      Yes     |            |          |    Yes    |
| Calendar               |     Yes      |    Yes    |     Yes      |    Yes     |      Yes     |      Yes     |            |          |    Yes    |
| Roles                  |    simple    |  complex  |    complex   |   simple   |    complex   |    complex   |   simple   |  simple  |           | 
| Electonic signature    |     Yes      |           |              |            |              |              |            |          |           |
| E2EE                   |              |           |              |            |              |              |            |          |           |
| Print                  |              |           |              |            |              |              |            |          |           |
| Export/import Templates|     Yes      |    Yes    |              |            |              |      Yes     |            |          |    Yes    |
|                        |              |           |              |            |              |              |            |          |           |
|                        |              |           |              |            |              |              |            |          |           |
| Data Integrity         |   built-in   |           |   built-in   |            |              |              |            |          |           |

<details>
<summary>Technology Description</summary>
The Child Care Management System is built on top of several no-code and low-code applications, providing a powerful and flexible foundation for development. These technologies were carefully selected to ensure the project's ease of use, scalability, and maintainability, empowering people of all skill levels to contribute and extend the functionality of the Child Care Management System.
</details>

<details>
<summary>Use case note</summary>
Please note that the use case and available features of the Child Care Management System (CCMS) can vary depending on the chosen no-code application. For instance, when deploying CCMS with Seatable, the system may leverage forms for data entry and management, providing a streamlined experience. However, Seatable may not support user logins for parents. On the other hand, deploying CCMS with NoCodeBase offers more robust user role management and customizable page features, allowing for tailored user experiences and versatile access controls. The selection of a specific no-code application will influence the functionality and capabilities of CCMS, enabling child care centers to choose the platform that best aligns with their unique requirements.
</details>

<details>
<summary>Installation and Usage</summary>
Clone the repository: git clone https://github.com/PierAlbertoPierini/ChildCareManagementSystem.git
Navigate to the project directory: cd child-care-management-system
Follow the installation instructions for each of the underlying technologies in their respective documentation.
Customize the system to fit your child care center's specific requirements by configuring the database schemas, workflows, and UI components.
Run the application and start managing your child care center efficiently.
</details>
<details>
<summary>Contributing</summary>

Contributions are welcome! If you would like to contribute to the Child Care Management System, there are several ways you can get involved:

## Code Contributions

Since these no-code systems are not designed with coding contributions in mind, we welcome ideas and suggestions for integration with the project.

## Financial Support

If you find the Child Care Management System valuable and would like to support its development, you can contribute by donating through platforms like Ko-fi or Buy Me a Coffee. Your generous contributions will help me cover hosting expenses, implement new features, and improve the project's overall quality.

- Support us on [Ko-fi] <a href='https://ko-fi.com/pieralberto' target='_blank'><img height='35' style='border:0px;height:46px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' />
- Buy us a coffee on [Buy Me a Coffee] <a href="https://www.buymeacoffee.com/pieralberto" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

## Share Your Ideas

We believe in the power of collaboration and community input. If you have any innovative ideas, suggestions, or feature requests, we would love to hear them! Please create an issue in the GitHub repository with a detailed description of your idea. We appreciate your input and will review it as soon as possible.
</details>

## License
The Child Care Management System is released under the MIT License.

## Acknowledgments
We would like to express our gratitude to the developers and contributors of SeaTable, Rei3, NocoDB, NocoBase, and other open-source projects that have made this system possible.

<details>
<summary>Project Timeline</summary>

Please note that this timeline is subject to change as the project progresses. 

### Database Design and Calendar Activities
- [x] Basic database design for children registration
- [x] Implement calendar activities functionality
- [x] Implementig ccms in SEATABLE
- [ ] Implementig ccms in Grist
- [ ] Implementig ccms in Rei3

### Staff Management and Billing
- [ ] Develop staff management features (roles, schedules, certifications)
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

Support us on [Ko-fi] <a href='https://ko-fi.com/pieralberto' target='_blank'><img height='35' style='border:0px;height:46px;' src='https://az743702.vo.msecnd.net/cdn/kofi3.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' />


Buy me a coffee on [Buy Me a Coffee] <a href="https://www.buymeacoffee.com/pieralberto" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

## Customization and Installation Services

If you require customization of the Child Care Management System to suit your specific needs or need assistance with installation and configuration, we provide paid services to help you. Please reach out to us at `pier_alberto@pierini.com` for further details and pricing information. I'm dedicated to providing tailored solutions and ensuring a smooth experience for your child care center.