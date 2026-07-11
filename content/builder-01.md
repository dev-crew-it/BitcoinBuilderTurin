+++
title = "Builders Turin 1"
date = 2026-07-11
+++

## Agenda
- 16:30–16:45 — Networking
- 16:45–17:00 — Presentation
- 17:00–17:45 — Socratic Seminar
- 17:45–18:00 — Demos & Startup Showcase

A participatory afternoon: bring questions, jump into the discussion, and share what you're building — or what you're stuck on. Plenty of Q&A throughout.

## Intro
- [Chatham House Rules](https://grok.com/share/bGVnYWN5LWNvcHk_0ddfe410-0f5a-466a-a2b4-835edd791e30) — no photos/video
- First Builders Turin! 10-second intros: name · what you do · what you want out of it

## Socratic Seminar

### Lightning: reliability & the mobile problem
- [Matt Corallo: 99% payment success is unacceptable — LN is far better than that](https://x.com/TheBlueMatt/status/2072359464171454728)
- [LDK: async payments fix receiving on mobile](https://x.com/lightningdevkit/status/2070513005465342300)
- [Breez SDK "Class of Q2 2026" — instant bitcoin in every app](https://x.com/Breez_Tech/status/2072681032357233042)

### Open source: control vs. cost
- [Corallo: open source is about control, not customizability](https://x.com/TheBlueMatt/status/2071031197720047644)
- [Xiaoyin Qu: "Open source will win AI — because it's cheaper"](https://x.com/quxiaoyin/status/2073540332353208325)
- [GitHub killed our CI mid-release](https://x.com/TheBlueMatt/status/2069800092534468699) + [banned twice "by mistake"](https://x.com/luisschwab_/status/2069084591369924644) — FOSS infra risk

### Quick hits: mining & dev tooling
- [First StratumV2 block (GoMining / DMND_Sv2)](https://x.com/pavlenex/status/2070132430875267538)
- [Fable 5 / Claude dev-tooling](https://x.com/ClaudeDevs/status/2072429181565288665)

### Local spotlight
- [Vincenzo: CLN plugin manager / Coffee plugin in Core Lightning](https://x.com/PalazzoVincenzo/status/2068045408257900705)
- [BLOX, Piazza Solferino — a Torino hub](https://x.com/bloxspace_turin/status/2071615093402472659)

## Demos & Startup Showcase

**Slot:** 17:45–18:00 (~15 min). Format: short live demo or pitch + 1–2 min Q&A. Community proposals are tracked as [GitHub issues](https://github.com/dev-crew-it/BitcoinBuilderTurin/issues); program notes below merge review for **Builders Turin 1** (2026-07-11).

### What to do (hosts & presenters)

1. **Before the event:** confirm order and timeboxes with accepted pitches (DM or issue thread).
2. **Open with** suggested local demo: [CLN plugin manager / Coffee](https://x.com/PalazzoVincenzo/status/2068045408257900705) (~5 min).
3. **Run community pitches** in priority order: [#11 Hokm](https://github.com/dev-crew-it/BitcoinBuilderTurin/issues/11) first if confirmed; [#12 MATPay](https://github.com/dev-crew-it/BitcoinBuilderTurin/issues/12) only if live PoC; [#13 XPoster](https://github.com/dev-crew-it/BitcoinBuilderTurin/issues/13) deferred to BT2.
4. **Reserve ~3 min** for open mic if time allows (one stuck-on problem or WIP).
5. **Experimental demos:** remind room to use **small amounts only**; no liability for loss of funds.

### Community proposals — review & program (BT1)

#### [#11 — Hokm](https://github.com/dev-crew-it/BitcoinBuilderTurin/issues/11) (Arshia-r-m) — **Accept for showcase (priority 1)**

Persian 4-player card game (Hokm) with online multiplayer, AI, RTL EN/FA, and **Lightning via Breez Spark** (paid rooms, sats balance, prizes). Stack: React/TS, Node, Socket.IO, Redis. Live: [hokm.unico.quest](https://hokm.unico.quest).

**Review:** Strong fit for “product on Bitcoin” and aligns with the seminar thread on Lightning + mobile (Breez). Best **show-don’t-tell** pitch of the three open issues. Caveat: app repo is private today — fine for demo; consider opening source post-event if possible.

**Demo plan:** cultural intro → create/join room → Lightning entry → partial hand → prize flow (~8–10 min).

#### [#12 — MATPay](https://github.com/dev-crew-it/BitcoinBuilderTurin/issues/12) (mgrassotti) — **Hold for seminar Q&A or short PoC demo (priority 2)**

Protocol idea for mass adoption: Bitcoin payments anchored to a **temporary** stable fiat price, P2P, no shitcoins. [Slides](https://github.com/user-attachments/files/29888800/MATPay_Eng.pdf), PoC: [eur-token-poc](https://github.com/mgrassotti/eur-token-poc).

**Review:** Relevant to adoption and RGB/Lightning narrative, but topic can run long in debate. Prefer **live PoC** over slides-only; if only slides fit in 15 min window, fold into seminar discussion instead of showcase.

**If showcased:** 5 min PoC transfer + 3 min “what is / isn’t a stablecoin” framing.

#### [#13 — XPoster](https://github.com/dev-crew-it/BitcoinBuilderTurin/issues/13) (artcava) — **Defer to Builders Turin 2 or lightning talk (priority 3)**

AI social automation (C#/.NET, Azure Functions, orchestrator + sender plugins). [XPoster](https://github.com/artcava/XPoster).

**Review:** Good “AI tools for builders” case study and Italian OSS example, but **not** core Bitcoin/LN/Nostr product. Better as a **Builders 2** slot (community comms / responsible automation) than competing with Lightning demos on BT1.

### Fallback

- Open mic: show what you're building — or what you're stuck on.
- Suggested local demo if no community pitch confirms: live demo of the CLN plugin manager.

## Wrap
- What landed? What should change next month?
- Recommended read: [Spiral x Goose: The Best is Yet to Honk](https://spiralxyz.substack.com/p/spiral-x-goose-the-best-is-yet-to)
