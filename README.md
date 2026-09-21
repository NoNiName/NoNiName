<div align="center">

# Kitsuna &nbsp;·&nbsp; `@NoNiName`

**Unity game systems · Next.js web apps · Lua tooling**

Most of what I build is *plumbing*: time systems, dialogue engines, admin panels, UI libraries —
the layer other features get to stand on.

[![Read in Thai](https://img.shields.io/badge/%F0%9F%87%B9%F0%9F%87%AD_%E0%B8%AD%E0%B9%88%E0%B8%B2%E0%B8%99%E0%B8%89%E0%B8%9A%E0%B8%B1%E0%B8%9A%E0%B8%A0%E0%B8%B2%E0%B8%A9%E0%B8%B2%E0%B9%84%E0%B8%97%E0%B8%A2-readme--thai.md-1f6feb?style=for-the-badge)](./readme-thai.md)

</div>

---

## About

I work across three fairly different worlds and enjoy all of them for different reasons:

- **Game development** — Unity + C#, mostly simulation-style systems and narrative tooling
- **Web** — Next.js, TypeScript, Supabase, deployed on Vercel
- **Scripting & tooling** — Lua UI libraries, Python automation, sysadmin-flavoured glue

Comfortable on both Linux (Ubuntu) and Windows. I write my project docs in Thai and my code in English.

---

## Tech Stack

**Languages**

![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Game**

![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![ShaderLab](https://img.shields.io/badge/ShaderLab-222C37?style=flat-square&logo=unity&logoColor=white)
![Roblox](https://img.shields.io/badge/Roblox_Lua-00A2FF?style=flat-square&logo=roblox&logoColor=white)

**Web**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**Tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)

---

## What I'm Working On

### 🎮 Game Development

**DESTINY / `UnityDestiny`** &nbsp;·&nbsp; *Unity, C#* &nbsp;·&nbsp; 🔒 private

A life-simulation game built as a stack of small, independent systems rather than one big
`GameManager`. Time, stats (money, grades, debt), activities, locations and travel costs,
interaction, dialogue, an in-game phone with apps and messenger, wandering NPCs, day/night
lighting, arcade minigames — each one documented on its own and planned out across a long-form
phase roadmap.

**Unity Dialogue System** &nbsp;·&nbsp; *Unity, TypeScript editor* &nbsp;·&nbsp; 🔒 private

A dialogue / visual-novel toolkit with a plain-text script format and a browser-based editor,
so writing branching conversations doesn't mean living inside the Unity inspector.

**[`Dungenos-Cube`](https://github.com/NoNiName/Dungenos-Cube)** &nbsp;·&nbsp; *Unity, ShaderLab* &nbsp;·&nbsp; public

A Unity project on the rendering side of things — shaders and visual experiments.

### 🌐 Web

**New Web Portfolio** &nbsp;·&nbsp; *Next.js, TypeScript, Supabase, Vercel* &nbsp;·&nbsp; 🔒 private

A portfolio site with a real admin surface behind it: a `/dashboard` panel, an activity log with
filters, cover-image upload with compression and format conversion, a swappable storage layer
(Supabase or local `DATA_DIR`), and a documented deployment path for the classic
"works locally, breaks on Vercel" problem.

**[`DOOXY-SHOP`](https://github.com/NoNiName/DOOXY-SHOP)** &nbsp;·&nbsp; *Next.js, TypeScript* &nbsp;·&nbsp; public &nbsp;·&nbsp; [live ↗](https://dooxy-shop.vercel.app)

A shop front-end built on the Next.js App Router and deployed to Vercel.

**`nextjs-boilerplate`** &nbsp;·&nbsp; *Next.js, TypeScript* &nbsp;·&nbsp; 🔒 private

My own starting point for new Next.js projects, so every new idea begins a few hours ahead.

### 🌙 Lua & Roblox

**[`Library`](https://github.com/NoNiName/Library)** &nbsp;·&nbsp; *Lua* &nbsp;·&nbsp; public

A long-running collection of Lua modules and UI libraries — the oldest thing here, and still the
one with the most commits behind it.

**[`Celestara-Hub`](https://github.com/NoNiName/Celestara-Hub)** &nbsp;·&nbsp; *Lua* &nbsp;·&nbsp; public

A newer UI library, rebuilt from what the older one taught me.

### 📚 Learning & Experiments

[`Learn-MMD`](https://github.com/NoNiName/Learn-MMD) · [`MiNiProject`](https://github.com/NoNiName/MiNiProject) · [`Html`](https://github.com/NoNiName/Html) — smaller repos where I try a thing out and keep the notes.

---

## How I Build

A few rules I keep coming back to, mostly learned the hard way:

- **Wrap what exists, don't overwrite it.** If there's already a day/night cycle, the time system
  wraps it. Two clocks in one project is a bug waiting for a deadline.
- **Keep data separate from runtime.** The thing that *describes* an activity and the thing that
  *runs* it are different objects.
- **Game logic should be testable without entering Play Mode.** `Tick(float deltaTime)` always
  lives apart from `Update()`.
- **Write the docs while the context is still in your head.** Every project here has a `docs/`
  folder aimed at whoever opens it in six months — usually me.

---

## Reach Me

[![GitHub](https://img.shields.io/badge/GitHub-@NoNiName-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/NoNiName)
[![Discord](https://img.shields.io/badge/Discord-Negative-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com)

<div align="center">

*Several repositories above are private — happy to talk through the architecture of any of them.*

</div>
