# Sakditad Pinkaew (Phos)

**Software Engineer** specializing in **Full-Stack, Edge-Native Architectures, and Concurrent Systems**.  
3rd-year IT student at King Mongkut's Institute of Technology Ladkrabang (KMITL).

Passionate about low-latency distributed systems, strict type safety, and real-time application state management.

[Portfolio](https://phos-portfolio.maverxk07.workers.dev/) • [LinkedIn](https://linkedin.com/in/sakditadpinkaew) • [GitHub](https://github.com/Phoz07)[cite: 1] • [Email](mailto:maverxk07@gmail.com)[cite: 1]

---

### 🏆 Key Achievements & Highlights
- **1st Runner-Up (National Round), Huawei ICT Competition 2024–2025 (Computing Track)**  
  Awarded 1st Runner-Up among 140+ nationwide collegiate teams in Linux OS, Database Systems, and CPU Architecture.
- **Production-Proven Engineering:** Developed high-traffic web infrastructure, real-time coordination engines with 150+ concurrent users[cite: 1], and automated verification systems reducing manual audit overhead by 90%[cite: 1].

---

### 🛠️ Core Engineering Stack

- **Languages:** TypeScript, JavaScript, Python, Go, Java, SQL, HTML/CSS, Bash[cite: 1]
- **Frontend & Full-Stack:** React 19, Next.js 15 (App Router, Turbopack), TailwindCSS v4, TanStack Query, Jotai, shadcn/ui[cite: 1]
- **Backend & APIs:** Node.js, Bun, Hono, tRPC, REST APIs (@hono/zod-openapi), Zod, Better-Auth[cite: 1]
- **Edge & Cloud:** Cloudflare Workers / Pages / D1, Linux (Kernel/CLI), Docker, Git[cite: 1]
- **Databases & ORM:** PostgreSQL (Neon), Cloudflare D1 (SQLite), Drizzle ORM, Prisma[cite: 1]

---

### 🚀 Production Track Record & Projects

#### **[PrePro 68 Bootcamp Platform](https://github.com/PrePro68/prepro68-monorepo)**
*Lead Full-Stack Engineer & Core Contributor (Top #1 Contributor — 230+ Commits)*[cite: 1]
- Architected the internal "Hotmail" communication infrastructure (`hotmailRoute.ts`) featuring UUID message tracking, read receipts, and debounced real-time directory search[cite: 1].
- Engineered the "Glearn" LMS video lesson portal with individual progress calculation and edge runtime streaming delivery.
- Implemented edge-level access control via custom middleware (`blockAfterTimeMiddleware.ts`) to enforce strict deadline cutoffs.

#### **[Sairahat 10 Platform & Minigames](https://github.com/Sairahut10-IT-KMITL/sairahat10-monorepo)**
*Full-Stack Engineer (Real-Time Game Engine & Onboarding)*[cite: 1]
- Designed and built the Game Room Coordination Engine (`gameRoom.ts` ~400 lines), resolving concurrency conflicts, room pairing, 6-digit passcode authentication, and randomized clue assignments[cite: 1].
- Optimized query cache invalidation and client-side polling intervals via TanStack Query, reducing server query overhead by 40% during peak events (150+ concurrent students)[cite: 1].
- Developed multi-step student onboarding flows with automated draft persistence (`form_draft`) and role-based access control.

#### **[ITCAMP 22 Web Platform](https://github.com/itcamp22-tech/itcamp22-website)**
*Full-Stack Engineer (Confirmation & Payment Lead)*[cite: 1]
- Developed the end-to-end confirmation and payment pipeline with multi-step draft autosaving (`confirm_application_draft`) running on Cloudflare Workers and D1[cite: 1].
- Integrated PromptPay QR slip verification via SlipOK API, establishing tamper-evident audit logs (`slip_logs`) that reduced manual finance verification time by 90%[cite: 1].
- Built dynamic status resolution workflows filtering candidates across verified, reserve, and unselected states.

#### **[ITCAMP 21 Website](https://github.com/itcamp-21/itcamp-21)**
*Frontend & Full-Stack Developer*[cite: 1]
- Architected the applicant history and status verification module using React Context (`HistoryProvider`) integrated directly with tRPC routers.
- Built interactive landing page animations and dynamic UI components using Framer Motion and Embla Carousel (Interactive Timeline, Dynamic FAQ Accordion, and Travel Guide).
