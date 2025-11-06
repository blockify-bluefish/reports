# Individual Work History & Weekly Detail for Sep–Oct
> **Submission deadline:** 2025-11-06 (Thu)  
> **Principle:** No confidential materials — **list 100% of deliverables/evidence/links**  
> **Filename:** `Team_Name_FullName_WorkHistory_vYYYYMMDD.md` (e.g., `R&D_JohnDoe_WorkHistory_v20251106.md`)  
> **Week basis:** Monday–Sunday

---

## 1) Work History (Past → Present Summary)
| Period (YYYY-MM~) | Project/Work | Role    | Summary of Contribution                                                                                                                                                                                                   | Results (quant)                                                                                                                                                                        | Deliverable Links (required)                                                                                    | Collaborators                      | Tech/Tools                                                  | Notes |
|-------------------|--------------|---------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|------------------------------------|-------------------------------------------------------------|-------|
| 2025-08 ~ 2025-11 | Botanika     | Backend | Deployed website and backend API for staging. Designed gRPC and REST APIs for embedded-backend comms; Built REST APIs to simulate client-side PoSA/PoST/PoEr file uploads; developed desktop app to scan QR for burn UUID | gRPC services and backend APIs have been successfully implemented and are nearly complete in testing. The desktop QR scanning application for UUID burning is currently under testing. | https://admin-botanika.blockifyy.com/, https://miner-botanika.blockifyy.com/, https://botanika.blockifyy.com/   | 2×FE, embedded team, hardware team | NodeJs, MongoDB, Grpc, Docker |       |
| 2025-08 ~ 2025-11 | Belpy NFT    | Backend | Set up Candy Machine, developed API & admin panel, deployed production site, tested NFT minting                                                                                                                           | Go live 10/10/2025                                                                                                                                                                     | https://belpy.xyz/ and contract address https://solscan.io/account/FqSAi6Uda8ri9zV1RBfq25GdfPdeKb24yHqvSgsi83Z4 | 2×FE                               | NodeJs, MongoDB, Docker, Candy machine, metaplex-foundation |       |
| 2025-09 ~ 2025-11 | Redsea       | Backend | Deployment setup and API testing using Postman                                                                                                                                                                            | All backend APIs are now fully functional and ready for frontend integration.                                                                                                          | http://redsea-api.blockifyy.com/                                                                                | 1×FE                               | Postman, Docker                                             |       |

> Tips  
> - Include **numbers/metrics** (p95 latency, throughput, error rate, cost, etc.).  
> - List **all** verifiable links: PRs/commits/tickets/docs/dashboards/releases.

---

## 2) Weekly Log for Sep–Oct (copy this section per week)
### 2025-09 W1–W2 (Sep 01–Sep 12)
- **Project/Work: Botanika
- **Details (what/why/how):** 
  - Designed and implemented gRPC services between embedded software and backend.
  - Built REST APIs to simulate client-side PoSA/PoST/PoEr file uploads.
  - Performed initial integration testing with embedded team.
- **Deliverables/Evidence (required):** 
  - gRPC IP: 13.251.58.132:50051,  
  - Simulate client-side PoSA/PoST/PoEr file uploads and fix bugs API [Commits link: bd8e5fc, aa7ba0d, ...., 4703b3b](https://github.com/botanika-blockify/botanika-core/commits?author=trunghph)
- **Hours (h):** 32
- **Metrics/Results:** gRPC services and backend APIs have been successfully implemented and are nearly complete in testing.
- **Issues & Risks / Mitigation:** Documentation inconsistencies between modules caused delays in API alignment.
- **Next Actions (Owner / Due):** Continue monitoring logs and optimize the code for stability and performance.

### 2025-09 W3-W4 (Sep 15–Sep 26)
- **Project/Work: Belpy NFT
- **Details (what/why/how):** 
  - Setup Candy Machine and configured NFT minting pipeline.
  - Deployed website and backend API for staging.
- **Deliverables/Evidence (required):** Website testing, API integration successful.
  - https://belpy.blockifyy.com
  - Some wallets for testing: 
    - https://solscan.io/account/BQKHinECp1JgTi4kvi3uR6fWVP6gFCq4YSch7yJGuBKX?cluster=devnet 
    - https://solscan.io/account/Fz4SxAPAbG3PprY47vzdYCWqhesntLKP8q3q8zvjwrtR?cluster=devnet 
    - https://solscan.io/account/Fz4SxAPAbG3PprY47vzdYCWqhesntLKP8q3q8zvjwrtR?cluster=devnet
  - Setup Candy Machine and APIs [API commits](https://github.com/belp-nft/belp-contract/commits?author=trunghph)
- **Hours (h):** 24
- **Metrics/Results:** NFT mint success in staging.
- **Issues & Risks / Mitigation:** Delays due to on-chain transaction retries.
- **Next Actions (Owner / Due):** Prepare for mainnet go-live (Oct W2).

### 2025-09 W5 (Sep 29–Sep 30)
- **Project/Work: Redsea
- **Details (what/why/how):** 
  - Deployed Redsea backend and frontend environments.
  - Conducted manual Postman testing to validate all API endpoints.
  - Fixed missing DB columns caused by migration mismatch.
- **Deliverables/Evidence (required):**
  - http://redsea-api.blockifyy.com/
  - Setup source and deploy [Commits](https://github.com/blockify-redsea/redsea_server/commits?author=trunghph)
- **Hours (h):** 12
- **Metrics/Results:**  All backend APIs are now fully functional and ready for frontend integration.
- **Issues & Risks / Mitigation:** DB mismatch fixed by schema update.
- **Next Actions (Owner / Due):** Waiting for testing

### 2025-10 W1-W2 (Oct 06–Oct 10)
- **Project/Work: Belpy NFT
- **Details (what/why/how):** 
  - Tested full minting process on mainnet.
  - Validated Candy Machine configuration and transaction flow.
  - Go-live on 10/10/2025.
- **Deliverables/Evidence (required):**
  - https://belpy.xyz/
  - Wallets mainnet: https://solscan.io/account/9s3R5QoBNQvTh7Vt7g4ZksdKjrQp4i5aMCD23LhTPWAW
- **Hours (h):** 30
- **Metrics/Results:** Go live success
- **Issues & Risks / Mitigation:** Testing and verification were repeated across multiple wallets to ensure stable minting performance and correct NFT generation.
- **Next Actions (Owner / Due):** Prepare simple Admin 

### 2025-10 W3 (Oct 13–Oct 17)
- **Project/Work: Botanika
- **Details (what/why/how):**
  - Incident reproduction and alert threshold tuning for backend monitoring.
- **Deliverables/Evidence (required):**
  - Testing PoSA/PoST/PoEr and fix bugs API [Commits link](https://github.com/botanika-blockify/botanika-core/commit/e7ea279f2032ba203a5600f9323a450883b79700)
- **Hours (h):** 20
- **Metrics/Results:** Several bugs resolved; API performance and code structure optimized for cleaner implementation.
- **Issues & Risks / Mitigation:** No major issues encountered.
- **Next Actions (Owner / Due):** Continue monitoring API logs and prepare for further performance tuning.

### 2025-10 W4 (Oct 20–Oct 31)
- **Project/Work: Belpy NFT
- **Details (what/why/how):**
    - Deployed admin website for NFT management.
    - Implemented admin UI for NFT conversion and Candy Machine reconfiguration.
- **Deliverables/Evidence (required):**
  - https://admin.belpy.xyz/
  - Some commits setup APIs and update UI: 
    - UI[Commits: 9215ea3, 3a023353, 8efaf6e, 42868c5](https://github.com/belp-nft/belp-admin/commits/prod) 
    - APIs[Commits](https://github.com/belp-nft/belp-contract/commit/9370abc64a0f96ea8dc4e38a73689646ea6babb9) 
- **Hours (h):** 30
- **Metrics/Results:** All tasks completed; Belpy NFT Results tested successfully.
- **Issues & Risks / Mitigation:** No major issues encountered.
- **Next Actions (Owner / Due):** Ready for next mint or delivery.

### 2025-11 W1 (Nov 03–Nov 06)
- **Project/Work: Botanika
- **Details (what/why/how):**
    - Developed a simple desktop app to scan QR codes and burn UUIDs into miners.
- **Deliverables/Evidence (required):**
  - Desktop app [Commits](https://github.com/botanika-blockify/botanika-factory/commits/staging/)
- **Hours (h):** 25
- **Metrics/Results:** The desktop QR scanning application for UUID burning is currently under testing.
- **Issues & Risks / Mitigation:** 
  - Lack of documentation for this feature required additional research and troubleshooting time.
  - The miner’s OS currently does not support data transmission via Type-C, creating a dependency for full feature validation.
- **Next Actions (Owner / Due):** 
  - Update the miner OS to enable Type-C data transmission and re-test the desktop application after the update.