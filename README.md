<h1 align="center">Lier Mi</h1>

<p align="center">
  <b>AI × Web3 Product Manager</b> · curator turned builder<br>
  <i>I turn protocol-level problems into places people can walk into.</i>
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

Six builds in 2026 across AI × Web3, music-tech and medical AI — **one track championship and one runner-up** among them.

---

### What I'm actually good at

**🎯 Concept origination — 0→1 产品策划**
Every project below started from a blank page. My strength is finding the framing that makes an infrastructure problem legible *and* emotionally sticky: on-chain exploits become a **disaster museum**; agent spending limits become a **personal constitution**; agent liability becomes a **labor arbitration court**. Judges and users understand the product in one sentence, because the sentence came first.

**🗺 Curation as information architecture**
Deciding what to show, in what order, and — harder — what to cut. On one project I took an exhibit page from ~16,000px of stacked sections down to ~3,000px by inlining the core narrative and folding the rest away. Naming, sequencing, and pacing are product decisions, not decoration.

**🚧 Defining what the system must *not* claim**
The product decision I care most about is where the machine should stop. Sound Atlas curates pre-built halls so the AI never has to fake a match to your personal memory. Silicon Labor Arbitration settles the measurable clauses automatically and freezes the subjective one with an explicit *"I cannot adjudicate this — you decide."* [Cyber Memory Cemetery](https://github.com/LierMi/cyber-memory-cemetery) ships two genuinely separate verification calls rather than presenting mock output as real. Honest boundaries are a feature, and I spec them deliberately.

**🔧 Enough engineering to spec it and ship it**
42 School's C curriculum ([libft](https://github.com/LierMi/libft) → [push_swap](https://github.com/LierMi/push_swap) → [minitalk](https://github.com/LierMi/minitalk) → [fract-ol](https://github.com/LierMi/fractol)) gave me the vocabulary to write specs engineers don't have to translate. I build the frontends and author the agent system prompts myself, hand off to backend engineers through JSON contracts, and use **Claude Code** as my default implementation loop — which is how a solo concept reaches a deployed demo inside a hackathon weekend.

---

### 🚀 Featured Projects

#### [Digital Pompeii · 数字庞贝](https://github.com/10yu7ian/digital-pompeii)
`🏆 Champion — Z.AI track, AI × Web3 Agentic Builders Hackathon`

A dark museum for on-chain failures. Paste a contract address and an autonomous forensic agent (GLM-5.1) runs 6–12 rounds of tool calls over public chain evidence — resolving proxy storage slots and doing *upgrade archaeology* to reach the implementation that was actually live at the time of the attack — then returns a two-layer exhibit: a citable technical autopsy with transaction hashes, and a literary epitaph. Five canonical disasters (The DAO, Parity, Beanstalk, Ronin, Nomad) reconstructed end-to-end. Design rule: **investigate first, write second — zero fiction in the technical layer.**

`React` `Python` `GLM-5.1` `Etherscan API` — *concept, curation & exhibition copy, agent system prompt, frontend*
🏛 [digital-pompeii.vercel.app](https://digital-pompeii.vercel.app)

#### [Pocket Republic · 口袋共和国](https://github.com/LierMi/pocket-republic)
`🥈 Runner-up — KITE AI track (The Future of Agentic Payment), AI × Web3 Growth Hackathon`

When an AI agent starts spending your money, a wallet isn't enough — it needs a constitution. You write a nine-article personal constitution; a seven-member AI cabinet debates each proposal with live LLM personas; a **deterministic rule engine — never the model — decides the money**; execution runs inside a Kite Agent Passport scoped spending session and is written to a public national gazette. Real Passkey-approved session on Kite testnet, with gated settlement labeled honestly instead of faked.

`JavaScript` `Kite Agent Passport` `Gonka` `Vercel Serverless` — *concept, governance design, constitution text, frontend*
🌐 [pocket-republic.vercel.app](https://pocket-republic.vercel.app)

#### [Silicon Labor Arbitration · 硅基劳动仲裁院](https://github.com/LierMi/Silicon-Labor-Arbitration)

Where does accountability go when a human hires an agent, that hires an agent, that calls a tool? An on-chain arbitration layer built on one strict separation: a deterministic rule layer is the **only** layer allowed to move money, while the AI layer may only cross-examine, cite evidence and explain. Objective acceptance criteria settle automatically; the subjective one — the demo's *"is this actually a cat?"* — is frozen and escalated to a human. Not a court: an arbitration body, because arbitration was never meant to be final.

`TypeScript` `Solidity` `Monad Testnet` `Foundry` — *concept, product framing & positioning, UX*

#### [The Sound Atlas · 声音星图](https://github.com/LierMi/The_Sound_Atlas)
`TME Tencent Music Hackathon 2026 — Track A, Innovative Music Products`

An era of music, rebuilt as a museum you can walk into. Drag through a 3D galaxy of musical time-coordinates, dive into one, and an AI curator reconstructs its sound, stories and geography as a hall: curator's notes, a listening route through the real city, an exhibit label written from your own memory, and a stamped "passport" constellation you can export and share.

`React` `React Three Fiber` `Vite` `Tailwind` `GLM API` — *full product concept, curation, 3D homepage & frontend*
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

### 🧰 Toolkit

**Product** — concept & positioning · problem framing · information architecture · narrative & UX copy · demo and pitch design
**AI** — LLM agent design · system prompts · long-horizon tool-calling loops · multi-agent deliberation · GLM / Claude / Gonka APIs
**Web3** — on-chain forensics (Etherscan, proxy & upgrade tracing) · agentic payments (Kite Passport, x402) · EVM / Monad / Solidity
**Build** — React · Vite · Tailwind · R3F · JavaScript / TypeScript · Python · C · Vercel

---

### 🌍 Languages

🇨🇳 Chinese · 🇬🇧 English · 🇮🇹 Italian · 🇩🇪 German

### 📫 Get in touch

📧 **liermi1996@gmail.com** — open to AI × Web3 product roles, and to hackathon teams that need someone to decide what the thing actually *is*.
