<!--
  SETUP
  1. Create a public repo named exactly like your GitHub username. Its README.md becomes your profile.
  2. Put this README.md at the repo root and the three SVGs in /assets.
  3. Find-and-replace GH_USER below with your username (used by the two stats cards).
  4. Live coding stats: add the .github/workflows folder, then add two repo secrets,
     WAKATIME_API_KEY and GH_TOKEN (see the workflow file), and run the "Waka Readme" workflow once
     from the Actions tab. The action fills in the block between the two waka comment markers below.

  WHY SVGs: GitHub strips CSS/JS from Markdown, but it renders SVG files loaded through <img>.
  That is the only way to get custom layout and typography on a profile, so the visual identity
  lives in /assets and the README just arranges it.
-->

<div align="center">

<img src="assets/header.svg" alt="Prescription label: Rx, Tways Navarro. Sig: plan with the agent, review every diff, ship, then learn what it did." width="100%">

<a href="https://webportfolio-two-phi.vercel.app">
  <img src="https://img.shields.io/badge/portfolio-visit-0E7A5A?style=for-the-badge&labelColor=12303A&logo=vercel&logoColor=white" alt="Portfolio">
</a>

</div>

<br>

## About

I'm a 3rd-year IT student at the University of San Agustin, building real systems for campuses, local government and small businesses. I build mostly through Claude Code and agentic workflows, and I'm using every project to learn what those tools are doing underneath: data structures, databases, auth, and the tradeoffs behind each pattern.

```ts
// Modeled on a prescription: what I take on, how I work, and what I'm working on.
const tways = {
  name: "Theodore Samuel M. Navarro",
  goesBy: ["Tways", "Twice"],
  base: "Iloilo City, Philippines",

  roles: [
    "Lead developer, capstone team",
    "VP for External Affairs, Information Technology Student Association (ITSA)",
    "Founder, AskTwice (freelance academic services)",
  ],

  // Nothing ships without a second check.
  workflow: ["plan with the agent", "delegate", "review every diff", "ship", "learn what it did"],

  stack: ["Next.js", "TypeScript", "Supabase", "Tailwind CSS", "Claude Code", "MCP"],
  learning: ["data structures", "SQL and RLS", "agent loops", "system design"],
  certifications: ["Google Prompting Essentials", "Google AI"],
} as const;
```

<br>

<div align="center">
<img src="assets/formulary.svg" alt="Formulary: Next.js, TypeScript, React, Tailwind CSS, Supabase; Claude Code, MCP servers, Anthropic API, Vercel AI SDK, Vercel; Zod, RLS, Git and CI, ESLint, Docker." width="100%">
</div>

<br>

## Dispensary

Selected work. Each one solves a specific problem for a specific set of people.

| Project | What it does |
|---|---|
| **ClauseGuard** | Flags risky clauses in SaaS contracts (capstone platform) |
| **FaciliTrak** | AI-assisted facility condition reporting (capstone) |
| **PASA** | Multi-agent permit compliance checker for local government units |
| **SENTRO** | Integrated management system for municipalities |
| **UniLend** | QR-based reservations for university equipment and venues |
| **Baylo Agustino** | Campus trading and bartering PWA for University of San Agustin |
| **MedMinder** | Inventory and expiry tracking for medicine stock |
| **Spot** | Attendance PWA for my IT-3C class |

<!-- Link each project name to its repo or live demo once it is public: **[ClauseGuard](https://github.com/GH_USER/clauseguard)** -->

<br>

## Dispensing log

Live coding metrics, refreshed twice a day by a GitHub Action. It shows how much of my time goes to each language and editor, including Claude Code.

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->

<br>

## Chart

<div align="center">

<!-- Third-party hosted cards. They occasionally rate-limit; if one shows an error, refresh later. -->
<img height="170" src="https://streak-stats.demolab.com?user=GH_USER&background=FBFCFA&ring=0E7A5A&fire=C4720E&currStreakNum=12303A&currStreakLabel=0E7A5A&sideNums=12303A&sideLabels=4A6670&dates=4A6670&border=C4720E&stroke=C4720E44" alt="GitHub streak">
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GH_USER&layout=compact&custom_title=Most%20prescribed%20languages&bg_color=FBFCFA&title_color=0E7A5A&text_color=12303A&border_color=C4720E" alt="Top languages">

<br><br>

<img src="assets/footer.svg" alt="Keep out of reach of production without a code review." width="100%">

</div>
