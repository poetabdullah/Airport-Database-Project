# 🛫 Airport Database Management System

> *A robust, SQL-powered system to streamline passenger, flight, baggage, and airport operations with integrated security and maintenance tracking.*

---

## 📖 Overview

This project presents a **comprehensive Airport Management System** built with:

* 🗄️ **Microsoft SQL Server Management Studio (SSMS 19)** → Database design & management
* ⚙️ **Django Framework** → Simple Backend integration
* 💻 **Visual Studio Code** → Frontend development

The system covers **passenger management, flight schedules, baggage tracking, security protocols, fueling, maintenance, and resource allocation** — providing a **full-scale airport operations solution**.

---

## 🏗️ Project Foundation

### 1️⃣ Choosing the Topic

After exploring CRM, HR, and E-Commerce, the team chose **Airport Management** due to its **complexity, real-world relevance, and extensive learning opportunities**.

### 2️⃣ Database Software

* Chosen DBMS: **SQL Server Management Studio (SSMS 19)**
* Reasons: Seamless integration with VS Code, advanced security, team familiarity

### 3️⃣ Backend Integration

* **Django Framework** → Selected for simplicity, reliability, and SSMS compatibility

---

## 🧩 Database Design

### 🔹 Entities

* 👤 **Passenger** → personal info & linked tickets
* ✈️ **Flight** → schedules & details
* 🏢 **Airport** → airport-specific info
* 🎟️ **Ticket** → pricing & type
* 🏷️ **Airline** → airline data
* 🛡️ **Security** → personnel & zones
* 👨‍✈️ **Pilot** → qualifications & flight assignments
* 📡 **Traffic Control** → towers & controllers
* 🧳 **Luggage** → passenger baggage info
* ⛽ **Fueling Station** → station data & capacity
* 🛣️ **Runway** → availability & usage

### 🔹 Relationships

* Passenger ↔ Ticket → 1\:M
* Flight ↔ Airport → 1\:M
* Ticket ↔ Flight → M:1
* Flight ↔ Airline → M:1
* Pilot ↔ Flight → M\:M
* Passenger ↔ Luggage → 1\:M

### 🔹 Visuals

* 📊 **ERD** → Entity relationships
* 🗂️ **Relational Schema** → Table structure
* 📏 **Normalization** → Reduced redundancy, optimized schema

---

## 🔐 Authorization & Roles

Defined **4 user roles** with specific privileges:

* 👨‍💻 **Admin**
* 👔 **Airport Staff**
* 🛡️ **Security Personnel**
* 🧳 **Passengers**

---

## 🛠️ Core Features

### 📋 Views & Joins

* Passenger View → passenger, luggage & tickets
* Pilot View → pilot + flights
* Runway View → runway usage
* Flight View → daily flight count
* Fueling View → station data

### ⚡ Stored Procedures

* Luggage weight check & ticket price adjustment
* Security area updates
* Passenger detail reports
* Flight booking summaries
* Lighting system checks

### 🚨 Triggers

* Ticket availability checks
* Ticket upgrades
* Flight delay notifications
* Luggage overweight alerts
* Fuel monitoring

### 📈 Indexing

* Clustered → primary keys
* Non-clustered → departure times, ticket prices, fueling stations, pilot experience

---

## 💾 Backup & Recovery

* 🔄 **Full Backups** → Weekly, dual locations
* 📂 **Differential Backups** → Every 2 days
* 📜 **Transactional Logs** → Daily, continuous protection
* 🛠️ **Recovery Plans** → Full, differential, transaction log restores for minimal downtime

---

## 🎯 Objectives

* Efficiently manage **passenger info, flights, security, baggage, and maintenance**
* Provide **integrity, security, and optimized performance**
* Enable **real-world scalability** for large airports

---

## 🌍 Scope

Covers all **airport operations**:
✔ Passenger management
✔ Flight tracking & pilot assignment
✔ Security enforcement
✔ Baggage tracking
✔ Resource allocation (fuel, runways, staff)
✔ Maintenance scheduling

---

## 🔎 Performance & Validation

* ✅ **Relationship Checks** → Subqueries for referential integrity
* ❌ **Foreign Key Violation Checks**
* 🧩 **Logical Error Checks** → Data consistency
* 🔒 **Integrity Validation** → Ensured across entities

---

## 👥 Contributors

* **Abdullah Imran** → [@poetabdullah](https://github.com/poetabdullah)
* **Ambreen** → [@AmbreenAmbi04](https://github.com/AmbreenAmbi04)

---

## 📬 Inquiries

For questions or collaboration, feel free to reach out!

---

🔥 This system demonstrates how **SQL + Django + structured database design** can power **complex, mission-critical airport operations**.
