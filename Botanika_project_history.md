# Project History & Weekly Detail (Project-Level)
> **Deadline:** 2025-11-06  
> **Filename:** PaymentsAPIv2_ProjectHistory_v20251106.md

## 0) Overview
- **Project:** Botanika
- **Owner/Lead:** Hieu Trung (Backend)  
- **Duration:** 2025-08 ~ 2025-11  
- **Goal/KPI:** p95 ≤ 300ms, 0 incidents/mo, +1.5pp success rate  
- **Scope:** Design and implement gRPC and REST APIs for communication between embedded software and the Botanika backend; develop mock APIs for client-side file handling related to PoSA, PoST, and PoEr processes; build a desktop application for scanning QR codes and burning UUIDs into miners. 
- **Key deliverables:** Functional gRPC communication module, stable API endpoints for embedded interaction, mock file storage APIs for PoSA/PoST/PoEr testing, and a working desktop QR scan app for UUID burning.

## 1) Participants & Responsibilities
| Name       | Role | Responsibility                                                      | Key Contribution (quant) | Evidence Links |
|------------|---|---------------------------------------------------------------------|---|---|
| Hieu Trung | Backend | gRPC service design, API implementation, desktop QR scan | Delivered full backend communication layer and mock API suite for PoSA/PoST/PoEr |  |
| Bee Nguyễn | Frontend Developer | React/Next.js development, UI/UX implementation, responsive design | Built 2 complete platforms; 100+ components; <2s load times | Local development repositories |

## 2) Weekly Log
### 2025-08 W1 (Aug 04–Aug 10)
- **Key work:** Project setup and architecture planning for Botanika ecosystem
- **Owners:** Bee Nguyễn
- **Deliverables/Evidence (required):** Initial Next.js project scaffolding, TypeScript configuration, Tailwind CSS setup
- **Team hours (h):** 32h
- **Metrics/Results:** 2 project repositories initialized with proper tooling
- **Dependencies & Risks / Mitigation:** Need design mockups / Created initial component library
- **Next Actions (Owner / Due):** Start admin dashboard development (Bee / Aug 17)


### 2025-08 W2 (Aug 11–Aug 17)
- **Key work:** Botanika Admin Dashboard foundation development
- **Owners:** Bee Nguyễn
- **Deliverables/Evidence (required):** Core dashboard components, authentication system, routing structure
- **Team hours (h):** 36h
- **Metrics/Results:** 20+ reusable components created, authentication flow implemented
- **Dependencies & Risks / Mitigation:** GraphQL schema definition needed / Mock data implementation
- **Next Actions (Owner / Due):** Complete admin user management (Bee / Aug 24)

### 2025-08 W3 (Aug 18–Aug 24)
- **Key work:** Admin user management and data tables implementation
- **Owners:** Bee Nguyễn
- **Deliverables/Evidence (required):** User management module, customer dashboard, data visualization components
- **Team hours (h):** 35h
- **Metrics/Results:** Complete CRUD operations, responsive table components, search/filter functionality
- **Dependencies & Risks / Mitigation:** API endpoints for user data / Implemented with mock data
- **Next Actions (Owner / Due):** Start marketing website development (Bee / Aug 31)

### 2025-08 W4 (Aug 25–Aug 31)
- **Key work:** Admin dashboard advanced features and data visualization
- **Owners:** Bee Nguyễn
- **Deliverables/Evidence (required):** Advanced admin features, data visualization components, reporting system
- **Team hours (h):** 38h
- **Metrics/Results:** Interactive charts with Chart.js, comprehensive reporting, mobile-responsive design
- **Dependencies & Risks / Mitigation:** Chart.js integration challenges / Implemented custom chart components
- **Next Actions (Owner / Due):** Marketing website development (Bee / Sep 7)

### 2025-09 W1 (Sep 01–Sep 07)
- **Key work:** Botanika marketing website architecture and hero section
- **Owners:** Bee Nguyễn
- **Deliverables/Evidence (required):** Marketing website foundation, hero section, navigation system
- **Team hours (h):** 32h
- **Metrics/Results:** Responsive hero section, smooth animations with Framer Motion
- **Dependencies & Risks / Mitigation:** Marketing content and assets / Used placeholder content
- **Next Actions (Owner / Due):** Complete marketing sections (Bee / Sep 14)


### 2025-09 W2 (Sep 08–Sep 14)
- **Key work:** Marketing website content sections and contact forms
- **Owners:** Bee Nguyễn
- **Deliverables/Evidence (required):** Services section, stats section, contact form with validation
- **Team hours (h):** 36h
- **Metrics/Results:** Interactive contact form, input validation, responsive grid layouts
- **Dependencies & Risks / Mitigation:** Email service integration / Implemented form handling
- **Next Actions (Owner / Due):** Cross-platform testing (Bee / Sep 21)

### 2025-09 W1 - W2 (Sep 01–Sep 12)
- **Key work:** 
  - Designed and implemented gRPC services for backend–embedded communication. 
  - Created REST APIs to handle client file operations simulating PoSA, PoST, and PoEr workflows.
  - Conducted integration tests between embedded software and backend services.
- **Owners:** Hieu Trung
- **Links:**
  - gRPC IP: 13.251.58.132:50051,
  - Simulate client-side PoSA/PoST/PoEr file uploads and fix bugs API [Commits link: bd8e5fc, aa7ba0d, ...., 4703b3b](https://github.com/botanika-blockify/botanika-core/commits?author=trunghph)
- **Team hours (h):** 32
- **Results:** gRPC services and backend APIs have been successfully implemented and are nearly complete in testing.
- **Dependencies & Risks / Mitigation:**  Documentation inconsistencies.

### 2025-10 W3 (Oct 13–Oct 17)
- **Key work:** 
  - Incident reproduction and alert threshold tuning for backend monitoring.
- **Owners:** Hieu Trung
- **Links:** 
    - Testing PoSA/PoST/PoEr and fix bugs API [Commits link](https://github.com/botanika-blockify/botanika-core/commit/e7ea279f2032ba203a5600f9323a450883b79700)
- **Team hours (h):**  20
- **Results:** Several bugs resolved; API performance and code structure optimized for cleaner implementation.
- **Dependencies & Risks / Mitigation:** No major issues encountered.

### 2025-09 W4 (Sep 22–Sep 28)
- **Key work:** Advanced dashboard features and data visualization
- **Owners:** Bee Nguyễn
- **Deliverables/Evidence (required):** Advanced charts, data export functionality, dashboard customization
- **Team hours (h):** 35h
- **Metrics/Results:** Interactive dashboard with Highcharts, CSV export, customizable widgets
- **Dependencies & Risks / Mitigation:** Real-time data requirements / Implemented with mock data
- **Next Actions (Owner / Due):** Admin portal enhancements (Bee / Oct 5)

### 2025-10 W4 (Oct 20–Oct 26)
- **Key work:** Cross-platform integration testing and bug fixes
- **Owners:** Bee Nguyễn
- **Deliverables/Evidence (required):** Integration test results, bug fix documentation, performance benchmarks
- **Team hours (h):** 30h
- **Metrics/Results:** 95% test coverage, resolved 8 critical bugs, optimized performance by 25%
- **Dependencies & Risks / Mitigation:** QA testing resources / Self-testing with comprehensive checklist
- **Next Actions (Owner / Due):** Final deployment preparation (Bee / Nov 2)

### 2025-11 W1 (Nov 3 – Nov 6)
- **Key work:**
    - Developed a simple desktop application to scan QR codes and burn UUIDs into miner devices.
- **Owners:** Hieu Trung
- **Links:**
  - Desktop app [Commits](https://github.com/botanika-blockify/botanika-factory/commits/staging/)
- **Team hours (h):** 25
- **Metrics:** The desktop QR scanning application for UUID burning is currently under testing.
- **Dependencies & Risks / Mitigation:** 
  - Lack of documentation for this feature required additional research and troubleshooting time.
  - The miner’s OS currently does not support data transmission via Type-C, creating a dependency for full feature validation.