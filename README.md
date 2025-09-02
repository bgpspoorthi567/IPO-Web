IPO-Web-App
IPO WEB APPLICATION BY BLUESTOCK FINTECH

🧾 Bluestock IPO Web App
This project is a full-stack Django + React-based IPO management system developed for Bluestock Fintech. This project was created by B.G.P. Spoorthi and B.G.P. Sahithi

Name	Role	Work
B.G.P. Sahithi    Frontend Developer 
B.G.P. Spoorthi   Backend Developer

IPO Web Application
Introduction
This project is developed for Bluestock Fintech as part of a production-level software development Intern. The IPO Web Application provides IPO-related information for the Bluestock website/app and clients’ platforms. This project aims to give interns handson experience with industry-standard web development practices.

Objective
The web application and its REST API offer essential IPO details to the public, including:

Company Logo (placeholder image)
Company Name
Price Band
Opening and Closing Dates
Issue Size
Issue Type
Listing Date
Status
IPO Price
Listing Price
Listing Gain
Current Market Price (CMP)
Current Return
Downloadable RHP and DRHP PDFs
ER Diagram Overview
Entities
Companies

ID
Name
Logo URL
IPOs

ID
Company ID
Price Band
Dates (Open/Close, Listing)
Prices (IPO Price, Listing Price, CMP)
Status
Return
Documents

ID
IPO ID
RHP
DRHP
Relationships
One Company ➝ Many IPOs (Cascade Delete)
One IPO ➝ Many Documents (Cascade Delete)
Technology Stack
Backend (Python Django)
Language: Python 3.12.3
Framework: Django 5.0.6
API: Django REST Framework
Database: PostgreSQL
Auth: Django Built-in / JWT
Frontend (React + Tailwind CSS)
Framework: React.js
Styling: Tailwind CSS
Routing: React Router
Component Library: Headless UI / Custom
Build Tool: Vite / Webpack
Project Features
Company & IPO Listings with detailed filtering options
Real-time IPO Data including Price Band, CMP, Returns
Document Downloading (RHP & DRHP PDFs)
Authentication System using JWT
Responsive UI optimized with Tailwind CSS
