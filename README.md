<p align="center">
  <img src="assets/banner.png" alt="Arogya-SMC Banner" width="100%">
</p>

<h1 align="center">Arogya-SMC</h1>

<h3 align="center">
Smart Public Health Management System for Municipal Healthcare
</h3>

<p align="center">

![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Android-blue)
![Backend](https://img.shields.io/badge/Backend-Spring%20Boot-success)
![Database](https://img.shields.io/badge/Database-MySQL-orange)
![Frontend](https://img.shields.io/badge/Frontend-Android%20%7C%20React-9cf)
![License](https://img.shields.io/badge/License-Academic-lightgrey)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

</p>

---

# Overview

**Arogya-SMC** is a digital public healthcare platform designed for municipal corporations to streamline disease surveillance, citizen healthcare services, hospital management, and field data collection.

The platform provides a unified ecosystem where **ASHA workers, citizens, hospitals, and municipal authorities** collaborate through dedicated applications connected to a centralized backend.

Instead of relying on paper records and disconnected workflows, Arogya-SMC digitizes healthcare operations by enabling:

- Digital beneficiary registration
- Disease reporting
- Real-time health monitoring
- Hospital management
- Citizen healthcare services
- Municipal analytics
- Data-driven decision making

The project was developed as a complete Smart City healthcare solution with emphasis on scalability, accessibility, and transparency.

---

# Problem Statement

Municipal healthcare systems often face several operational challenges:

- Manual maintenance of health records
- Delayed disease reporting
- Lack of centralized patient information
- Limited communication between hospitals and field workers
- Poor visibility into healthcare analytics
- Difficulty in tracking public health programs

These issues lead to delayed decision-making and inefficient resource allocation.

---

# Solution

Arogya-SMC addresses these challenges by integrating multiple healthcare stakeholders into one digital platform.

The solution consists of:

- ASHA Worker Mobile Application
- Citizen Mobile Application
- Hospital Management Portal
- Municipal Administration Dashboard
- Centralized Backend Services

Together, these components provide a seamless public healthcare ecosystem.

---

# Key Features

## ASHA Worker Module

- Beneficiary Registration
- Family Survey
- Pregnancy Monitoring
- Child Health Records
- Vaccination Tracking
- Disease Reporting
- Offline Data Collection
- Secure Authentication

---

## Citizen Application

- Nearby Hospitals
- Healthcare Announcements
- Government Health Schemes
- Emergency Contacts
- Public Health Notifications
- Healthcare Information

---

## Municipal Dashboard

- Disease Analytics
- Ward-wise Statistics
- Health Program Monitoring
- Resource Allocation
- Citizen Reports
- Administrative Controls

---

## Hospital Portal

- Patient Records
- Hospital Registration
- Resource Management
- Health Data Synchronization
- Medical Reporting

---

# System Architecture

```text
                        +----------------------+
                        | Municipal Dashboard  |
                        +----------+-----------+
                                   |
                                   |
+-------------+          +----------v-----------+
| Citizen App |--------->| Spring Boot Backend  |
+-------------+          +----------+-----------+
                                   |
                                   |
+-------------+          +----------v-----------+
| ASHA Worker |--------->|      MySQL DB        |
|     App     |          +----------+-----------+
+-------------+                     |
                                    |
                          +---------v---------+
                          | Hospital Portal   |
                          +-------------------+
```

---

# Technology Stack

| Category | Technologies |
|----------|--------------|
| Backend | Spring Boot, Java |
| Mobile | Android (Java) |
| Dashboard | React.js |
| Database | MySQL |
| Authentication | JWT |
| API | REST APIs |
| Version Control | Git, GitHub |
| IDE | Android Studio, VS Code, IntelliJ IDEA |

---

# Platform Components

| Module | Description |
|---------|-------------|
| ASHA Worker App | Digital field healthcare management |
| Citizen App | Healthcare services for citizens |
| Hospital Portal | Hospital operations and reporting |
| Municipal Dashboard | Administration and analytics |
| Backend APIs | Centralized business logic and database management |

---

# Project Highlights

- Multi-platform Healthcare Ecosystem
- Role-based Access Control
- RESTful Architecture
- Centralized Database
- Real-time Data Synchronization
- Scalable Modular Design
- Smart City Healthcare Initiative
- Municipal Decision Support System

---

# Repository Architecture

The Arogya-SMC ecosystem is divided into multiple repositories for modular development and maintainability.

```

---

## End of Part 1 ✅

This already looks far more professional than a typical college README.

### **Part 2** will include:

- 📱 Beautiful screenshots (ASHA & Public App)
- 📂 Repository links
- ▶️ YouTube demo
- 🚀 Installation
- 📁 Project structure
- ⚙️ Getting Started

It will make the README feel like a polished open-source project landing page.
