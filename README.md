# Project to Supply Leftover Food to the Poor Using Salesforce

**Submitted by**  
KEMBURU MANEESH  
**Roll Number:** 21131A0593  
**College:** Gayatri Vidya Parishad College of Engineering (A), Visakhapatnam  
**Email:** 21131A0593@gvpce.ac.in  

### Project Demonstration Video
[![Project Video](https://img.youtube.com/vi/sBvETQqh-6E/0.jpg)](https://youtu.be/sBvETQqh-6E?si=__1K343onr5UH6rY)


## 1. Project Overview

This project aims to reduce food waste and alleviate hunger by using Salesforce technology to manage the distribution of surplus food to those in need. The solution connects food donors, such as restaurants and grocery stores, with organizations that assist the needy. Through Salesforce CRM, we enable real-time donation tracking, manage logistics, and ensure timely deliveries, promoting transparency and accountability within the food donation network.

## 2. Objectives

- **Business Goals:** Minimize food waste and fight hunger by linking food suppliers with non-profits and shelters.
- **Specific Outcomes:**
  - Build a network of food donors and recipients.
  - Automate matching of food donations by location, food type, and urgency.
  - Allow field agents to track deliveries and provide real-time status updates.

## 3. Key Salesforce Features and Concepts

- **Objects:** Custom objects for Drop-Off Points, Tasks, Execution Details, Volunteers, and Venues.
- **Tabs:** Created custom tabs for Venues, Execution Details, and Volunteers to enhance data access.
- **Lightning App:** Developed for a user-friendly interface.
- **Fields:** Custom fields to capture detailed information on tasks, volunteer details, and drop-off points.
- **Flows:** Automated workflows for creating records and notifying users.
- **Triggers:** Apex triggers to enforce business logic.
- **Profiles and Users:** Defined roles and access levels to ensure data security.
- **Public Groups:** Simplified sharing and permissions management for user groups.
- **Report Types:** Custom reports to monitor volunteer efficiency and food distribution.
- **Dashboards:** Visual insights into key metrics for improved decision-making.
- **Sharing Rules:** Extended access to records for users in public groups.

## 4. Solution Design Steps

- **Data Model:** Custom objects and relationships to streamline data handling and the donation distribution workflow.
- **User Interface:** Custom tabs and Lightning components for efficient data access, optimized for mobile.
- **Business Logic:** Flows and triggers automate donation alerts, volunteer assignments, and delivery tracking.

## 5. Salesforce Developer Setup

1. **Developer Account Creation:** Created a Salesforce developer organization and activated the account.
2. **Objects and Tabs:** Developed custom objects and tabs for essential elements like Venues, Volunteers, and Drop-Off Points.
3. **Lightning App & Fields:** Custom fields and a Lightning app interface to simplify access and usage.

## 6. Core Concepts Implemented

### Objects in Salesforce

- **Standard Objects:** Default Salesforce objects such as Accounts, Contacts.
- **Custom Objects:** Project-specific objects for data management, such as:
  - Drop-Off Point
  - Task
  - Execution Detail
  - Volunteer
  - Venue

### Tabs, Fields, Flows, and Triggers

- **Tabs:** Custom tabs were created for various objects to facilitate record management and display.
- **Fields:** Fields like Volunteer ID, Contact Email, and Task Name were designed for precise data capture.
- **Flows:** Automate key workflows, such as record creation in Venue objects.
- **Triggers:** Apex triggers enforce business rules and custom logic.

### Additional Configurations

- **Profiles and Users:** Custom profiles define access levels, and users are organized based on roles.
- **Public Groups:** Used to simplify sharing and manage permissions.
- **Report Types & Dashboards:** Created custom report types for monitoring key metrics, with dashboards for visual insights.
- **Sharing Rules:** Applied to grant additional record access securely.

## 7. Testing and Validation

- **Unit Testing:** Ensured Apex classes and triggers performed as expected.
- **User Interface Testing:** Verified a smooth experience on both web and mobile, particularly for field agents updating delivery statuses.

## 8. Key Scenarios Addressed

- **Automated Matching:** Matches food donations by location and urgency.
- **Real-Time Updates:** Allows field agents to update delivery statuses on the go.
- **Reporting:** Tracks donation efficiency, volunteer engagement, and project impact.

## 9. Conclusion

This project provides a structured, transparent system for managing surplus food donations. It streamlines the coordination between donors and recipients, minimizing food waste and helping address hunger in underserved communities. Through the Salesforce platform, we’ve built a robust solution that optimizes resources and amplifies positive social impact.
