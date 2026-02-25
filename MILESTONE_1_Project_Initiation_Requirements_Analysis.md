# Milestone 1: Project Initiation & Requirements Analysis (Week 1)

## Overview
This milestone focuses on establishing the project foundation, defining scope, and gathering comprehensive requirements for the Expense Report Generator system.

## Deliverables

### 1. Project Charter
**Objective:** Outline the project scope, goals, and team structure.

**Content:**
- **Project Name:** Expense Report Generator
- **Project Goal:** Develop a desktop application enabling employees and managers to efficiently submit, track, and manage expense reports with categorization and approval workflows.
- **Scope:**
  - User authentication and role-based access (Employee, Manager, Admin)
  - Expense submission with categorization
  - Report generation and approval workflow
  - Data export (CSV/PDF)
  - Dashboard with expense summary

- **Team Roles:**
  - **Project Manager:** Project planning, Gantt chart creation, risk management, progress tracking
  - **Systems Analyst:** Requirements gathering, UI/UX design, use case diagrams, testing strategy
  - **Programmer:** Technical implementation, GUI development, database/file management

- **Timeline:** 6 weeks
- **Target Users:** Employees (expense submitters), Managers (approvers), Finance team (reviewers)

### 2. Requirements Specification Document

#### Functional Requirements

| Req ID | Requirement | Description |
|--------|-------------|-------------|
| FR-1 | User Authentication | System shall authenticate users with username and password |
| FR-2 | Role-Based Access | System shall provide different features based on user roles (Employee, Manager, Admin) |
| FR-3 | Add Expense | Employee shall be able to add new expenses with date, amount, category, description, and receipt attachment |
| FR-4 | Categorize Expenses | System shall support predefined expense categories (Travel, Meals, Accommodation, Office, etc.) |
| FR-5 | View Expenses | Users shall be able to view a list of all submitted expenses with filters |
| FR-6 | Edit/Delete Expenses | Employees shall be able to edit or delete their own pending expenses |
| FR-7 | Generate Reports | System shall generate expense reports by date range, category, or employee |
| FR-8 | Approve/Reject | Managers shall be able to approve or reject submitted expense reports |
| FR-9 | Data Export | System shall export reports in CSV and PDF formats |
| FR-10 | Dashboard | System shall display summary statistics (total expenses, pending approvals, budget utilization) |
| FR-11 | Data Persistence | System shall save all data to local files (JSON or CSV) |

#### Non-Functional Requirements

| Req ID | Requirement | Description |
|--------|-------------|-------------|
| NFR-1 | Usability | Application shall be intuitive with average learning time < 5 minutes |
| NFR-2 | Performance | Application shall load data within 2 seconds |
| NFR-3 | Reliability | System shall have 99% uptime with data backup mechanisms |
| NFR-4 | Security | Passwords shall be stored securely; sensitive data shall be encrypted |
| NFR-5 | Scalability | System shall handle up to 1000 expense records without performance degradation |
| NFR-6 | Compatibility | Application shall run on Windows, macOS, and Linux |
| NFR-7 | Maintainability | Code shall follow Java best practices with clear documentation |
| NFR-8 | Accessibility | UI shall follow accessibility standards (WCAG 2.1 Level AA) |

### 3. Use Case Diagram & Descriptions

**Primary Actors:**
- Employee (Expense Submitter)
- Manager (Approver)
- Admin (System Administrator)

**Use Cases:**

| Use Case ID | Use Case Name | Actor | Description |
|-------------|---------------|-------|-------------|
| UC-1 | Login | All Users | User authenticates with credentials |
| UC-2 | Submit Expense | Employee | Employee enters expense details and submits |
| UC-3 | View My Expenses | Employee | Employee views their submitted expenses |
| UC-4 | Edit Pending Expense | Employee | Employee modifies a pending expense |
| UC-5 | View Pending Approvals | Manager | Manager views expenses awaiting approval |
| UC-6 | Approve/Reject Expense | Manager | Manager reviews and approves/rejects expenses |
| UC-7 | Generate Report | Manager/Admin | Generate summary report by filters |
| UC-8 | Export Report | Manager/Admin | Export report in CSV or PDF format |
| UC-9 | View Dashboard | All Users | View expense summary and statistics |
| UC-10 | Manage Users | Admin | Admin adds/removes users and assigns roles |

---

## HCI Focus: User Personas

### Persona 1: Emily (Employee)
- **Background:** Junior consultant, files 8-10 expenses per month
- **Goals:** Quick expense submission, easy tracking
- **Pain Points:** Remembers receipts but struggles with categorization
- **Needs:** Intuitive interface, mobile-friendly submission, receipt upload

### Persona 2: David (Manager)
- **Background:** Project manager, approves 20+ expenses weekly
- **Goals:** Efficient approval workflow, clear visibility of team spending
- **Pain Points:** Manual approval process is time-consuming
- **Needs:** Dashboard overview, batch approval option, detailed reports

### Persona 3: Sarah (Finance Admin)
- **Background:** Finance coordinator, processes all expense reports
- **Goals:** Accurate tracking, compliance, audit trails
- **Pain Points:** Data inconsistency, manual entry errors
- **Needs:** Robust data export, comprehensive reporting, user management

---

## Acceptance Criteria
- [ ] Project Charter approved by all team members
- [ ] Requirements document reviewed and signed off
- [ ] Use cases validated with stakeholders
- [ ] User personas documented and agreed upon
- [ ] All deliverables in GitHub repository

## Team Responsibilities

**Project Manager:**
- Coordinate requirements gathering sessions
- Create initial Gantt chart
- Schedule stakeholder meetings

**Systems Analyst:**
- Document all requirements
- Create use case diagrams
- Develop user personas

**Programmer:**
- Review technical feasibility
- Prepare development environment setup plan

---

**Status:** Complete
**Due Date:** End of Week 1
**Approval:** [To be signed off by team and instructor]