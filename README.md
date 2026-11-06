# Adarsh Singh

**Software engineer · Full-stack applications & developer tooling**

I build React and Node.js applications, connect the services behind them, and make their behavior easier to understand. My work spans technical course development, booking and payment workflows, connected storage, and hands-on security experiments.

[Email](mailto:adarshbambahadur@gmail.com) · [LinkedIn](https://linkedin.com/in/adarsh-singh-bam) · [Portfolio source](https://github.com/adarshbam/my-atlas-portfolio) · [Vault demo](https://yourvaultstorage.com/)

Open to full-time software engineering roles in product engineering, full-stack development, and developer tooling.

## Experience

### ProCodrr · Technical Course Assistant

*2023–2026 · Working with Anurag Singh*

- Built JavaScript, React, TypeScript, and Node.js reference projects for YouTube and paid courses.
- Created interview questions and hands-on exercises aligned with course lessons, and helped learners work through technical questions.
- Contributed to the Node.js course storage project, then independently extended my implementation into [Vault Storage](https://github.com/adarshbam/my-storage).

### Harigurus · Full Stack Developer

*2022–2023 · Eight months · Team contribution*

- Built React ceremony-selection and scheduling flows, with Node.js/Express APIs to validate and persist customer and booking records.
- Integrated Razorpay checkout and server-side payment verification, followed by Twilio booking confirmations and status notifications.

[Written case study](https://github.com/adarshbam/harigurus-enterprise-architecture) · [Company website](https://harigurus.com/)

Production source code belongs to Harigurus and remains private. The case-study repository documents my contributions.

## Selected projects

### [Security Lab](https://github.com/adarshbam/security-lab)

**Predict → experiment → inspect → compare.** A browser laboratory for understanding web security through real requests.

- Three modules cover HttpOnly cookies versus localStorage, SameSite and CSRF, and JWT decoding, verification, and historical vulnerabilities.
- A request inspector shows authentication outcomes and state changes; Playwright checks compare vulnerable and protected behavior.

React · TypeScript · Express · Playwright. Intentionally vulnerable teaching routes run locally only.

### [Vault Storage](https://github.com/adarshbam/my-storage)

A connected workspace for Vault files, GitHub repositories, and Google Drive.

- Independently built GitHub and Drive workspaces, cross-service transfers, owner controls, runtime plan rules, and billing on the ProCodrr storage foundation.
- Owner plan edits invalidate Redis state; requests resolve current plan rules for feature access.

React · Node.js · MongoDB · Redis · Backblaze B2 · Cloudflare Workers. [Explore the demo](https://yourvaultstorage.com/).

### [CI/CD Pipeline Engine](https://github.com/adarshbam/ci-cd-pipeline-engine)

A self-hosted workflow runner with signed GitHub webhooks and a React Flow dashboard for pipeline graphs, logs, and run history.

- Dependency-aware scheduling uses two job slots per run, with downstream skip propagation and cycle diagnostics.
- Step retries, timeouts, process-tree cancellation, and workspace-scoped artifacts make execution behavior visible and controllable.

TypeScript · Node.js · Express · React Flow. Jobs run as host processes in temporary directories; they are not container-sandboxed.

## Tools I use

- **Languages & interfaces:** JavaScript, TypeScript, React, HTML, CSS
- **Services & data:** Node.js, Express, MongoDB, Redis
- **Storage & delivery:** Backblaze B2, Cloudflare Workers, GitHub and Google Drive integrations
- **Verification:** Playwright, browser request inspection, focused server tests

## A personal side

I also build for people I care about. [Valentine’s Day Journey](https://github.com/adarshbam/valentine-day) and [Our Love Story](https://github.com/adarshbam/our-love-story) began as interactive gifts for my girlfriend—small reminders that software can be personal, too.
