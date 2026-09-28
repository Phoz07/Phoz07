# Sakditad Pinkaew (Phos)

**Software Engineer** specializing in **Full-Stack, Edge-Native Architectures, and Concurrent Systems**.  
3rd-year IT student at King Mongkut's Institute of Technology Ladkrabang (KMITL).

Passionate about low-latency distributed systems, strict type safety, and real-time application state management.

[Portfolio](https://phos-portfolio.maverxk07.workers.dev/) • [LinkedIn](https://linkedin.com/in/sakditadpinkaew) • [Resume / CV](https://phos-portfolio.maverxk07.workers.dev/) • [GitHub](https://github.com/Phoz07) • [Email](mailto:maverxk07@gmail.com)

---

### 🏆 Key Achievements & Honors
- **1st Runner-Up (National Round), Huawei ICT Competition 2024–2025 (Computing Track)**  
  Awarded National 1st Runner-Up among 140+ collegiate teams nationwide in Linux OS, Database Systems, and CPU Architecture (40,000 THB prize).
- **Production Track Record:** Engineered scalable systems supporting 500+ applicants, real-time game coordination for 150+ concurrent users, and automated financial audits cutting manual overhead by 90%.

---

### 🛠️ Core Engineering Stack

- **Languages:** TypeScript, JavaScript, Python, Go, Java, SQL, HTML/CSS, Bash
- **Frontend & Full-Stack:** React 19, Next.js 15 (App Router, Turbopack), TailwindCSS v4, TanStack Query, Jotai, shadcn/ui
- **Backend & APIs:** Node.js, Bun, Hono, tRPC, RESTful APIs, OpenAPI/Swagger (@hono/zod-openapi), Zod, Better-Auth
- **Edge, Cloud & Tools:** Cloudflare Workers / Pages / D1, Linux (Kernel/CLI), Docker, Docker Compose, SlipOK API, Git
- **Databases & ORM:** PostgreSQL (Neon), Cloudflare D1 (SQLite), Drizzle ORM, Prisma

---

### 🚀 Production Track Record & Projects

#### **[PrePro 68 Bootcamp Platform](https://github.com/PrePro68/prepro68-monorepo)**
*Role: Lead Full-Stack Engineer & Core Contributor (Top #1 Contributor — 234 Commits, >50% of Codebase)*
- Served as the lead contributor for a full-stack monorepo built with Cloudflare Workers (Hono), Next.js, and Drizzle ORM serving 300+ students.
- Architected the internal "Hotmail" messaging infrastructure featuring debounced real-time directory search, read receipts, and role-based mentor-freshman routing.
- Developed the "Glearn" video LMS with individual progress tracking and Edge runtime optimization, alongside onsite registration with time-based cutoff middleware.

#### **[Sairahat 10 Platform & Minigames](https://github.com/Sairahut10-IT-KMITL/sairahat10-monorepo)**
*Role: Full-Stack Engineer (Real-Time Game Engine & Onboarding)*
- Engineered a real-time multiplayer orientation system using Next.js 15 (React 19), PostgreSQL (Neon), Drizzle ORM, tRPC, and TanStack Query (100 core commits).
- Developed the game room coordination engine (`gameRoom.ts`) with concurrency conflict resolution, 6-digit passcode authorization, and query polling tuning that cut server overhead by 40% for 150+ concurrent students.
- Implemented multi-step onboarding registration flows with auto-saving drafts (`form_draft`), role-based auth routing, and time-based registration cutoff gates.

#### **[ITCAMP 22 Web Platform](https://github.com/itcamp22-tech/itcamp22-website)**
*Role: Full-Stack Engineer (Confirmation & Payment Lead)*
- Engineered an end-to-end confirmation module for 500+ applicants using Next.js 15, Cloudflare Workers (Hono), Better-Auth, and Drizzle ORM on Cloudflare D1 & R2.
- Integrated SlipOK API for automated PromptPay QR slip verification (649 THB), slashing manual finance auditing by 90% with tamper-evident audit logs (`slip_logs`).
- Implemented a multi-step confirmation wizard with auto-saving draft state (`confirm_application_draft`), edge rate-limiting (5 uploads/24h), and dynamic status resolution for admitted and waitlisted candidates.

#### **[ITCAMP 21 Portal](https://github.com/itcamp-21/itcamp-21)**
*Role: Frontend & Full-Stack Developer*
- Engineered a candidate application history and status tracking portal using Next.js 15, tRPC, and React Context (`HistoryProvider`), enabling transparent status verification.
- Designed responsive UI modules using Framer Motion and Embla Carousel, delivering interactive event timelines, travel guides, and dynamic FAQ accordions.
