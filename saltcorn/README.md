# Saltcorn Directory

Visit: https://saltcorn.com/
GitHub: https://github.com/saltcorn/saltcorn
Docs: https://wiki.saltcorn.com
Docker Hub: https://hub.docker.com/r/saltcorn/saltcorn

> [!WARNING] Local Use Only
> 
> This repository contains scripts for installing the application in a Docker container. These scripts are intended for **local development and testing purposes only**. They have not been secured or optimized for production environments.
> 
> - Do not use these scripts in a production environment without proper security auditing and hardening.
> - Ensure all sensitive information, such as passwords and API keys, are removed or properly secured before deploying online.
> - Review and modify the scripts to follow security best practices before using them in any public or production setting.
> 
> Users are responsible for implementing appropriate security measures before deploying this application online or in a production environment.

## Saltcorn Directory

This directory contains the necessary files and configurations for deploying the Child Care Management System (CCMS) using Saltcorn, a powerful open-source no-code application builder. With Saltcorn, you can easily create and customize web applications without writing code.

## About Saltcorn

Saltcorn provides a flexible and user-friendly platform for building database-driven web applications. It offers a range of features, including form builders, workflow automation, and role-based access control, allowing you to create robust and secure applications.

## Getting Started

To get started with CCMS using Saltcorn, follow these steps:

Install Saltcorn by referring to the Saltcorn documentation.
Import the backup-ccms.zip file from Settings/Backup.
Delete the sample data and users, change Admin email and password.

Defaults:
- Admin:    ccms@example.com    Password: 8a55w0rd
- User:     user@example.com    Password: 8a55w0rd
- User2:    user2@example.com   Passowrd: 8a55w0rd
- Staff:    staff@example.com   Passowrd: 8a55w0rd

Now, you can start to use CCMS application.

## Compatibility

CCMS on Saltcorn is compatible with the latest version of the Saltcorn platform. Please ensure that you have a compatible version installed to avoid any compatibility issues.

## Contributing

Contributions to the Saltcorn implementation of CCMS are welcome! If you encounter any issues or have suggestions for improvements, please submit them through the issue tracker or contribute by submitting pull requests.

## License

CCMS on Saltcorn is released under the MIT License.

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