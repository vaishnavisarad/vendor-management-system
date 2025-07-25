# vendor-management-system
This is a full-stack web application built with Django (REST Framework) for the backend and React for the frontend. It uses JWT-based authentication for secure login/logout and supports robust vendor, item, and requisition management workflows, designed to streamline procurement processes in an organization.

✅ Key Features
🔐 Authentication
JWT-based login/logout

Protected API endpoints using IsAuthenticated

Token blacklisting on logout

📇 Vendor Management
Add, view, edit, and delete vendors

Search, filter, and export vendor list

Vendor categories and active/inactive status

🧾 Item Management
Maintain item master records

Add items with name, code, unit, category, and description

Import/export items via CSV or Excel

Edit/deactivate items

📋 Requisition Workflow
Submit item requisitions with quantities, delivery dates, notes

Upload supporting documents

Auto-generate requisition numbers

Approval flow from project head to purchase team

📤 Request for Quotation (RFQ)
Select vendors and send RFQ links

Vendors submit Excel-based quotes

System generates quote comparison sheets

📑 Purchase Order (PO)
Finalize vendor based on price and terms

Auto-generate and dispatch purchase orders

Maintain historical price data

🔔 Notifications & Alerts
Real-time notifications for all stages (submission, approval, PO sent)

Admin and vendor notifications via system alerts

📈 Reports
Vendor master report

Item list report

Requisition & RFQ status reports

Quotation comparison sheet

PO logs

Exportable in CSV / Excel

| Layer       | Technology                                   |
| ----------- | -------------------------------------------- |
| Frontend    | React, Axios, Bootstrap                      |
| Backend     | Django, Django REST Framework                |
| Auth        | JWT (djangorestframework-simplejwt)          |
| Database    | SQLite (can be upgraded to PostgreSQL/MySQL) |
| API Testing | Postman                                      |
