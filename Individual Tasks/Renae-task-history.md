# Individual Work History & Weekly Detail for Sep–Oct
> **Submission deadline:** 2025-11-06 (Thu)  
> **Principle:** No confidential materials — **list 100% of deliverables/evidence/links**  
> **Filename:** `Renae_Nguyen_FullName_WorkHistory_v2024M1106.md`  
> **Week basis:** Monday–Sunday

---

## 1) Work History (Past → Present Summary)
| Period (YYYY-MM~) | Project/Work | Role | Summary of Contribution | Results (quant) | Deliverable Links (required) | Collaborators | Tech/Tools | Notes |
|---|---|---|---|---|---|---|---|---|
| 2025-08 ~ Present |NIMBUS OS  |Software engineer  |Performed board bring-up on RK3588-based NIMBUS device: Ethernet activation, Wi-Fi module replacement + driver validation, Wi-Fi AP onboarding with captive portal, fallback auto-recovery, USB OTG console, provisioning agent deployment  |  Wi-Fi onboarding success; Ethernet stable; provisioning upgrade path consistent;| https://github.com/botanika-blockify/wifi-captive-portal | MYiR Engineering team, internal OS team |Debian 12, Buildroot, hostapd, dnsmasq, systemd, configfs (USB gadget), rkdevtool  |  |

> Tips  
> - Include **numbers/metrics** (p95 latency, throughput, error rate, cost, etc.).  
> - List **all** verifiable links: PRs/commits/tickets/docs/dashboards/releases.

---

## 2) Weekly Log for Sep–Oct (copy this section per week)
### 2025-09 W1 (Sep 01–Sep 07)
- **Project/Work:**  Research for install RadxaOs on NIMBUS
- **Details (what/why/how):**  
    Flashed RadxaOS to NIMBUS board and performed UART-based system bring-up.
    Investigated missing drivers and device tree mismatches.
- **Deliverables/Evidence (required):**  
- **Hours (h):** 40 hours
- **Metrics/Results:**  Board boots reliably; baseline hardware survey completed.
- **Issues & Risks / Mitigation:**  RadxaOS base image lacks required hardware enablement
- **Next Actions (Owner / Due):**  Connect with Chinese Teams for rebuild OS by their tool

### 2025-09 W2 (Sep 08–Sep 14)
- **Project/Work:**  SDK Setup & Debian 12 Build Attempt
- **Details (what/why/how):**  
    Cloned RK3588 SDK
    Flashed via RKDevTool CLI (Linux).
- **Deliverables/Evidence (required):**  
- **Hours (h):** 40 hours
- **Metrics/Results:**  Build success; U-Boot entry: 100%; OS boot: 0% (stuck at "Starting kernel...").
- **Issues & Risks / Mitigation:** Device tree mismatch (EVB vs CM5)
- **Next Actions (Owner / Due):** Request Chinese team revised device tree

### 2025-09 W3 (Sep 15–Sep 21)
- **Project/Work:**  MYiR OS Bring-up
- **Details (what/why/how):**  
    Flashed `update_RK3588_RVB7_Debian11.rar`; used RKDevTool; captured logs; identified EVB7 ≠ CM5.
- **Deliverables/Evidence (required):**  
- **Hours (h):** 40 hours
- **Metrics/Results:** 7 flash attempts; load error.
- **Issues & Risks / Mitigation:** Board mismatch
- **Next Actions (Owner / Due):** Flash MYiR v1.0
- 
### 2025-09 W4 (Sep 22–Sep 28)
- **Project/Work:**  SDK Setup & Debian 12 Build Attempt
- **Details (what/why/how):**  
    Verified Ethernet link, DHCP, and Internet connectivity.
- **Deliverables/Evidence (required):**  
- **Hours (h):** 40 hours
- **Metrics/Results:** Ethernet 100% operational
- **Issues & Risks / Mitigation:**Wi-Fi chipset driver pending.
- **Next Actions (Owner / Due):** Begin Wi-Fi hardware validation.

### 2025-09 W5 (Sep 29–Sep 30) *optional*
- (same format)

### 2025-10 W1 (Oct 01–Oct 05)
- **Project/Work:**  SDK Setup & Debian 12 Build Attempt
- **Details (what/why/how):**  
    Confirmed Wi-Fi module replacement (AP6275P → EWN-8852BER3BB, chipset RTL8852BE).
    Verified Wi-Fi client mode connectivity and IP assignment.
- **Deliverables/Evidence (required):**  
- **Hours (h):** 40 hours
- **Metrics/Results:** 7 flash attempts; load error.
- **Issues & Risks / Mitigation:** Board mismatch
- **Next Actions (Owner / Due):** Flash MYiR v1.0
### 2025-10 W2 (Oct 06–Oct 12)
- **Project/Work:**  Wi-Fi Onboarding Design
- **Details (what/why/how):**  
    Defined Wi-Fi AP → Captive Portal → Credential Save → STA Mode → Fallback flow.
    Synced roadmap with MYiR for Debian 12 migration.
- **Deliverables/Evidence (required):**  
- **Hours (h):** 40 hours
- **Metrics/Results:**Onboarding design confirmed.
- **Next Actions (Owner / Due):** Implement AP mode and networking services.

### 2025-10 W3 (Oct 13–Oct 19)
- **Project/Work:**  System Service Stack
- **Details (what/why/how):**  
    Implemented network boot sequence with systemd.
    Ensured deterministic wlan0 naming.
- **Deliverables/Evidence (required):**  
- **Hours (h):** 40 hours
- **Metrics/Results:**  Reliable console and boot networking behavior.
- **Next Actions (Owner / Due):** Enable AP mode.

### 2025-10 W4 (Oct 20–Oct 26)
- **Project/Work:** Wi-Fi AP Mode Implementation
- **Details (what/why/how):**  
    Implemented Wi-Fi Access Point mode
    Configured AP interface and created hostapd config + systemd override for reliable startup.    
    Added dnsmasq for DHCP + DNS redirect and validated device connectivity.
- **Deliverables/Evidence (required):**  https://github.com/botanika-blockify/wifi-captive-portal
- **Hours (h):** 40 hours
- **Metrics/Results:**  Install successfully
- **Issues & Risks / Mitigation:**  Conflict system configurations
- **Next Actions (Owner / Due):**  Implement captive portal UI + redirect


### 2025-10 W5 (Oct 27–Oct 31) *optional*
- **Project/Work:**  Captive Portal + Fallback
- **Details (what/why/how):**  
    Enabled auto browser launch via DNS catch-all redirect
    Integrated captive portal setup page and enabled automatic browser pop-up via DNS catch-all + HTTP redirect.
    Added fallback logic: if STA connection fails → return to AP mode.
    Verified end-to-end onboarding flow: AP → portal → credential save → client mode → fallback.
    Install mining server to the board
- **Deliverables/Evidence (required):**  https://github.com/botanika-blockify/wifi-captive-portal
- **Hours (h):** 40 hours
- **Metrics/Results:** Wi-Fi onboarding is fully autonomous and user-facing.
- **Issues & Risks / Mitigation:** Tech detb - virtual wifi interface for better user expirience 
- **Next Actions (Owner / Due):**  Burn UUID through scanner; BLE, tempeture portal
---

## 3) Monthly Rollup (optional)
- **Sep total hours:**  
- **Oct total hours:**  
- **Top 3 outcomes:**  
- **Open issues & immediate actions:**
