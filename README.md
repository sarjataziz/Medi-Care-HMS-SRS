# Software Requirements Specification (SRS) - Medi-Care HMS
1. [Introduction](#1-introduction)
   - [1.1 Purpose](#11-purpose)
   - [1.2 Definition, Acronyms, and Abbreviations](#12-definition-acronyms-and-abbreviations)
   - [1.3 Overview of the System](#13-overview-of-the-system)
   - [1.4 Business Context](#14-business-context)

2. [The Overall Description](#2-the-overall-description)
   - [2.1 Product Perspective](#21-product-perspective)
   - [2.2 Product Functions](#22-product-functions)
   - [2.3 User Characteristic](#23-user-characteristic)
   - [2.4 Use Case Diagram](#24-use-case-diagram)

3. [Justification: Benefits of the System](#3-justification-benefits-of-the-system)
4. [Stakeholder Analysis](#4-stakeholder-analysis)
5. [Product Vision and Scope](#5-product-vision-and-scope)
6. [Diagrams for the system](#6-diagrams-for-the-system)
7. [Components/Modules of the System](#7-componentsmodules-of-the-system)
8. [Functional Requirements](#8-functional-requirements)
9. [Non-Functional Requirements for the System](#9-non-functional-requirements-for-the-system)
10. [System Requirements](#10-system-requirements)
11. [Manpower Requirement for Implementation](#11-manpower-requirement-for-implementation)
12. [Budget](#12-budget)
13. [Constraints of this Document](#13-constraints-of-this-document)
14. [Conclusion](#14-conclusion)

## 1. Introduction

### 1.1 Purpose

The SRS outlines the functionality of the Medi-Care Hospital Management System (HMS), aiming to revolutionize healthcare service accessibility. It connects patients with suitable doctors, services, and resources, supporting the continuity of treatment and informed decisions.

### 1.2 Definition, Acronyms, and Abbreviations

- **SRS (Software Requirements Specification):**

  - _Definition:_ Comprehensive document outlining software requirements.
  - _Purpose:_ Ensures shared understanding among stakeholders.

- **HMS (Hospital Management System):**

  - _Definition:_ Web-based platform streamlining healthcare processes.
  - _Purpose:_ Improves service delivery, optimizes resource utilization.

- **Medi-Care:**

  - _Definition:_ Trademarked name for the HMS platform.
  - _Purpose:_ Represents brand identity.

- **EMR (Electronic Medical Records):**

  - _Definition:_ Digital patient records.
  - _Purpose:_ Facilitates efficient record-keeping.

- **CPOE (Computerized Physician Order Entry):**

  - _Definition:_ System for electronic entry of medical orders.
  - _Purpose:_ Improves accuracy and efficiency.

- **HL7 (Health Level Seven):**
  - _Definition:_ Standards for electronic health information exchange.
  - _Purpose:_ Ensures interoperability and data exchange.

### 1.3 Overview of the System

The Medi-Care HMS is a web-based platform designed to enhance the interconnected experience among patients, medical professionals, and health services. It streamlines healthcare interactions, offers a seamless booking experience, and provides clear cost breakdowns for medical expenses. The platform ensures swift emergency response and establishes international connectivity with extensive disease databases.
<img src="https://github.com/sarjataziz/Medi-Care-HMS-SRS/blob/e3ae7cd019db7e716c9ffa5b0222170c41980802/img/Medi-Care.png" alt="Medi-Care">

### 1.4 Business Context

**Medi-Care HMS** tackles healthcare challenges:

### Challenges

- **Info Asymmetry**
- **Inefficiency**
- **Lack of Accessibility**

### Solutions

- **Empower Patients:** User-friendly portal.
- **Bridge Communication Gaps:** Seamless care coordination.
- **Unify Healthcare:** Integration for intelligent recommendations.
- **Promote Transparency:** Upfront cost estimates.
- **Support Personalization:** Patient control.

### Expected Benefits

- **Improved Patient Experience**
- **Enhanced Healthcare Quality**
- **Efficiency and Cost-Effectiveness**
- **Robust Healthcare Infrastructure**

### Target Audience

- **Patients**
- **Healthcare Professionals**
- **Administrators**
- **Emergency Responders**
- **Medi-Care Staff**

## 2. The Overall Description

### 2.1 Product Perspective

**Medi-Care HMS:**

- **Scope:** Backend database, online/mobile platforms, healthcare interfaces.
- **Interfaces:** User-friendly interfaces for personnel, administrators, physicians, and patients.
- **Features:** Clinical recording, billing, analytics, appointment scheduling, and interoperability.
- **Architecture:** Modular, on-premise/cloud delivery, scalability, and compliance with healthcare standards.

**Integration:**

- **Digital Hub:** Cloud-based, integrating clinical and administrative systems.
- **User Experience:** Responsive web, mobile apps, patient portal.
- **Design:** Intuitive dashboards, workflows, AI-assisted decision-making.
- **Interoperability:** Third-party systems, wearables, databases, payment systems.

**Expansion:**

- **Release Focus:** Hospitals, clinic chains, scalable to national-level public health systems.
- **Access:** Cloud-native for ubiquitous access, ensuring continuity of care.

### 2.2 Product Functions

Medi-Care HMS Functions:

**Patient-Facing:**

- **Smart Selection:** Input location, symptoms, present healthcare options.
- **Rating and Info:** Display hospital ratings, doctor lists, appointment details.
- **Booking:** Showcase cabins, appointment times, tests, and prices.
- **Online Appointment:** Enable online appointments and partial payments.

**Hospital/Diagnostic Staff:**

- **Patient Management:** View and manage appointments, medical records, and billing.
- **Communication:** Send secure messages, provide online consultations.
- **Scheduling:** Manage appointment schedules, optimize resource allocation.

**Administrative:**

- **User Management:** Admin functions to manage accounts and settings.
- **Configuration:** Manage system settings, preferences, and security measures.
- **Analysis and Reporting:** Generate reports on demographics, appointments, billing, and KPIs.

### 2.3 User Characteristic

**Roles:**

1. **Admin:**

   - Manage software settings, prices, fees, and user accounts.

2. **Patients:**

   - Browse categories, update profiles, choose healthcare options, and leave comments/reviews.

3. **Hospital/Diagnostic Staff:**
   - Manage patient appointments, reply to comments, provide information, and communicate with administration.

## 3. Justification: Benefits of the System

Implementing Medi-Care HMS brings several benefits:

1. **Enhanced Accessibility:**

   - Connects patients with suitable providers.
   - Overcomes geographical barriers.

2. **Cost Reduction:**

   - Streamlines processes, reducing treatment costs.
   - Empowers informed decision-making.

3. **Efficient Appointments:**

   - User-friendly booking.
   - Minimizes waiting times.

4. **Comprehensive Information:**

   - Centralized healthcare data.
   - Empowers users in decision-making.

5. **Improved Patient Experience:**

   - Customized healthcare solutions.
   - Emphasizes ease of access.

6. **Optimized Resource Allocation:**

   - Efficient appointment and resource management.
   - Reduces administrative burdens.

7. **Data-Driven Decisions:**

   - Analyzes healthcare trends.
   - Enables smart decision-making.

8. **Technology-Driven Management:**

   - Streamlines healthcare processes.
   - Adapts to industry advancements.

9. **Community Health Improvement:**

   - Addresses healthcare gaps.
   - Promotes preventive healthcare.

10. **Scalable System:**
    - Adapts to evolving needs.
    - Ensures long-term viability.

## 4. Stakeholder Analysis

**Primary Stakeholders:**

1. **Patients:**

   - Needs: Book appointments, view records, manage bills.
   - Expectations: User-friendly platform.

2. **Healthcare Providers:**

   - Needs: Quick access, efficient workflows, quality care.
   - Expectations: Streamlined tools.

3. **Insurance Companies:**
   - Needs: Integrated claims processing.
   - Expectations: Access to visit and medical records.

**Secondary Stakeholders:**

1. **Government Agencies:**

   - Interest: Improved healthcare data.
   - Expectations: Enhanced data capabilities.

2. **Technology Companies:**
   - Interest: Providing support.
   - Expectations: Seamless operation.

## 5. Product Vision and Scope

**Vision:**
Revolutionize healthcare delivery through a comprehensive platform, empowering patients and enhancing healthcare efficiency.

**Scope - What the System Will Do:**

1. **Patient-Facing Features:**

   - Book appointments, manage records, communicate.
   - Facilitate emergency response.

2. **Provider-Facing Features:**

   - Assist in appointment and resource management.
   - Streamline workflows.

3. **Administrative Features:**

   - Manage accounts, settings, data analysis.
   - Track key performance indicators.

4. **Unify Healthcare Services:**

   - Integrate providers across facilities.
   - Facilitate care coordination.

5. **Leverage Data and Intelligence:**

   - Provide intelligent recommendations.
   - Support data-driven decisions.

6. **Facilitate Research and Collaboration:**
   - Securely share patient data.
   - Contribute to global health advancements.

**What the System Will Not Do:**

- Provide direct medical diagnosis or treatment.
- Replace the role of healthcare professionals.
- Conduct physical exams or administer medicine.

**Key Benefits:**

- Enhanced patient experience.
- Improved healthcare quality.
- Increased efficiency for providers.
- Reduced healthcare costs.
- Increased accessibility in underserved areas.
- Enhanced collaboration and global contributions.

This concise vision and scope capture the essence of Medi-Care HMS, emphasizing its holistic approach to healthcare improvement.

## 6. Diagrams for the system

In Software Requirements Specification (SRS) includes the following diagrams:

- Class Diagram

- Sequence Diagram

- State Diagram

- Activity Diagram

These diagrams provide a comprehensive visual representation of the system's architecture, interactions, states, and activities.

## 7. Components/Modules of the System

1. **User Management (UM):**

   - Manages user registration, login, and profile information.

2. **Search and Recommendation (SR):**

   - Enables users to search for healthcare providers and receive recommendations.

3. **Information Management (IM):**

   - Allows admin to manage information about hospitals, doctors, and diagnostic centers.

4. **Health Condition/Symptoms (HC):**

   - Deals with user input regarding their health condition or symptoms.

5. **Hospital Selection (HS):**

   - Involves selecting hospitals based on various criteria.

6. **Doctor Selection (DS):**

   - Involves selecting doctors based on various criteria.

7. **Tests Selection (TS):**

   - Involves selecting tests based on health conditions or specific test names.

8. **Selecting Living Area (SLA):**

   - Allows users to refine their search for healthcare providers based on location.

9. **Select Test Center (STC):**

   - Allows users to choose dedicated test centers for their selected test.

10. **Doctor Selecting (DS):**

    - Allows users to search and select doctors based on various criteria.

11. **Show Reviews and Price (RP):**

    - Displays user reviews and price information for chosen hospitals or diagnostic centers.

12. **Show Filtered Hospitals and Diagnostic Center (FHD):**

    - Displays a list of hospitals or diagnostic centers filtered by health condition or selected test name and location.

13. **Show Provider Details (PD):**

    - Displays additional information about chosen healthcare providers.

14. **Recommend Providers (RC):**

    - Based on the user's needs and preferences, shows the most suitable healthcare provider for them.

15. **Show Appointment Times (AT):**

    - Displays available appointment slots for chosen doctors or tests.

16. **Booking Appointment/Cabin (AB):**

    - Allows users to book appointments and cabins online.

17. **Provide Booking Details (BD):**

    - Provides users with a summary of their chosen healthcare provider, appointment details, and any additional booking information.

18. **IT Staff Management (ISM):**

    - IT staff can manage patient information and help IT.

19. **Data Backup and Recovery (DBR):**
    - Ensures regular data backups and recovery processes.

## 8. Functional Requirements

#### Module-1: User Management

| Req ID | Date       | Requirement Description                             | Dependencies | Originator | Testing Criteria                                    |
| ------ | ---------- | --------------------------------------------------- | ------------ | ---------- | --------------------------------------------------- |
| UM1    | 01/12/2023 | Users can login using valid information.            | None         | User       | Successful registration redirects to user profile.  |
| UM2    | 01/12/2023 | Users can log in using valid credentials.           | UM1          | User       | Successful login redirects to the dashboard.        |
| UM3    | 01/12/2023 | Users cannot login with incomplete or invalid info. | UM2          | User       | Error message displayed for invalid login attempts. |
| UM4    | 01/12/2023 | Users can create and update their profiles.         | UM2          | User       | Profile updates reflect in the user's dashboard.    |

### Continue...

#### Module-19: Data Backup and Recovery

| Req ID | Date       | Requirement Description                     | Dependencies | Originator | Testing Criteria                                                        |
| ------ | ---------- | ------------------------------------------- | ------------ | ---------- | ----------------------------------------------------------------------- |
| DBR1   | 15/12/2023 | The system regularly performs data backups. | None         | System     | Data can be successfully restored after a simulated data loss scenario. |

## 9. Non-Functional Requirements

a) **Performance:**

- Respond within 1.0 seconds.
- Swift user interactions.

b) **Scalability:**

- Handle growth seamlessly.
- Simultaneously support 1000 users.

c) **Reliability:**

- Minimal downtime for accessibility.

d) **Security:**

- Encrypt user data.
- Restrict changes to authorized personnel.

e) **Usability:**

- Adhere to accessibility standards.
- User training under 30 minutes.

f) **Tech Requirements:**

- Accessible via major browsers.
- Responsive for all devices.

g) **Integration:**

- Integrate with secure payment gateways.

h) **Data:**

- Secure storage and backups.

i) **Interoperability:**

- Integrate with external databases.

j) **Availability:**

- Users access weekly.

k) **Maintainability:**

- Resolve problems within hours.

l) **Serviceability:**

- Prompt support for user requests.

## 10. System Requirements

### 10.1 Tech Requirements

- React, Angular, HTML, CSS, JavaScript.
- Secure APIs for payment and databases.
- MongoDB.

### 10.2 Infrastructure

- Reliable hosting with sufficient bandwidth.
- Regular server maintenance.

### 10.3 Software

- Latest Chrome, Firefox, Safari.

### 10.4 Security

- Robust data encryption.
- Regular security audits.
- Regulatory compliance.

### 10.5 User Interface

- User-friendly with accessibility.

### 10.6 Version Compatibility

- Chrome, Firefox, Safari: Latest versions.

## 11. Manpower Requirement

a) **Development Team:**

- Project Manager: 1.
- Software Developers (Frontend: 2, Backend: 2).
- UI/UX Designer: 1.

b) **IT Staff:**

- Database Administrator: 1.
- System Administrator: 1.

c) **Admin Staff:**

- Administrator: 1.

d) **Medical Experts:**

- Medical Professionals: 2.

**Total Manpower Needed: 11.**

## 12. Budget

### Effort Estimation using COCOMO

We are using COCOMO for software development effort estimation:

Effort (PM) = 3.0 x (SLOC / 1000) ^ P

- Coefficient (C) = 3.0
- SLOC = 600,000
- P = 1.12

Calculating Effort:
Effort (PM) = 2,316.195 person-months

Development Time (DM):
Development Time (DM) = 2.50 x Effort ^ T
= 34.725 months

### Budget Estimation

#### Development Costs:

- Total Development Costs: 1,320,000 BDT

#### Infrastructure Costs:

- Total Infrastructure Costs: 250,000 BDT

#### Maintenance & Server Costs:

- Total Maintenance & Server Costs: 550,000 BDT

#### Marketing Costs:

- Total Marketing Costs: 925,000 BDT

#### Other Costs:

- Total Other Costs: 290,000 BDT

#### Grand Total Budget (in BDT):

- Grand Total Budget: 3,335,000 BDT

#### Profit Margin (10% of Total Budget):

- Profit Margin: 333,500 BDT

#### Total Budget (including profit):

- Total Budget (including profit): 3,668,500 BDT

## 13. Constraints of this Document

### General Constraints

- Evolution of Healthcare Standards
- Technological Advancements
- Budgetary Limitations
- Data Privacy and Security Regulations
- User Adoption
- Interoperability Challenges
- External Dependencies
- Global Health Landscape

### Scope Flexibility

- Additional Features
- Scope Adjustments

### Resource Constraints

- Resource Availability

### Technology Adoption Constraints

- User Adoption

### Data Security Constraints

- Data Privacy and Security

### Adaptability Constraints

- Evolving Healthcare Landscape

## 14. Conclusion

The Software Requirements Specification (SRS) for the Medi-Care Hospital Management System (HMS) outlines constraints and considerations. The development team aims to navigate challenges effectively for successful delivery and sustained effectiveness.

### Next Steps

Collaborative efforts in the design phase, followed by development, testing, and implementation, are essential. Stakeholder engagement is crucial for successful delivery.

### Call to Action

Active participation from all stakeholders is encouraged to shape a healthcare solution that evolves to meet future challenges.

# Team Members

- [Sarjat Aziz Rumi](https://github.com/sarjataziz)

- [Afsan Sany](https://github.com/Amp47)
----

[Back to Top](#table-of-contents)
