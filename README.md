🏫 Campus Access AI

AI-Powered Smart Campus Access and Monitoring System

A smart campus security and access management prototype that combines **QR-based identity verification, category-based access control, CCTV person detection, and user status management**.

🎯 Problem

Managing access to a large campus can be difficult when students, employees, faculty, workers, and visitors have different access permissions.

Traditional ID-card systems may not provide real-time verification or easily handle changes such as graduation, expiry, or account deactivation.

💡 Our Solution

Campus Access AI provides a centralized system where campus users can be registered, assigned a unique QR code, verified during entry, and granted or denied access based on their category and current status.

The system also provides a CCTV monitoring prototype using AI-based person detection.

✨ Key Features

- 👤 Student and employee registration
- 📱 Unique QR code generation
- 🔍 QR-based identity verification
- 🔐 Category-based access permissions
- 🟢 Active / inactive / expired status
- 📹 AI-based CCTV person detection
- 👥 Real-time person counting
- 📊 Admin monitoring dashboard
- 🚫 Deactivation of expired or graduated users

## 🔄 Main Workflow

```text
User Registration
       ↓
Unique QR Code Generated
       ↓
QR Code Scanned
       ↓
Identity Retrieved
       ↓
Category & Status Verified
       ↓
┌───────────────────────┐
│                       │
ACTIVE              INACTIVE
│                       │
↓                       ↓
ACCESS GRANTED      ACCESS DENIED
```

📹 CCTV Monitoring

The system uses computer vision to detect people from a CCTV feed or sample video.

The prototype displays:

- Number of people detected
- Detection bounding boxes
- CCTV monitoring status

🧑‍💻 Technology Stack

- Python
- SQLite
- OpenCV
- YOLO
- QR Code
- Streamlit
- REST API
- HTML/CSS/JavaScript (if required)

🗃️ Identity Categories

The prototype supports different campus identities such as:

- Student
- Faculty
- Employee
- Food Outlet Worker
- Visitor

🔐 Access Status

Each registered user can have a status such as:

- `ACTIVE`
- `INACTIVE`
- `EXPIRED`

Access is granted only when the user's identity and status satisfy the required permission rules.

🚀 Prototype Goal

The main demonstration will show an end-to-end campus access workflow:

> Register a student → Generate QR → Scan QR → Verify identity → Grant access → Change student status → Scan again → Deny access.

The CCTV module will demonstrate AI-based person detection alongside the access management system.

⚠️ Hackathon Prototype

This project is being developed as a rapid hackathon prototype.

Where real campus infrastructure or live CCTV feeds are unavailable, sample data and sample video footage may be used for demonstration purposes.

👥 Team

Hackathon Team – GDG DevCampus 2026

📌 Project Status

🚧 **Currently under development**

---

Built for GDG DevCampus 2026 🚀
