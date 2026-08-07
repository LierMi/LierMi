<h1 align="center">Lier Mi</h1>

<p align="center">
  <b>AI × Web3 Product Manager</b> · AI Full-Stack Builder · UI/UX Designer<br>
  <i>Curator turned builder — I turn protocol-level problems into places people can walk into.</i>
</p>

<p align="center">
  <a href="mailto:liermi1996@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Based%20in-Rome,%20Italy-555?style=flat" alt="Location">
  <img src="https://img.shields.io/badge/Open%20to-AI%20%C3%97%20Web3%20Product%20roles-2ea44f?style=flat" alt="Open to work">
</p>

---

### About

I came to AI and Web3 from **fine arts and curation**, by way of **42 School** (C, systems programming).

A curator's job is to decide what deserves to exist in a room, what story it tells, and how a stranger finds their way through it. That turned out to be the same job as product. I now do it for AI agents and on-chain systems: I originate the concept, define the problem it has to earn its keep on, write the narrative and the interface, and ship a working, deployed demo.

I entered two AI × Web3 hackathons in 2026 — **one championship, one runner-up.**

---

### What I'm actually good at

**🎯 Concept origination — 0→1 产品策划**<br>
Every project below started from a blank page. My strength is finding the framing that makes an infrastructure problem legible *and* emotionally sticky: on-chain exploits become a **disaster museum**; agent spending limits become a **personal constitution**; agent liability becomes a **labor arbitration court**. Judges and users understand the product in one sentence, because the sentence came first.

**🗺 Curation as information architecture**<br>
Deciding what to show, in what order, and — harder — what to cut. On one project I took an exhibit page from ~16,000px of stacked sections down to ~3,000px by inlining the core narrative and folding the rest away. Naming, sequencing, and pacing are product decisions, not decoration.

**🚧 Defining what the system must *not* claim**<br>
The product decision I care most about is where the machine should stop. Sound Atlas curates pre-built halls so the AI never has to fake a match to your personal memory. Silicon Labor Arbitration settles the measurable clauses automatically and freezes the subjective one with an explicit *"I cannot adjudicate this — you decide."* [Cyber Memory Cemetery](https://github.com/LierMi/cyber-memory-cemetery) ships two genuinely separate verification calls rather than presenting mock output as real. Honest boundaries are a feature, and I spec them deliberately.

**🔧 Enough engineering to spec it and ship it**<br>
42 School's C curriculum ([libft](https://github.com/LierMi/libft) → [push_swap](https://github.com/LierMi/push_swap) → [minitalk](https://github.com/LierMi/minitalk) → [fract-ol](https://github.com/LierMi/fractol)) gave me the vocabulary to write specs engineers don't have to translate. I build the frontends and author the agent system prompts myself, hand off to backend engineers through JSON contracts, and use **Claude Code** as my default implementation loop — which is how a solo concept reaches a deployed demo inside a hackathon weekend.

---

### 🚀 Featured Projects

#### [Digital Pompeii · 数字庞贝](https://github.com/10yu7ian/digital-pompeii)
`🏆 Champion — Z.AI track, AI × Web3 Agentic Builders Hackathon`

A dark museum for on-chain failures. Paste a contract address and an autonomous forensic agent (GLM-5.1) runs 6–12 rounds of tool calls over public chain evidence — resolving proxy storage slots and doing *upgrade archaeology* to reach the implementation that was actually live at the time of the attack — then returns a two-layer exhibit: a citable technical autopsy with transaction hashes, and a literary epitaph. Five canonical disasters (The DAO, Parity, Beanstalk, Ronin, Nomad) reconstructed end-to-end. Design rule: **investigate first, write second — zero fiction in the technical layer.**

`React` `Python` `GLM-5.1` `Etherscan API` — *concept, curation & exhibition copy, agent system prompt, frontend*<br>
🏛 [digital-pompeii.vercel.app](https://digital-pompeii.vercel.app)

#### [Pocket Republic · 口袋共和国](https://github.com/LierMi/pocket-republic)
`🥈 Runner-up — KITE AI track (The Future of Agentic Payment), AI × Web3 Growth Hackathon`

When an AI agent starts spending your money, a wallet isn't enough — it needs a constitution. You write a nine-article personal constitution; a seven-member AI cabinet debates each proposal with live LLM personas; a **deterministic rule engine — never the model — decides the money**; execution runs inside a Kite Agent Passport scoped spending session and is written to a public national gazette. Real Passkey-approved session on Kite testnet, with gated settlement labeled honestly instead of faked.

`JavaScript` `Kite Agent Passport` `Gonka` `Vercel Serverless` — *concept, governance design, constitution text, frontend*<br>
🌐 [pocket-republic.vercel.app](https://pocket-republic.vercel.app)

#### [Silicon Labor Arbitration · 硅基劳动仲裁院](https://github.com/LierMi/Silicon-Labor-Arbitration)

Where does accountability go when a human hires an agent, that hires an agent, that calls a tool? An on-chain arbitration layer built on one strict separation: a deterministic rule layer is the **only** layer allowed to move money, while the AI layer may only cross-examine, cite evidence and explain. Objective acceptance criteria settle automatically; the subjective one — the demo's *"is this actually a cat?"* — is frozen and escalated to a human. Not a court: an arbitration body, because arbitration was never meant to be final.

`TypeScript` `Solidity` `Monad Testnet` `Foundry` — *concept, product framing & positioning, UX*

#### [The Sound Atlas · 声音星图](https://github.com/LierMi/The_Sound_Atlas)
`TME Tencent Music Hackathon 2026 — Track A, Innovative Music Products`

An era of music, rebuilt as a museum you can walk into. Drag through a 3D galaxy of musical time-coordinates, dive into one, and an AI curator reconstructs its sound, stories and geography as a hall: curator's notes, a listening route through the real city, an exhibit label written from your own memory, and a stamped "passport" constellation you can export and share.

`React` `React Three Fiber` `Vite` `Tailwind` `GLM API` — *full product concept, curation, 3D homepage & frontend*<br>
🌌 [sound-atlas-five.vercel.app](https://sound-atlas-five.vercel.app)

#### [Timeframe Estimator](https://github.com/U-Mina/42-Internal-Hackthon)
`42 Internal Hackathon — team of four`

A pace-keeping tool for 42 students that estimates realistic project timelines, built against the 42 Intra API for student, project and attendance data.

`TypeScript` `42 Intra API`

#### [Histopathology Image Classification](https://github.com/Qiaoli-Li-Res/histopathology-classification)
`Research collaboration`

Nine-class colorectal cancer tissue classifier: EfficientNet-B0 transfer learning trained on NCT-CRC-HE-100K (100,000 H&E patches) and evaluated on the patient-independent CRC-VAL-HE-7K set — a compact, reproducible baseline for tissue recognition.

`Python` `PyTorch` `EfficientNet-B0`

---

### 🧰 Toolkit — three hats, one person

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black" alt="C">
  <img src="https://img.shields.io/badge/Solidity-363636?style=flat&logo=solidity&logoColor=white" alt="Solidity">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/Three.js-000000?style=flat&logo=three.js&logoColor=white" alt="Three.js">
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white" alt="Vite">
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Shell-4EAA25?style=flat&logo=gnu-bash&logoColor=white" alt="Shell">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white" alt="Vercel">
</p>

**🎯 项目策划 · Product Strategy & Planning**<br>
0→1 concept origination · problem framing & market positioning · PRD and specs engineers don't have to translate · information architecture · scope, roadmap & prioritisation · narrative, UX copy and pitch design · hackathon-speed delivery under a deadline

**🤖 AI 全栈 · AI Full-Stack Engineering**<br>
LLM agent architecture · system prompt engineering & evaluation · long-horizon autonomous tool-calling loops · multi-agent deliberation and role design · **standing up AI workflows and automation tooling for a team** · API integration & data processing · RAG and structured-output pipelines · serverless deployment<br>
`Python` · `Node.js` · GLM · Claude · Gonka · OpenAI-compatible APIs · `PyTorch` · Vercel Serverless

**🎨 UI 设计 · UI/UX Design & Frontend**<br>
design systems built from scratch · visual and art direction · 3D / WebGL interactive scenes · motion, transitions & micro-interactions · responsive and mobile · exhibition-grade layout and typography · design-to-code with no handoff loss<br>
`React` · `React Three Fiber` · `Tailwind` · `Vite` · `TypeScript` / `JavaScript` · HTML/CSS

**⛓ Web3**<br>
on-chain forensics (Etherscan, proxy resolution, upgrade-history tracing) · agentic payments (Kite Agent Passport, scoped spending sessions, x402) · smart-contract integration & testnet deployment<br>
`Solidity` · EVM · Monad · Foundry · Etherscan API

**🧱 Foundations**<br>
systems programming and memory management from 42 School · shell scripting & Unix tooling · Git-based collaborative workflows · writing code that is correct, efficient and actually maintainable<br>
`C` · `Shell` · `Linux` · `Git`

> **What that means for a team:** I can take a vague idea all the way to a deployed, demo-able product on my own — concept, spec, agent pipeline, interface and pitch — and I can set up the AI workflows and internal tooling the rest of the team runs on day to day.

---

### 🌍 Languages

🇨🇳 Chinese · 🇬🇧 English · 🇮🇹 Italian · 🇩🇪 German

### 📫 Get in touch

📧 **liermi1996@gmail.com** — open to AI × Web3 product roles, and to teams that need one person who can decide what the thing should be, build it, and make it look like it belongs.
