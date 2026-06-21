# Residential Maintenance Management System 

A comprehensive software engineering, requirements specification, and data analysis project designed to enhance the operational efficiency of facility management and maintenance within residential communities.

This repository demonstrates an end-to-end software engineering lifecycle approach, spanning stakeholder identification, requirements engineering, UML modeling, and interactive dashboard development.

---

## Project Deliverables

- Software Requirements Specification (SRS)
- UML Diagrams
- Simulated Maintenance Dataset
- Interactive Management Dashboard
- Final Project Report

---

## Project Overview

The Residential Maintenance Management System (RMMS) is designed to optimize how maintenance requests are submitted, assigned, tracked, and evaluated.

The system improves communication and coordination between residents, technicians, supervisors, and property managers.

### Residents

- Submit maintenance requests with image and video attachments.
- Specify urgency levels and service categories.
- Track request progress in real time.
- Provide feedback after service completion.

### Technicians

- Receive assigned maintenance tasks.
- Manage schedules and assigned workloads.
- Update work progress throughout task execution.
- Submit completion reports and service updates.

### Supervisors and Property Managers

- Monitor maintenance operations through centralized dashboards.
- Track technician performance and workload distribution.
- Analyze maintenance trends and operational metrics.
- Support decision-making using real-time analytics.

---

## Key System Features and Requirements

### Functional Requirements

#### User and Profile Management

- Secure registration and authentication.
- Role-based access control.
- Profile management for all system roles.

#### Maintenance Request Management

- Automatic request ID generation.
- Timestamp recording.
- Media attachment support.
- Priority and category assignment.

#### Request Tracking

- Real-time status monitoring.
- Automated notifications.
- Complete request lifecycle visibility.

#### Resource Scheduling

- Technician skill and availability tracking.
- Supervisor scheduling interface.
- Calendar-based task management.

#### Feedback and Evaluation

- Resident ratings and comments.
- Performance monitoring.
- Quality assurance support.

### Non-Functional Requirements

#### Performance and Scalability

- Page load times below three seconds.
- Support for concurrent users.
- Scalable architecture capable of handling future growth.

#### Media Service Architecture

- Independent image and video hosting.
- Reduced workload on the primary application server.

#### Security

- Data encryption for sensitive information and media.
- Secure authentication mechanisms.
- Role-Based Access Control (RBAC).

---

## System Design and UML Modeling

To ensure system correctness and compliance with the specified requirements, the platform was modeled using standard UML methodologies.

### Use Case Diagram

Illustrates system boundaries and interactions between user roles and major functionalities such as request submission, technician scheduling, and reporting.

<img width="588" height="1101" alt="image0 (5)" src="https://github.com/user-attachments/assets/247f8292-ad50-4a0d-b875-6b0d0b6a1b8f" />

---

### Class Diagram

Represents the structural blueprint of the system, defining core entities, attributes, methods, and relationships.

Key entities include:

- Resident
- MaintenanceRequest
- MediaAttachment
- Rating
- Notification
- Supervisor
- PropertyManager

<img width="904" height="984" alt="image1 (3)" src="https://github.com/user-attachments/assets/c9052bd4-f225-4312-afce-61201082ac7f" />

---

### Sequence Diagram

Captures the sequence of interactions involved when a resident submits a maintenance request through the application.

<img width="961" height="442" alt="image2 (3)" src="https://github.com/user-attachments/assets/c43cea48-cf22-4ae6-8e4d-b65dcc97209f" />

---

## Interactive Property Manager Dashboard

A dataset consisting of **1,000 simulated maintenance records** was generated to evaluate the proposed system architecture and support operational analysis.

Using this dataset, an interactive dashboard was developed to monitor key performance indicators and maintenance operations.

### Key Analytics

#### Priority Distribution

- High Priority
- Medium Priority
- Low Priority

#### Resolution Performance

- Task completion time analysis.
- Resolution performance by priority level.

#### Request Status Distribution

- Open
- In Progress
- Closed

#### Maintenance Category Analysis

- Electrical
- Plumbing
- Elevator
- General Maintenance

#### Workload Distribution

- Technician task allocation.
- Resource utilization monitoring.

<img width="1855" height="617" alt="Screenshot 2026-06-20 071036" src="https://github.com/user-attachments/assets/102e63fe-845f-42ed-bf20-d404b1e43f04" />

The dashboard includes interactive slicers that dynamically update charts and pivot tables based on selected criteria.

---

## Repository Structure

```text
RMMS/
│
├── maintainance_requests.xlsx
├── Residential_Maintenance_Management_System_Report.pdf
└── README.md
```

---

## Included Artifacts

### `maintainance_requests.xlsx`

Contains:

- 1,000 simulated maintenance records.
- Pivot tables and formulas.
- Interactive slicers.
- Dynamic charts and dashboard visualizations.

### `Residential_Maintenance_Management_System_Report.pdf`

Contains:

- System requirements specification.
- UML diagrams.
- System architecture documentation.
- Design and analysis artifacts.

---

## Direct File Links

### Complete System Engineering Report

[View Project Report PDF](Residential_Maintenance_Management_System_Report.pdf)

### Data Model and Dashboard Backend

[View Excel Sheet Source](maintainance_requests.xlsx)

---

## Tools and Technologies

| Category | Tool |
|-----------|------|
| System Modeling and UML | Visual Paradigm |
| Data Analysis and Dashboards | Microsoft Excel |
| Dashboard Development | Pivot Tables, Charts, and Interactive Slicers |
| Requirements Specification | Microsoft Word and PDF Documentation |
| Software Engineering | Requirements Engineering and System Design |

---

## Academic Information

**Taif University**  
**College of Computer and Information Technology**  
**Computer Engineering Department**
