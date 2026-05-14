# 🎓 StudyLink — Peer Tutoring Ecosystem

![Project Status](https://img.shields.io/badge/Status-Academic_Project-blue)
![C#](https://img.shields.io/badge/Language-C%23-purple)
![WPF](https://img.shields.io/badge/Framework-WPF-blueviolet)
![MySQL](https://img.shields.io/badge/Database-MySQL-orange)

> **Bridging the academic gap through a secure, peer-to-peer knowledge exchange platform.**

---

## 📑 1. Thorough Project Analysis

### 1. Problem Statement
**Target Segment:** 1st and 2nd-year university students facing academic or financial challenges.
**The Problem:** Professional tutoring is prohibitively expensive, leading to increased stress and higher dropout rates. Simultaneously, high-achieving upper-year students often lack opportunities to monetize their academic expertise in a relevant field.

### 2. Value Proposition (The Solution)
StudyLink bridges this gap by providing an accessible marketplace for:
* **Peer-to-Peer Learning:** Connecting students directly to reduce costs.
* **Accountability:** Transparent review and rating systems.
* **Security:** A closed ecosystem where all interactions, bookings, and simulated payments are tracked.

### 3. Societal Impact
* **Positive:** Promotes educational equity and social mobility by leveling the playing field for mid-to-low income students.
* **Risk Mitigation:** To combat inconsistent tutoring quality, we implement a robust **Review & Rating System** monitored by Administrators.


### 4.In-Depth Analysis
Unlike generic scheduling apps, StudyLink implements a **Safe-Learning Environment**. This is achieved through:
* **Accountability:** A robust review and rating system that ensures quality control.
* **Administrative Oversight:** A unique **Jury System** that allows administrators to monitor and resolve disputes between students and tutors.
* **Data Integrity:** A normalized relational database structure that ensures every booking, payment simulation, and review is traceable and secure.

---

## 🛡️ 2. Core Features

### 👨‍🎓 For Students
*   **Smart Search:** Locate tutors instantly by course code or subject.
*   **Verified Profiles:** View tutor expertise, ratings, and transparent hourly rates.
*   **Booking System:** Schedule sessions and track history with ease.

### 👩‍🏫 For Tutors
*   **Profile Management:** Customize bio, set rates, and showcase academic expertise.
*   **Availability Management:** Dedicated calendar slots for dynamic scheduling.
*   **Reputation System:** Build trust through verified peer reviews and ratings.

### 🛡️ For Administrators
*   **User Oversight:** Full management of accounts and tutor approval workflows.
*   **Dispute Resolution:** Handle "Jury Cases" to maintain high tutoring standards.
*   **System Analytics:** Access platform statistics and security logs.

---

## 📊 3. Diagrams

### ERD (Entity Relationship Diagram)
<img width="653" height="953" alt="erd" src="https://github.com/user-attachments/assets/d7a57945-bf97-4fe5-a731-874f66d71d9a" />

### UML (Unified Modeling Language)
<img width="1115" height="2024" alt="uml" src="https://github.com/user-attachments/assets/5f73ef93-d45b-453c-95bf-4470abc5147a" />




---

## 🖥️ 4. Wireframes (Screen-by-Screen Depiction)

StudyLink follows a clean, intuitive UI flow designed for students.

1.  **Login/Register Window:** The entry point featuring secure credential verification and password recovery.
2.  **Dashboard (Student View):** A searchable marketplace where students filter tutors by **Course Code** or **Subject**.
3.  **Tutor Profile View:** A detailed breakdown of a tutor's bio, hourly rate, subjects, and past student reviews.
4.  **Booking Popup:** A focused window to select dates/times, featuring the **Live Price Calculator**.
5.  **Payment Simulation:** A transparent confirmation screen showing the total cost and balance deduction.
6.  **Admin Panel:** A specialized high-level dashboard for user management, tutor approvals, and managing jury cases.

---

## 🏗 Tech Stack & Requirements

* **Language:** C#
* **UI Framework:** WPF (.NET 10.0+)
* **Database:** MySQL 8.0
* **ORM:** Raw SQL with MySqlConnector for high performance.
* **Security:** SHA256 Hashing.

---

## 👥 Authors & Credits
* **Ihsan Hamdi Mercan**
* **Mehmet Erdemli**
* *Thomas More University — Inspiration Lab Project (OOP)*
