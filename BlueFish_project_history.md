# Project History & Weekly Detail for Sep–Oct (Project-Level)
> **Submission deadline:** 2025-11-06 (Thu)  
> **Principle:** **Github repo** — https://github.com/blockify-bluefish/bluefish-mobile
> **Week basis:** Monday–Sunday

---

## 0) Project Overview
- **Project name:**  BlueFish Wallet
- **Owner/Lead:**  Jack Le
- **Duration (YYYY-MM ~ YYYY-MM):**  2024-11 ~ 2025-07
- **Goal / Success Criteria (KPI):** Multi-chain wallet supporting BTC, ETH, SOL with complete mobile app features
- **In-scope / Out-of-scope:**  Design, Frontend Development, Backend Development, Smart Contract Integration
- **Key deliverables:** Mobile App UI/UX, Wallet functionality (BTC/ETH/SOL), Storyboard, User flows

## 1) Participants & Responsibilities
| Name | Role | Responsibility | Key Contribution (quant) | Evidence Links (required) |
|---|---|---|---|---|
| Rachel | UIUX Designer | Lead UI/UX design for BlueFish mobile wallet, creating complete design system and user flows for v1.0 & v1.1 releases | • Designed 2 complete app versions (v1.0 & v2.0) with 8+ core features<br>• Created comprehensive design system and component library<br>• Designed storyboards & user flows for app navigation<br>• Implemented features: Login, Home, Wallet, Contact, Mission, Chat, Browser, Airdrop, NFT details<br>• Added dark mode color palette and visual refinements<br>• 6 months of iterative design improvements (Nov 2024 - Jul 2025)<br>• Figma design documentation and handoff to development team | • Figma Design System: https://www.figma.com/design/ZovLgCmIn10m8E9Lprd2T5/BLUE-FISH---ver02?node-id=0-1&t=l5yIaIQ58rwtYsYW-1<br>• Storyboard v1: https://docs.google.com/presentation/d/1qEVpcCBTy7XqCXQ3e7Y3g1LV9NNrHe2iI34CwxLklZ4<br>• Storyboard v2: https://docs.google.com/presentation/d/1WB3nn9ifRA7Lb6IwKG6Nm-V4Hj9U8qWCyBJVWAsv0MY |
| Andy | Senior Developer | Lead technical development for Bluefish App & NIMBUS OS, resolving critical production issues and building core blockchain features | • Resolved 2/3 major Google Play compliance blockers<br>• Executed 20+ commits for strategic repository migration<br>• Built multi-chain wallet supporting 3+ blockchain networks<br>• Architected backend trading systems with Kafka integration | • https://github.com/blockify-bluefish/core<br>• https://github.com/blockify-bluefish/wallet-core<br>• https://github.com/blockify-bluefish/backend-0x<br>• https://github.com/blockify-bluefish/bluefish-core<br>• https://github.com/blockify-bluefish/bluefish-android<br>• https://github.com/blockify-bluefish/bluefish-mobile<br>• https://github.com/Blockify-CEX/order-book |
| Chay | iOS Developer | Lead iOS mobile development for BlueFish v1.0 & v1.1, managing Apple App Store submissions and VoIP integration | • Successfully deployed BlueFish v1.0 & v1.1 to Apple App Store<br>• Handled 11 rounds of Apple Review communication solo (Oct 16 - Nov 6)<br>• Implemented complete VoIP/CallKit integration for iOS<br>• Built CallBanner UI and global call state management<br>• Platform-specific biometry implementation<br>• 13+ commits with ~2,000+ lines of code changes | • https://github.com/blockify-bluefish/bluefish-mobile/commit/819d82c755a099dfa105fdcfe65218876ea02fe5<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/44a525b0f4b550c489c545fe581a69d72b2dddc5<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/e8bb733398577d0657efa45f6d7a9e7ceed7141d<br>• App Store Connect Submission: `60076b46-9f33-4b10-9377-6d163895f50f` |
| Renea Nguyen (login: `rrenae`) | Blockchain / Feature Developer | Implement and refine **Solana swap functionality**; develop **multi-chain send features**; integrate **transaction notifications**; improve **mission system**; implement **error tracking** | • **Complete swap flow** (quote → confirmation → execution)<br>• **Multi-chain send** (BTC, Solana, SPL tokens)<br>• **Transaction notification system**<br>• **UI/UX improvements** across features<br>• Extensive commit history showing continuous development and refinement of swap and send features<br>• React Native, Solana Web3.js, Bitcoin libraries, Sentry for monitoring | • GitHub Commits: See weekly log for April-August 2025 section with full commit URLs<br>• **Swap ETH confirmation** — Multiple commits refining confirmation flow<br>• **Send raw transaction** — Transaction execution improvements<br>• **Slippage settings** — User-configurable swap parameters<br>• **Multi-chain support** — BTC, Solana, SPL token transactions<br>• **Tooling & process:** React Native, Solana Web3.js, Bitcoin libraries, Sentry for monitoring, iterative feature development |

> Tips  
> - Use **numbers/metrics** for contributions (e.g., throughput +2.1×, p95 −71%).  
> - Evidence must be verifiable (PRs, docs, dashboards, releases).

---

## 2) Weekly Log for Sep–Oct (project view)

### 2025-04 (April 01–April 30)
- **Key work:** Android wallet infrastructure, Address selection, BTC send UI, Solana send, FCM integration
- **Owners:** Renea Nguyen
- **Deliverables/Evidence (required):** • https://github.com/blockify-bluefish/bluefish-mobile/commit/3f05d4997<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/e9998021e<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/3d703a7e7<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/a7ec21955<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/126f1b4f0<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/2cd8d3768<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/b2ea939c0<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/ee4d939d5<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/648a37333<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/c05871694<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/1c7b7feeb<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/ece41d80f

- **Metrics/Results:** Foundation for swap functionality, Mobile wallet infrastructure, Wallet address picker for sending, Bitcoin transaction interface, Initial Solana transaction implementation, Push notification setup
- **Dependencies & Risks / Mitigation:** None
- **Next Actions (Owner / Due):** Send functionality

### 2025-05 (May 01–May 31)
- **Key work:** Send functionality, Fee calculation, Transaction notifications, Address scanning, Bitcoin transactions, Solana notifications, Solana token list, Aggregator selection, Token list management, Wallet token integration
- **Owners:** Renea Nguyen
- **Deliverables/Evidence (required):** • https://github.com/blockify-bluefish/bluefish-mobile/commit/e4c93f652<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/20f80ec63<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/e02357668<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/59c60c254<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/339910574<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/8cdf829d5<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/1204be25b<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/dcfb1ea29<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/523003f05<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/162c1bc34<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/c9bcd4570<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/2a7d16aca<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/530acd694<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/43aa1aaa0<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/6a0b2e84f<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/a87efe1c0<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/77e9ef680<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/700c6a4e9<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/40d4e9914<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/9a05f9e54

- **Metrics/Results:** Multi-asset sending implementation, Dynamic fee estimation, Multi-chain notification system, QR code integration for send flow, BTC transaction list and sync, Transaction status alerts, Integrated Solana token metadata, Multi-dex swap routing, Enhanced token loading and display, Connected wallet assets to swap/send
- **Dependencies & Risks / Mitigation:** None
- **Next Actions (Owner / Due):** ETH transactions

### 2025-06 (June 01–June 30)
- **Key work:** ETH transactions, Transaction refactor, Solana swap setup, UI structure, Destination token selection, UI improvements, Quote system, Transaction UI
- **Owners:** Renea Nguyen
- **Deliverables/Evidence (required):** • https://github.com/blockify-bluefish/bluefish-mobile/commit/c7d5135c2<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/79f4ab33f<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/fb86849d6<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/970bba8f9<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/62acb6345<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/72b3a4b6d<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/6828cf4f8<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/48b426220<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/4b3d79496<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/af884585c<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/40f0f7939<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/16e3ce9b9<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/d79680510<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/8099f1b48<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/1743c1b19<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/97504b91c

- **Metrics/Results:** Ethereum transaction handling, Improved transaction management, Initial Solana swap infrastructure, Foundation for swap interface, Enhanced token picker for Solana, Various swap interface refinements, Implemented swap quote generation and management, Improved transaction history and display
- **Dependencies & Risks / Mitigation:** None
- **Next Actions (Owner / Due):** Sentry setup

### 2025-07 (July 01–July 31)
- **Key work:** Sentry setup, Swap confirmation, Swap environment setup, Send raw transaction, Slippage settings, Sentry integration, RPC configuration, Mission system refactor
- **Owners:** Renea Nguyen
- **Deliverables/Evidence (required):** • https://github.com/blockify-bluefish/bluefish-mobile/commit/ec2e0b05e<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/f58d161cb<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/276ce0877<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/9c3f7145a<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/f5562c079<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/df005c2f4<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/a897888e7<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/84c6111ee<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/87a994e6b<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/8a7b991c6<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/de3785f17<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/8a294ce28<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/710dbd36a<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/1f1b00e26<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/c76733cd5<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/d6006c76e<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/68c662db5<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/d0840782a

- **Metrics/Results:** Implemented comprehensive error tracking, Enhanced swap confirmation UI and logic, Configured swap for different environments, Implemented direct transaction broadcasting, Added user-configurable swap parameters, Enhanced error tracking and monitoring, Improved blockchain connection settings, Improved mission UI and functionality
- **Dependencies & Risks / Mitigation:** None
- **Next Actions (Owner / Due):** Destination token list

### 2025-08 (August 01–August 31)
- **Key work:** Destination token list, Disable liveness, Swap UI improvements, ETH address integration, Quote auto reload, Swap ETH confirmation
- **Owners:** Renea Nguyen
- **Deliverables/Evidence (required):** • https://github.com/blockify-bluefish/bluefish-mobile/commit/56484c404<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/e7623ee63<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/647560b3f<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/1955d24f6<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/c965bc02b<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/3f312526e<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/f114d294f<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/450ac4287<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/d670d5464<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/d49d76833<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/2e714acc5<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/17690d06d<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/e7e6284aa<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/a5f63eaf<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/66a73e146<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/b711605e3<br>• https://github.com/blockify-bluefish/bluefish-mobile/commit/cae33e79d

- **Metrics/Results:** Improved token selection UI, Feature flag management, Multiple UI refinements and renaming for clarity, Added ETH address support for swap functionality, Implemented automatic quote refresh for better UX, Finalized swap confirmation flow with multiple merges, Multiple PR merges completing swap confirmation feature
- **Dependencies & Risks / Mitigation:** None
- **Next Actions (Owner / Due):** None

---

### Rachel — Design Work
- **Key work:**  
- **Owners:**  
- **Deliverables/Evidence (required):**  

- **Metrics/Results:**  
- **Dependencies & Risks / Mitigation:**  
- **Next Actions (Owner / Due):**  

### 2024-11 - 2024-12 (Sep 27– Dec 31)
- **Key work:**  Checking document, build design system & Design BlueFish App ver 01 with main features : Login, Home, Wallet,
- **Owners:** Rachel
- **Deliverables/Evidence (required):** https://www.figma.com/design/ZovLgCmIn10m8E9Lprd2T5/BLUE-FISH---ver02?node-id=0-1&t=l5yIaIQ58rwtYsYW-1

- **Metrics/Results:**  Complete features: Login, Home, Wallet
- **Dependencies & Risks / Mitigation:**  None
- **Next Actions (Owner / Due):**  Contact


### 2025-01 W1 (Jan 01–Jan 05)
- **Key work:**  Design BlueFish App ver 01 with main features : Contact
- **Owners:**  Rachel
- **Deliverables/Evidence (required):**  https://www.figma.com/design/ZovLgCmIn10m8E9Lprd2T5/BLUE-FISH---ver02?node-id=0-1&t=l5yIaIQ58rwtYsYW-1

- **Metrics/Results:**  Complete feature: Contact
- **Dependencies & Risks / Mitigation:**  
- **Next Actions (Owner / Due):**  Mission

### 2025-01 W2 (Jan 06–Jan 12)
- **Key work:**  Design BlueFish App ver 01 with main features : Mission
- **Owners:**  Rachel
- **Deliverables/Evidence (required):**  https://www.figma.com/design/ZovLgCmIn10m8E9Lprd2T5/BLUE-FISH---ver02?node-id=0-1&t=l5yIaIQ58rwtYsYW-1

- **Metrics/Results:**  Complete feature: Mission
- **Dependencies & Risks / Mitigation:**  
- **Next Actions (Owner / Due):**  Chat, Browser


### 2025-01 W3 (Jan 13–Jan 19)
- **Key work:**  Design BlueFish App ver 01 with main features : Chat, Browser
- **Owners:**  Rachel
- **Deliverables/Evidence (required):**  https://www.figma.com/design/ZovLgCmIn10m8E9Lprd2T5/BLUE-FISH---ver02?node-id=0-1&t=l5yIaIQ58rwtYsYW-1

- **Metrics/Results:**  Complete features: Chat, Browser
- **Dependencies & Risks / Mitigation:**  
- **Next Actions (Owner / Due):**  Updating the UI for app and Storyboard

### 2025-01 W4 (Jan 20–Jan 26)
- **Key work:**  Checking with PO to update the UI for app and update the storyboard
- **Owners:**  Rachel
- **Deliverables/Evidence (required):**  https://www.figma.com/design/ZovLgCmIn10m8E9Lprd2T5/BLUE-FISH---ver02?node-id=0-1&t=l5yIaIQ58rwtYsYW-1

- **Metrics/Results:**  Updated Mission feature, Home
- **Dependencies & Risks / Mitigation:**  
- **Next Actions (Owner / Due):**  Updating the UI for app and Storyboard

### 2025-01 W5 (Jan 27–Jan 31)
- **Key work:**  Updating Storyboard
- **Owners:**  Rachel
- **Deliverables/Evidence (required):**  https://docs.google.com/presentation/d/1qEVpcCBTy7XqCXQ3e7Y3g1LV9NNrHe2iI34CwxLklZ4/edit?slide=id.g31a520495f0_0_74#slide=id.g31a520495f0_0_74

- **Metrics/Results:**  Completed ver01
- **Dependencies & Risks / Mitigation:**  
- **Next Actions (Owner / Due):**  Storyboard

### 2025-02 W1 (Feb 02–Feb 08)
- **Key work:**  Updating Storyboard
- **Owners:**  Rachel
- **Deliverables/Evidence (required):**  https://docs.google.com/presentation/d/1qEVpcCBTy7XqCXQ3e7Y3g1LV9NNrHe2iI34CwxLklZ4/edit?slide=id.g31a520495f0_0_74#slide=id.g31a520495f0_0_74

- **Metrics/Results:**  Completed ver01
- **Dependencies & Risks / Mitigation:**  
- **Next Actions (Owner / Due):**  Ver02

### 2025-02 W2 (Feb 09–Feb 15)
- **Key work:**  Update ver 02 with main features: Home, Contact
- **Owners:**  Rachel
- **Deliverables/Evidence (required):**  https://www.figma.com/design/ZovLgCmIn10m8E9Lprd2T5/BLUE-FISH---ver02?node-id=0-1&p=f&t=3Jm0MciM3AlOQ4t5-0

- **Metrics/Results:**  Completed Home, Contact
- **Dependencies & Risks / Mitigation:**  
- **Next Actions (Owner / Due):**  Mision, Airdrop ver02
- **Owners:**  Rachel ver02 

### 2025-02 W2 (Feb 16–Feb 22)
- **Key work:**  Update ver 02 with main features: Mision, Airdrop
- **Deliverables/Evidence (required):**  https://www.figma.com/design/ZovLgCmIn10m8E9Lprd2T5/BLUE-FISH---ver02?node-id=0-1&p=f&t=3Jm0MciM3AlOQ4t5-0

- **Metrics/Results:**  Completed Mission & Airdrop ver02
- **Dependencies & Risks / Mitigation:**  
- **Next Actions (Owner / Due):** Chat ver02 & Browser

### 2025-02 W3 (Feb 23–Feb 28)
- **Key work:**  Update ver 02 with features related to Community : Profile, Publicize, Contact
- **Deliverables/Evidence (required):**  https://www.figma.com/design/ZovLgCmIn10m8E9Lprd2T5/BLUE-FISH---ver02?node-id=0-1&p=f&t=3Jm0MciM3AlOQ4t5-0

- **Metrics/Results:**  
- **Dependencies & Risks / Mitigation:**  
- **Next Actions (Owner / Due):** Updating to Storyboard

### 2025-02 W1 (March 01–March 08)
- **Key work:**  Update user flow for Dev view
- **Deliverables/Evidence (required):**  https://www.figma.com/design/ZovLgCmIn10m8E9Lprd2T5/BLUE-FISH---ver02?node-id=429-3632&p=f&t=3Jm0MciM3AlOQ4t5-0

- **Metrics/Results:**  Complete the flow
- **Dependencies & Risks / Mitigation:**  
- **Next Actions (Owner / Due):** Updating to Storyboard

### 2025-03 W3 (March 16–March 22)
- **Key work:**  Updating Storyboard 
- **Owners:**  Rachel
- **Deliverables/Evidence (required):**  https://docs.google.com/presentation/d/1WB3nn9ifRA7Lb6IwKG6Nm-V4Hj9U8qWCyBJVWAsv0MY/edit?slide=id.g338865f3076_0_108#slide=id.g338865f3076_0_108

- **Metrics/Results:**  Completed the storyboard
- **Dependencies & Risks / Mitigation:**  
- **Next Actions (Owner / Due):** Updating to Storyboard

### 2025-04 W5 (April 26–April 30)
- **Key work:**  Updating Storyboard 
- **Owners:**  Rachel
- **Deliverables/Evidence (required):**  https://docs.google.com/presentation/d/1WB3nn9ifRA7Lb6IwKG6Nm-V4Hj9U8qWCyBJVWAsv0MY/edit?slide=id.g338865f3076_0_108#slide=id.g338865f3076_0_108

- **Metrics/Results:**  Completed the storyboard
- **Dependencies & Risks / Mitigation:**  None
- **Next Actions (Owner / Due):** None

### 2025-04 W2 (July 6– July 12)
- **Key work:**  Updating UI- -Darkmode
- **Owners:**  Rachel
- **Deliverables/Evidence (required):**  https://www.figma.com/design/ZovLgCmIn10m8E9Lprd2T5/BLUE-FISH---ver02?node-id=0-1&p=f&t=3Jm0MciM3AlOQ4t5-0

- **Metrics/Results:**  Completed the Color palette for darkmode
- **Dependencies & Risks / Mitigation:**  None
- **Next Actions (Owner / Due):** None

### 2025-09 W1-W2 (Sep 01–Sep 14)
**Milestone:** Apple App Store v1.0 Launch 🎉

- **Key work:**  VoIP Call System v1.0 implementation, Apple Store submission & approval, Production deployment of BlueFish v1.0
- **Owners:** Chay
- **Deliverables/Evidence (required):**  https://github.com/blockify-bluefish/bluefish-mobile/commit/819d82c755a099dfa105fdcfe65218876ea02fe5

- **Metrics/Results:**  Commit: 1 major feature commit, Lines changed: ~441 insertions, ~227 deletions, Files modified: 10, Review turnaround: ~3-5 days, Deployment success: ✅
- **Dependencies & Risks / Mitigation:**  CallKit required proper background permissions and PushKit certificates, Socket event handling needed state synchronization, iOS native bridge required Objective-C modifications in AppDelegate.m
- **Next Actions (Owner / Due):**  Apple Review Compliance & VoIP Refinement

### 2025-09 W3-W4 (Sep 30–Oct 06)
**Focus:** Apple Review Compliance & VoIP Refinement

- **Key work:**  VoIP compliance improvements for Apple review, CallKit cleanup and debugging enhancements, Navigation flow improvements, Configuration cleanup
- **Owners:** Chay
- **Deliverables/Evidence (required):**  • Apple Compliance: https://github.com/blockify-bluefish/bluefish-mobile/commit/2651cd4130025f2ae13966c1b6ad8e2d0a56f5ff<br>• VoIP Debugging: https://github.com/blockify-bluefish/bluefish-mobile/commit/b7da967f3629fbe52185f523f62a4dabfd4d2557

- **Metrics/Results:**  Commits: 8, Lines changed: ~300 insertions, ~250 deletions, Files modified: ~25, Bug fixes: 6, Compliance updates: 2
- **Dependencies & Risks / Mitigation:**  Apple requires strict VoIP usage justification, Had to balance compliance with functionality, Multiple iteration cycles for call flow optimization
- **Next Actions (Owner / Due):**  Documentation & Code Quality

### 2025-10 W1 (Oct 07–Oct 13)
**Focus:** Documentation & Code Quality

- **Key work:**  Comprehensive project documentation (PROJECT_GUIDE.md), CallKeep service enhancement, Improved CallScreen component
- **Owners:** Chay
- **Deliverables/Evidence (required):**  https://github.com/blockify-bluefish/bluefish-mobile/commit/fbaea30d5394b7e476a8c88e194dd9cecc6d522f

- **Metrics/Results:**  Commits: 1, Documentation added: 294 lines, Lines changed: ~490 insertions, ~26 deletions, Files modified: 4
- **Dependencies & Risks / Mitigation:**  None
- **Next Actions (Owner / Due):**  Call Banner UI Implementation

### 2025-10 W2 (Oct 14–Oct 20)
**Focus:** Call Banner UI Implementation

- **Key work:**  VoIP Call Banner technical analysis (1,099 lines), Call Banner UI component implementation, Global call state management
- **Owners:** Chay
- **Deliverables/Evidence (required):**  • Documentation: https://github.com/blockify-bluefish/bluefish-mobile/commit/4cf59da2cecf540000765fc6cd56bb4e54d10119<br>• Implementation: https://github.com/blockify-bluefish/bluefish-mobile/commit/e0bf24cbb3df09b8a88701bbc41b6845dd84526c

- **Metrics/Results:**  Commits: 2, Documentation added: 1,442 lines (including analysis expansion), Lines changed: ~785 insertions, ~17 deletions, New components: 3, Files modified: 9
- **Dependencies & Risks / Mitigation:**  None
- **Next Actions (Owner / Due):**  Planning & Testing for v1.1 Release

### 2025-10 W3 (Oct 21–Oct 27)
**Focus:** Planning & Testing for v1.1 Release

- **Key work:**  Planning Apple Store v1.1 submission, Testing new features, Preparing compliance documentation, Code review and QA
- **Owners:** Chay
- **Deliverables/Evidence (required):**  (Planning phase, documentation prepared for Apple review)

- **Metrics/Results:**  Commits: 0 (planning phase)
- **Dependencies & Risks / Mitigation:**  None
- **Next Actions (Owner / Due):**  Apple App Store v1.1 Launch

### 2025-10 W4 - 2025-11 Early (Oct 28–Nov 03 + Nov 04–Nov 06)
**Milestone:** Apple App Store v1.1 Launch 🎉 (with extended Apple Review process through Nov 6)

- **Key work:**  Apple Store v1.1 deployment, Solo management of 11-round Apple Review communication (Oct 16 - Nov 6), Platform-specific biometry implementation, Apple review documentation (3 docs, ~371 lines), Swap feature compliance workaround, Enhanced NFT details
- **Owners:** Chay
- **Deliverables/Evidence (required):**  • v1.1 Release: https://github.com/blockify-bluefish/bluefish-mobile/commit/44a525b0f4b550c489c545fe581a69d72b2dddc5<br>• Swap Workaround: https://github.com/blockify-bluefish/bluefish-mobile/commit/e8bb733398577d0657efa45f6d7a9e7ceed7141d<br>• App Store Connect Submission: `60076b46-9f33-4b10-9377-6d163895f50f`<br>• Apple Review Video Clip: https://bluefishwallet.com/app-clips

- **Metrics/Results:**  Commits: 2 (major releases), Lines changed: ~947 insertions, ~222 deletions, Documentation added: ~371 lines (Apple review), Apple messages handled: 11 (solo), Files modified: 44, New service modules: 1, Review duration: 3+ weeks (ongoing), Apple Review Process: 11 rounds (Oct 16 - Nov 6) all handled by Chay solo
- **Dependencies & Risks / Mitigation:**  **Swap Feature Compliance:** App has Swap functionality but lacks required financial documentation; Implemented temporary workaround: Swap code exists but is conditionally disabled; Waiting for regulatory documentation approval; Backend team will re-enable via API once approved (no client update needed). **Multi-round Apple Review:** Required persistent communication over 3+ weeks; Each response needed careful technical + compliance documentation; Balancing feature functionality with Apple's guidelines. Platform-specific biometry handling required separate iOS/Android implementations. Apple review required detailed guideline response documentation.
- **Next Actions (Owner / Due):**  None (Pending Apple Review approval - ongoing as of Nov 6)

---


## 3) Monthly Rollup (optional)

### September 2025
- **Sep total hours (team):** ~480 hours (estimated: 4 team members × 4 weeks × 30 hrs/week)
  - Chay: VoIP implementation, Apple Store v1.0 launch, compliance documentation
  - Renea: Destination token list, quote auto-reload, swap ETH confirmation refinements
  - Rachel: UI dark mode updates and storyboard finalization
  - Andy: Support and infrastructure maintenance

### October 2025
- **Oct total hours (team):** ~520 hours (estimated: 4 team members × 4 weeks × 32.5 hrs/week)
  - Chay: Apple v1.1 preparation, testing, 11-round Apple Review communication (solo management), biometry implementation
  - Renea: Swap functionality refinement and edge case handling
  - Rachel: Minor UI iterations and support
  - Andy: Backend stability and production support

### Top 3 Outcomes
1. **🎉 Apple App Store v1.0 & v1.1 Launches (Sep & Oct-Nov):** Successfully deployed two major releases to App Store with full VoIP/CallKit integration and platform-specific biometry. Managed 11 rounds of Apple Review communication solo (Chay), demonstrating strong technical and compliance documentation skills.

2. **Complete Multi-Chain Swap Functionality (Aug-Oct):** Implemented end-to-end swap flow across BTC, Solana, and ETH with quote generation, user-configurable slippage, automatic quote refresh, and comprehensive error tracking via Sentry integration. Enabled users to seamlessly exchange tokens across multiple blockchain networks.

3. **Comprehensive Design System & User Flows (Nov 2024-Jul 2025):** Created complete design system with 2 full app versions (v1.0 & v2.0), 8+ core features, storyboards, and user flows. Delivered 6 months of iterative design improvements with dark mode palette, enabling smooth handoff to development team.

### Open Issues & Immediate Actions
- **Swap Feature Compliance (Pending):** Swap functionality currently disabled pending regulatory documentation approval. Waiting for backend team to re-enable via API once compliance docs are approved. No client update needed for re-enablement.
- **Apple Review Status (Ongoing):** BlueFish v1.1 still undergoing Apple Review as of Nov 6. Chay maintaining communication with Apple review team. Expected approval by Nov 10-14.
- **Production Stability:** Continue monitoring Sentry error tracking for any runtime issues in production. Focus on user feedback loops for next iteration (v1.2 planning).
- **Next Sprint Planning:** Schedule v1.2 feature planning with product team; prioritize based on user feedback from v1.0/v1.1 usage data.
