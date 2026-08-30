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

### 🏆 Featured Systems & Architecture

<table>
  <tr>
    <td width="50%">
      <h3 align="center">🛡️ Vault (Cloud Storage & Workspace Platform)</h3>
      <p align="center">
        <a href="https://yourvaultstorage.com"><img src="https://img.shields.io/badge/Live_Production-https%3A%2F%2Fyourvaultstorage.com-00C7B7?style=flat-square&logo=googlechrome&logoColor=white"/></a>
        <img src="https://img.shields.io/badge/Express_5-000000?style=flat-square&logo=express&logoColor=white"/>
        <img src="https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white"/>
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white"/>
        <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black"/>
        <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
      </p>
      <p><b>Enterprise-grade cloud drive & developer workspace</b> engineered for high-concurrency file transfers, zero-memory-leak streaming, and robust multi-tenant permissions.</p>
      <ul>
        <li><b>Direct-to-S3 Multipart Uploads:</b> Direct chunk transfers via presigned URLs and transform streams with zero RAM overhead.</li>
        <li><b>Throttling & Abuse Prevention:</b> Distributed Redis rate limiters enforcing strict sliding-window policies per IP/User tier.</li>
        <li><b>RBAC & Owner Permissions:</b> Granular Owner/Editor/Viewer permission policies with ancestor-path array authorization.</li>
        <li><b>Pricing & Dynamic Quotas:</b> Middleware-driven subscription tiers (Free, Pro, Enterprise) integrated with Razorpay webhooks.</li>
        <li><b>Media Processing:</b> Background libuv worker threads for Sharp WebP thumbnails and FFmpeg video transcoding.</li>
      </ul>
      <p align="center">
        <a href="https://yourvaultstorage.com"><b>🌐 Live App</b></a> •
        <a href="https://github.com/adarshbam/my-storage"><b>Monorepo</b></a> •
        <a href="https://github.com/adarshbam/my-storage-frontend"><b>Frontend</b></a> •
        <a href="https://github.com/adarshbam/my-storage-backend"><b>Backend</b></a>
      </p>
    </td>
    <td width="50%">
      <h3 align="center">🔐 JWT Security & Vulnerability Lab</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white"/>
        <img src="https://img.shields.io/badge/Cryptography-0052CC?style=flat-square"/>
        <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
      </p>
      <p><b>Security research lab & test suite</b> demonstrating real-world token vulnerabilities, replay exploits, and cryptographic mitigations.</p>
      <ul>
        <li><b>Exploit Vectors:</b> Simulates algorithm confusion (RS256 vs HS256), signature stripping, and token replay attacks.</li>
        <li><b>Defensive Architecture:</b> Implements secure HTTP-only cookies, token rotation, and distributed revocation via Redis.</li>
      </ul>
      <p align="center">
        <a href="https://github.com/adarshbam/exployting-jwt-tokens"><b>Explore Security Lab</b></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">🏎️ CodeRacer (Developer Speed Engine)</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black"/>
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
        <img src="https://img.shields.io/badge/Tailwind_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
        <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white"/>
      </p>
      <p><b>Real-time developer typing benchmark platform</b> with syntax-aware coding challenges.</p>
      <ul>
        <li><b>Event-Loop Timing:</b> Millisecond-accurate WPM, accuracy, and penalty calculations using high-precision timers.</li>
        <li><b>Zero-Jank Rendering:</b> Built with React 19 and Tailwind CSS v4 for smooth 60+ FPS interaction.</li>
      </ul>
      <p align="center">
        <a href="https://github.com/adarshbam/coderacer"><b>View Repository</b></a>
      </p>
    </td>
    <td width="50%">
      <h3 align="center">🤖 FakeGPT (AI Token Streaming)</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white"/>
        <img src="https://img.shields.io/badge/SSE_Streaming-00C7B7?style=flat-square"/>
      </p>
      <p><b>Lightweight Node.js AI streaming engine</b> with zero external framework overhead.</p>
      <ul>
        <li><b>Stream Piping:</b> Server-Sent Events (SSE) token streaming via raw Node.js HTTP server.</li>
        <li><b>Stream Handling:</b> Asynchronous chunk iterators, abort signal handling, and context buffering.</li>
      </ul>
      <p align="center">
        <a href="https://github.com/adarshbam/fakegpt"><b>View Repository</b></a>
      </p>
    </td>
  </tr>
</table>

---

### 💡 An Interesting Fact About Me

> *"I built two interactive web projects to impress my girlfriend—and it worked! She was blushing, giggling, and amazed all throughout the day."*

- 💖 **[Valentine's Day Journey](https://github.com/adarshbam/valentine-day)** ([🌐 Live Experience](https://valentinesdaypresentformybubu.netlify.app/)) — Interactive storytelling experience featuring glowing path animations, glassmorphism UI, and audio synchronization.
- ✨ **[Our Love Story](https://github.com/adarshbam/our-love-story)** ([🌐 Live Experience](https://our-sweet-love-story.netlify.app/)) — Personal interactive memory timeline built with smooth CSS keyframes and DOM animations.

---

### 🛠️ Technical Arsenal

<table>
  <tr>
    <td align="center" width="20%"><b>Backend & Systems</b></td>
    <td>
      <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
      <img src="https://img.shields.io/badge/Express.js_5-000000?style=for-the-badge&logo=express&logoColor=white"/>
      <img src="https://img.shields.io/badge/REST_APIs-02569B?style=for-the-badge"/>
      <img src="https://img.shields.io/badge/Streams_%26_Buffers-E0234E?style=for-the-badge"/>
      <img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=for-the-badge&logo=cloudflare&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center" width="20%"><b>Databases & Cloud</b></td>
    <td>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white"/>
      <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
      <img src="https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"/>
      <img src="https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center" width="20%"><b>Security & Auth</b></td>
    <td>
      <img src="https://img.shields.io/badge/TOTP_2FA-24292E?style=for-the-badge"/>
      <img src="https://img.shields.io/badge/Argon2-0052CC?style=for-the-badge"/>
      <img src="https://img.shields.io/badge/JWT_%26_Cookies-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
      <img src="https://img.shields.io/badge/Rate_Limiting-8E24AA?style=for-the-badge"/>
      <img src="https://img.shields.io/badge/Zod_Validation-3E67B1?style=for-the-badge&logo=zod&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center" width="20%"><b>Frontend & Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/JavaScript_(ESNext)-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
      <img src="https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
      <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td align="center" width="20%"><b>Tools & Practices</b></td>
    <td>
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
      <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
      <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
      <img src="https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white"/>
      <img src="https://img.shields.io/badge/Razorpay_APIs-0C2340?style=for-the-badge&logo=razorpay&logoColor=white"/>
    </td>
  </tr>
</table>

---

### 📊 GitHub Activity & Metrics

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=adarshbam&theme=tokyonight" height="175"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=adarshbam&theme=tokyonight" height="175"/>
</div>

<div align="center">
  <br/>
  <img src="https://streak-stats.demolab.com?user=adarshbam&theme=tokyonight&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakNum=FFFFFF" alt="GitHub Streak" />
</div>

---

<div align="center">
  <p>💼 <b>Open to Full-Time Software Engineering & Backend Systems Roles</b></p>
  <p>📫 Reach me at: <a href="mailto:adarshbambahadur@gmail.com">adarshbambahadur@gmail.com</a> • <a href="https://linkedin.com/in/adarsh-singh-bam">LinkedIn</a></p>
</div>
