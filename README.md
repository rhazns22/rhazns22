
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

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111111)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=111111)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433E38?style=flat-square)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Discord.js](https://img.shields.io/badge/Discord.js-5865F2?style=flat-square&logo=discord&logoColor=white)
![discord.py](https://img.shields.io/badge/discord.py-5865F2?style=flat-square&logo=discord&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Unreal Engine](https://img.shields.io/badge/Unreal_Engine-0E1128?style=flat-square&logo=unrealengine&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-F05138?style=flat-square&logo=swift&logoColor=white)

### Design

![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Adobe Photoshop](https://img.shields.io/badge/Photoshop-31A8FF?style=flat-square&logo=adobephotoshop&logoColor=white)
![Adobe Illustrator](https://img.shields.io/badge/Illustrator-FF9A00?style=flat-square&logo=adobeillustrator&logoColor=white)
![Adobe Premiere Pro](https://img.shields.io/badge/Premiere_Pro-9999FF?style=flat-square&logo=adobepremierepro&logoColor=white)
![Adobe After Effects](https://img.shields.io/badge/After_Effects-9999FF?style=flat-square&logo=adobeaftereffects&logoColor=white)

---

## Selected Projects

### GuildRank

Full-stack Discord community platform for member management, seasonal progression, rewards, party coordination, game server monitoring, and bot-driven community operations.

_Source code is private._

**Engineering notes**
- Runs the Express API and Discord bot in a single Node.js process, with deployment constrained to one replica to prevent duplicate gateway sessions.
- Synchronizes Discord guild membership and roles with web-side identities and permissions.
- Separates season, point, reward, party, game-server, voice, and admin domains into independent services and routes.
- Uses PostgreSQL + Prisma for persistent domain state and Redis for session / runtime coordination.
- Supports both web and Tauri desktop builds.

`React` `TypeScript` `Tauri` `Express` `Discord.js` `PostgreSQL` `Prisma` `Redis` `Railway`

---

### NULLTRACE 4093

Browser-based ARG built around observation, evidence, and verification rather than conventional puzzle progression.

[Live](https://4093nulltracepage3904.vercel.app/) · _Source code is private._

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

[Live](https://chaengim.vercel.app/) · _Source code is private._

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

_Source code is private._

**Engineering notes**
- Models request state transitions across received, in-progress, review-requested, completed, and rejected states.
- Separates admin, worker, and client roles with authenticated API access.
- Keeps uploaded assets private in Supabase Storage and exposes them through time-limited signed URLs.
- Uses Zod at API boundaries, centralized async error handling, JWT auth, Helmet, rate limiting, and Prisma-backed relational data.
- Preserves request activity and review history instead of treating status as a single mutable field.

`React` `TypeScript` `Express` `PostgreSQL` `Supabase` `Prisma` `Zod`

---

### PetLog

Web application for recording and organizing veterinary expenses, including AI-assisted receipt analysis and structured expense data.

_Source code is private._

**Engineering notes**
- Uses a human-in-the-loop flow: AI-extracted receipt data is treated as a draft and is only persisted after user review and correction.
- Proxies Gemini requests through a Vercel Serverless Function so API credentials are not exposed in the client bundle.
- Resizes and compresses high-resolution receipt images in the browser before upload to reduce transfer cost and analysis latency.
- Stores authenticated user data in Firebase and keeps expense records, pet profiles, and receipt assets separated by user context.
- Provides fallback paths for malformed AI responses, failed analysis, and manual entry.

`React` `TypeScript` `Firebase` `Firestore` `Gemini API` `Vercel`

---

## Other Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

