## Luis Hernández

**Software engineer** building real‑time multiplayer systems, full‑stack platforms and cloud infrastructure.
Currently an **RPA & AI Engineer Intern at H‑E‑B**, replacing manual back‑office steps with Power Automate workflows and folding AI‑assisted document handling into them.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luis-hernandez-79b108141/)
[![Email](https://img.shields.io/badge/Email-luisitol2006@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:luisitol2006@gmail.com)

---

### What I like building

Most of what I build has a moment where it stops being a demo. Thirty players hitting the same board at once. A scoring service that has to answer while someone waits. An API that turns out to serve one request at a time under load.

That's the part I find interesting, and it's where I've learned the most — authoritative servers, deterministic state, and putting slow work somewhere it can't block anyone.

---

### Featured projects

| Project | What it is | Stack | Live |
| --- | --- | --- | --- |
| **[Bomb It](https://github.com/oft24/bomb-it-)** | Competitive multiplayer minesweeper racing. Up to 30 players get the exact same board from one server‑side seed — first to clear it clean wins. Five mistakes cost you time; the sixth wipes your board. A `RANDOM` preset turns every cell action into a wager against blackjack, roulette or dice. | TypeScript · Next.js · Socket.IO · Prisma · Supabase | [Play →](https://sector-zero-blush.vercel.app) |
| **[Matching](https://github.com/oft24/Matching)** | Matchmaking platform for players. Profiles cover games, rank and play style, and a dedicated FastAPI service scores how compatible two people actually are — so the algorithm can change without redeploying the API. | React 19 · Express 5 · Prisma · PostgreSQL · FastAPI | [Open →](https://matching-2.vercel.app) |
| **[Inventory System on AWS](https://github.com/oft24/sistema-inventario-aws)** | Stock control API over an append‑only movement log, with automatic alerts when a product drops below its minimum. Containerised on EC2 against managed RDS MySQL, then load tested to find where it actually breaks. | Python · Flask · MySQL · Docker · AWS EC2/RDS | — |
| **[Monolith → Microservices](https://github.com/oft24/luis-hdz-microservicios)** | A registration system split into two services over HTTP to test what really happens when half of it goes down. It degraded instead of failing: registrations were still accepted and stored. | JavaScript · Python · Docker Compose · AWS EC2 | — |
| **Therapy Practice Website** | Client site for a private psychotherapy practice, with appointment booking backed by Supabase, WhatsApp handoff for enquiries and email notification when a slot is taken. | Python · Flask · Supabase · Pytest | — |
| **[BuldakShop](https://github.com/oft24/Bbldak)** | Product catalog and ordering experience built for a friend who sells Buldak products. It combines a multilingual 3D showroom, detailed preparation guidance, Supabase-backed inventory, a persistent cart and demo checkout. | Python · Flask · Supabase · Vanilla JS · Vercel | [App →](https://buldakshop.vercel.app/) 

> My RPA work at H‑E‑B isn't public — attended and unattended automations across enterprise systems, with proper error handling, logging and retries. Happy to talk through the approach.

---

### Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=databricks&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)

**Backend & real‑time**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

**Cloud & automation**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=flat-square&logo=powerautomate&logoColor=white)

---

### Currently

-  Building **BuldakShop** for a friend who sells Buldak products, refining the catalog, product guidance and ordering flow.
-  Shipping **Bomb It** — the next piece is moving the casino wager onto the game server so a modified client can't bypass it.
-  Tuning the compatibility scoring in **Matching** now that it lives in its own service.
-  Automating enterprise processes at **H‑E‑B**, and writing Python utilities for validation and reporting around them.
-  Working in English and Spanish.

---

### Get in touch

I'm open to **internships, junior engineering roles and freelance automation work**. Email is the fastest way to reach me.

[![Email](https://img.shields.io/badge/luisitol2006@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:luisitol2006@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luis-hernandez-79b108141/)
