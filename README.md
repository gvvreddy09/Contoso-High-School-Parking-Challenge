# 🚗 Contoso High School Parking Challenge

**A Power Platform Solution for Smart Parking Management**

---

## 🌟 Project Overview

This project was developed as part of the **Power Up Challenge**, a capstone initiative to demonstrate hands-on Power Platform skills through a real-world scenario.

**Scenario:**
Contoso High School has been facing parking space shortages and rising complaints from teachers and visitors. To improve parking management, a digital solution was needed to:

* Allow **staff and visitors** to request parking spaces daily.
* Enable **inspectors** to log vehicles during the daily parking inspection.
* Provide **leadership insights** into parking usage, occupancy, and unauthorized use.

This project showcases the ability to combine multiple Microsoft Power Platform tools into a cohesive, data-driven business application.

---

## 🧩 Solution Summary

The complete solution — titled **“Parking Challenge”** — integrates the following Power Platform components:

| Component            | Description                                                                 |
| -------------------- | --------------------------------------------------------------------------- |
| **Dataverse**        | Centralized data model for vehicles, parking requests, and inspections.     |
| **Model-Driven App** | Administrative interface for managing parking requests and inspection data. |
| **Canvas App**       | Mobile-friendly app used by parking inspectors to log vehicles on-site.     |
| **Power Automate**   | Automates email confirmations for parking requests.                         |
| **Power BI Report**  | Provides analytical insights into parking occupancy and compliance.         |

---

## 🏗️ System Design

### **1. Dataverse Data Model**

Three custom tables were designed to support the business logic:

* **Vehicles:** Stores details such as vehicle name, make, model, image, and owner email.
* **Parking Requests:** Logs daily parking requests from staff and visitors.
* **Parking Inspections:** Records vehicles found during inspections (performed once daily at 5 PM).

Each table includes **custom forms and views**, along with sample data imported from CSV files.

---

### **2. Model-Driven App**

A management application built for administrative staff to:

* Review and manage vehicles, requests, and inspections.
* Create parking requests on behalf of users.
* Access real-time records and relationships across all three tables.

---

### **3. Canvas App (Tablet Version)**

A Power Apps **tablet-optimized application** designed for on-site use by the parking inspector.

**Key Screens:**

* **Home Screen** – Simple navigation to other pages.
* **Review Screen** – Displays a filtered gallery of today’s inspections.
* **New Inspection Screen** – Allows creation of inspection records with pre-filled date and time.
* **New Vehicle Screen** – Enables quick registration of new vehicles discovered on-site.

The app uses **modern controls**, intuitive navigation, and real-time Dataverse integration.

---

### **4. Power Automate Flow**

**Flow Name:** `Parking Request Notification`
Automatically sends a **confirmation email** when a parking request is created.
Each message includes:

* Vehicle name
* Parking request ID
* Custom signature for Contoso High School

This automation streamlines communication and ensures transparency between staff and vehicle owners.

---

### **5. Power BI Dashboard**

An interactive **Power BI report** to help the leadership team analyze parking trends and identify unauthorized usage.

**Report Pages:**

1. **Home Page:** Clean navigation to other report views.
2. **Filters Page:** Filter by vehicle make, model, date, and day of week.
3. **Parking Review Page:**

   * KPIs showing total inspections and requests
   * % of inspections with valid parking requests
   * Bar charts tracking daily parking activity
   * Matrix table summarizing inspections by vehicle
   * Drill-through links back to Dataverse records

Includes a **Date Dimension Table** built using DAX for time-based reporting and analysis.

---

## ⚙️ Key Features

* 🔄 **End-to-end Power Platform integration**
* 📱 **Responsive, modern Power Apps design**
* 💌 **Automated email notifications via Power Automate**
* 📊 **Power BI insights with dynamic filters and KPIs**
* 🧮 **Dataverse relationships for real-time data flow**
* 🔐 **Simplified, role-based accessibility for staff and inspectors**

---

## 💡 Future Enhancements

Potential ways to extend the solution:

* 🧠 AI-based parking prediction using Power BI and Azure ML.
* 📷 QR code scanning for quick vehicle identification.
* 🕒 Real-time parking availability tracker.
* 💬 Microsoft Teams notifications for parking approvals.
* 🌐 Multi-location scalability for large organizations.

---

## 📁 Deliverables Summary

* ✅ Dataverse tables: Vehicles, Parking Requests, Parking Inspections
* ✅ Model-Driven App (admin view)
* ✅ Canvas App (tablet view for inspections)
* ✅ Power Automate flow for confirmation emails
* ✅ Power BI dashboard with 3 report pages
* ✅ Solution packaged with a unique publisher prefix (`vrg`)

---

## 🧠 Learning Highlights

Through this project, I applied and strengthened key Power Platform skills:

* Data modeling and relationship design in **Dataverse**
* Building both **model-driven** and **canvas** Power Apps
* Automating workflows with **Power Automate**
* Visual storytelling and KPI analysis using **Power BI**
* Applying **real-world business logic** to a complete digital solution

---

## 👤 About the Creator

* **Developer:** *Viswavardhan Reddy Gundavarapu*
* **Publisher:** `Viswavardhan Reddy Gundavarapu`
* **Program:** Microsoft **Power Up Challenge**

> *“Technology is powerful when it solves real problems. This project reflects my approach to building practical, data-driven, and user-friendly business solutions using Microsoft Power Platform.”*

---

## 🔗 Links

* 🎥 [Watch Presentation Video](https://www.youtube.com/watch?v=TV6TIR9FUYU)
* 🏅 [View Credly Badge](https://www.credly.com/badges/633c4d09-42a9-41ef-b88e-64f053ceacb6/public_url)
* 💼 [LinkedIn Profile](https://www.linkedin.com/in/gviswavardhanreddy/)
* 🌐 [Portfolio Website](https://codebasics.io/portfolio/G-Viswavardhan-Reddy)

---
