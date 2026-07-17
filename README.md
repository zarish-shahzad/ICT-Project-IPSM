# Integrated Public Service Management System (IPSM)

The **Integrated Public Service Management System (IPSM)** is a project designed to manage public service requests in an organized, efficient, and transparent manner. It allows citizens to submit service-related issues while enabling administrators to monitor, update, and analyze these requests.

This repository contains the complete IPSM project: the backend database, the front-end web interface, data analysis workbooks, the project presentation, and the full project report.

---

## 📌 Objectives

- Provide an easy-to-use platform for submitting public service requests
- Store and manage service request data efficiently
- Allow administrators to track, update, and resolve requests
- Analyze service data using charts and reports
- Present and document the project professionally using standard software tools

---

## 🛠️ Tools & Technologies Used

| Tool | Role in the Project |
|---|---|
| **Microsoft Access** | Backend database — stores citizens, service requests, and status records |
| **HTML** | Structure of the IPSM web interface (Home, Submit Request, Admin Panel, Reports) |
| **CSS** | Styling and responsive design of the web interface |
| **Microsoft Excel** | Data analysis — pivot tables, charts, and conditional formatting |
| **Microsoft PowerPoint** | Project presentation of objectives, tools, and outcomes |
| **GitHub** | Version control and centralized storage of project files |
| **Microsoft Word** | Formal academic project documentation |

---

## 🗄️ Database (Microsoft Access)

The backend database (`IPSM_Database.accdb`) is organized around the following objects:

**Tables**
- `Departments` — information about all departments
- `Requests` — all service requests submitted by citizens
- `Services` — list of services offered by each department
- `Status` — status of each request (Pending, Resolved, etc.)

**Forms**
- `Admin Form` — used by administrators to manage and monitor the system
- `Navigation Form` — provides easy navigation to all forms, queries, and reports
- `Submit Request Form` — used by citizens to submit new service requests

**Queries**
- Department Performance Summary
- Requests per Service
- Requests per Department with Status Breakdown
- Resolved vs Pending Task
- Total Requests
- Track Request by Citizen

**Reports**
- Citizens Requests
- Department Performance Summary
- Request per Service
- Requests
- Resolved vs Pending Task

**Macros**
- Email Sender — sends automated emails from the system
- Export Department Report in PDF Form
- Export Request — exports request data to an external file

---

## 🌐 Web Interface (`IPSM_Dashboard.html`)

The dashboard is a single-page application (HTML, CSS, and JavaScript) with four sections, switchable via the top navigation bar:

- **🏠 Home** — welcome view with live stats (total, pending, in-progress, and resolved requests)
- **📝 Submit Request** — form for citizens to submit a new service request (name, email, phone, service type, date, location, description)
- **⚙️ Admin Panel** — search and manage requests by ID or citizen name, with edit, delete, and view actions, plus a status-update panel
- **📊 Reports & Analytics** — summary stat cards and charts (requests per service, request status breakdown)

CSS is embedded in the same file and provides gradients, card layouts, hover effects, and a responsive layout for desktop and mobile.

---

## 📊 Data Analysis (Microsoft Excel)

IPSM data was analyzed in Excel using:
- Pivot tables for summarizing requests
- Bar and column charts for visualizing trends
- Conditional formatting to highlight critical departments
- Filters, sorting, and formulas for deeper analysis

Key analyses include requests per service, request status breakdown, and resolved vs. pending vs. in-progress comparisons.

---

## 📁 Repository Structure

```
├── IPSM_Dashboard.html                  # IPSM web interface — Home, Submit Request, Admin Panel, Reports (HTML + CSS + JS)
├── IPSM_Database.accdb                  # Backend database (tables, forms, queries, reports, macros)
├── IPSM_Analysis_EXCEL.xlsx             # Data analysis workbook (pivot tables, charts, formulas)
├── ICT_Project_Report.docx              # Full project report (tools, technologies, procedures, outputs)
├── ICT_Project_IPSM_Presentation.pptx   # Project presentation slides
└── README.md                            # Project overview (this file)
```

### Excel Analysis Workbook Sheets

`IPSM_Analysis_EXCEL.xlsx` contains the following sheets:
- **Requests per Department** — request counts broken down by department
- **Departments_status** — status overview per department
- **Request per Service** — request counts broken down by service
- **Resolved vs Pending** — comparison of resolved, pending, and in-progress requests

---

## 🚀 Final Output

- Fully functional IPSM system
- Organized, relational database
- Interactive web interface for citizens and administrators
- Analytical reports and charts
- Professional presentation
- Complete project documentation

---

## ✅ Conclusion

The IPSM project successfully integrates multiple tools — Microsoft Access, HTML, CSS, Excel, PowerPoint, GitHub, and Word — to achieve effective public service management. Each tool served a specific purpose, contributing to system development, analysis, presentation, and documentation, demonstrating practical application of database systems, web technologies, and productivity software.

---

