# Corporate Social Responsibility Management
> A ServiceNow-based CSR management platform for managing NGO partnerships, employee volunteering, budgets, verified impact, KPIs, and AI-assisted decision support.

## Overview
Corporate Social Responsibility (CSR) activities are often managed across spreadsheets, emails, and disconnected systems. This makes NGO onboarding, compliance, volunteering, budget tracking, impact verification, and reporting difficult to manage consistently.

Our solution centralizes the complete CSR lifecycle on **ServiceNow**.

### Core Workflow
**Plan → Execute → Measure → Verify → Analyze → Improve**

The platform connects:
- CSR planning and budgeting
- NGO/partner onboarding and compliance
- CSR programs and events
- Employee volunteering and attendance
- Budget and expense governance
- Impact reporting and verification
- KPI tracking and dashboards
- AI-assisted risk analysis and recommendations
- Corrective actions and continuous improvement

---

## Key Features

### 1. CSR Planning & Budgeting
- CSR categories and annual plans
- Budget allocation and targets
- Budget approval workflows
- Committed vs. spent budget tracking
- Budget threshold controls

### 2. NGO / Partner Management
- NGO registration and onboarding
- Registration Number and PAN duplicate checks
- Compliance document management
- Document expiry reminders
- AI-assisted partner risk screening
- Compliance Officer verification

### 3. Program & Event Management
- Program proposals
- Event creation and approval
- Objectives, beneficiaries, targets, and budgets
- Available budget calculation
- Program and event lifecycle tracking

### 4. Employee Volunteering
- Volunteer registration
- Capacity and waitlist management
- Eligibility and participation controls
- Attendance and check-in/check-out
- Volunteer hours calculation
- Certificates, recognition, and badges

### 5. Impact Verification
- NGO impact report submission
- Beneficiary and outcome tracking
- Evidence submission
- CSR Coordinator verification
- Only verified impact contributes to official KPIs

### 6. Financial Governance
- Expense tracking
- Budget utilization monitoring
- Committed budget tracking
- Budget exception handling
- Finance integration support

### 7. KPI & Management Analytics
Key CSR metrics include:

- CSR Hours Achievement
- Employee Participation
- Beneficiary Achievement
- NGO Engagement
- Program Completion
- Budget Utilization
- Volunteer Hours
- No-Show Rate
- Cost per Beneficiary
- Impact Verification Rate

### 8. AI-Assisted Decision Support
AI is used to support—not replace—business decisions.

**AI capabilities:**
- NGO partner risk screening
- CSR budget allocation suggestions
- KPI trend analysis
- Management summaries
- Risk and performance insights

Deterministic calculations, compliance controls, financial rules, and official KPI values remain controlled by ServiceNow Business Rules and human approval.

---

## ServiceNow Architecture
Users & Stakeholders
        │
        ▼
Employee Center / Partner Portal / CSR Workspace
        │
        ▼
ServiceNow CSR Scoped Application
        │
        ├── Service Catalog
        ├── Flow Designer
        ├── Business Rules
        ├── Script Includes
        ├── Approvals
        ├── Notifications
        ├── Roles & ACLs
        ├── UI Builder
        └── Reports & Dashboards
        │
        ▼
CSR Data Layer
        │
        ├── Plans & Budgets
        ├── Partners / NGOs
        ├── Programs & Events
        ├── Registrations
        ├── Attendance
        ├── Expenses
        ├── Impact Reports
        └── KPI Results
        │
        ▼
AI Decision Support
        │
        ├── Partner Risk
        ├── Budget Suggestions
        └── Management Insights
        │
        ▼
Human Review & Approval
        │
        ▼
ServiceNow Workflow
        │
        ▼
Continuous Improvement

---

## AI Decision Model
ServiceNow Records
        ↓
Validation & Business Rules
        ↓
Verified Metrics & Trusted Data
        ↓
AI Analysis
        ↓
Risk / Insight / Recommendation
        ↓
Human Review & Approval
        ↓
Approved Action
        ↓
New Outcome Data
        ↓
Re-measurement & Continuous Improvement

---

## Technology Stack
| Area           | Technology                                 |
| -------------- | ------------------------------------------ |
| Platform       | ServiceNow                                 |
| Application    | App Engine Studio / Scoped Application     |
| Workflow       | Flow Designer                              |
| Backend Logic  | Business Rules, Script Includes            |
| User Interface | Employee Center, UI Builder                |
| Data           | ServiceNow Tables                          |
| Automation     | Scheduled Flows, Notifications             |
| Security       | Roles & ACLs                               |
| AI             | Now Assist / Predictive Intelligence       |
| Analytics      | Reports, Dashboards, Performance Analytics |
| Integrations   | IntegrationHub / REST APIs                 |
| Testing        | Automated Test Framework (ATF)             |

---

## Core ServiceNow Components
* Custom CSR tables
* Service Catalog
* Record Producers
* Flow Designer workflows
* Business Rules
* Script Includes
* Scheduled automation
* Approval workflows
* Notifications
* Roles and ACLs
* Employee Center
* UI Builder
* Reports and dashboards
* Performance Analytics
* IntegrationHub / REST
* AI-assisted analysis

---

## Business Rules
Examples of important business controls:

* Duplicate NGO detection
* Compliance document validation
* Partner suspension controls
* Budget availability validation
* Budget commitment at approval
* Volunteer capacity and waitlist handling
* Attendance and volunteer-hour validation
* Impact report verification
* KPI calculation
* Budget exception handling
* Event closure validation

An event cannot be fully closed until required attendance, expense, and impact information is completed.

---

## Key Innovation

### Verified Impact
The platform does not treat every submitted impact value as an official KPI.

**Submitted Impact → Verification → Trusted CSR KPI**

### AI + Human Governance
AI provides recommendations and insights while ServiceNow workflows and human approvals control final decisions.

### Real-Time Budget Governance
The system considers both:

**Spent + Committed Budget**
to prevent over-allocation.

### Closed-Loop CSR Management
Plan
 ↓
Execute
 ↓
Measure
 ↓
Verify
 ↓
Analyze
 ↓
Improve
 ↓
Plan Again

---

## Project Structure
Corporate-Social-Responsibility-Management/
│
├── README.md
├── sn_source_control.properties
│
├── docs/
│   ├── architecture/
│   ├── workflows/
│   ├── screenshots/
│   └── diagrams/
│
└── src/
    └── ServiceNow application files

---

## Project Status

### Implemented / Prototyped
* ServiceNow scoped application
* CSR custom tables
* Business Rules
* Workflows and automation
* Notifications
* Access controls
* CSR management flows
* Basic PDI implementation and testing

### Planned / Extended
* Advanced AI capabilities
* External HRMS integration
* Finance system integration
* Advanced management intelligence
* Expanded Performance Analytics
* Enterprise-scale deployment

---

## Project Impact
The platform is designed to improve:

* CSR operational efficiency
* NGO onboarding speed
* Budget visibility
* Employee participation tracking
* Impact data quality
* Compliance monitoring
* Reporting efficiency
* Management decision-making

Success can be evaluated using baseline vs. post-implementation measurements such as processing time, manual effort, budget utilization, participation, impact verification, and reporting time.

---

## Team
| Member                      | Role                                  |
| --------------------------- | ------------------------------------- |
| Shalini Chinnaguravagari    | Project Manager & Automation Engineer |
| Hasvanth Reddy Ponnapureddy | Backend & Integration Developer       |
| J Ruchitha Reddy            | ServiceNow Developer                  |
| Shrinidhi T                 | ServiceNow Architect                  |
| Chittabattuni Sowjanya      | UI/UX & Analytics Designer            |
| Tirumalasetty Mounika       | QA & Testing Engineer                 |

---

## Hackathon

**ServiceNow University HackNow India 2026**

**Problem Statement:** Corporate Social Responsibility (CSR) Management

**Team:** ServiceNow Mavericks
**Institution:** Mohan Babu University

The project focuses on building a centralized, automated and AI-assisted CSR management platform using ServiceNow as the core platform.

---

## Future Scope
* Advanced predictive CSR analytics
* Intelligent resource allocation
* More external system integrations
* Advanced partner performance scoring
* Automated corrective-action recommendations
* Enterprise-scale deployment
* Expanded AI-powered management intelligence

---

## Repository
This repository contains the ServiceNow application source-control project and supporting project documentation.

**GitHub:**
[https://github.com/The-shalinicodes/Corporate-Social-Responsibility-Management](https://github.com/The-shalinicodes/Corporate-Social-Responsibility-Management)

---

## Built With
**ServiceNow · App Engine Studio · Flow Designer · Business Rules · Script Includes · Service Catalog · Employee Center · UI Builder · Now Assist / AI · IntegrationHub · REST APIs · Performance Analytics**

---

## Disclaimer
This project is developed as a hackathon/prototype implementation for demonstrating a ServiceNow-based CSR management solution. Some advanced integrations and AI capabilities may require additional ServiceNow products, configurations, or enterprise system integrations.
```
```
