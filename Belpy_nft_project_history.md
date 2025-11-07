# Project History & Weekly Detail for Sep–Oct (Project-Level)

> **Submission deadline:** 2025-11-06 (Thu)  
> **Principle:** **Github repo** — https://github.com/orgs/belp-nft/repositories  
> **Filename:** `Belpy_nft_project_history.md` (e.g., `Belpy_nft_ProjectHistory_v20251106.md`)  
> **Week basis:** Monday–Sunday

---

## 0) Project Overview

- **Project name:** BELPY NFT
- **Owner/Lead:** Jack Le
- **Duration (YYYY-MM ~ YYYY-MM):** 2025-07 ~ 2025-10
- **Goal / Success Criteria (KPI):** Complete NFT platform with Landing page, Mint pages, History page, My collection page, Lore page
- **In-scope / Out-of-scope:** Design, Frontend Development, Backend Development, Smart Contract Development
- **Key deliverables:** Figma design, Frontend implementation, Backend API, Smart contracts

## 1) Participants & Responsibilities

| Name       | Role               | Responsibility                                                                               | Key Contribution (quant)                                              | Evidence Links (required)                                                                                                               |
| ---------- |--------------------|----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------|
| Kate       | UI Designer        | Design                                                                                       | Landing page, Mint pages, History page, My collection page, Lore page | https://www.figma.com/design/ZE8ncHWNQGe9WrsEaSB3XH/BELP-NFT?node-id=0-1&p=f&t=SWO89jhkY4ETFYhR-0                                       |
| Bee Nguyễn | Frontend Developer | UI development, wallet integration, advanced components  | Successfully apply CandyMachine for page, handle history, storaged item NFTs | https://github.com/belp-nft/belp-website                            |
| Hieu Trung | Backend + Devops   | Set up Candy Machine and NFT backend APIs, built admin panel, and deployed production site.  | NFT minting successfully launched and verified.                       | https://belpy.xyz/ and contract address https://solscan.io/account/FqSAi6Uda8ri9zV1RBfq25GdfPdeKb24yHqvSgsi83Z4, Releases (2025-10-10)  |

> Tips
>
> - Use **numbers/metrics** for contributions (e.g., throughput +2.1×, p95 −71%).
> - Evidence must be verifiable (PRs, docs, dashboards, releases).

---

## 2) Weekly Log for Sep–Oct (project view)

### 2025-08 W1 (Jul 28–Aug 03)

- **Key work:** Landing page
- **Owners:** Kate
- **Deliverables/Evidence (required):** https://www.figma.com/design/ZE8ncHWNQGe9WrsEaSB3XH/BELP-NFT?node-id=0-1&p=f&t=SWO89jhkY4ETFYhR-0
- **Metrics/Results:** Landing page design
- **Dependencies & Risks / Mitigation:**
- **Next Actions (Owner / Due):** continue design others pages

### 2025-08 W1 (Aug 04–Aug 10)

- **Key work:** Mint pages, My collection page
- **Owners:** Kate
- **Deliverables/Evidence (required):** https://www.figma.com/design/ZE8ncHWNQGe9WrsEaSB3XH/BELP-NFT?node-id=0-1&p=f&t=SWO89jhkY4ETFYhR-0
- **Metrics/Results:** Mint pages, My collection page
- **Dependencies & Risks / Mitigation:**
- **Next Actions (Owner / Due):** continue design others pages

### 2025-08 W1 (Aug 11–Aug 17)

- **Key work:** Lore page, History page
- **Owners:** Kate
- **Deliverables/Evidence (required):** https://www.figma.com/design/ZE8ncHWNQGe9WrsEaSB3XH/BELP-NFT?node-id=0-1&p=f&t=SWO89jhkY4ETFYhR-0
- **Metrics/Results:** Lore page, History page
- **Dependencies & Risks / Mitigation:**
- **Next Actions (Owner / Due):**

### 2025-08 W4 (Aug 26–Aug 31) - Project Initialization

- **Key work:** Project setup, Next.js initialization, basic structure
- **Owners:** Bee Nguyễn
- **Deliverables/Evidence (required):**
  - Initial Next.js 15.4.5 setup with TypeScript
  - Package.json with Solana Web3.js, Metaplex dependencies
  - Basic folder structure (components, pages, providers)
  - Commits:
    - [`b9d5f3d`](https://github.com/belp-nft/belp-website/commit/b9d5f3d) - Initialize Next.js project with basic structure
    - [`3f03db4`](https://github.com/belp-nft/belp-website/commit/3f03db4) - Configure development environment
    - [`497019f`](https://github.com/belp-nft/belp-website/commit/497019f) - Setup initial dependencies and build tools
- **Metrics/Results:** Project foundation established, build pipeline working
- **Dependencies & Risks / Mitigation:** None at this stage
- **Next Actions (Owner / Due):** Start UI development (Bee / Sep 02)

### 2025-09 W1 (Sep 02–Sep 08) - Core UI Development

- **Key work:** Landing page components, wallet connection UI, responsive design
- **Owners:** Bee Nguyễn
- **Deliverables/Evidence (required):**
  - Hero section with animated elements (`HeroSection`)
  - Wallet connection modal with multi-provider support
  - Header/Footer components with navigation
  - Commits:
    - [`87ae580`](https://github.com/belp-nft/belp-website/commit/87ae580) - Implement modern UI components with responsive design
    - [`324f1f2`](https://github.com/belp-nft/belp-website/commit/324f1f2) - Build hero section with animated elements
    - [`cf5fe7f`](https://github.com/belp-nft/belp-website/commit/cf5fe7f) - Add navigation and header components
    - [`e0aa9ed`](https://github.com/belp-nft/belp-website/commit/e0aa9ed) - Update to latest UI framework version
- **Metrics/Results:** Basic landing page functional, responsive on mobile/desktop
- **Dependencies & Risks / Mitigation:** Wallet adapter compatibility - used standardized @solana/wallet-adapter
- **Next Actions (Owner / Due):** Implement Solana wallet integration (Bee / Sep 15)

### 2025-09 W2 (Sep 09–Sep 15) - Wallet Integration Phase 1

- **Key work:** Phantom wallet connection, basic Solana Web3.js integration
- **Owners:** Bee Nguyễn
- **Deliverables/Evidence (required):**
  - Phantom wallet provider implementation
  - Basic wallet state management
  - Connection/disconnection functionality
  - Commits:
    - [`2df5ec3`](https://github.com/belp-nft/belp-website/commit/2df5ec3) - Implement Phantom wallet connection functionality
    - [`947c3bf`](https://github.com/belp-nft/belp-website/commit/947c3bf) - Configure package manager and dependencies
    - [`38aebb3`](https://github.com/belp-nft/belp-website/commit/38aebb3) - Add environment configuration files
    - [`e3152ea`](https://github.com/belp-nft/belp-website/commit/e3152ea) - Setup production and development environments
- **Metrics/Results:** Phantom wallet connection working, balance display functional
- **Dependencies & Risks / Mitigation:** Phantom extension detection - added fallback install prompts
- **Next Actions (Owner / Due):** Add multi-wallet support (Bee / Sep 22)

### 2025-09 W3 (Sep 16–Sep 22) - Multi-Wallet Support

- **Key work:** Solflare, Backpack, OKX wallet integrations, universal wallet hook
- **Owners:** Bee Nguyễn
- **Deliverables/Evidence (required):**
  - Universal `useWallet` hook supporting 5+ wallets
  - WalletProvider with automatic detection
  - Enhanced wallet selection UI
  - Commits:
    - [`f61fd53`](https://github.com/belp-nft/belp-website/commit/f61fd53) - Add auto-install prompts for missing wallets
    - [`de70218`](https://github.com/belp-nft/belp-website/commit/de70218) - Optimize Dockerfile for Node 20 and improve build process
    - [`cb4f16d`](https://github.com/belp-nft/belp-website/commit/cb4f16d) - Merge Docker improvements to main branch
    - [`14e2e96`](https://github.com/belp-nft/belp-website/commit/14e2e96) - Remove unused build arguments and update Next.js config
    - [`0e62649`](https://github.com/belp-nft/belp-website/commit/0e62649) - Merge production deployment configurations
- **Metrics/Results:** 5 wallet types supported, 95% connection success rate
- **Dependencies & Risks / Mitigation:** Different wallet APIs - standardized through adapter pattern
- **Next Actions (Owner / Due):** Start NFT minting implementation (Bee / Sep 29)

- **Key work:**
  - Developed and tested backend APIs for https://belpy.xyz
  - Setup Candy Machine for NFT minting 
  - Deployed the Belpy NFT website and backend for staging.
- **Owners:** Hieu Trung
- **Links:** 
  - Setup Candy Machine and APIs [API commits](https://github.com/belp-nft/belp-contract/commits?author=trunghph)
  - https://belpy.blockifyy.com
      - Some wallets for testing:
          - https://solscan.io/account/BQKHinECp1JgTi4kvi3uR6fWVP6gFCq4YSch7yJGuBKX?cluster=devnet
          - https://solscan.io/account/Fz4SxAPAbG3PprY47vzdYCWqhesntLKP8q3q8zvjwrtR?cluster=devnet
          - https://solscan.io/account/Fz4SxAPAbG3PprY47vzdYCWqhesntLKP8q3q8zvjwrtR?cluster=devnet
- **Dependencies & Risks / Mitigation:** Some delays were caused by on-chain transaction validation and Candy Machine configuration updates. Testing and verification were repeated across multiple wallets to ensure stable minting performance and correct NFT generation.

### 2025-09 W4 (Sep 23–Sep 29) - Advanced UI Components

- **Key work:** Lore section, image carousels, animation systems
- **Owners:** Bee Nguyễn
- **Deliverables/Evidence (required):**
  - Lore page with story sections and animations
  - Cat carousel with Swiper.js integration
  - Framer Motion animations throughout site
  - Advanced responsive layouts
  - Commits:
    - [`8e11aed`](https://github.com/belp-nft/belp-website/commit/8e11aed) - Implement NFT minting collection functionality
    - [`939cf8e`](https://github.com/belp-nft/belp-website/commit/939cf8e) - Add general updates and improvements
    - [`ba7a6de`](https://github.com/belp-nft/belp-website/commit/ba7a6de) - Remove development files and update gitignore
    - [`bd5d912`](https://github.com/belp-nft/belp-website/commit/bd5d912) - Update landing page with new components
    - [`9a4c98a`](https://github.com/belp-nft/belp-website/commit/9a4c98a) - Upgrade UI framework version for better performance
    - [`8f9cd66`](https://github.com/belp-nft/belp-website/commit/8f9cd66) - Fix ESLint configuration and code formatting
- **Metrics/Results:** Interactive storytelling sections, smooth animations, mobile-optimized
- **Dependencies & Risks / Mitigation:** Animation performance - optimized with Framer Motion best practices
- **Next Actions (Owner / Due):** Begin Candy Machine integration (Bee / Oct 06)

- **Key work:** 
  - Deployed the Belpy NFT admin website
  - Built a simple admin interface for NFT conversion and Candy Machine reconfiguration
- **Owners:** Hieu Trung
- **Links:** 
    - https://admin.belpy.xyz/
    - Some commits setup APIs and update UI:
        - UI[Commits: 9215ea3, 3a023353, 8efaf6e, 42868c5](https://github.com/belp-nft/belp-admin/commits/prod)
        - APIs[Commits](https://github.com/belp-nft/belp-contract/commit/9370abc64a0f96ea8dc4e38a73689646ea6babb9)
- **Dependencies & Risks / Mitigation:**  No major issues encountered.

---

## 3) Monthly Rollup (optional)

### August-September 2025
- **Aug total hours (team):** 120 hours
  - Kate: Design all 5 core pages (Landing, Mint, History, Collection, Lore)
  - Bee Nguyễn: Project setup, UI development, wallet integration (Phantom, Solflare, Backpack, OKX)
  - Hieu Trung: Candy Machine setup, API implementation, admin interface

- **Sep total hours (team):** ~240 hours (estimated: 3 team members × 4 weeks × 20 hrs/week)
  - Bee Nguyễn: Core UI components, advanced animations, Candy Machine integration
  - Hieu Trung: Backend deployment, testing, admin panel development
  - Kate: Design refinements and component specifications

### Top 3 Outcomes
1. **Complete NFT Platform Design & Frontend:** Delivered all 5 core pages (Landing, Mint, History, Collection, Lore) with responsive design, animated components, and modern UI framework. Full wallet integration supporting 5+ wallet providers (Phantom, Solflare, Backpack, OKX).

2. **Candy Machine Integration & NFT Minting:** Successfully configured Metaplex Candy Machine, implemented minting functionality with multi-wallet support, and deployed staging environment at https://belpy.blockifyy.com with active testing and verification across multiple wallets.

3. **Admin Dashboard & Backend Infrastructure:** Built admin interface at https://admin.belpy.xyz for NFT conversion management and Candy Machine reconfiguration. Deployed complete backend API infrastructure supporting minting operations and state management.

### Open Issues & Immediate Actions
- **🔴 Phantom Wallet Domain Verification (CRITICAL):** Phantom wallet requires domain verification for NFT minting operations. Domain verification must be completed before production launch. Action: Contact Phantom support and complete domain verification process for belpy.xyz domain.
- **🔴 High Candy Machine Creation Cost for General Collection**
- **Production Deployment:** Prepare for mainnet deployment once Phantom domain verification is approved. Update DNS and SSL certificates as needed.

