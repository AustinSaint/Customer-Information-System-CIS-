# Customer Relationship Management System (Customer Information System)

A lightweight, browser-based Customer Relationship Management (CRM) system that helps staff store, view, and manage customer information, purchase history, and loyalty points.  
The system is built as a simple single-page web app using **HTML, CSS, and JavaScript** with **localStorage** as the data store for the MVP.

## Features (MVP)

- **Create and manage customer profiles**
  - Name, email, phone
- **Store purchase information**
  - Purchase item and amount
- **Track loyalty points**
  - Add and update loyalty points per customer
- **Search customers**
  - Search by name, email, or phone
- **Edit and delete records**
  - Update existing customers
  - Delete customer records with confirmation
- **Dashboard overview**
  - Total customers
  - Total purchase amount
  - Total loyalty points


## Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Storage:** Browser `localStorage` (no backend required)
- **Tools (project):**
  - GitHub (version control, collaboration)
  - Trello (Kanban / task management)
  - WhatsApp & Google Meet (communication)
  - Visio / draw.io (UML, ER/EER diagrams)


## Project Structure

```text
.
├── index.html        # Main UI layout
├── style.css         # Styling and responsive layout
└── script.js         # Application logic (CRUD, search, dashboard)

Getting Started (Local)

1. Clone the repository
git clone https://github.com/AustinSaint/Customer-Information-System-CIS-.git
cd Customer-Information-System-CIS-

2. Open the app
Option 1: Double-click index.html to open it in your browser.
Option 2 (recommended): Use a local server (e.g. VS Code Live Server) for a smoother dev experience.

3. Use the system
Fill in the form and click “Save Customer”.
Use the search bar to filter customers.
Click Edit to modify a record, Delete to remove it.

Development Workflow
We follow a branch-based workflow with clear naming:
main – stable, production-ready code
develop – integration branch for ongoing work
feature/* – new features (e.g. feature/reporting-dashboard)
bugfix/* – fixes for issues (e.g. bugfix/fix-loyalty-calculation)
docs/* – documentation updates (e.g. docs/update-readme)
release/* – optional, for preparing tagged releases

Future Enhancements
Advanced reporting and analytics dashboards
Export/import customer data (CSV/JSON)
Role-based access control (RBAC)
Backend API and database integration
Data validation and input masking for phone and email
