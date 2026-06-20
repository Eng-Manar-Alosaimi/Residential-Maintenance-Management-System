# Residential Maintenance Management System (RMMS)

[cite_start]A comprehensive system engineering, requirements specification, and data analysis project designed to enhance the operational efficiency of facility management and maintenance within residential communities[cite: 94, 99]. 

[cite_start]This repository showcases an end-to-end software engineering lifecycle approach—spanning from stakeholder identification and functional/non-functional requirements engineering to UML behavioral modeling and building a high-fidelity data analysis dashboard[cite: 104, 205, 311].

---

## 📌 Project Overview
[cite_start]The Residential Maintenance Management System is structured to optimize how maintenance requests are tracked, assigned, and evaluated[cite: 99]. [cite_start]The system bridges the communication gap between tenants, technicians, and property managers[cite: 103]:
* [cite_start]**Residents** can frictionlessly submit requests with required image/video evidence and track progress in real-time[cite: 100].
* [cite_start]**Technicians** receive specialized schedules, log work progress, and submit completion data[cite: 101].
* [cite_start]**Supervisors & Property Managers** utilize centralized dashboard tools to analyze performance, track operational throughput, and control quality[cite: 102].

---

## 🚀 Key System Features & Requirements

### 1. Functional Requirements (FR) Breakdown
* [cite_start]**User & Profile Management:** Secure registration, authentication, and access limits based on distinct system roles (Resident, Technician, Supervisor, Property Manager)[cite: 111, 125].
* [cite_start]**Request Submission Pipeline:** Unique tracking ID and timestamp generation per request with mandatory media attachments, urgency ratings, and service categorization[cite: 132, 136, 138].
* [cite_start]**Live Status Tracking:** Real-time visibility into the lifecycle of a request (Open, In Progress, Closed) with automated instant notification triggers[cite: 143, 145].
* [cite_start]**Resource Scheduling:** Database tracking of technician skills and availability with calendar view operations for supervisors[cite: 148, 152].
* [cite_start]**Feedback Mechanism:** Aggregated resident ratings and comments post-completion for quality assurance and performance reviews[cite: 169, 171].

### 2. Non-Functional Requirements (NFR) High-level Targets
* [cite_start]**Performance & Scalability:** Sub-3-second page loads [cite: 177][cite_start], support for concurrent users without lag [cite: 178][cite_start], and a decoupled **Media Service architecture** to offload image/video hosting and processing independently from the main server[cite: 200, 201].
* [cite_start]**Security Constraints:** Mandatory end-to-end data encryption for private user data/images [cite: 189] [cite_start]alongside strict role-based access control (RBAC)[cite: 190].

---

## 🗺️ System Design & UML Modeling

[cite_start]To ensure strict system compliance and correct logical flows, the platform architecture was formally modeled using standard UML conventions:

### Use Case Diagram
[cite_start]Illustrates structural system boundaries, detailing how the user roles interact with key system functions (e.g., submitting requests, technician scheduling, and report generation)[cite: 206, 207].
![Use Case Diagram](./images/use_case_diagram.png)

### Class Diagram
[cite_start]Represents the structural data blueprint of the system, defining core entities (`Resident`, `MaintenanceRequest`, `MediaAttachment`, `Rating`, `Notification`, `Supervisor`, `PropertyManager`), their internal attributes, methods, and relationships[cite: 239].
![Class Diagram](./images/class_diagram.png)

### Sequence Diagram
[cite_start]Captures the dynamic object interactions and message passing sequence when a resident initiates and submits a maintenance request through the application interface to the media and assignment modules[cite: 281].
![Sequence Diagram](./images/sequence_diagram.png)

---

## 📈 Interactive Property Manager Dashboard
[cite_start]An advanced data engineering dataset consisting of **1,000 generated maintenance records** was simulated to validate and evaluate the operational performance of the proposed system architecture.

[cite_start]Using this data, a high-fidelity, dynamic analytical dashboard was built to track critical Key Performance Indicators (KPIs) in real-time:

### Key Analytics Tracked:
* [cite_start]**Priority Metrics:** Categorization of high, medium, and low urgency items[cite: 312].
* [cite_start]**Resolution Throughput:** Analysis of task duration based on priority tiers[cite: 312].
* [cite_start]**Operational Volumes:** Distribution of request statuses (Closed, In Progress, Open)[cite: 312].
* [cite_start]**Categorical Volume Analysis:** Tracking the most common issue types (e.g., Electrical, Elevator, General, Plumbing)[cite: 312].
* [cite_start]**Workload Balancing:** Dynamic tracking of task allocations per technician to manage labor utilization[cite: 312].

![Property Manager Dashboard](./images/dashboard_screenshot.png)
[cite_start]*The interactive dashboard features built-in **slicers by priority** that dynamically filter and adjust all associated pivot tables and charts simultaneously[cite: 312]. All components are completely driven by the underlying structured Microsoft Excel data backend.*

---

## 📂 Repository Structure & Artifacts
* [cite_start]`/data/`: Contains the optimized Excel data file (`.xlsx`) featuring the 1,000 simulated maintenance rows, formulas, pivot tables, and charts[cite: 311, 312].
* [cite_start]`/images/`: Houses the UML design models and dashboard visualizations used in this file[cite: 206, 239, 281].
* [cite_start]`/reports/`: Contains the final formal software architecture and specifications documentation.

### Direct File Links:
* **Complete System Engineering Report:** [View Project Report PDF](./reports/Residential_Maintenance_Management_System_Report.pdf)
* **Data Model & Dashboard Backend:** [View Excel Sheet Source](./data/Maintenance_Data_Model.xlsx)

---

## 🧰 Engineering Tooling & Stack
* [cite_start]**System Modeling & UML:** [Visual Paradigm (System Diagrams & Flowcharts)] 
* [cite_start]**Data Analysis & Dashboards:** Microsoft Excel (Advanced Pivot Tables, Interactive Slicers, and Dynamic Charts) [cite: 312]
* [cite_start]**Requirements Specification:** Microsoft Word / PDF Document Processor 
* [cite_start]**Institution:** Taif University, College of Computer & Information Technology, Computer Engineering Department[cite: 91, 93].
