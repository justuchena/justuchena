# 💫 About Me:

🔭 **I'm currently building:** [Whollify](https://whollify.com), an education platform where I own the core systems end to end: the API, the student-facing applications, the assessment engine, and the automation that runs live learner cohorts.

🛠️ **How I work:** I go deep rather than wide. Most of what I build is long-lived production software that other people depend on daily, which means I care as much about migrations, test coverage, and observability as about shipping the feature.

🌱 **I'm currently learning:** How to align my energy and habits with my goals, how to communicate more effectively, and how to stay grounded in purpose through growth.

🤝 **I'm looking for help with:** Navigating new creative and career transitions, and staying focused while balancing big ideas with day-to-day execution.

💬 **Ask me about:** Designing assessment systems, running technical cohorts, multi-tenant platform architecture, conversational AI, messaging infrastructure at scale, or self-discovery and real conversations.

⚡ **Fun fact:** I notice the small stuff, like the tone in a message or the vibe in a room, and I use it to connect more deeply with people. I also have a soft spot for aesthetic details and moments that feel cinematic.

---

## 🏗️ What I Build

### 🎓 Education platform

A multi-tenant system covering the full institutional lifecycle, not just coursework. The API spans **40+ domain modules**:

| Domain | Coverage |
|---|---|
| **Academic** | Admissions, courses, assessments, attendance, academic records, transcripts, reporting |
| **Financial** | Payments, entitlements, multi-currency handling |
| **Community** | Forums, live chat, direct messaging, push notifications, SMS and email delivery, gamification and karma |
| **Operations** | Staff and directory management, calendars, transport, careers, marketing, bulk data import |
| **Platform** | Single sign-on, two-factor authentication, granular permissions, semantic search over institutional content, third-party integrations |

Built on Django with async support through Channels and Daphne, PostgreSQL with pgvector for embeddings, Redis for caching and queues, a distributed task queue for background work, JWT auth with TOTP second factor, and a generated OpenAPI specification. The web client is React with TanStack Query, Radix primitives, Tailwind, Zod validation, and Sentry.

### ⚙️ Automated code assessment

The part I find most interesting:

- Executing **untrusted learner code** inside sandboxed, containerised runners with resource and time limits
- Programmatic repository provisioning via a bot that has created **thousands of assignment repositories** across cohorts of roughly 160 learners
- Language-agnostic exercise specifications, so one problem definition drives multiple language tracks
- Grading that inspects submissions structurally rather than only diffing output
- Curriculum and challenge content authored in C, Python, and TypeScript

### 🤖 AI systems

**Academic research co-pilot.** A research-to-writing workspace where a researcher can discover papers across academic sources, search them semantically, draft and revise while preserving their own voice, run citation and coherence checks, and carry out a structured systematic review through to submission-ready export. A standalone FastAPI service that trusts JWTs issued by the main platform.

**LLM middleware.** Production services sitting between applications and language models, handling provider routing and failover, retrieval-augmented generation over a vector store, intent classification, lead qualification, streaming responses, and background processing through a task queue. Includes a **dedicated evaluation harness** with labelled intent and quality datasets, so prompt and model changes are scored rather than guessed at.

**Voice agents.** Conversational systems written in **Rust**, wired into live telephony with streaming speech-to-text and neural text-to-speech, session orchestration, and pluggable provider backends.

### 📡 Communications infrastructure

- **Omnichannel messaging platforms** unifying multiple channels behind a single interface
- **Business messaging APIs** covering provisioning, routing, templates, and delivery-state handling
- **SMS platforms**, both delivery backends and customer-facing portals
- **Connectivity provisioning** flows for mobile data products
- **Embedded mobile widgets** in Flutter, dropped into existing native applications
- **Real-time video and audio** over WebRTC peer-to-peer, including TURN and STUN server configuration for restrictive networks

### 🔐 Regulatory compliance

A compliance workspace for Nigerian universities under the **NDPA 2023**: data mapping, assessment against all **63 official Statement-of-Applicability controls**, and generation of regulator-ready evidence. Alongside it, applied cryptography benchmarking and load testing against the same problem space.

### 🏢 Business systems

Custom ERP addon development against the Odoo core, covering models, controllers, access rules, and seeded demo data. Plus full-stack products in NestJS and Next.js, deployed as single-service builds.

### 🔀 Open source and forks

- [**MiroTalk P2P**](https://github.com/miroslavpejic85/mirotalk): forked and integrated into our platform, with TURN infrastructure and production deployment
- [**Odoo**](https://github.com/odoo/odoo): custom addon development against the ERP core
- [**bulletproof-react**](https://github.com/alan2207/bulletproof-react) and [**FastAPI-template**](https://github.com/s3rius/FastAPI-template): architectural references I adapt into production patterns
- A data-protection compliance workspace I forked and rebuilt, contributing every commit on my branch

> 📊 **4,500+ commits authored** across 40+ active repositories, spanning GitHub and GitLab.

---

## 🌐 Socials:
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/justuchena) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/uchenna-ngozi) [![TikTok](https://img.shields.io/badge/TikTok-%23000000.svg?logo=TikTok&logoColor=white)](https://tiktok.com/@justuchena) [![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/justuchena) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:uchenangozi@gmail.com)

# 💻 Tech Stack:

**Languages**<br>
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white) ![Ruby](https://img.shields.io/badge/ruby-%23CC342D.svg?style=for-the-badge&logo=ruby&logoColor=white) ![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white) ![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white) ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)

**Frontend**<br>
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white) ![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Sass](https://img.shields.io/badge/SASS-hotpink.svg?style=for-the-badge&logo=SASS&logoColor=white)

**Backend and Frameworks**<br>
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) ![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Rails](https://img.shields.io/badge/rails-%23CC0000.svg?style=for-the-badge&logo=ruby-on-rails&logoColor=white) ![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white) ![Odoo](https://img.shields.io/badge/Odoo-%23714B67.svg?style=for-the-badge&logo=odoo&logoColor=white) ![Celery](https://img.shields.io/badge/celery-%23a9cc54.svg?style=for-the-badge&logo=celery&logoColor=ddf4a4) ![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io&badgeColor=010101) ![WebRTC](https://img.shields.io/badge/WebRTC-%23333333.svg?style=for-the-badge&logo=webrtc&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens) ![Gunicorn](https://img.shields.io/badge/gunicorn-%298729.svg?style=for-the-badge&logo=gunicorn&logoColor=white) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)

**Databases**<br>
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) ![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white) ![SurrealDB](https://img.shields.io/badge/SurrealDB-FF00A0?style=for-the-badge&logo=surrealdb&logoColor=white)

**Cloud and DevOps**<br>
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![DigitalOcean](https://img.shields.io/badge/DigitalOcean-%230167ff.svg?style=for-the-badge&logo=digitalOcean&logoColor=white) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white) ![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7) ![Render](https://img.shields.io/badge/Render-%2346E3B7.svg?style=for-the-badge&logo=render&logoColor=white) ![GitLab CI](https://img.shields.io/badge/gitlab%20CI-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

**Observability and Tooling**<br>
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-FFFFFF?&style=for-the-badge&logo=opentelemetry&logoColor=black) ![Sentry](https://img.shields.io/badge/Sentry-%23362D59.svg?style=for-the-badge&logo=sentry&logoColor=white) ![Datadog](https://img.shields.io/badge/datadog-%23632CA6.svg?style=for-the-badge&logo=datadog&logoColor=white) ![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=Twilio&logoColor=white) ![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white) ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white) ![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white)

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=justuchena&theme=transparent&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=justuchena&theme=transparent&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=justuchena&theme=transparent&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

> ℹ️ These cards reflect public GitHub activity only. The majority of my work lives in private organisations and on GitLab, so treat them as a floor rather than a measure.

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=justuchena&theme=radical&no-frame=false&no-bg=true&margin-w=4)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

---
[![](https://visitcount.itsvg.in/api?id=justuchena&icon=0&color=0)](https://visitcount.itsvg.in)

  ## 💰 You can help me by Donating
  [![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/boluuch)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
