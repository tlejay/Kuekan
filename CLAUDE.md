# CLAUDE.md - KueKan Project Guide

## Project Overview

**KueKan (คือกัน)** is a Loyalty & Rewards platform with Gamification capabilities, developed by **Digitalmedia Outsource Solution Co., Ltd. (DOS)**.

### What is KueKan?
- A centralized loyalty and engagement platform using gamification mechanics
- Designed as digital economic infrastructure for cities, organizations, and businesses
- LINE-first approach (Thai market focus) - no separate app download required
- Multi-tenant capable for enterprise deployments

### Core Value Propositions
1. **For End Users:** Earn points through missions (check-ins, purchases, actions), redeem rewards
2. **For Partners/Merchants:** QR-based point distribution and redemption, analytics dashboard
3. **For Administrators:** Full ecosystem management, fraud detection, analytics

---

## Company Context

**Developer:** Digitalmedia Outsource Solution Co., Ltd. (DOS)
- **Team:** 30+ members, 12+ years experience, 100+ projects completed
- **Expertise:** E-Commerce, Customer Loyalty & Rewards, Mobile Apps, Cloud Architecture
- **Tech Stacks:** Laravel, Next.js/Nuxt, Flutter, GCP/AWS, PostgreSQL, MongoDB, Redis

### Leadership
- **Jakapong (Tle)** - Chief Operating Officer
- **Nitipong (Ohm)** - Head of Design
- **Surasee (Peck)** - Head of Infrastructure
- **Wasin (Gift)** - Head of Developer

---

## Technical Architecture

### Applications
1. **Customer Mobile Site** - Web app for LINE integration (end users)
2. **Partner Mobile Site** - Web app for merchants/event staff
3. **Admin Console** - Full management dashboard

### Tech Stack
- **Backend:** Laravel PHP, RESTful API, JWT Auth
- **Databases:** PostgreSQL (primary), MongoDB (logs), Redis (cache)
- **Cloud:** Google Cloud Platform (GCP)
- **Integrations:** LINE Login/Messaging, Google Maps, SMS Gateway, Sentry

### Key Technical Features
- Geofencing for location-based missions
- QR code hybrid system (single QR for multiple actions)
- Real-time fraud detection
- PDPA compliance (Thai privacy law)

---

## Project Phases

### Phase 1: POC (Proof of Concept)
- **Budget:** THB 1,000,000
- **Timeline:** 8-10 weeks
- **Scope:** Basic LINE login, check-in missions, point display, partner QR scanner

### Phase 2: MVP (Minimum Viable Product)
- **Budget:** THB 3,000,000 - 5,000,000
- **Timeline:** 16-20 weeks
- **Scope:** Full mission types, rewards catalog, tiering, fraud prevention, analytics

### Phase 3: Full-Scale Ecosystem
- **Budget:** ~THB 10,000,000
- **Timeline:** 24-30 weeks
- **Scope:** AI fraud detection, personalization, multi-tenant, credit card integration

---

## Target Markets

### 1. Korat PAO (Provincial Administration Organization)
- Government partnership for "Smart City" initiatives
- Tourism promotion through gamified check-ins
- Public health campaigns
- Data-driven policy making

### 2. Korat NCC (Chamber of Commerce)
- Shared loyalty system for SME members
- Event gamification (Korat Mega Sale)
- Cross-promotion between member businesses
- MICE and wellness tourism

---

## Workspace Structure

```
/Kuekan
├── 00 Preparation/          # Business context and prep documents
├── 01 Proposals/            # Client proposals and pitches
│   ├── Archived/            # ⚠️ OLD DOCUMENTS - DO NOT ANALYZE
│   └── Presentations/       # PowerPoint/Keynote presentation files
├── 02 Requirements/         # Feature specs and requirements
├── 03 Design/               # UI/UX designs and wireframes
├── 04 Technical/            # Technical specs and architecture
├── 05 Marketing/            # Marketing materials and content
├── 06 Contracts/            # Legal documents and agreements
├── 07 Project Management/   # Timelines, meeting notes, status
└── 08 Assets/               # Images, logos, brand assets
```

### Excluded Folders
The following folders contain outdated documents and should **NOT** be analyzed:
- `01 Proposals/Archived/` - Legacy proposals (kept for reference only)

---

## Writing Guidelines

### Language
- **Primary:** Thai (ภาษาไทย) for client-facing documents
- **Secondary:** English for technical documentation
- **Bilingual:** Business proposals should include both languages

### Document Standards
- Use markdown format for all documentation
- Include version numbers and dates
- Reference feature IDs from the feature list (e.g., 1.2.1 for Location-Based missions)

### Key Terminology
| English | Thai | Description |
|---------|------|-------------|
| KueKan Pocket | กระเป๋าแต้ม | Central point wallet |
| Mission | ภารกิจ | Gamified tasks to earn points |
| Partner | พันธมิตร | Merchant/business partner |
| Tier | ระดับสมาชิก | Membership level |
| Redemption | การแลกรางวัล | Point exchange for rewards |

---

## AI Agent Instructions

### When Creating Documents
1. Always reference the feature list in `00 Preparation/Prep KueKan Features.md`
2. Consider Thai language support where applicable
3. Follow enterprise-grade standards (major clients include SCG, CP ALL, Central)
4. Include proper cost estimates based on engagement models in Business Context

### When Analyzing Requirements
1. Map requirements to existing features using the feature matrix
2. Identify which phase (POC/MVP/Full-Scale) features belong to
3. Flag any features not in the current scope

### When Writing Proposals
1. Reference strategic alignment from Prep Korat PAO/NCC documents
2. Include measurable KPIs (the platform's key selling point)
3. Emphasize LINE-first approach for Thai market accessibility

---

## Important Contacts

**Primary Contact:**
- **Jakapong Lomvong (Tle)** - COO
- Email: jakapong@digitalmedia.co.th
- Phone: 088-622-2488

---

## Quick Reference

- **Feature List:** `00 Preparation/Prep KueKan Features.md`
- **Business Context:** `00 Preparation/Business_Context.md`
- **Korat PAO Strategy:** `00 Preparation/Prep Korat PAO.md`
- **Korat NCC Strategy:** `00 Preparation/Prep Korat NCC.md`
