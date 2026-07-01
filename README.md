# AquaLink Salone: Digital Public Good for Water Safety

![AquaLink Salone Banner](https://private-us-east-1.manuscdn.com/sessionFile/6fmIrNSCktmiXP1wEnPawI/sandbox/ZNOXHERZEwsBKnPPJ809ec-images_1782909675348_na1fn_L2hvbWUvdWJ1bnR1L2FxdWFsaW5rX3NhbG9uZV9iYW5uZXI.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvNmZtSXJOU0NrdG1pWFAxd0VuUGF3SS9zYW5kYm94L1pOT1hIRVJaRXdzQktuUFBKODA5ZWMtaW1hZ2VzXzE3ODI5MDk2NzUzNDhfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwyRnhkV0ZzYVc1clgzTmhiRzl1WlY5aVlXNXVaWEkucG5nIiwiQ29uZGl0aW9uIjp7IkRhdGVMZXNzVGhhbiI6eyJBV1M6RXBvY2hUaW1lIjoxODMwMjk3NjAwfX19XX0_&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=nGZN--0lC9~cdT2Y-lR1sY0dD5NykQwyKchTdaf9HalX1imvL82OzJdt1fpajrBSFClQTL2uEasqvR7E9UJxNlYCcnDWK6I~03BQVLewL4x3bM7TPJfi4LsFcY~xSCAchcfmsTJF7uq-42bNqGYTayNnx5LB5Ckjka5yAiUK3risXxON91kXvu5XvIDuiOXO~AKxSiHAdm-vVuKcHZgkFxwQdF7mErZt1OEb~LiNFvLOxYqKAFKaY0bl9ttcXoLCXVR1LeqH2enGs9vEq710t3p9~9M1TEQoQyzlqR9arh0LoQZjgaCT4BROqG28SUkduK2Yz13cuJwGCAU3Z2Zfqw__)

## 🌊 Overview
**AquaLink Salone** is an open-source, community-first reporting platform designed to improve access to safe public water in Sierra Leone. As a **Digital Public Good (DPG)**, it provides a reusable software framework for residents to report water safety issues, enables volunteers to verify field data, and supports local officers in coordinating repairs.

The project aligns with the United Nations **Sustainable Development Goal 6 (Clean Water and Sanitation)**, turning water safety challenges into visible, trackable cases with public accountability.

---

## ✨ Key Features
- 📱 **Mobile Reporting:** Easy-to-use interface for residents to report broken pumps or unsafe water.
- 🗺️ **GIS Mapping:** Real-time visualization of water points with color-coded status indicators.
- 🛡️ **Volunteer Verification:** Field verification system with photo evidence and GPS confirmation.
- 📊 **Admin Dashboard:** Centralized workspace for water officers to prioritize repairs and monitor trends.
- 🔔 **SMS Alerts:** Low-bandwidth notifications for community-wide water safety updates.
- 📈 **Open Data:** Publicly accessible water safety analytics to ensure transparency and accountability.

---

## 🏗️ System Architecture
The system follows a **layered architecture** for scalability and maintenance:
- **Presentation Layer:** Mobile App (React Native), Volunteer Tablet View, and Admin Web Dashboard.
- **API Gateway:** Secure routing, authentication, and traffic management.
- **Service Layer:** Modules for reporting, repair workflows, analytics, and GIS services.
- **Data Layer:** PostgreSQL with PostGIS for spatial data storage.
- **Integrations:** SMS Gateways and Open Data publishing services.

---

## 📂 Repository Structure
```text
aqualink-salone-dpg/
├── report/           # Final project report (PDF/DOCX)
├── diagrams/         # UML diagrams (Use Case, Class, Sequence)
├── prototype/        # UI/UX design assets and Figma screens
├── docs/             # Technical documentation and SDG alignment
├── src/              # Source code for API, Mobile, and Web (Placeholder)
├── tests/            # Test cases and quality assurance logs
├── LICENSE           # MIT License
└── README.md         # Project overview and guide
```

---

## 🚀 Getting Started
### Prerequisites
- Node.js (v18+)
- PostgreSQL with PostGIS extension
- Docker (optional for containerized deployment)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/aqualink-salone-dpg.git
   ```
2. Navigate to the project directory:
   ```bash
   cd aqualink-salone-dpg
   ```
3. (Future) Install dependencies and start services:
   ```bash
   # Development steps will be added here
   ```

---

## 🎯 SDG Alignment
- **SDG 6:** Ensuring availability and sustainable management of water and sanitation for all.
- **SDG 3:** Reducing water-related health risks through proactive reporting.
- **SDG 11:** Strengthening community resilience via better infrastructure maintenance.

---

## 📜 License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 🤝 Acknowledgments
- Developed as part of **PROG 102 - Principles of Software Engineering**.
- Examiner: **Santigie Foday Kamara**.
- Inspired by the need for Digital Public Goods in community infrastructure.

---
*Connecting communities. Safeguarding our water. Building a resilient Sierra Leone.*
