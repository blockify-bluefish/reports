# Project History & Weekly Detail for Sep–Oct (Project-Level)
> **Submission deadline:** 2025‑11‑06 (Thu)  
> **Principle:** No confidential materials — **list 100% of deliverables/evidence/links**  
> **Filename:** `Bluefish_project_history.md`  
> **Week basis:** Monday–Sunday

---

## 0) Project Overview  
- **Project name:** Bluefish (Brave Fork)  
- **Owner/Lead:** Jack  
- **Duration (2024‑07–present)**  
- **Goal / Success Criteria (KPI):** Fork & Rebrand Brave Browser for Mobile, improve UX (widgets, toolbar, settings), and evaluate Chromium internals  
- **Research:**  
  - ✅ Chromium architecture reviewed (2024‑07)  
  - ✅ Compatibility analysis (Android WebView / iOS WKWebView)  
  - ❌ Chromium engine modifications = out of scope  
- **In‑scope / Out‑of‑scope:**  
  - **In-scope:** UI/UX, rebranding, widgets/toolbar, feature toggles, Chromium feasibility  
  - **Out-of-scope:** Engine-level changes, backend re-architecture  
- **Key deliverables:**  
  - Branding change: https://github.com/blockify-bluefish/core/commit/0f139bac9ddb993c4943a6264849a260d7daa072  
  - Hide buy/swap: https://github.com/blockify-bluefish/core/commit/ab8043513edd7e061048cc901940113066aaec4b  
  - Widget & toolbar/menu updates  
  - Messenger view chore  
  - Merges with develop branch (e.g., https://github.com/blockify-bluefish/core/commit/730e0f513bab8bdbe5fd0ffd972fc7a2cd315651)  

---

## 1) Participants & Responsibilities  
| Name   | Role            | Responsibility                          | Key Contribution (quant)     | Evidence Links                                   |
|--------|-----------------|-----------------------------------------|------------------------------|--------------------------------------------------|
| Rrenae | Senior Full‑Stack | UI features, branding, merges            | ~20+ commits in Oct           | [Commit history for Rrenae](https://github.com/blockify-bluefish/core/commits?author=rrenae) |
| Andy   | Senior Full‑Stack | Build fixes, Android compatibility      | ~10+ commits in Sep/Oct       | [Commit history for Andy](https://github.com/blockify-bluefish/core/commits?author=anhnguyen) |
| Jack   | Lead            | Lead     | Lead | |

---

## 2) Weekly Log for Sep–Oct (project view)  

### 2024‑09 W4 (Sep 23–Sep 29)  
- **Key work:** Bugfix backlog for Android build  
- **Owners:** Andy  
- **Links:**  
  - https://github.com/blockify-bluefish/core/commit/06f48ac3b357ea3320ad943e6651f7cf63512772  
  - https://github.com/blockify-bluefish/core/commit/bca5f33b010919879d8b96c58e3d76aad1a15db9  
- **Team hours (h):** 40  
- **Metrics:** 3/3 bugs resolved  
- **Dependencies & Risks / Mitigation:** N/A  

---

### 2024‑10 W1 (Sep 30–Oct 06)  
- **Key work:** File structure/output, branding foundation  
- **Owners:** Andy  
- **Links:**  
  - https://github.com/blockify-bluefish/core/commit/13c7f7a191f0c95cb0a9dcda2fb41b84e9150b94  
  - https://github.com/blockify-bluefish/core/commit/0f139bac9ddb993c4943a6264849a260d7daa072  
- **Team hours (h):** 40  
- **Metrics:** 2/2 features delivered  
- **Dependencies & Risks / Mitigation:** QA not in place → actioned  

---

### 2024‑10 W2 (Oct 07–Oct 13)  
- **Key work:** Major UI/UX pass — toolbar/menu, branding, hide network  
- **Owners:** Rrenae  
- **Links:**  
  - https://github.com/blockify-bluefish/core/commit/830b4a7cf905a8ed72a060eb62fe3193f937066c  
  - https://github.com/blockify-bluefish/core/commit/2f56447842b00e2c702219d59cea75cc238e9dd6  
  - https://github.com/blockify-bluefish/core/commit/ef89b67a36219cab3ae884430bbfb502670c21f8  
- **Team hours (h):** 40  
- **Metrics:** 6/6 shipped  
- **Dependencies & Risks / Mitigation:** Merge lags → addressed in weekly sync  

---

### 2024‑10 W3 (Oct 14–Oct 20)  
- **Key work:** UI polish — widget color, hide iOS buy/swap, messenger  
- **Owners:** Rrenae  
- **Links:**  
  - https://github.com/blockify-bluefish/core/commit/12752a5a7c152c3778152665b26afe9b46c3057d  
  - https://github.com/blockify-bluefish/core/commit/ab8043513edd7e061048cc901940113066aaec4b  
  - https://github.com/blockify-bluefish/core/commit/ac21fbf025b15b5a15a1b3b30a64d84f0498f59a  
  - https://github.com/blockify-bluefish/core/commit/730e0f513bab8bdbe5fd0ffd972fc7a2cd315651  
- **Team hours (h):** 40  
- **Metrics:** 4/4  
- **Dependencies & Risks / Mitigation:** Merge conflict with develop resolved  

---

## 3) Monthly Rollup  
- **Sep total hours (team):** ~80  
- **Oct total hours (team):** ~120  
- **Top 3 outcomes:**  
  1. Branding overhaul complete  
  2. Core UI features (toolbar, widget, menu) delivered  
  3. Toggle features fully working (hide swap, network)  

- **Open issues & immediate actions:**  
  - Improve develop → feature branch merge process  
  - Pending QA testing for iOS behavior  
  - Stabilize Android edge case crashes  

---