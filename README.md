<div align="center">

## Gabriel Carlos

Full-stack developer

</div>

I build software that real businesses run on, from the database to the PC on site and the TV on the wall.

### What I've built

**QuadraSystem**: Not a CRUD booking app: a multi-tenant SaaS that runs the whole business, with booking, WhatsApp, payments, invoicing, cash register, stock and on-site hardware. 46 modules, 33 workers, 10+ integrations.

- **Instant replays (end to end):** press a button on the court and get the clip on your phone and on the venue's TV. Edge agent on Linux and Windows, FFmpeg, live cameras, an Android TV app in Kotlin, fleet OTA updates with rollback
- **Customer portal:** mobile-first redesign, cancel and reschedule, packages, loyalty card, team invites and Google sign-in
- **Back office:** permissions per role and per person, finance reconciliation, anti-fraud cash register, stock ledger, time-based promotions, customer dedup and merge
- **WhatsApp:** concurrency-safe booking flow, AI date parsing, waitlist with overbooking, multi-tenant isolation, team inbox with human handoff
- **Operations:** admin console with fleet monitoring, incident alerts, unified logs, support tickets and 2FA, plus an AI sales agent on WhatsApp
- **Quality:** idempotent migrations with a CI drift guard, 450+ test files, and a full UX audit with Playwright (135 findings) fixed in stages

### Other projects

**Autora** <sub>(private)</sub>: a desktop app where an AI agent per social media profile turns a video library into original short-form edits and learns from each post's metrics. Python, FastAPI, Claude API, FFmpeg, React.

**[fraude-paysim](https://github.com/gabecarloss/fraude-paysim)**: fraud detection on PaySim with eight scikit-learn pipelines and a FastAPI demo.

**Airflow + Kafka pipeline** <sub>(private)</sub>: Parquet files land in S3 and are streamed to Kafka, with delivery confirmed.

**[liberty-city-ceasefire](https://github.com/gabecarloss/liberty-city-ceasefire)**: fixes broken GTA III DE saves by patching the running game's memory, so the game re-signs the save.

**[ExpoHotel](https://github.com/gabecarloss/ExpoHotel)**: a hotel booking app with React Native, Supabase and Stripe.

### Stack

<img src="https://go-skill-icons.vercel.app/api/icons?i=ts,nodejs,react,postgres,prisma,redis,kotlin,cs,py,java,fastapi,kafka,docker,githubactions,cloudflare,linux,claude&perline=17" height="40" alt="TypeScript, Node.js, React Native, PostgreSQL, Prisma, Redis, Kotlin, C#, Python, Java, FastAPI, Kafka, Docker, GitHub Actions, Cloudflare, Linux, Claude"/>

- **Languages:** TypeScript, JavaScript, Python, Kotlin, C#, Java, SQL, Bash, PowerShell
- **Frontend and mobile:** React, React Native, Expo Router, Vite, Zustand, TanStack Query, React Hook Form, Zod, Android TV, HTML/CSS
- **Backend:** Node.js, Express, FastAPI, Pydantic, Joi, Socket.IO, BullMQ, REST APIs, webhooks
- **Data and ML:** PostgreSQL, Prisma, Redis, SQLite, Supabase, Apache Airflow, Kafka, PyArrow/Parquet, scikit-learn, Jupyter
- **Video:** FFmpeg, Bunny Stream, TUS, Media Source Extensions
- **Infra:** Docker, Docker Swarm, GitHub Actions, Cloudflare R2, Linux, Windows services, WSL2, Dev Containers
- **Testing and monitoring:** Jest, Vitest, pytest, Playwright, Sentry, Winston
- **Integrations:** WhatsApp (Evolution API, Meta Cloud), OpenAI API, Claude API, Google sign-in, Mercado Pago, Pagar.me, Stripe, AWS SES
- **AI tooling:** Claude Code, MCP, subagents, skills, hooks
- **Tools:** Git, GitHub CLI, VS Code, Postman
