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

## 2) Weekly Log
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