Residential Maintenance Management System (RMMS)
A comprehensive system engineering, requirements specification, and data analysis project designed to enhance the operational efficiency of facility management and maintenance within residential communities.

This repository showcases an end-to-end software engineering lifecycle approach—spanning from stakeholder identification and functional/non-functional requirements engineering to UML behavioral modeling and building a high-fidelity data analysis dashboard.

Project Overview
The Residential Maintenance Management System is structured to optimize how maintenance requests are tracked, assigned, and evaluated.  
The system bridges the communication gap between tenants, technicians, and property managers.

Residents can frictionlessly submit requests with required image/video evidence and track progress in real-time.

Technicians receive specialized schedules, log work progress, and submit completion data.

Supervisors & Property Managers utilize centralized dashboard tools to analyze performance, track operational throughput, and control quality.

Key System Features & Requirements
1. Functional Requirements (FR) Breakdown
User & Profile Management: Secure registration, authentication, and access limits based on distinct system roles (Resident, Technician, Supervisor, Property Manager).

Request Submission Pipeline: Unique tracking ID and timestamp generation per request with mandatory media attachments, urgency ratings, and service categorization.

Live Status Tracking: Real-time visibility into the lifecycle of a request (Open, In Progress, Closed) with automated instant notification triggers.

Resource Scheduling: Database tracking of technician skills and availability with calendar view operations for supervisors.

Feedback Mechanism: Aggregated resident ratings and comments post-completion for quality assurance and performance reviews.

2. Non-Functional Requirements (NFR) High-level Targets
Performance & Scalability: Sub‑3‑second page loads, support for concurrent users without lag, and a decoupled Media Service architecture for independent media processing.

Security Constraints: Mandatory end‑to‑end data encryption for private user data/images alongside strict role‑based access control (RBAC).

System Design & UML Modeling
To ensure strict system compliance and correct logical flows, the platform architecture was formally modeled using standard UML conventions.

Use Case Diagram
Illustrates structural system boundaries and how user roles interact with key system functions (request submission, scheduling, reporting).

<img width="588" height="1101" alt="image0 (5)" src="https://github.com/user-attachments/assets/247f8292-ad50-4a0d-b875-6b0d0b6a1b8f" />

Class Diagram
Represents the structural data blueprint of the system, defining core entities (Resident, MaintenanceRequest, MediaAttachment, Rating, Notification, Supervisor, PropertyManager) and their relationships.

<img width="904" height="984" alt="image1 (3)" src="https://github.com/user-attachments/assets/c9052bd4-f225-4312-afce-61201082ac7f" />

Sequence Diagram
Captures dynamic object interactions when a resident submits a maintenance request through the application interface.

<img width="961" height="442" alt="image2 (3)" src="https://github.com/user-attachments/assets/c43cea48-cf22-4ae6-8e4d-b65dcc97209f" />

Interactive Property Manager Dashboard
An advanced dataset of 1,000 generated maintenance records was simulated to evaluate the operational performance of the system.

Using this data, a high‑fidelity analytical dashboard was built to track critical KPIs in real time.

Key Analytics Tracked
Priority Metrics: High, medium, and low urgency categorization.

Resolution Throughput: Task duration analysis by priority tier.

Operational Volumes: Distribution of request statuses (Closed, In Progress, Open).

Categorical Volume Analysis: Most common issue types (Electrical, Elevator, General, Plumbing).

Workload Balancing: Technician task allocation tracking.

<img width="1855" height="617" alt="Screenshot 2026-06-20 071036" src="https://github.com/user-attachments/assets/102e63fe-845f-42ed-bf20-d404b1e43f04" />

The dashboard includes interactive slicers that dynamically filter all pivot tables and charts. All components are driven by a structured Excel backend.

Repository Structure & Artifacts
maintenance_requests.xlsx: Contains the optimized Excel dataset with 1,000 simulated rows, formulas, pivot tables, and charts.

Residential_Maintenance_Management_System_Report: Contains the final formal software architecture and specifications documentation.

Direct File Links
Complete System Engineering Report: Residential_Maintenance_Management_System_Report.pdf

Data Model & Dashboard Backend: maintenance_requests.xlsx

Engineering Tooling & Stack
System Modeling & UML: Visual Paradigm

Data Analysis & Dashboards: Microsoft Excel (Pivot Tables, Slicers, Dynamic Charts)

Requirements Specification: Microsoft Word / PDF

Institution: Taif University — College of Computer & Information Technology, Computer Engineering Department
