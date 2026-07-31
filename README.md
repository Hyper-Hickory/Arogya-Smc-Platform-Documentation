<p align="center">
    <img src="./Assets/banner.png" alt="Arogya-SMC Banner">
</p>
<h1 align="center">Arogya-SMC</h1>

<p align="center">
Smart Public Health Monitoring & Decision Support System
<br>
for Solapur Municipal Corporation
</p>

<p align="center">

<img src="https://img.shields.io/badge/Competition-SAMVED%202026-blue">

<img src="https://img.shields.io/badge/Category-Smart%20Healthcare-success">

<img src="https://img.shields.io/badge/Status-Prototype-orange">

<img src="https://img.shields.io/badge/License-Academic-lightgrey">

</p>

---

## Contents

- Overview
- Recognition
- Problem Statement
- Solution Overview
- Platform Overview
- System Architecture
- Platform Modules
- Technology Stack
- Repository Structure
- Project Demonstration
- Technical Documentation
- Contributors
- Future Scope
- License

---

# Overview

Arogya-SMC is a smart public healthcare platform designed for **Solapur Municipal Corporation (SMC)** to improve disease surveillance, municipal healthcare operations, and citizen health services through a unified digital ecosystem.

The platform integrates multiple healthcare stakeholders—including ASHA workers, hospitals, citizens, and municipal authorities—into a centralized system for real-time reporting, analytics, and decision support.

Unlike traditional municipal healthcare workflows that depend on fragmented records and delayed reporting, Arogya-SMC provides a modular digital platform capable of supporting field data collection, healthcare monitoring, ward-level analytics, and public health administration. The project addresses the challenge of fragmented health information across ASHA workers, hospitals, and laboratories while enabling centralized monitoring and structured decision support. :contentReference[oaicite:0]{index=0}

---

# Recognition

Arogya-SMC was developed for the **SAMVED 2026 Innovation Challenge**.

The project was selected among the **Top 7 teams** from **546 participating teams across 10 states**, recognizing the team's approach to solving municipal public healthcare challenges through an integrated digital platform.

The official selection document is available in:

```text
assets/
└── Achievements/
    └── achievement.pdf
```

---

# Project Demonstration

The complete prototype demonstration is available on YouTube.

**Demo Video**

https://youtu.be/0s_siwg91rY

---

# Problem Statement

Municipal healthcare systems often operate using disconnected data sources distributed across ASHA workers, hospitals, laboratories, and administrative departments.

This results in:

- fragmented health records
- delayed disease reporting
- manual data consolidation
- limited ward-level visibility
- inefficient resource allocation
- delayed public health response

The absence of a centralized health information platform prevents municipal authorities from identifying emerging disease trends and making timely, evidence-based decisions. :contentReference[oaicite:1]{index=1}

---

# Solution

Arogya-SMC proposes an integrated Smart Public Health Monitoring & Decision Support System that connects field workers, hospitals, citizens, and municipal authorities through a centralized digital platform.

The system focuses on:

- Digital field reporting
- Structured healthcare data collection
- Disease surveillance
- Municipal decision support
- Citizen healthcare services
- Healthcare resource monitoring
- Real-time analytics
- Public health awareness

The proposed platform follows a modular architecture that enables secure data collection, standardization, analytics, and visualization while supporting future expansion toward interoperable municipal healthcare systems. :contentReference[oaicite:2]{index=2}

---

# Platform Overview

The ecosystem consists of five major components working together.

| Component | Purpose |
|-----------|---------|
| ASHA Worker Application | Field data collection and healthcare reporting |
| Citizen Application | Public health services and advisories |
| Hospital Portal | Hospital capacity and disease reporting |
| Municipal Dashboard | Analytics, monitoring and decision support |
| Backend Services | Centralized data processing and API services |
---

# Platform Overview

Arogya-SMC is designed as a multi-platform healthcare ecosystem where each component serves a specific stakeholder while remaining connected through centralized backend services.

The platform consists of independent applications for ASHA workers, citizens, healthcare administrators, and municipal authorities, enabling efficient data collection, healthcare monitoring, and evidence-based decision-making.

---

# Platform Modules

<table>
<tr>
<td align="center" width="33%">

## ASHA Worker Application

<img src="Assets/asha_app_1.jpeg" width="220"/>

Designed for Accredited Social Health Activists (ASHAs), this application enables healthcare workers to digitally record household surveys, monitor pregnancies, track immunization schedules, report communicable diseases, and synchronize field data with the central platform.

</td>

<td align="center" width="33%">

## Citizen Application

<img src="Assets/public_app1.jpeg" width="220"/>

Provides citizens with access to health-related services, public advisories, awareness initiatives, and communication with municipal healthcare systems through a mobile-first interface.

</td>

<td align="center" width="33%">

## Municipal Dashboard

<img src="Assets/Muncipal_dashboard_1.png" width="220"/>

A centralized dashboard designed for municipal authorities to visualize healthcare trends, monitor disease statistics, evaluate ward-level indicators, and support public health planning.

</td>
</tr>
</table>

---

# Application Gallery

## ASHA Worker Application

<p align="center">
<img src="Assets/asha_app_1.jpeg" width="220">
<img src="Assets/asha_app_2.jpeg" width="220">
<img src="Assets/asha_app_3.jpeg" width="220">
<img src="Assets/asha4.jpeg" width="220">
</p>

The ASHA application digitizes field operations by replacing manual registers with structured digital workflows. It enables healthcare workers to capture demographic information, conduct household surveys, report health events, and synchronize collected data with the municipal platform.

---

## Citizen Application

<p align="center">
<img src="Assets/public_app1.jpeg" width="220">
<img src="Assets/public_app2.jpeg" width="220">
<img src="Assets/Public_app3.jpeg" width="220">
</p>

The citizen application focuses on improving public engagement by providing healthcare information, awareness campaigns, and simplified access to municipal health services through an intuitive mobile interface.

---

## Municipal Dashboard

<p align="center">
<img src="Assets/Muncipal_dashboard_1.png" width="30%">
<img src="Assets/Muncipal_dashboard_2.png" width="30%">
<img src="Assets/Muncipal_dashboard_3.png" width="30%">
</p>

The Municipal Dashboard aggregates information from multiple stakeholders and presents interactive visualizations to support healthcare administrators. It enables monitoring of disease distribution, demographic indicators, healthcare resources, and operational performance across municipal wards.

---

# System Architecture

The Arogya-SMC ecosystem follows a modular architecture that separates client applications, backend services, data storage, analytics, and administrative interfaces. This design improves maintainability while allowing independent development of platform components. :contentReference[oaicite:0]{index=0}

<p align="center">
<img src="Assets/architecture/architecture.png" width="100%">
</p>

---

# Context Diagram

The context diagram illustrates the interaction between external stakeholders—including citizens, ASHA workers, hospitals, laboratories, and municipal authorities—and the centralized healthcare platform. It highlights the flow of healthcare information across organizational boundaries while maintaining a unified data ecosystem. :contentReference[oaicite:1]{index=1}

<p align="center">
<img src="Assets/architecture/context.png" width="95%">
</p>

---

# Data Flow

The platform processes information through a structured workflow beginning with data collection, followed by validation, centralized storage, analytics, visualization, and decision support. This architecture enables timely reporting and supports municipal public health operations. :contentReference[oaicite:2]{index=2}

<p align="center">
<img src="Assets/architecture/dataflow.png" width="95%">
</p>

---
