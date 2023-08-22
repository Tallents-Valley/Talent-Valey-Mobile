# Freelancer Fintech App

Welcome to the Freelancer Fintech App repository! This app is designed as a Minimum Viable Product (MVP) to provide freelancers with a streamlined solution to withdraw their earnings from global platforms using local payment methods. The app targets the local market and is accessible on both mobile devices and web browsers.

![Main Image](https://github.com/Tallents-Valley/Talents-Valey-Mobile/assets/28483872/9ac6e07e-9129-44c9-80bc-351f1d854371)

## Table of Contents

- [Overview](#overview)
- [User Roles](#user-roles)
- [Features](#features)
- - [Authentication and Verification](#authentication-and-verification)
- - [Invoice System](#invoice-system)
- - [Withdrawal System](#withdrawal-system)
- - [Notification System](#notification-system)
- - [Contacts Management](#contacts-management)
- - [Personal Information Management](#personal-information-management)
- - [Team Dashboard](#team-dashboard)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Collaboration with Different Teams](#collaboration-with-different-teams)
- [Cross-Platform Development with Flutter & Dart](#cross-platform-development-with-flutter--dart)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Freelancer Fintech App is designed to serve as a MVP solution for freelancers, teams, and clients within the local market. It offers a streamlined way to withdraw earnings using local payment methods while maintaining cross-platform compatibility between mobile devices and web browsers.

## User Roles

1. **Freelancer:**
   - Provides services to clients.
   - Can withdraw funds using local payment methods.
   - Manages personal and contact information.
   - Utilizes the invoicing system for billing clients.
   - Receives notifications for account activities.

2. **Team (Business Owner):**
   - Accesses a team dashboard for managing user roles and activities.
   - Manages freelancers' accounts.
   - Monitors team activities.
   - Receives relevant notifications.

3. **Client:**
   - Benefits from the services provided by freelancers.
   - Interacts with the invoice system for billing and payments.

## Features

Authentication and Verification

- Users can register and log in securely.
- Multi-factor verification using email, mobile number, ID verification, and address verification ensures account security.

Invoice System

- Freelancers can generate and manage invoices for their services.
- Clients can view and process invoices for payments.

Withdrawal System

- Freelancers can initiate fund withdrawals using local payment methods.
- Integration with Stripe payment gateway for seamless transactions.

Notification System

- Integration with OneSignal for sending relevant notifications to users.
- Notifications for account activities, transactions, and updates.

Contacts Management:

- Users can manage their contact information.
- Improved communication between freelancers and clients.

Personal Information Management:

- Users can maintain and update their personal details.
- Ensures accurate and up-to-date user information.

Team Dashboard:

- Team members (business owners) access a comprehensive dashboard.
- User management features for handling freelancer accounts.
- Monitoring and tracking of team activities.


## Technology Stack

- Utilization of MVC architecture for modular development.
- Provider state management for efficient data handling.
- Service locator pattern for managing services.
- Dependency injection pattern for flexible and maintainable code.
- Integration of Stripe payment gateway for secure transactions.
- Dio package for network layer handling.
- Implementation of clean code principles for maintainability.
- Version control using Git and GitHub for collaboration.
- REST APIs for seamless communication between frontend and backend.
- Testing framework for ensuring app reliability.

## Collaboration with Different Teams

The development of the Freelancer Fintech App is a collaborative effort involving various teams:

1. **Product Managers:**
   - Responsible for defining project goals and requirements.
   - Coordinate feature prioritization and roadmap planning.

2. **Designers Team:**
   - Creates visually appealing and user-friendly app designs.
   - Ensures a consistent and intuitive user interface across platforms.

3. **Mobile Developer Teams:**
   - Implements app functionality using Flutter and Dart.
   - Ensures compatibility and responsiveness on both mobile devices and web browsers.

4. **Backend Team:**
   - Develops the Node.js backend for data storage, authentication, and payment gateway integration.
   - Ensures secure and efficient communication between frontend and backend.

5. **Frontend Teams:**
   - Develops the React-based web frontend, maintaining the same user experience as the mobile app.
   - Collaborates with mobile teams to ensure consistency in design and functionality.

## Cross-Platform Development with Flutter & Dart

The Freelancer Fintech App is built using the Flutter framework, leveraging the power of Dart programming language. Flutter enables seamless cross-platform development, allowing us to create a single codebase for both mobile and web applications. This approach ensures consistent user experience and reduces development efforts across multiple platforms.

## Getting Started

To get started with the Freelancer Fintech App, follow these steps:

1. Clone this repository: `git clone https://github.com/your-username/freelancer-fintech-app.git`
2. Install the required dependencies: `flutter pub get`
3. Run the app: `flutter run`


## License

This project is licensed under the [MIT License](LICENSE).
