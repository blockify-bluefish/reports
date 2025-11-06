# Project History & Weekly Detail for Sep–Oct (Project-Level)
> **Submission deadline:** 2025-11-06 (Thu)  
> **Filename:** `NimbusOS_ProjectHistory_v20251106.md`  
> **Week basis:** Monday–Sunday

---

## 0) Project Overview
- **Project name:** NimbusOS  
- **Owner/Lead:** Jack Le  
- **Duration (YYYY-MM ~ YYYY-MM):** 2025-08 ~ Present

- **Goal / Success Criteria (KPI):**  
  - Enable Ethernet + Wi-Fi STA/AP  
  - Implement captive portal onboarding + fallback AP recovery  
  - Provide provisioning + firmware backup workflows  
  - Fan / Temperature / BLE console portal  
  - UUID scanner + burn workflow integration

- **In-scope:**  
  - OS bring-up on RK3588 CM5  
  - Wi-Fi module driver enablement (RTL8852BE)  
  - Captive portal onboarding logic  
  - Provisioning directory & UUID scanner workflow

- **Out-of-scope:**  
  - USB OTG console enablement

- **Key deliverables:**  
  - Wi-Fi Captive Portal: https://github.com/botanika-blockify/wifi-captive-portal  
  - Systemd networking orchestration files  
  - Firmware imaging & recovery documentation  
  - Scanner integration

---

## 1) Participants & Responsibilities
| Name | Role | Responsibility | Key Contribution (quant) | Evidence Links |
|---|---|---|---|---|
| **Renae Nguyen** | Engineer | OS bring-up, Wi-Fi onboarding, captive portal, provisioning stack, UUID scanner | Wi-Fi onboarding success rate 100% with automatic fallback; UUID scanner integrated end-to-end | https://github.com/botanika-blockify/wifi-captive-portal |

---

## 2) Weekly Log for Sep–Oct

### 2025-09 W1 (Sep 01–Sep 07)
- **Key work:** Initial OS bring-up (RadxaOS) on NIMBUS  
- **Owners:** Renae  
- **Deliverables/Evidence:** UART boot logs  
- **Team hours:** ~40h  
- **Metrics/Results:** Board boots; device tree incomplete  
- **Dependencies & Risks / Mitigation:** Missing board-specific drivers → need vendor build  
- **Next Actions:** Request MYiR board-specific OS images

### 2025-09 W2 (Sep 08–Sep 14)
- **Key work:** SDK & Buildroot evaluation  
- **Owners:** Renae  
- **Deliverables/Evidence:** Kernel hang capture logs  
- **Team hours:** ~40h  
- **Metrics/Results:** Identified EVB vs CM5 device tree mismatch  
- **Dependencies & Risks / Mitigation:** Requires correct base image from China 
- **Next Actions:** Wait for MYiR v1.0 release

### 2025-09 W3 (Sep 15–Sep 21)
- **Key work:** Flash & validate MYiR v1.0 OS  
- **Owners:** Renae  
- **Deliverables/Evidence:** `dmesg`, `lsmod`, boot screenshots  
- **Team hours:** ~40h  
- **Metrics/Results:** System stable; Wi-Fi interface missing  
- **Dependencies & Risks / Mitigation:** RTL8852BE driver pending  
- **Next Actions:** Ethernet subsystem verification

### 2025-09 W4 (Sep 22–Sep 28)
- **Key work:** Ethernet bring-up & stability testing  
- **Owners:** Renae  
- **Deliverables/Evidence:** Ping & DHCP lease logs  
- **Team hours:** ~40h  
- **Metrics/Results:** Ethernet stable (100% link uptime)  
- **Dependencies & Risks / Mitigation:** Wi-Fi unavailable until driver merged  
- **Next Actions:** Verify Wi-Fi hardware replacement compatibility

### 2025-09 W5 (Sep 29–Sep 30) *optional*
- **Key work:** Wi-Fi hardware compatibility validation  
- **Owners:** Renae  
- **Deliverables/Evidence:** Module datasheet comparison notes  
- **Team hours:** ~16h  
- **Metrics/Results:** AP6275P → EWN-8852BER3BB (RTL8852BE) confirmed compatible  
- **Dependencies & Risks / Mitigation:** Driver release controlled by MYiR  
- **Next Actions:** Wi-Fi STA mode testing

---

### 2025-10 W1 (Oct 01–Oct 05)
- **Key work:** Wi-Fi STA mode bring-up  
- **Owners:** Renae  
- **Deliverables/Evidence:** Network connection test logs  
- **Team hours:** ~40h  
- **Metrics/Results:** Wi-Fi client mode operational  
- **Dependencies & Risks / Mitigation:** None  
- **Next Actions:** Define captive portal onboarding flow

### 2025-10 W2 (Oct 06–Oct 12)
- **Key work:** Captive portal onboarding workflow design  
- **Owners:** Renae  
- **Deliverables/Evidence:** Flow diagram + configuration plan  
- **Team hours:** ~40h  
- **Metrics/Results:** Onboarding workflow approved  
- **Dependencies & Risks / Mitigation:** Must consider Debian 12 migration timeline  
- **Next Actions:** Implement AP mode + portal service stack

### 2025-10 W3 (Oct 13–Oct 19)
- **Key work:** Systemd service orchestration for Wi-Fi + portal  
- **Owners:** Renae  
- **Deliverables/Evidence:** `hostapd.service.d` + `wifi-portal.service` configs  
- **Team hours:** ~40h  
- **Metrics/Results:** Deterministic `wlan0` bring-up every reboot  
- **Dependencies & Risks / Mitigation:** Service boot-order conflicts resolved via override  
- **Next Actions:** Validate AP stability

### 2025-10 W4 (Oct 20–Oct 26)
- **Key work:** Wi-Fi AP mode implementation  
- **Owners:** Renae  
- **Deliverables/Evidence:** https://github.com/botanika-blockify/wifi-captive-portal  
- **Team hours:** ~40h  
- **Metrics/Results:** AP + DHCP + DNS redirect stable  
- **Dependencies & Risks / Mitigation:** Must guard against accidental wlan0 rename events  
- **Next Actions:** Implement captive portal UI + auto-redirect

### 2025-10 W5 (Oct 27–Oct 31) *optional*
- **Key work:** Captive portal UI + fallback logic + provisioning & UUID scanner  
- **Owners:** Renae  
- **Deliverables/Evidence:**  
  - wifi-captive-portal repo  
  - UUID scanner → burn → verify logs  
- **Team hours:** ~40h  
- **Metrics/Results:** Onboarding fully autonomous; UUID scanner workflow functional  
- **Dependencies & Risks / Mitigation:** enable USB-C device mode  
- **Next Actions:** Integrate UUID scanner + burn process into factory

---

## 3) Monthly Rollup
- **Sep total hours (team):** ~160h  
- **Oct total hours (team):** ~200h  

- **Top 3 outcomes:**
- **Open issues & immediate actions:** 
