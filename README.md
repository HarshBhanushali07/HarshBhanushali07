<!-- HARSH BHANUSHALI · GitHub README -->

<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,20:0a0f14,60:0d1b2a,100:112240&height=180&section=header&text=&fontSize=0&animation=fadeIn"/>
</div>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=26&duration=3000&pause=1400&color=E2E8F0&center=true&vCenter=true&width=700&lines=Harsh+Bhanushali;Full-Stack+Engineer+%C2%B7+AI+Systems+%C2%B7+Founder" alt="name" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=400&size=13&duration=2400&pause=1000&color=64748B&center=true&vCenter=true&width=740&lines=Flutter+%C2%B7+.NET+Web+API+%C2%B7+Firebase+%C2%B7+Supabase+%C2%B7+Azure+%C2%B7+Cloudflare;Building+and+shipping+production+systems+%E2%80%94+end+to+end.;Open+to+internships+%C2%B7+freelance+%C2%B7+early-stage+startups." alt="subtitle" />

<br/>

[![GitHub followers](https://img.shields.io/github/followers/HarshBhanushali07?style=flat-square&logo=github&logoColor=8b9eb0&label=followers&color=0d1b2a&labelColor=112240)](https://github.com/HarshBhanushali07) &nbsp;[![Profile Views](https://komarev.com/ghpvc/?username=HarshBhanushali07&style=flat-square&label=profile+views&color=0d1b2a&labelColor=112240)](https://github.com/HarshBhanushali07) &nbsp;[![Open to Work](https://img.shields.io/badge/status-open_to_work-3b82f6?style=flat-square&labelColor=112240)](mailto:bhanushaliharsh434@gmail.com) &nbsp;[![Site](https://img.shields.io/badge/dualmindlab.tech-live-3b82f6?style=flat-square&labelColor=112240&logo=googlechrome&logoColor=3b82f6)](http://dualmindlab.tech)

</div>

---

```
harsh@dualmind:~$ whoami
```

```
  Name     :  Harsh Bhanushali
  Role     :  CS Student · Full-Stack Engineer · Founder, DualMind Labs
  Stack    :  Flutter · .NET Web API · Node.js · Firebase · Supabase · Azure · Cloudflare
  Location :  India  [UTC +5:30]
  Status   :  Open — internships, freelance, early-stage startups

  I build production systems: mobile, backend, infra, AI, security, deployment.
  DualMind Arena is live, has handled peak traffic of 5000+ requests, ranks on
  Google, and runs a real security and observability stack.

  Not portfolio work. Deployed systems. Real users.
```

---

```
harsh@dualmind:~$ cat proof.log
```

```
  [traffic]      Handled 5000+ requests during peak traffic spike (bots + real users)
  [payments]     Razorpay integration — real-time payment status sync across 3 apps
  [security]     Login anomaly detection · IP logging · risk scoring · email alerts
  [seo]          Ranks #1 for "DualMind Labs" · ~Top 95 for "AI arenas" on Google
  [real-time]    Three-app Firebase sync · payment webhooks · live order state
  [docs]         Full user documentation written and shipped for DualMind Arena
  [ownership]    Design → code → infra → deployment · solo end-to-end
```

---

```
harsh@dualmind:~$ ls -la projects/
```

<br/>

**DualMind Arena** — AI Model Evaluation Platform &nbsp; [![live](https://img.shields.io/badge/LIVE-112240?style=flat-square&logo=googlechrome&logoColor=3b82f6)](http://dualmindlab.tech) [![peak-traffic](https://img.shields.io/badge/peak_5000%2B_requests-112240?style=flat-square&logoColor=3b82f6)]()

```
  Problem  →  AI benchmarks are vendor-controlled and brand-biased.
               No neutral, community-driven evaluation exists.

  Solution →  Blind head-to-head model battles. Community votes.
               No brand shown until after the verdict.

  Flow:

    [prompt submitted]
          │
    ┌─────┴──────┐
    ▼            ▼
  [Model A]   [Model B]   ← identities hidden
    └─────┬──────┘
          ▼
    [community votes]
          ▼
    [live leaderboard]  →  auditable · exportable · free
```

```
  Architecture highlights:

  · Cloudflare CDN        front-of-stack; absorbs traffic spikes before origin
  · Cloudflare AI Gateway unified LLM routing, rate limiting, per-call observability
  · .NET Web API          stateless; horizontally scalable by design
  · Supabase (PostgreSQL) chosen over Firebase — leaderboard queries need real SQL
  · Azure Cloud           compute and hosting layer
  · DevOps pipelines      GitHub Actions CI/CD end-to-end

  Security:
  · Login anomaly detection with IP capture and risk-level classification
  · Automated email alerts to account owner on suspicious activity

  SEO:
  · Ranks #1 for "DualMind Labs" on Google
  · Ranks ~Top 95 for "AI arenas"

  Docs:
  · Full user documentation written, structured, and published
```

`Stack:` `.NET Web API` · `Vanilla JS` · `Supabase` · `Azure` · `Cloudflare CDN` · `Cloudflare AI Gateway` · `GitHub Actions`

---

**MealMind** — Restaurant Management System (3-App Ecosystem) &nbsp; [![built](https://img.shields.io/badge/BUILT-112240?style=flat-square&logoColor=22c55e)](https://github.com/HarshBhanushali07)

```
  Three coordinated Flutter apps. One Firebase backend. Real-time sync.

  Apps:
  · Customer   browse · order · pay (Razorpay) · track status live
  · Chef        receive orders · update preparation state
  · Admin       manage menu · staff · view revenue in real-time

  A Firestore write from the customer app propagates to the chef
  screen and the admin dashboard in under a second.

  Payment flow:
  · Razorpay handles transaction
  · Webhook hits Firebase Cloud Function
  · Payment status updates across all three apps instantly
  · Customer, chef, and admin each receive role-specific notification

  Architecture:
  · Firebase Firestore   real-time sync; security rules per role
  · Firebase Auth        role-based access (customer / chef / admin)
  · Firebase Cloud Functions  payment webhook handler
  · Razorpay             full payment lifecycle integration
  · GitHub Actions       CI/CD pipeline across all three apps
```

`Stack:` `Flutter (3 apps)` · `Firebase Firestore` · `Firebase Auth` · `Cloud Functions` · `Razorpay` · `GitHub Actions`

---

**AI Customer Support Agent** — Automated Query Pipeline &nbsp; [![built](https://img.shields.io/badge/BUILT-112240?style=flat-square&logoColor=22c55e)](https://github.com/HarshBhanushali07)

```
  [inbound query]
        │
  [AI agent]  ← Claude / GPT-4o with function calling
        │
        ├─ resolved  →  auto-respond + log to CRM
        │
        └─ escalate  →  human review, pre-drafted context attached

  Handles routine query volume. Humans receive only what needs judgment.
```

`Stack:` `Node.js` · `Anthropic Claude` · `OpenAI` · `Supabase` · `Function Calling` · `Webhooks`

---

**Dev Infrastructure & CI/CD Templates** — Internal Tooling &nbsp; [![ongoing](https://img.shields.io/badge/ONGOING-112240?style=flat-square)](https://github.com/HarshBhanushali07)

```
  Reusable GitHub Actions pipelines, backend starter kits, and
  deployment templates maintained across projects.
  New projects skip setup and ship from day one.
```

---

```
harsh@dualmind:~$ cat system_design.md
```

```
  SCALABILITY
  ──────────────────────────────────────────────────────────────────
  Cloudflare CDN sits in front of DualMind Arena. Traffic spikes are
  absorbed before they reach the origin. The .NET API is stateless —
  scaling horizontally is a config change, not a rewrite.
  Cloudflare AI Gateway adds caching and rate limiting on every
  LLM call. The model layer doesn't get hit unnecessarily.

  OBSERVABILITY
  ──────────────────────────────────────────────────────────────────
  Every production system has logging and alerting from day one.
  DualMind: real-time login alerts with IP + risk scoring.
  AI Gateway: per-request visibility across all model providers.
  MealMind: payment webhook logs + Cloud Function execution traces.
  Observability is architecture, not an afterthought.

  SECURITY
  ──────────────────────────────────────────────────────────────────
  Login anomaly detection, IP capture, risk classification, and
  email alerts to account owners — built into DualMind at launch.
  Not a post-incident addition. Designed in from the start.

  TRADEOFFS
  ──────────────────────────────────────────────────────────────────
  Firebase vs Supabase:
    MealMind uses Firebase — real-time sync across 3 apps is exactly
    what Firestore is built for. Right tool, right problem.
    DualMind uses Supabase — leaderboard queries and relational data
    need proper SQL. Firebase NoSQL becomes unmanageable at that depth.

  Cloudflare AI Gateway vs direct API calls:
    Adds unified rate limiting, caching, and observability across
    multiple LLM providers. Worth the abstraction for a multi-model
    platform where cost and visibility matter.
```

---

```
harsh@dualmind:~$ cat tech-stack.json
```

<div align="center">

**Languages**
![C](https://img.shields.io/badge/C-1e3a5f?style=flat-square&logo=c&logoColor=8b9eb0) ![C#](https://img.shields.io/badge/C%23-1e3a5f?style=flat-square&logo=dotnet&logoColor=8b9eb0) ![JavaScript](https://img.shields.io/badge/JavaScript-1e3a5f?style=flat-square&logo=javascript&logoColor=8b9eb0) ![TypeScript](https://img.shields.io/badge/TypeScript-1e3a5f?style=flat-square&logo=typescript&logoColor=8b9eb0) ![Dart](https://img.shields.io/badge/Dart-1e3a5f?style=flat-square&logo=dart&logoColor=8b9eb0) ![Go](https://img.shields.io/badge/Go-1e3a5f?style=flat-square&logo=go&logoColor=8b9eb0) ![SQL](https://img.shields.io/badge/SQL-1e3a5f?style=flat-square&logo=mysql&logoColor=8b9eb0) ![Bash](https://img.shields.io/badge/Bash-1e3a5f?style=flat-square&logo=gnubash&logoColor=8b9eb0)

**Mobile & Frontend**
![Flutter](https://img.shields.io/badge/Flutter-1e3a5f?style=flat-square&logo=flutter&logoColor=8b9eb0) ![Next.js](https://img.shields.io/badge/Next.js-1e3a5f?style=flat-square&logo=nextdotjs&logoColor=8b9eb0) ![Vanilla JS](https://img.shields.io/badge/Vanilla_JS-1e3a5f?style=flat-square&logo=javascript&logoColor=8b9eb0) ![HTML5](https://img.shields.io/badge/HTML5-1e3a5f?style=flat-square&logo=html5&logoColor=8b9eb0) ![CSS3](https://img.shields.io/badge/CSS3-1e3a5f?style=flat-square&logo=css3&logoColor=8b9eb0)

**Backend & APIs**
![.NET Web API](https://img.shields.io/badge/.NET_Web_API-1e3a5f?style=flat-square&logo=dotnet&logoColor=8b9eb0) ![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-1e3a5f?style=flat-square&logo=dotnet&logoColor=8b9eb0) ![Node.js](https://img.shields.io/badge/Node.js-1e3a5f?style=flat-square&logo=nodedotjs&logoColor=8b9eb0) ![REST](https://img.shields.io/badge/REST_API-1e3a5f?style=flat-square&logo=postman&logoColor=8b9eb0) ![Webhooks](https://img.shields.io/badge/Webhooks-1e3a5f?style=flat-square&logoColor=8b9eb0) ![JWT](https://img.shields.io/badge/JWT-1e3a5f?style=flat-square&logo=jsonwebtokens&logoColor=8b9eb0)

**Databases & Cloud**
![Firebase](https://img.shields.io/badge/Firebase-1e3a5f?style=flat-square&logo=firebase&logoColor=8b9eb0) ![Supabase](https://img.shields.io/badge/Supabase-1e3a5f?style=flat-square&logo=supabase&logoColor=8b9eb0) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1e3a5f?style=flat-square&logo=postgresql&logoColor=8b9eb0) ![MySQL](https://img.shields.io/badge/MySQL-1e3a5f?style=flat-square&logo=mysql&logoColor=8b9eb0) ![Azure](https://img.shields.io/badge/Azure-1e3a5f?style=flat-square&logo=microsoftazure&logoColor=8b9eb0)

**DevOps & Infrastructure**
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-1e3a5f?style=flat-square&logo=githubactions&logoColor=8b9eb0) ![Cloudflare CDN](https://img.shields.io/badge/Cloudflare_CDN-1e3a5f?style=flat-square&logo=cloudflare&logoColor=8b9eb0) ![Cloudflare AI Gateway](https://img.shields.io/badge/Cloudflare_AI_Gateway-1e3a5f?style=flat-square&logo=cloudflare&logoColor=8b9eb0) ![Linux](https://img.shields.io/badge/Linux-1e3a5f?style=flat-square&logo=linux&logoColor=8b9eb0) ![Docker](https://img.shields.io/badge/Docker-1e3a5f?style=flat-square&logo=docker&logoColor=8b9eb0) ![Git](https://img.shields.io/badge/Git-1e3a5f?style=flat-square&logo=git&logoColor=8b9eb0)

**AI & Integrations**
![OpenAI](https://img.shields.io/badge/OpenAI_GPT--4o-1e3a5f?style=flat-square&logo=openai&logoColor=8b9eb0) ![Anthropic Claude](https://img.shields.io/badge/Anthropic_Claude-1e3a5f?style=flat-square&logo=anthropic&logoColor=8b9eb0) ![Gemini](https://img.shields.io/badge/Google_Gemini-1e3a5f?style=flat-square&logo=google&logoColor=8b9eb0) ![RAG](https://img.shields.io/badge/RAG_Pipelines-1e3a5f?style=flat-square&logoColor=8b9eb0) ![Multi-Agent](https://img.shields.io/badge/Multi--Agent_Systems-1e3a5f?style=flat-square&logoColor=8b9eb0) ![Razorpay](https://img.shields.io/badge/Razorpay-1e3a5f?style=flat-square&logo=razorpay&logoColor=8b9eb0)

**Engineering Focus Areas**
![System Design](https://img.shields.io/badge/System_Design-112240?style=flat-square&logoColor=3b82f6) ![Real-time Systems](https://img.shields.io/badge/Real--time_Systems-112240?style=flat-square&logoColor=3b82f6) ![Security](https://img.shields.io/badge/Security_Fundamentals-112240?style=flat-square&logoColor=3b82f6) ![Observability](https://img.shields.io/badge/Observability-112240?style=flat-square&logoColor=3b82f6) ![Payment Integration](https://img.shields.io/badge/Payment_Integration-112240?style=flat-square&logoColor=3b82f6) ![Scalability](https://img.shields.io/badge/Scalability-112240?style=flat-square&logoColor=3b82f6)

</div>

---

```
harsh@dualmind:~$ github --stats
```

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=HarshBhanushali07&show_icons=true&hide_border=true&bg_color=0d1117&title_color=3b82f6&icon_color=3b82f6&text_color=8b9eb0&include_all_commits=true&count_private=true&rank_icon=github"/>
<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs?username=HarshBhanushali07&layout=compact&hide_border=true&bg_color=0d1117&title_color=3b82f6&text_color=8b9eb0&langs_count=8"/>

<img src="https://streak-stats.demolab.com?user=HarshBhanushali07&hide_border=true&background=0d1117&ring=3b82f6&fire=3b82f6&currStreakLabel=3b82f6&sideLabels=8b9eb0&dates=64748b&stroke=112240&currStreakNum=e2e8f0&sideNums=e2e8f0"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=HarshBhanushali07&bg_color=0d1117&color=3b82f6&line=1d4ed8&point=3b82f6&area=true&area_color=1e3a5f&hide_border=true&radius=4"/>

<img src="https://github-profile-trophy.vercel.app/?username=HarshBhanushali07&theme=onestar&no-frame=true&no-bg=true&row=1&column=7&margin-w=10"/>

</div>

---

```
harsh@dualmind:~$ cat services.md
```

```
  [01]  Mobile Apps
        Flutter · iOS & Android · Firebase / Razorpay integration
        Multi-role auth · CI/CD pipeline · production deployment
        Turnaround: 2–6 weeks

  [02]  Backend APIs
        .NET Web API or Node.js · auth · real-time · security alerting
        Supabase or Firebase · full documentation · built to scale
        Turnaround: 1–3 weeks

  [03]  AI Product Development
        RAG pipelines · AI support agents · multi-agent systems
        OpenAI + Claude + Cloudflare AI Gateway
        Cost-optimised · prompt-engineered · production-ready
        Turnaround: 1–4 weeks

  [04]  Full-Stack MVPs
        Mobile + backend + AI + security + DevOps + deployment
        Azure · Cloudflare CDN · CI/CD pipelines · full handoff
        Turnaround: 3–8 weeks

  Upfront scoping. Weekly deliverables. Full source on completion.
  Response time: < 24 hours.
```

---

```
harsh@dualmind:~$ cat principles.md
```

```
  [01]  Ship early.
        Real users surface problems that planning never will.

  [02]  Design for scale from day one.
        Cloudflare in front. Stateless API behind. SQL where it matters.
        These decisions are cheap early and expensive later.

  [03]  Observability is not optional.
        Logging, alerting, security notifications — day one, not post-incident.

  [04]  Pick the right tool, not the familiar one.
        Firebase for real-time sync. Supabase for relational queries.
        The tradeoff matters more than the preference.

  [05]  Own the outcome.
        Closing the ticket is not the goal. The working system is.

  [06]  Communicate clearly.
        Async-first. Updates unprompted. No surprises.
```

---

```
harsh@dualmind:~$ render --contribution-graph
```

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/HarshBhanushali07/HarshBhanushali07/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/HarshBhanushali07/HarshBhanushali07/output/github-contribution-grid-snake.svg"/>
  <img alt="contribution graph" src="https://raw.githubusercontent.com/HarshBhanushali07/HarshBhanushali07/output/github-contribution-grid-snake-dark.svg"/>
</picture>
</div>

---

```
harsh@dualmind:~$ open --channels
```

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-HarshBhanushali07-0d1b2a?style=for-the-badge&logo=github&logoColor=8b9eb0)](https://github.com/HarshBhanushali07)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-harshu--dev-0d1b2a?style=for-the-badge&logo=linkedin&logoColor=8b9eb0)](https://linkedin.com/in/harshu-dev)
[![Dev.to](https://img.shields.io/badge/Dev.to-harshudev-0d1b2a?style=for-the-badge&logo=devdotto&logoColor=8b9eb0)](https://dev.to/harshudev)
[![GitLab](https://img.shields.io/badge/GitLab-HarshBhanushali07-0d1b2a?style=for-the-badge&logo=gitlab&logoColor=8b9eb0)](https://gitlab.com/HarshBhanushali07)
[![Discord](https://img.shields.io/badge/Discord-harshu911-0d1b2a?style=for-the-badge&logo=discord&logoColor=8b9eb0)](https://discord.com)
[![Email](https://img.shields.io/badge/Email-contact-0d1b2a?style=for-the-badge&logo=gmail&logoColor=8b9eb0)](mailto:bhanushaliharsh434@gmail.com)
[![Website](https://img.shields.io/badge/dualmindlab.tech-live-0d1b2a?style=for-the-badge&logo=googlechrome&logoColor=3b82f6)](http://dualmindlab.tech)

<br/>

```
  I build systems that handle real traffic, real payments, and real users.
  If your team needs an engineer who owns the outcome end-to-end — let's talk.

  bhanushaliharsh434@gmail.com   ←  fastest reply
  dualmindlab.tech               ←  live product
  linkedin.com/in/harshu-dev     ←  professional profile

  Open to: internships · freelance · AI product builds · early-stage startups
```

```
harsh@dualmind:~$ exit
  Logging off. Come back when you have something to ship.
  [session closed]
```

</div>

<div align="center">
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:112240,40:0d1b2a,80:0a0f14,100:000000&height=120&section=footer"/>
</div>
