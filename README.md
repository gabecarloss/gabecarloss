<div align="center">

## Gabriel Carlos

Full-stack developer · Development Intern

[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](https://mail.google.com/mail/?view=cm&fs=1&to=devgabrielrigo@gmail.com)


</div>

I like solving real problems for real people. At work that means features that hold up in production and tools that non-technical users can operate on their own. I enjoy problems that cross boundaries: database, API, on-site device and screen.

---

### What I've built

A scheduling platform for service businesses and sports venues, with WhatsApp booking and an AI chatbot.<br/>
<sub>Private repository · 200+ commits · ~300 test files</sub>

- **Instant replays (owner, end to end):** players press a button on the court and get the last few minutes as a clip. A PC cuts it with FFmpeg, adds intros and sponsors, uploads it to Bunny Stream, and it plays on a public portal and on the venue's TV.
- **Android TV app (Kotlin):** a self-updating APK for the venue's screen, with remote-control navigation and performance tuned for Fire TV Stick.
- **Live cameras:** H.264 streams from the court remuxed to fMP4 and played in the browser with Media Source Extensions, plus live streaming.
- **Edge agent:** a Node.js service on Linux and Windows PCs, with one-command install, fleet OTA updates with rollback, and a LAN cache that feeds the TV. On Windows it runs as a service, with a C# installer and tray app.
- **Booking core:** WhatsApp booking with concurrency-safe slots on PostgreSQL, a waitlist, AI date parsing, and customer self-service.
- **Support and operations:** an admin console with fleet monitoring, incident alerts, unified logs, support tickets and 2FA, plus an installation guide written for non-technical users.
- **Quality:** idempotent migrations with a drift guard in CI, and fixes for timezone, concurrency and IDOR bugs.
- **Testing:** unit and integration tests with Jest, gated in CI against a baseline; hardware tests across camera and button types; real installs of the edge agent on Linux and Windows PCs, with Windows also on every CI run; and Playwright for visual smoke tests and an end-to-end UX audit of the whole system.




### AI-assisted engineering

I use **Claude Code** every day on a production monorepo, with the same review discipline as hand-written code: tests, CI and manually reviewed migrations.

- I maintain layered `CLAUDE.md` files with the project's architecture and rules, plus project skills for verification, safe schema migrations, UI smoke tests and deploy promotion.
- I set up guard-rail hooks, rolled out the security-guidance plugin to the team, and connect MCP servers (Sentry, Cloudflare, Mercado Pago, Playwright).
- I work with plan mode, subagents, persistent memory, and AI-assisted code and security review.

### Stack

<img src="https://skillicons.dev/icons?i=ts,nodejs,react,postgres,prisma,redis,kotlin,cs,python,docker,githubactions,cloudflare,linux" height="40" alt="TypeScript, Node.js, React Native, PostgreSQL, Prisma, Redis, Kotlin, C#, Python, Docker, GitHub Actions, Cloudflare, Linux"/>

- **Languages:** TypeScript, JavaScript, SQL, Kotlin, C#, Python, Java, Bash, PowerShell
- **Frontend & mobile:** React Native, Expo Router, Zustand, Zod, Android TV, HTML/CSS
- **Backend & data:** Node.js, Express, Prisma, PostgreSQL (Supabase), Redis, BullMQ, Socket.IO, Joi, FastAPI, scikit-learn
- **Infra & quality:** Docker Swarm, GitHub Actions, Cloudflare R2, FFmpeg, Sentry, Winston, Jest, Playwright
- **Integrations:** WhatsApp (Evolution API, Meta Cloud), OpenAI API, Bunny Stream, Mercado Pago, Pagar.me, Stripe, AWS SES
- **Tools:** Claude Code, MCP, VS Code, WSL2, Dev Containers, Git, GitHub CLI, Postman, Jupyter
