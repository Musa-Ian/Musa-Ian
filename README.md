<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,65:3D2A0C,100:C77B0A&height=200&section=header&text=Ian%20Musa&fontSize=54&fontColor=fff&animation=fadeIn&fontAlignY=33&desc=Full-Stack%20Developer%20·%20Founder%20·%20Systems%20Builder&descSize=17&descAlignY=57)

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=900&color=F59E0B&center=true&vCenter=true&multiline=false&width=580&height=55&lines=Twenty+microservices.+One+developer.;Escrow%2C+payments%2C+logistics+%E2%80%94+built+solo.;Self-hosted+the+whole+thing.+On+purpose.;Nairobi+%E2%86%92+Calgary.+Still+building." alt="Typing SVG" />

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/Building-Jogeave-F59E0B?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Based_in-Calgary,_Canada_🍁-21262D?style=for-the-badge" />
  <img src="https://img.shields.io/badge/From-Nairobi,_Kenya_🌍-21262D?style=for-the-badge" />
</p>

</div>

---

## 🌟 About Me

Here's the thing nobody tells you about "full-stack": most people mean they can write a React component *and* an API route. I mean I wrote the services, designed the database, built the payment rails, wrote the CI pipeline, and then went and set up the Linux servers the whole thing runs on. I wanted to know how far down it goes. Turns out it goes all the way down, and that's the fun part.

For the past year I've been solo-building **[Jogeave](https://www.jogeave.com/)** — a marketplace for film and TV crew where the money actually behaves. Twenty microservices, three frontends, a self-hosted cloud. No team, no outside engineers, no funding. I designed it, built it, shipped it, and I'm the one who gets paged when it breaks.

I got here sideways. Before software I worked on **aircraft structures**, and that job rewires how you think: you learn to assume your own work is wrong until you've proven otherwise, because the alternative is somebody falling out of the sky. Then I found out software has the same property — it just hides the consequences better. Money, though? Money doesn't hide anything. Get escrow wrong and someone doesn't get paid for their work. That's the kind of problem I want.

So I build the way I do for a reason: **understand the whole system, or you're just guessing politely.**

**What I actually believe:**

- **Go deep, not wide.** Knowing one system completely beats knowing five well enough to be dangerous.
- **If you ship it, you own it.** Anyone can hand off a repo. Running the thing in production is where you find out if you were right.
- **Break it yourself first.** I learn by doing, failing, and rebuilding — theory alone never sticks for me.
- **Boring infrastructure is a feature.** The best systems are the ones nobody has to think about.
- **The good work happens with other people.** I do my sharpest thinking when someone's pushing back.

> *Anybody can ship something that works today. I'm interested in what's still standing in five years.*

---

## Tech Arsenal

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=ts,js,go,py,bash,html,css" alt="Languages" />

**Frontend**

<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,vite" alt="Frontend" />
<br/>
<img src="https://img.shields.io/badge/React_Native-Expo_SDK_55-000020?style=flat-square&logo=expo&logoColor=white" />
<img src="https://img.shields.io/badge/Framer_Motion-black?style=flat-square&logo=framer&logoColor=white" />

**Backend & Data**

<img src="https://skillicons.dev/icons?i=nodejs,nestjs,fastapi,postgres,redis,prisma" alt="Backend" />
<br/>
<img src="https://img.shields.io/badge/Go-Gin-00ADD8?style=flat-square&logo=go&logoColor=white" />
<img src="https://img.shields.io/badge/Temporal-Workflows-21262D?style=flat-square" />
<img src="https://img.shields.io/badge/pgvector-Semantic_Search-21262D?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Socket.IO-Realtime-010101?style=flat-square&logo=socketdotio&logoColor=white" />

**Infra & DevOps**

<img src="https://skillicons.dev/icons?i=docker,linux,gitlab,git,cloudflare,nginx,grafana" alt="Infra" />
<br/>
<img src="https://img.shields.io/badge/mTLS-step--ca-21262D?style=flat-square" />
<img src="https://img.shields.io/badge/Semgrep_+_Trivy-Security_Scanning-21262D?style=flat-square" />
<img src="https://img.shields.io/badge/Sentry_+_HyperDX-Observability-21262D?style=flat-square&logo=sentry&logoColor=white" />

**Payments & AI**

<img src="https://img.shields.io/badge/Stripe_Connect-Escrow_&_Payouts-635BFF?style=flat-square&logo=stripe&logoColor=white" />
<img src="https://img.shields.io/badge/LLM_Orchestration-Multi--model_routing-21262D?style=flat-square" />
<img src="https://img.shields.io/badge/Claude_Code-AI--assisted_dev-21262D?style=flat-square&logo=anthropic&logoColor=white" />

</div>

---

## What I'm Building

### 🎬 Jogeave — [jogeave.com](https://www.jogeave.com/) · [log in to the app](https://app.jogeave.com/login)

<img src="https://img.shields.io/badge/Status-In_Production-238636?style=for-the-badge" />
<img src="https://img.shields.io/badge/Team_Size-1-21262D?style=for-the-badge" />

**The problem:** an entire global industry hires its crews on spreadsheets, group chats and vibes. Money shows up late or not at all, nobody can prove who actually turned up on set, and everyone has just accepted this. It's 2026.

**What I built:** a marketplace where funds go into escrow and only come out when the work is *verified* — 75% on confirmed arrival, the rest on completion. Booking, payments, logistics and ticketing in one system, so the money and the reality can't drift apart.

The engineering is where it gets fun:

- **20-service backend** — NestJS/TypeScript for the platform, **Go** for the financial core, FastAPI where Python wins
- **Escrow + Stripe Connect** — milestone-based release, QR-verified arrival checkpoints, automated global payouts, orchestrated with **Temporal** workflows so money never gets stranded mid-transaction
- **High-concurrency ticketing** — Redis atomic inventory so events can't oversell, plus identity-bound tickets with rotating QR validation
- **Semantic search** — PostgreSQL 17 + **pgvector** with embeddings, so discovery understands intent instead of keywords
- **Multi-model AI pipeline** — aggregates public data into 125+ structured categories with primary/fallback LLM routing
- **Self-hosted everything** — I pulled the entire platform *off* Vercel, Railway and Neon onto Linux servers I provision and run myself: Docker Swarm, Postgres 17, Redis, mTLS between every service, Cloudflare at the edge. It cut hosting costs hard and I own the whole stack.
- **134-job CI/CD pipeline** — parallel test/build/deploy across the monorepo with SAST, container scanning, environment-gated deploys and rollback jobs

Next.js 16 + React 19 on the web. React Native (Expo) for mobile, in progress.

---

### 💫 Matchastra — [matchastra.com](https://matchastra.com)

<img src="https://img.shields.io/badge/Status-Live-238636?style=for-the-badge" />
<img src="https://img.shields.io/badge/Stack-Next.js_|_TypeScript_|_Python-21262D?style=for-the-badge" />

Everyone assumes this is a personality-quiz app. It isn't. Underneath the friendly UI it's an **astronomy problem** — real ephemeris math, real coordinate systems, and the kind of timezone bugs that ruin lives.

- Integrated the **Swiss Ephemeris** to compute real planetary positions — ecliptic longitude, retrograde speed, house systems — from birth date, time and coordinates
- Timezone-correct UTC conversion against a 5MB world-cities dataset, handling **historical time zones and DST** — the part everyone gets wrong
- **Forked and extended** an open-source Python astronomy library ([Musa-Ian/natal](https://github.com/Musa-Ian/natal)) to add native synastry-chart generation
- A weighted multi-system scoring engine — aspect/orb geometry, BaZi four pillars, lunisolar calendar boundaries, numerology — that scales dynamically with how much data you actually have
- Scoring runs **server-side only**, so the algorithm never ships to the client bundle

---

### 📱 Instagram Downloader — [live demo](https://v0-instagram-download-website.vercel.app) · [source](https://github.com/Musa-Ian/Instagram-pull)

<img src="https://img.shields.io/badge/UI-Fully_Working-238636?style=for-the-badge" />
<img src="https://img.shields.io/badge/Instagram_API-Now_Gated-6E4A0E?style=for-the-badge" />

I built this to prove out a flow end to end: paste a link, resolve the media, hand back a clean download, no ads and no nonsense. The interface does exactly what it promises and the pipeline behind it is sound.

**Then Instagram gated their API, and the fetching stopped working.** I'm leaving it up anyway, on purpose. Deleting it would be tidier and also dishonest — this is what building on somebody else's platform actually looks like, and pretending otherwise helps nobody. The architecture is real, the UI works, the door got closed from the other side. Click it knowing that.

---

### 🔬 Things I built purely because I wanted to know

Not products. Just questions I couldn't leave alone:

| Project | The question it answers |
|---|---|
| [youtube-quality-tester](https://musa-ian.github.io/youtube-quality-tester/) | *Why does the same YouTube video look worse in a small player?* Turns out the IFrame player silently drops your resolution tier based on element size. This proves it, live. |
| [Shortcuts-updates](https://github.com/Musa-Ian/Shortcuts-updates) | *Can an iOS/macOS Shortcut update itself?* Apple gives you no update mechanism, so I built a hosted manifest the Shortcut checks against — self-updating Shortcuts, tested end to end. |

---

## GitHub Stats

<div align="center">

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=Musa-Ian&theme=tokyo-night&hide_border=true&bg_color=0D1117&color=F59E0B&line=D97706&point=C9D1D9&area=true&area_color=B45309" />

</div>

> **Take this graph with a pinch of salt.** What you're looking at is my experiments and open-source forks. The actual work — Jogeave's monorepo, ~20 services, a 134-job pipeline, commits most days — lives in private repos this thing can't see. Contribution graphs measure what's *visible*, not what's *built*, and those are very different numbers.

---

## Beyond the Code

<div align="center">
<table>
<tr>
<td width="50%" valign="top">

### ✈️ Aircraft Structures

Aircraft don't care how confident you feel. The work teaches you to distrust your own judgment until you've actually checked — because "it should be fine" is how people die. Software let me relax that instinct for about a week before I realized it was the most valuable thing I owned.

</td>
<td width="50%" valign="top">

### 🌍 Nairobi → Calgary

Born in Nairobi, raised in Nakuru, building in Alberta. Moving across the world does one useful thing to your head: it kills the assumption that your normal is everyone's normal. So I build for the planet I've actually seen — multiple currencies, multiple timezones, and never once assuming the user is standing where I am.

</td>
</tr>
</table>
</div>

---

## 💭 My Philosophy

<img src="https://user-images.githubusercontent.com/74038190/212748830-4c709398-a386-4761-84d7-9e10b98fbe6e.gif" width="100%" />

```javascript
const whatIActuallyBelieve = {
  systems:   "They never fail loudly. They fail PARTIALLY — that's the 3am one",
  cloud:     "A convenience you rent, not a law of physics. So I self-host",
  speed:     "You move fast BECAUSE the fundamentals are solid, not despite it",
  ownership: "Built on someone else's API? You're renting. Plan accordingly",
  ai:        "Made me faster, never lazier. I still answer for every line",
  craft:     "Understand the whole system, or you're just guessing politely"
};

// Life's too short to build boring things.
// But payments? Payments should be extremely boring. 🚀
```

---

## 🤝 Let's Build Something

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.png" alt="Fire" width="100" />

</div>

I'm at my best when someone hands me a genuinely hard problem and then gets out of the way. If you're building something that has to be **correct** and not merely impressive — payments, infrastructure, anything where being wrong has consequences someone actually feels — that's the work I want.

Whether you're after a **collaborator**, a **co-founder**, or you just want to **argue about architecture for an hour** — I'm always up for talking to people who build things.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ianmusa-mi/)
[![Email](https://img.shields.io/badge/Email-Say_Hello-21262D?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ianmusa.m@gmail.com)
[![Jogeave](https://img.shields.io/badge/Jogeave-See_What_I_Build-F59E0B?style=for-the-badge)](https://www.jogeave.com/)
[![Matchastra](https://img.shields.io/badge/Matchastra-Try_It-21262D?style=for-the-badge)](https://matchastra.com)

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,65:3D2A0C,100:C77B0A&height=120&section=footer" />

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=Musa-Ian&style=for-the-badge&color=21262D&label=Profile+Views)

<br/>

**✨ Thanks for stopping by! ✨**

*Currently building the next big thing—stay tuned!*

</div>
