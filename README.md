# Jueun Park

**Full-Stack Developer**

I build product-oriented web systems with React and TypeScript, and usually take responsibility beyond the UI — API design, data modeling, authentication, deployment, and operational edge cases included.

[Portfolio](https://jueun.ai.kr/)

---

## Core Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white)

### Also Worked With

`JavaScript` `Python` `C` `Lua` `Next.js` `Vite` `Tailwind CSS` `Zustand` `TanStack Query` `FastAPI` `Discord.js` `discord.py` `GitHub Actions` `Playwright` `Vitest`

### Design

`Figma` `Photoshop` `Illustrator` `Premiere Pro` `After Effects`

---

## Selected Projects

### [GuildRank](https://github.com/rhazns22/GuildRank)

Full-stack Discord community platform for member management, seasonal progression, rewards, party coordination, game server monitoring, and bot-driven community operations.

[Frontend](https://github.com/rhazns22/GuildRank) · [Backend](https://github.com/rhazns22/GuildRank_sever)

**Engineering notes**
- Runs the Express API and Discord bot in a single Node.js process, with deployment constrained to one replica to prevent duplicate gateway sessions.
- Synchronizes Discord guild membership and roles with web-side identities and permissions.
- Separates season, point, reward, party, game-server, voice, and admin domains into independent services and routes.
- Uses PostgreSQL + Prisma for persistent domain state and Redis for session / runtime coordination.
- Supports both web and Tauri desktop builds.

`React` `TypeScript` `Tauri` `Express` `Discord.js` `PostgreSQL` `Prisma` `Redis` `Railway`

---

### [NULLTRACE 4093](https://github.com/rhazns22/NULLTRACE4093_FND)

Browser-based ARG built around observation, evidence, and verification rather than conventional puzzle progression.

[Live](https://4093nulltracepage3904.vercel.app/) · [Frontend](https://github.com/rhazns22/NULLTRACE4093_FND) · [Backend](https://github.com/rhazns22/NULLTRACE4093_BND)

**Engineering notes**
- Encodes clues through interaction state and computed CSS properties instead of relying only on visible UI.
- Tracks anonymous session state and restores interrupted runs through a repository-backed local persistence layer.
- Issues structured stage receipts with SHA-256 checksums using the Web Crypto API.
- Distinguishes verified and incomplete-evidence paths without pretending to detect AI use, DevTools, or external tools.
- Covers the Stage 1 flow with Playwright regression tests and static deployment through GitHub Actions.

`React` `TypeScript` `Vite` `Web Crypto API` `Playwright` `GitHub Actions` `Vercel`

---

### Chaengim

Mobile-first PWA for discovering government benefits from user profile data and managing application progress, required documents, deadlines, and recommendations.

[Frontend](https://github.com/rhazns22/chaengimweb) · [Backend](https://github.com/rhazns22/chaengim)

**Engineering notes**
- Combines rule-based eligibility filtering with Gemini-generated recommendation context instead of delegating the whole decision path to an LLM.
- Enforces ownership from the authenticated JWT identity instead of trusting client-provided user IDs.
- Models users, profiles, benefits, saved applications, checklists, AI recommendations, notifications, and sync jobs as relational domain data.
- Applies separate rate limits to general traffic, authentication, and AI-generation endpoints.
- Handles email verification with hashed one-time codes, expiry, resend cooldowns, and failed-attempt lockout logic.

`React` `TypeScript` `Express` `Prisma` `MySQL` `Gemini API` `Railway`

---

### SiteOps

Workflow system for website maintenance requests, assignment, review, approval, activity history, and customer-facing status tracking.

[Frontend](https://github.com/rhazns22/SiteOps_Front) · [Backend](https://github.com/rhazns22/SiteOps_back)

**Engineering notes**
- Models request state transitions across received, in-progress, review-requested, completed, and rejected states.
- Separates admin, worker, and client roles with authenticated API access.
- Keeps uploaded assets private in Supabase Storage and exposes them through time-limited signed URLs.
- Uses Zod at API boundaries, centralized async error handling, JWT auth, Helmet, rate limiting, and Prisma-backed relational data.
- Preserves request activity and review history instead of treating status as a single mutable field.

`React` `TypeScript` `Express` `PostgreSQL` `Supabase` `Prisma` `Zod`

---

### [PetLog](https://github.com/rhazns22/petlogwep)

Web application for recording and organizing veterinary expenses, including AI-assisted receipt analysis and structured expense data.

`React` `TypeScript` `Firebase` `Firestore` `Gemini API` `Vercel`

---

## Other Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

