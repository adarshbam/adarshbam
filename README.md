<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,20,50,100&height=200&section=header&text=Adarsh%20Singh&fontSize=65&fontAlignY=38&desc=Backend%20and%20Distributed%20Systems%20Engineer%20%7C%20Full%20Stack%20Developer&descFontSize=20&descAlignY=65&fontColor=ffffff" width="100%"/>
</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/adarsh-singh-bam)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:adarshbambahadur@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/adarshbam)

</div>

---

### 👨‍💻 Executive Summary

I am a **Software Engineer** specializing in **high-performance backend architectures, stream-based data pipelines, and scalable full-stack applications**. 

- ⚡ **Distributed Storage & Streaming:** Architected decoupled Direct-to-S3 multipart streaming engines with presigned URLs, eliminating server-side memory bottlenecks on multi-gigabyte transfers.
- 🚦 **Traffic Throttling & Rate Limiting:** Implemented Redis-backed token-bucket algorithms, per-user and per-IP request throttling, and decoupled rate limiters for authentication and OTP generation.
- 🛡️ **Granular RBAC & Multi-Tenant Security:** Engineered hierarchical access control (Owner, Editor, Viewer), cryptographically signed share tokens, Argon2id hashing, and RFC 6238 TOTP 2FA.
- 💳 **Business Logic & Monetization:** Developed dynamic storage quota middleware (`loadPlanContext`), webhook-driven Razorpay subscriptions with replay-attack defenses, and automated soft-delete retention lifecycles.

---

### 🏆 Featured Systems & Production Architecture

---

#### 🛡️ [Vault — Enterprise Cloud Storage & Developer Workspace](https://github.com/adarshbam/my-storage)
[![Live Production](https://img.shields.io/badge/Live_Production-https%3A%2F%2Fyourvaultstorage.com-00C7B7?style=for-the-badge&logo=googlechrome&logoColor=white)](https://yourvaultstorage.com)
[![Express 5](https://img.shields.io/badge/Express_5-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com)
[![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)](https://aws.amazon.com/s3/)
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)](https://redis.io)
[![React 19](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)](https://mongodb.com)

**Enterprise-grade distributed storage platform** engineered for high-concurrency file transfers, zero-memory-leak streaming, and robust multi-tenant permissions.

- **Direct-to-S3 Multipart Uploads:** Direct chunk transfers via presigned URLs and transform streams with zero RAM overhead on the backend.
- **Throttling & Abuse Prevention:** Distributed Redis rate limiters enforcing strict sliding-window policies per IP/User tier.
- **RBAC & Multi-Tenant Security:** Granular Owner/Editor/Viewer permission policies with ancestor-path array authorization.
- **Pricing & Dynamic Quotas:** Middleware-driven subscription tiers (Free, Pro, Enterprise) integrated with Razorpay webhooks.
- **Media Processing Engine:** Background libuv worker threads for Sharp WebP thumbnail generation and FFmpeg video transcoding.

> 🔗 **Explore:** [**🌐 Live Application (yourvaultstorage.com)**](https://yourvaultstorage.com) • [**Monorepo**](https://github.com/adarshbam/my-storage) • [**Frontend Code**](https://github.com/adarshbam/my-storage-frontend) • [**Backend Code**](https://github.com/adarshbam/my-storage-backend)

---

#### 🔐 [JWT Security & Vulnerability Research Lab](https://github.com/adarshbam/exployting-jwt-tokens)
[![JWT](https://img.shields.io/badge/JWT_Lab-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)](https://jwt.io)
[![Cryptography](https://img.shields.io/badge/Cryptography-0052CC?style=for-the-badge)](https://nodejs.org/api/crypto.html)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org)

**Security research test suite** demonstrating real-world token vulnerabilities, replay exploits, and cryptographic mitigations.

- **Exploit Simulation:** Simulates algorithm confusion (RS256 vs HS256), signature stripping attacks, and token replay vulnerabilities.
- **Defensive Cryptography:** Implements secure HTTP-only cookies, token rotation schemes, and distributed revocation via Redis blacklists.

> 🔗 **Explore:** [**View Security Research Lab**](https://github.com/adarshbam/exployting-jwt-tokens)

---

#### 🏎️ [CodeRacer — Developer Typing & Benchmark Engine](https://github.com/adarshbam/coderacer)
[![React 19](https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind v4](https://img.shields.io/badge/Tailwind_v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev)

**Real-time developer typing benchmark engine** featuring syntax-aware programming challenges and precise metrics.

- **Event-Loop Timing:** Millisecond-accurate WPM, accuracy rate, and penalty calculations using high-precision timers.
- **Zero-Jank Rendering:** Engineered with React 19 and Tailwind CSS v4 for smooth 60+ FPS interaction.

> 🔗 **Explore:** [**View CodeRacer Repository**](https://github.com/adarshbam/coderacer)

---

#### 🤖 [FakeGPT — AI Token Streaming Engine](https://github.com/adarshbam/fakegpt)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com)
[![SSE Streaming](https://img.shields.io/badge/SSE_Streaming-00C7B7?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events)

**Lightweight Node.js AI streaming service** built with zero external web framework overhead.

- **Stream Piping:** Server-Sent Events (SSE) token streaming via raw Node.js HTTP server.
- **Stream Handling:** Asynchronous chunk iterators, abort signal handling, and context buffering.

> 🔗 **Explore:** [**View FakeGPT Repository**](https://github.com/adarshbam/fakegpt)

---

### 💡 An Interesting Fact About Me

> *"I built two interactive web projects to impress my girlfriend—and it worked! She was blushing, giggling, and amazed all throughout the day."*

- 💖 **[Valentine's Day Journey](https://github.com/adarshbam/valentine-day)** ([🌐 Live Experience](https://valentinesdaypresentformybubu.netlify.app/)) — Interactive storytelling experience featuring glowing path animations, glassmorphism UI, and audio synchronization.
- ✨ **[Our Love Story](https://github.com/adarshbam/our-love-story)** ([🌐 Live Experience](https://our-sweet-love-story.netlify.app/)) — Personal interactive memory timeline built with smooth CSS keyframes and DOM animations.

---

### 🛠️ Technical Arsenal

#### ⚙️ Backend & Distributed Systems
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![Express.js 5](https://img.shields.io/badge/Express.js_5-000000?style=flat-square&logo=express&logoColor=white)](https://expressjs.com)
[![REST APIs](https://img.shields.io/badge/REST_APIs-02569B?style=flat-square)](https://restfulapi.net)
[![Streams & Buffers](https://img.shields.io/badge/Streams_%26_Buffers-E0234E?style=flat-square)](https://nodejs.org/api/stream.html)
[![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)](https://workers.cloudflare.com)

#### 🗄️ Databases & Cloud Infrastructure
[![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)](https://mongodb.com)
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)](https://redis.io)
[![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white)](https://aws.amazon.com/s3)
[![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)](https://aws.amazon.com/ec2)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](https://docker.com)
[![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)](https://nginx.org)

#### 🛡️ Security & Authentication
[![TOTP 2FA](https://img.shields.io/badge/TOTP_2FA-24292E?style=flat-square)](https://datatracker.ietf.org/doc/html/rfc6238)
[![Argon2](https://img.shields.io/badge/Argon2id-0052CC?style=flat-square)](https://github.com/ranisalt/node-argon2)
[![JWT & Cookies](https://img.shields.io/badge/JWT_%26_Cookies-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)](https://jwt.io)
[![Rate Limiting](https://img.shields.io/badge/Rate_Limiting-8E24AA?style=flat-square)](https://redis.io)
[![Zod Validation](https://img.shields.io/badge/Zod_Validation-3E67B1?style=flat-square&logo=zod&logoColor=white)](https://zod.dev)

#### 🎨 Frontend & Languages
[![JavaScript](https://img.shields.io/badge/JavaScript_(ESNext)-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![React 19](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)](https://react.dev)
[![Tailwind CSS v4](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vitejs.dev)

#### 🛠️ DevOps & Tooling
[![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)](https://github.com/features/actions)
[![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white)](https://ffmpeg.org)
[![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)](https://postman.com)
[![Razorpay](https://img.shields.io/badge/Razorpay_APIs-0C2340?style=flat-square&logo=razorpay&logoColor=white)](https://razorpay.com)

---

### 📊 GitHub Activity & Metrics

<div align="center">

[![Profile Summary](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=adarshbam&theme=tokyonight)](https://github.com/adarshbam)

[![Repos per Language](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=adarshbam&theme=tokyonight)](https://github.com/adarshbam)

[![GitHub Streak](https://streak-stats.demolab.com?user=adarshbam&theme=tokyonight&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakNum=FFFFFF)](https://github.com/adarshbam)

</div>

---

<div align="center">
  <p>💼 <b>Open to Full-Time Software Engineering & Backend Systems Roles</b></p>
  <p>📫 Reach me at: <a href="mailto:adarshbambahadur@gmail.com">adarshbambahadur@gmail.com</a> • <a href="https://linkedin.com/in/adarsh-singh-bam">LinkedIn</a></p>
</div>
