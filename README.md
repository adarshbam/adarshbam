<div align="center">
  <img src="https://raw.githubusercontent.com/adarshbam/adarshbam/main/header.svg" width="100%" alt="Adarsh Singh - Distributed Systems &amp; AI Infrastructure Engineer | Full Stack Developer" />
</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/adarsh-singh-bam)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:adarshbambahadur@gmail.com)
[![Vault Live](https://img.shields.io/badge/Vault_Cloud-yourvaultstorage.com-00C7B7?style=for-the-badge&logo=googlechrome&logoColor=white)](https://yourvaultstorage.com)
[![Harigurus Live](https://img.shields.io/badge/Commercial_Prod-harigurus.com-FF6B00?style=for-the-badge&logo=googlechrome&logoColor=white)](https://harigurus.com)

</div>

---

### 👨‍💻 Executive Summary

I am a **Full-Stack Distributed Systems & AI Infrastructure Engineer** with **8+ months of commercial production experience** building multi-repository enterprise platforms, zero-egress cloud storage engines, and autonomous LLM agentic pipelines.

- 🏛️ **Commercial Production Engineering (Harigurus — 8 Months):** Sole-architected a Next.js SSR e-commerce storefront (`harigurus-shop` — 100% commit ownership), migrated a 20,170-LOC production React platform (`harigurus.com`) from static data to **Sanity.io Headless CMS** via GROQ queries, and contributed to the multi-stage SMS OTP checkout & Express/MongoDB production backend (`harigurusBackend`).
- ⚡ **Distributed Zero-Egress Cloud Storage (`yourvaultstorage.com`):** Architected Direct-to-S3 multipart streaming engines on **AWS EC2 (Express 5 PM2 Cluster) + S3/CloudFront**, routing **Backblaze B2** streams through a **Cloudflare Worker Edge CDN** for **\$0 egress bandwidth**.
- 🤖 **Autonomous Agentic Systems & MCP Servers:** Engineered an end-to-end customer support triage pipeline that clusters semantically identical feature requests, raises GitHub Issues at threshold $N_1$, dispatches **HMAC-SHA256 signed one-click webhook emails** at threshold $N_2$, and triggers a headless **Codex Agent** to implement code, run unit tests, and open verified Pull Requests.
- 🛡️ **Granular RBAC, Security & Self-Hosted CI/CD:** Implemented Redis token-bucket rate limiters, Argon2id hashing, RFC 6238 TOTP 2FA, and a custom GitHub Webhook CI/CD build runner (`deploy-full.sh`) with mutex lock protection.

---

### 🏛️ Commercial Production Work Experience (8 Months Tenure)

#### 🚀 [Harigurus — Enterprise Ceremony Booking & E-Commerce Ecosystem (22,160+ LOC)](https://github.com/adarshbam/harigurus-enterprise-architecture)
[![Live Client Platform](https://img.shields.io/badge/Live_Production-https%3A%2F%2Fharigurus.com-FF6B00?style=for-the-badge&logo=googlechrome&logoColor=white)](https://harigurus.com)
[![Next.js SSR](https://img.shields.io/badge/Next.js_SSR-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org)
[![Sanity CMS](https://img.shields.io/badge/Sanity_Headless_CMS-F03E2F?style=for-the-badge&logo=sanity&logoColor=white)](https://www.sanity.io)
[![Node.js & Express](https://img.shields.io/badge/Node.js_%26_Express-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![MongoDB](https://img.shields.io/badge/MongoDB_Atlas-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://mongodb.com)

Engineered core systems across a **3-repository commercial production ecosystem** (`harigurus`, `harigurus-shop`, `harigurusBackend`):

- **Sole-Architected E-Commerce Storefront (`harigurus-shop` — 100% Commit Ownership):** Built Harigurus's dedicated Server-Side Rendered (SSR) e-commerce storefront from scratch across 63 files using **Next.js `getServerSideProps`, Sanity.io CMS, Material-UI v5, and TailwindCSS** with dynamic slug routing and `Intl` INR localization.
- **Headless CMS Architecture Migration (`harigurus.com`):** Replaced 670+ lines of hardcoded ceremony definitions in the 20,170-LOC core platform with a dynamic **Sanity.io Headless CMS** studio (`services.js`, `serviceitem.js`) and live **GROQ** queries, enabling non-technical staff to publish ceremony packages in real time with zero engineering redeployments.
- **Multi-Stage OTP Checkout & Production DB Cutover (`harigurusBackend`):** Contributed to the 940-line checkout state machine and Express/MongoDB REST API featuring Indian mobile validation, **Fast2SMS & Twilio** 4-digit OTP verification, JWT session persistence, and PhonePe QR payments; executed the production MongoDB database cutover.

> 🔗 **Explore:** [**🌐 Live Production Platform (harigurus.com)**](https://harigurus.com) • [**📐 Architecture Case Study & Technical Dossier**](https://github.com/adarshbam/harigurus-enterprise-architecture)

---

### 🏆 Flagship Distributed Systems & Agentic AI Projects

---

#### 🛡️ [Vault — Enterprise Cloud Storage & Developer Workspace](https://github.com/adarshbam/my-storage)
[![Live Production](https://img.shields.io/badge/Live_Production-https%3A%2F%2Fyourvaultstorage.com-00C7B7?style=for-the-badge&logo=googlechrome&logoColor=white)](https://yourvaultstorage.com)
[![Express 5](https://img.shields.io/badge/Express_5-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com)
[![AWS EC2 & S3](https://img.shields.io/badge/AWS_EC2_%26_S3-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com)
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)](https://redis.io)
[![React 19](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)

**Enterprise-grade distributed storage platform** engineered for zero-egress cloud streaming, high-concurrency transfers, and self-hosted CI/CD automation.

- **Zero-Egress Multi-Cloud Streaming:** Hosted React 19 on AWS S3 + CloudFront (ACM SSL) and Express 5 on AWS EC2 (PM2 cluster + Nginx unbuffered proxy); routed Backblaze B2 S3 streams through a Cloudflare Worker Edge CDN for **\$0 egress fees**.
- **Throttling, RBAC & Media Workers:** Distributed Redis token-bucket rate limiters, Argon2id, TOTP 2FA, hierarchical Owner/Editor/Viewer RBAC, Razorpay webhook quotas, and background `libuv` worker threads for Sharp WebP & FFmpeg transcoding.
- **Custom Webhook CI/CD Engine:** Self-hosted deployment runner (`deploy-full.sh`) with mutex lock protection (`isDeploying`), automated test verification, S3 sync, CloudFront invalidation, and zero-downtime PM2 reloads.

> 🔗 **Explore:** [**🌐 Live Application (yourvaultstorage.com)**](https://yourvaultstorage.com) • [**Monorepo**](https://github.com/adarshbam/my-storage) • [**Frontend Code**](https://github.com/adarshbam/my-storage-frontend) • [**Backend Code**](https://github.com/adarshbam/my-storage-backend) • [**CI/CD Engine**](https://github.com/adarshbam/ci-cd-pipeline-engine)

---

#### 🤖 [Autonomous AI Support $\rightarrow$ Webhook $\rightarrow$ Codex Auto-PR Pipeline & MCP Server](https://github.com/adarshbam/ai-support-codex-agent)
[![Node.js](https://img.shields.io/badge/Node.js_20%2B-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![MCP Server](https://img.shields.io/badge/Model_Context_Protocol-000000?style=for-the-badge)](https://modelcontextprotocol.io)
[![HMAC-SHA256](https://img.shields.io/badge/HMAC_SHA256_Webhooks-0052CC?style=for-the-badge)](https://nodejs.org/api/crypto.html)
[![Codex Agent](https://img.shields.io/badge/Autonomous_Codex_PR_Agent-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com)

**Event-driven autonomous triage and code-synthesis pipeline** connecting customer support streams directly to verified GitHub Pull Requests.

- **Semantic Ticket Clustering & Issue Escalation:** Computes TF-IDF Cosine Similarity across incoming customer requests, automatically opening structured **GitHub Issues** once cluster demand crosses threshold $N_1$.
- **HMAC-SHA256 One-Click Email Webhook $\rightarrow$ Codex PR:** Dispatches cryptographically signed alert emails to engineering leads at threshold $N_2$; clicking the link triggers a headless **Codex Agent** (protected against replay attacks via one-time nonces) that checks out a feature branch, writes the code + unit tests, runs verification suites, and opens a GitHub Pull Request.
- **MCP File Reorganization Server:** Includes a JSON-RPC 2.0 Model Context Protocol server that classifies and reorganizes workspace directories with atomic transaction rollback.

> 🔗 **Explore:** [**View AI Support $\rightarrow$ Codex Auto-PR & MCP Repository**](https://github.com/adarshbam/ai-support-codex-agent)

---

#### 📊 [Enterprise Operations & Financial BI Analytics Dashboard (7,279 LOC)](https://github.com/adarshbam/enterprise-admin-dashboard)
[![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Syncfusion EJ2](https://img.shields.io/badge/Syncfusion_EJ2-0052CC?style=for-the-badge)](https://www.syncfusion.com)

**Multi-view enterprise operations and financial analytics suite** featuring 8 specialized charting engines (Financial OHLC, Stacked, Pyramid, SparkLine, ColorMapping), drag-and-drop Kanban boards, recurring event schedulers, and global dark/light theme context state.

> 🔗 **Explore:** [**View Enterprise Analytics Dashboard Repository**](https://github.com/adarshbam/enterprise-admin-dashboard)

---

#### 🔐 [JWT Security & Vulnerability Research Lab](https://github.com/adarshbam/exployting-jwt-tokens) • 🏎️ [CodeRacer](https://github.com/adarshbam/coderacer) • ⚡ [FakeGPT SSE Engine](https://github.com/adarshbam/fakegpt)
- **[JWT Security Lab](https://github.com/adarshbam/exployting-jwt-tokens):** Simulates RS256-to-HS256 algorithm confusion, signature stripping, and replay exploits alongside defensive HTTP-only cookie rotation and Redis blacklists.
- **[CodeRacer](https://github.com/adarshbam/coderacer):** 60+ FPS syntax-aware developer typing benchmark built with React 19, TypeScript, and Tailwind v4.
- **[FakeGPT](https://github.com/adarshbam/fakegpt):** Zero-framework Node.js AI token streaming engine using raw Server-Sent Events (SSE) and backpressure-safe chunk iterators.

---

### 💡 An Interesting Fact About Me

> *"I built two interactive web projects to impress my girlfriend—and it worked! She was blushing, giggling, and amazed all throughout the day."*

- 💖 **[Valentine's Day Journey](https://github.com/adarshbam/valentine-day)** ([🌐 Live Experience](https://valentinesdaypresentformybubu.netlify.app/)) — Interactive storytelling experience featuring glowing path animations, glassmorphism UI, and audio synchronization.
- ✨ **[Our Love Story](https://github.com/adarshbam/our-love-story)** ([🌐 Live Experience](https://our-sweet-love-story.netlify.app/)) — Personal interactive memory timeline built with smooth CSS keyframes and DOM animations.

---

### 🛠️ Technical Arsenal

#### ⚙️ Backend, Distributed Systems & Agentic AI
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![Express.js 5](https://img.shields.io/badge/Express.js_5-000000?style=flat-square&logo=express&logoColor=white)](https://expressjs.com)
[![MCP Servers](https://img.shields.io/badge/MCP_Servers-000000?style=flat-square)](https://modelcontextprotocol.io)
[![Streams & Buffers](https://img.shields.io/badge/Streams_%26_Buffers-E0234E?style=flat-square)](https://nodejs.org/api/stream.html)
[![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)](https://workers.cloudflare.com)

#### 🗄️ Databases, Headless CMS & Cloud Infrastructure
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)](https://mongodb.com)
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)](https://redis.io)
[![Sanity CMS](https://img.shields.io/badge/Sanity_Headless_CMS-F03E2F?style=flat-square&logo=sanity&logoColor=white)](https://www.sanity.io)
[![AWS S3 & CloudFront](https://img.shields.io/badge/AWS_S3_%26_CloudFront-569A31?style=flat-square&logo=amazons3&logoColor=white)](https://aws.amazon.com/s3)
[![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)](https://aws.amazon.com/ec2)
[![Backblaze B2](https://img.shields.io/badge/Backblaze_B2-E21E26?style=flat-square)](https://www.backblaze.com/cloud-storage)
[![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)](https://nginx.org)

#### 🎨 Frontend & Mobile Languages
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript_(ESNext)-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![React 19](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)](https://react.dev)
[![Next.js](https://img.shields.io/badge/Next.js_SSR-000000?style=flat-square&logo=nextdotjs&logoColor=white)](https://nextjs.org)
[![Tailwind CSS v4](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Kotlin Android](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)](https://kotlinlang.org)

---

### 📊 GitHub Activity & Metrics

<div align="center">

[![Profile Summary](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=adarshbam&theme=tokyonight)](https://github.com/adarshbam)

[![Repos per Language](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=adarshbam&theme=tokyonight)](https://github.com/adarshbam)

[![GitHub Streak](https://streak-stats.demolab.com?user=adarshbam&theme=tokyonight&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakNum=FFFFFF)](https://github.com/adarshbam)

</div>

---

<div align="center">
  <p>💼 <b>Open to Full-Time Software Engineering, Distributed Backend & AI Systems Roles</b></p>
  <p>📫 Reach me at: <a href="mailto:adarshbambahadur@gmail.com">adarshbambahadur@gmail.com</a> • <a href="https://linkedin.com/in/adarsh-singh-bam">LinkedIn</a> • <a href="https://yourvaultstorage.com">yourvaultstorage.com</a></p>
</div>
