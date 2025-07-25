# Pro QA Bug Management (3D & Animated)
#### Enterprise-Ready Bug Tracking for Odoo 18

![Screenshot](static/description/screenshot_management_bug.png)

---

## Overview

**Pro QA Bug Management** is a next-level Odoo 18 module designed for Quality Assurance, Development, and Management teams.  
It brings 3D-animated Kanban boards, dashboards, and analytics—plus bulk bug assignment, tagging, and smart notification features—to help your organization manage and resolve software bugs efficiently.

---

## Features

- **Beautiful 3D Animated Kanban:** Modern, interactive board to track bugs visually.
- **Bulk Assignment Wizard:** Assign multiple bugs to a developer with just a few clicks.
- **Powerful Dashboards & Graphs:** Visualize bug status, assignments, and team performance.
- **Status Workflow:** New → Assigned → In Progress → Resolved → Closed/Cancelled.
- **Bug Tagging:** Organize, filter, and search bugs with tags.
- **Chatter Integration:** Log discussions and activities right on each bug.
- **Time to Solve:** See how long it takes to fix each bug.
- **Notifications & Activities:** Automated notifications and reminders on assignment and status change.
- **Role-based Security:** Users can manage/report their own bugs, managers see all.
- **Multi-language Support:** Translatable, with included Spanish (`es.po`) sample.

---

## Quick Start

1. **Copy the module folder** into your Odoo 18 `addons/` directory.

2. **Restart the Odoo server:**

bug_management_module/
├── __init__.py
├── __manifest__.py
├── controllers/
│   ├── __init__.py
│   └── main.py
├── data/
│   └── bugs_data.xml
├── models/
│   ├── __init__.py
│   └── management_bug.py
├── security/
│   ├── ir.model.access.csv
│   └── management_bug_security.xml
├── static/
│   ├── description/
│   │   ├── icon.png
│   │   └── screenshot_management_bug.png
│   └── src/
│       ├── css/
│       │   └── bug_management.css
│       └── js/
│           └── bug_management.js
├── views/
│   ├── assets.xml
│   ├── dashboard.xml
│   ├── management_bug.xml
│   ├── menu.xml
│   └── templates.xml
├── wizard/
│   ├── __init__.py
│   ├── bug_bulk_assign.py
│   └── bug_bulk_assign_view.xml
└── i18n/
    └── es.po