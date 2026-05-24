📌 Leave Management System (Power Apps + Power Automate)
🚀 Overview

This project is an enterprise-style Leave Management System built using Microsoft Power Platform. It automates leave submission, approval, notifications, and reporting while integrating productivity tracking, role-based dashboards, and administrative controls.

The system is designed to simulate real-world HR operations with rule-based automation and data-driven decision-making.

⚙️ Key Features
👤 Leave Management
- Leave submission via Power Apps form
- Automated notifications via Email and Microsoft Teams
- SharePoint-based data storage

🧠 Smart Approval Engine
- Weekly automated approval (every Monday)
- Approves 2 leave requests based on highest adherence score
- Tie-breaker: earliest submission time
- Weekend rule: only 1 leave approved
- Automatic approval/rejection notifications

📊 Dashboards
- Employee dashboard: personal productivity tracking
- SME dashboard: team productivity + calendar view
- Admin dashboard: organization-wide visibility

🧾 Reporting System
- Automated leave summary reports sent to:
  - Operations Team
  - RTA Team
  - BEC Team

🛠️ Admin Controls
- Maintenance mode toggle
- Disable leave filing based on adherence threshold (e.g. <95%)
- Dynamic business rule configuration

📅 Roster Management
- CRUD operations for employee roster
- Integrated with SharePoint lists

📈 Productivity System
- Score-based performance indicator (red/green UI)
- Filterable productivity reports

💬 Feedback & Reporting Tool
- Built-in issue reporting system
- Employee feedback submission module

🧱 Tech Stack
- Microsoft Power Apps (Canvas Apps)
- Power Automate (Workflows)
- SharePoint Lists (Data Source)
- Microsoft Teams (Notifications)
- Outlook (Email Automation)
- Microsoft Excel 

🧠 Business Logic
- Adherence-based prioritization system
- Fair scheduling with tie-break rules
- Automated decision-making for leave approvals
- Role-based access control (Employee / SME / Admin)

🏗️ Architecture
Power Apps (UI Layer)
        ↓
SharePoint Lists (Database)
        ↓
Power Automate (Business Logic Engine)
        ↓
Email + Microsoft Teams (Notifications)
        ↓
Dashboards (SME / Admin / Employee Views)
