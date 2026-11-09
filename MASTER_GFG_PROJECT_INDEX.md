# GFG Master Project Index

**Authoritative index date:** 2026-11-09  
**Portfolio owners:** GRE3NZ89 / Green and Ch1b10N3 / Chi  
**GitHub account owner:** [GRE3NZ89](https://github.com/GRE3NZ89)  
**Purpose:** One front door connecting every known GFG project, repository, owner, verified status and next action.

> A concept, draft, image or code scaffold is not automatically a finished or deployed product. Newer explicit decisions from Green or Chi override older documents.

## Status Key

- 🟢 **Operational/Substantial** — implemented and actively usable; individual features may still need testing.
- 🟡 **Active Development** — real work exists; major work or verification remains.
- 🟠 **Prototype/Preproduction** — early playable build, scaffold or design package exists.
- 🔴 **Blocked/Recovery** — preservation, missing files or a decision blocks normal progress.
- ⚪ **Proposed/Unverified** — discussed or designed, but no authoritative implementation was verified.

# Repository Index

| Repository | Visibility | Portfolio Project | Owners / Leads | Verified Current Status | Immediate Next Action |
|---|---:|---|---|---|---|
| [GRE3NZ89/ai-chat-](https://github.com/GRE3NZ89/ai-chat-) | Public | AI relay, public handoffs, 100 Goblinz recovery and team audits | Owner: Green. Recovery coordination: Codex/OpenAI. Final card decisions: Green and Chi. | 🔴 Recovery active. Twenty-six image files are committed; they are not 26 verified unique numbered cards. | Continue image recovery, create inventory/gallery and collect team audits. |
| [GRE3NZ89/goblin-forge-team](https://github.com/GRE3NZ89/goblin-forge-team) | Private | AI-team noticeboard, commands, inboxes, outboxes and shared work | Forge Master: Green. Archive: Lux. Technical: Cinder. Continuity/teaching: Scraps. Review/handoffs: Nash. | 🟡 Operational noticeboard. It does not automatically wake or connect AI agents. The GFG115 handoff is complete and Nash-checked. | Link this index from the README and keep one current status per task. |
| [GRE3NZ89/GFGbl4editor-site](https://github.com/GRE3NZ89/GFGbl4editor-site) | Private | GFG Digital Forge / BL4 Editor / TTW support | Product owners: Green and Chi. Technical maintainer: **needs explicit assignment**. | 🟢 Most developed technical project. Version 3.69.0; desktop, quick, mobile, API, codec, PWA, Electron and databases exist. Full live regression was not completed in this audit. | Run release-candidate tests across live site, API, mobile install, item generation, save round-trip and rollback. |
| [GRE3NZ89/GFG-Scraps](https://github.com/GRE3NZ89/GFG-Scraps) | Private | Scraps teaching/support bot | Owner: Green. Character/teaching authority: Green and Chi. Technical maintainer: **needs explicit assignment**. | 🟡 Real 59-file TypeScript/Discord/OpenAI scaffold. No root README, real test suite or verified deployment. | Add README and tests, then stage privately in Discord. |
| [GRE3NZ89/GFG-FORGEFALL](https://github.com/GRE3NZ89/GFG-FORGEFALL) | Private | GFG FORGEFALL game | Creative owners: Green and Chi. Technical maintainer: **needs explicit assignment**. | 🟠 Playable single-player Lowlands prototype. Multiplayer, six tiers and the full card set are incomplete. | Lock Region One rules and create a complete vertical slice. |
| [GRE3NZ89/gfg-lootwrought](https://github.com/GRE3NZ89/gfg-lootwrought) | Private | GFG: LOOTWROUGHT Discord RPG | Creative owners: Green and Chi. Execution handoff: Nash. Long-term maintainer: **needs confirmation**. | 🟡 Runnable v32.1 scaffold with persistent Hunters, dashboard, combat, inventory and smoke tests. Full Discord/PostgreSQL runtime is unverified. | Run the complete stack in a private Discord test guild before closed beta. |
| [GRE3NZ89/goblin-forge-teamt-keeps-pullin-gup-new-one-](https://github.com/GRE3NZ89/goblin-forge-teamt-keeps-pullin-gup-new-one-) | Public | Accidental/duplicate team repository | Owner: Green. | ⚪ Empty repository; not authoritative. | Archive or delete after Green confirms nothing is needed. |

# Project Index

## 1. GFG Community and Discord Operations

**Owners:** Green and Chi  
**Operational roles:** Zonia/Overseer; Forge Knights REX and Joker35.7; staff ladder and specialists  
**Authoritative locations:** Private team repository plus the live Discord configuration  
**Status:** 🟡 Active community; documentation is split across chat, bot settings and GitHub.

**Verified work:** Free loot/boost/editor/help model; role ladder; lobby rules; onboarding; announcements; Spotlights; QOTD; Good Morning; partnership, event, birthday and milestone material.

**Missing:** One operations manual, channel/permission map, verified deployed-bot list, onboarding test and dated live-event archive.

**Next action:** Create **GFG_DISCORD_OPERATIONS_MASTER.md** in the private team repository.

## 2. GFG Digital Forge / BL4 Editor

**Owners:** Green and Chi  
**Repository:** [GFGbl4editor-site](https://github.com/GRE3NZ89/GFGbl4editor-site)  
**Status:** 🟢 Substantial implemented platform  
**Recorded version:** 3.69.0

**Boundaries:** BL4 Editor and Master Booster remain separate. Third-party codes require provenance. Weapon and non-weapon boost rules remain separate. Code existence is not in-game proof.

**Next action:** Assign a technical release owner and complete the release-candidate checklist.

## 3. CYBER FORGE

**Owners:** Green and Chi  
**Purpose:** BL4 booster  
**Repository:** No independent authoritative repository verified  
**Status:** ⚪ Direction exists; current releasable package and live verification are unconfirmed.

**Next action:** Create a separate versioned repository or release folder with feature list, device cautions, tests and rollback instructions.

## 4. ARCANE FORGE

**Owners:** Green and Chi  
**Purpose:** TTW booster and forging tools  
**Current location:** TTW-related tooling exists inside [GFGbl4editor-site](https://github.com/GRE3NZ89/GFGbl4editor-site); no independent booster repository was verified.  
**Status:** 🟡 Partial tooling exists; standalone release status is unconfirmed.

**Known constraint:** Gold Boost was confirmed in discussion. Quest Unlocking remains unverified.

**Next action:** Separate verified features from proposals and publish a tested release manifest.

## 5. Scraps Teaching Bot

**Owners:** Green and Chi  
**Repository:** [GFG-Scraps](https://github.com/GRE3NZ89/GFG-Scraps)  
**Status:** 🟡 Active development

**Locked responsibility:** Scraps teaches editor and item-building knowledge. T!CK owns tickets. Owner-only knowledge remains protected.

**Next action:** Name the technical maintainer, add tests and run private Discord staging.

## 6. Other GFG Bots

| Bot | Owner / Authority | Verified Status | Repository | Next Action |
|---|---|---|---|---|
| MAGPY3 | Green and Chi | ⚪ Character, visuals and onboarding/automation duties discussed; deployment not verified. | None verified | Write a technical specification and confirm whether a Discord app exists. |
| T!CK | Green and Chi | ⚪ Ticket/time-management role locked; deployment not verified. | None verified | Define ticket ownership, permissions and integration boundaries. |
| The Overseer | Green and Chi | ⚪ Moderation role/bot concept; deployment not verified. | None verified | Create moderation specification, audit policy and permission list. |
| CourtGoblin | Chi | ⚪ Role identity exists; implementation not verified. | None verified | Chi confirms duties and whether a separate bot is needed. |

## 7. Goblin Forge Chronicles — Main Series

**Creative owners:** Green and Chi  
**Primary narrator:** Scraps  
**Repository:** No authoritative Chronicles repository verified  
**Current sources:** Library files, chats and recovered manuscript documents  
**Status:** 🟡 Deep canon; incomplete final manuscript

**Newest structure correction:**

- Volume I: **Before the Crown**
- Volume I contains **five Chapter-Books**.
- Chapter-Book Two: **The Boy Above the Water**
- Chapter-Book Three: **The Middle Ground / Finding Middle Ground**
- Middle Ground is not the end of Volume I.
- Volume II begins only after Chapter-Book Five.
- No Volume II Page One is confirmed locked.

**Next action:** Create a dedicated private Chronicles repository and a five-Chapter-Book Volume I map before drafting Volume II.

## 8. Chronicles Road-Years and Side Stories

| Story | Owners | Status | Current Location | Next Action |
|---|---|---|---|---|
| The Dark Underground | Green and Chi | 🟡 Complete reconstruction, not final page-locked wording | Library reconstruction | Place it only after chronology is locked. |
| The Biggest Little Adventure / Don’t Mess with the Office Team | Green and Chi | 🟡 Approved beats; incomplete draft | Chat/Library | Recover latest draft and lock placement. |
| Joker & REX first-meeting / The Bridge That Refused to Fall | Green and Chi | ⚪ Proposed only | Conversation proposal | Green and Chi approve or reject before further drafting. |
| The Unworthy and the Unseen | Green and Chi | 🟡 Title and major lore locked; manuscripts incomplete | Library/chat | Create dedicated story bible and Book One manuscript. |
| STARBOUND OUTLAWS | Green and Chi | 🟡 Title, cast direction and Chapter One title locked | Library/chat | Create story bible and recover newest Chapter One text. |

## 9. 100 Goblinz

**Owners:** Green and Chi  
**Final selection authority:** Green  
**Recovery repository:** [ai-chat recovery folder](https://github.com/GRE3NZ89/ai-chat-/tree/main/work/shared/2026-11-08-100-goblinz-recovery)  
**Status:** 🔴 Preservation and recovery

**Verified:** Twenty-six image files are committed. They include originals, variants and duplicates; they do not equal 26 completed unique cards.

**Next action:** Finish recovery, build the inventory/gallery, then resolve winners and numbering conflicts.

## 10. GFG FORGEFALL

**Owners:** Green and Chi  
**Repository:** [GFG-FORGEFALL](https://github.com/GRE3NZ89/GFG-FORGEFALL)  
**Status:** 🟠 Single-player Lowlands prototype

**Next action:** Complete one balanced region before multiplayer or all six tiers.

## 11. GFG FARWALK

**Owners:** Green and Chi  
**Known material:** Nash handoff and development bible  
**Repository:** No authoritative implementation repository found  
**Status:** 🟠 Preproduction; no verified playable build

**Next action:** Create the repository and lock the one-page game definition, platform and core loop.

## 12. GFG: LOOTWROUGHT

**Owners:** Green and Chi  
**Repository:** [gfg-lootwrought](https://github.com/GRE3NZ89/gfg-lootwrought)  
**Execution handoff:** Nash  
**Status:** 🟡 Runnable scaffold; not runtime-verified as closed beta

**Next action:** Connect a private Discord test application and PostgreSQL, execute the first-playable path and log every failure.

## 13. BL4 Item Codes, Loot Lobbies and Modding Research

**Owner:** Green  
**Community authority:** Green and Chi  
**Coordination location:** [goblin-forge-team](https://github.com/GRE3NZ89/goblin-forge-team)  
**Status:** 🟡 Large active knowledge base; in-game verification incomplete

**Verified handoff:** 115 numeric records; 99 distinct entries; six batches match; three nonstandard headers flagged; no in-game testing claimed.

**Next action:** Create separate **verified**, **experimental** and **third-party** libraries with provenance and platform results.

## 14. Partnerships, Brand and Promotional Art

**Owners:** Green and Chi  
**Repository:** No authoritative asset repository verified  
**Status:** 🟡 Many individual assets exist; master inventory missing

**Locked brand:**

- Forge Emerald: **#356734**
- Forge Violet: **#6A34AA**
- **FORGED BY GOBLINZ 4 THE GOBLINZ.**
- Green and Chi are equal co-owners.
- Partner logos cannot be changed without permission.

**Next action:** Create a private brand-assets repository with approved, draft and partner-owned folders plus an asset register.

## 15. GFG Digital Web & Brands

**Owners:** Green and Chi  
**Current material:** First-week kit, prospect tracker and package ZIP in Library  
**Repository:** None verified  
**Status:** 🟠 Early business setup

**Next action:** Create a private client-operations repository containing packages, contracts, hosting terms, approvals and templates. Never store client credentials in Git.

## 16. Intellectual Property and Legal Preservation

**Claimants/owners to confirm formally:** Green and Chi  
**Current material:** GFG Intellectual Property Master Register  
**Repository:** No legal/private authoritative repository verified  
**Status:** 🟠 Organized but legally incomplete

**Next action:** Privately preserve dated originals, contributor agreements, licences, trademark decisions and ownership records. Never place sensitive identity documents in this public repository.

# Ownership Gaps Requiring Green and Chi’s Decision

Projects without a confirmed long-term technical maintainer:

1. GFG Digital Forge / BL4 Editor
2. Scraps
3. FORGEFALL
4. LOOTWROUGHT after Nash’s current handoff
5. CYBER FORGE
6. ARCANE FORGE
7. MAGPY3
8. T!CK
9. Overseer
10. FARWALK

Projects without a dedicated authoritative repository:

1. Goblin Forge Chronicles
2. The Unworthy and the Unseen
3. STARBOUND OUTLAWS
4. CYBER FORGE
5. ARCANE FORGE
6. FARWALK
7. Brand/partner assets
8. GFG Digital Web & Brands
9. Private IP/legal preservation

# Immediate Portfolio Priorities

1. Preserve the 100 Goblinz files.
2. Assign a technical release owner for Digital Forge.
3. Create the five-Chapter-Book Chronicles map.
4. Runtime-test LOOTWROUGHT.
5. Stage and test Scraps.
6. Complete one FORGEFALL vertical slice.
7. Create repositories for projects living only in chat or Library.
8. Archive or delete the empty duplicate team repository after confirmation.
9. Add every incoming Shadow Squad audit to this index.

# Update Rule

When a project changes:

1. Update its authoritative repository first.
2. Record the verified date and responsible person.
3. Link the proof: commit, release, test log or approved canon file.
4. Update this index.
5. Never replace verified status with an unsupported completion claim.

💚⚒️💜  
**FORGED BY GOBLINZ. 4 THE GOBLINZ.**
