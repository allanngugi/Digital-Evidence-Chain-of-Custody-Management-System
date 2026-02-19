# 🔎 Digital Evidence Chain of Custody Management System (DECCMS)

## 📌 Overview
The Digital Evidence Chain of Custody Management System (DECCMS) is a secure web-based application designed to track, manage, and preserve the integrity of digital evidence throughout investigative processes.

The system addresses challenges faced by law enforcement and investigative bodies where evidence may be rejected due to broken or poorly documented chains of custody. Traditional paper-based tracking methods are prone to tampering, loss, and human error. This project provides a digital alternative that ensures accountability, traceability, and forensic reliability.

The system was developed using a structured Software Development Life Cycle (SDLC) approach to design a secure and scalable prototype suitable for real-world investigative environments.

---

## 🎯 Project Objectives
- Digitize chain-of-custody management processes
- Preserve integrity and authenticity of digital evidence
- Reduce risks of evidence tampering and human error
- Provide transparent and traceable audit trails
- Improve efficiency of evidence tracking and retrieval

---

## 🧰 Technologies Used
- **Node.js** – Backend application logic
- **MongoDB** – Database storage
- **HTML5 & CSS3** – Frontend interface
- **Web Application Architecture**
- **Cryptographic Hashing Techniques**

---

## ⚙️ Key Features
- Automated evidence logging
- Role-based access control (RBAC)
- Digital signature capture during evidence transfer
- Timestamped audit trails
- Secure evidence history tracking
- Automated custody event recording
- Fast evidence retrieval compared to manual systems

---

## 🔐 Cybersecurity & Digital Forensics Concepts
This project demonstrates practical cybersecurity and forensic principles:

- Chain of custody preservation
- Evidence integrity verification using cryptographic hashing
- Tamper detection through hash-linked records
- Access control and accountability
- Secure audit logging
- Digital forensic documentation practices

---

## 🏗️ System Architecture
The system follows a web-based architecture:

- **Frontend:** HTML5/CSS3 user interface
- **Backend:** Node.js server handling application logic
- **Database:** MongoDB storing custody records

Each custody record contains a cryptographic hash referencing the previous record, forming a linked structure that prevents unauthorized modification and ensures forensic integrity.

---

## 🔄 System Workflow
1. Evidence is registered into the system.
2. Custodian details are recorded.
3. Evidence transfers require authentication and digital confirmation.
4. Each transaction generates a timestamped audit entry.
5. Records are cryptographically linked to prevent tampering.
6. Investigators can retrieve complete custody history instantly.

---

## 📸 Screenshots

### Login
![Login](screenshots/login-page.png)

### Admin Dashboard
![Admin Dashboard](screenshots/admin-dashboard.png)

### Officer Dashboard
![Officer Dashboard](screenshots/officer-dashboard.png)

### Analyst Dashboard
![Analyst](screenshots/analyst-dashboard.png)

### Court Presentation
![Court Presentation](screenshots/court-presentation-dashboard.png)

### MongoDB Collection
![MongoDB Collection](screenshots/mongodb-collections.png)

### MongoDB Performance Metrics
![MongoDB Performance Metrics](screenshots/mongodb-performance-metrics.png)



## 📚 Documentation
Full academic project documentation is available here:

- [Final Project Report](docs/DECCMS_FINAL_DOCUMENTATION.pdf)

---

## 💻 Source Code
The full implementation is available in the `source-code` directory:

👉 [View Source Code](source-code/)

---

## 👥 Project Team
Developed as part of the Applied Information Technology program at
United States International University – Africa (USIU-A)
Team:
1. Allan Njuguna Ngugi
2. Jeremy Kamangara
3. Garnet Githinji

Supervisor:
Dr. Stanley Githinji, PhD

## 👤 Author Portfolio
Allan Njuguna Ngugi
Cybersecurity & Digital Forensics Enthusiast

## 📜 License

This project is released for educational and academic purposes.


