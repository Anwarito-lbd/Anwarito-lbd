# Anwar Issaoui

**Software Engineering @ University of Ottawa** · Ottawa, Canada  
Building AI-assisted full-stack products, fail-closed edge/robotics software, quantitative research terminals, and automated QA infrastructure.

[![Portfolio](https://img.shields.io/badge/Portfolio-anwar--issaoui.vercel.app-0F766E?style=flat-square)](https://anwar-issaoui.vercel.app/)
[![Rota](https://img.shields.io/badge/Live_Product-therotaapp.com-8E3FB0?style=flat-square)](https://therotaapp.com)
[![Rota Instagram](https://img.shields.io/badge/Instagram-%40therotaapp-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/therotaapp/)
[![Propel](https://img.shields.io/badge/Live_App-propelapply.vercel.app-1D4ED8?style=flat-square)](https://propelapply.vercel.app/)
[![Agri-Edge](https://img.shields.io/badge/Ops_UI-agri--edge--web.vercel.app-15803D?style=flat-square)](https://agri-edge-web.vercel.app)

---

## Featured Systems & Products

### Full-Stack Products & AI Marketplaces
- **[Rota](https://github.com/Anwarito-lbd/rota)** · [Live Site (`therotaapp.com`)](https://therotaapp.com) · [Instagram (`@therotaapp`)](https://www.instagram.com/therotaapp/)  
  Paris-first peer-to-peer outfit rental platform built with **Expo SDK 57 / React Native, TypeScript, Supabase Postgres, and Stripe Connect / Identity / Radar**. Enforces server-side price, calendar, and liability invariants in Postgres (`56` tables, `108` RLS policies, `53` SQL migrations, `12` Deno Edge Functions), geo-approximated Paris privacy, and verified `390×844` mobile walkthroughs.
- **[Propel](https://github.com/Anwarito-lbd/propel)** · [Live Frontend (`propelapply.vercel.app`)](https://propelapply.vercel.app/)  
  Fact-safe career workspace matching Canadian students and early-career engineers to live Greenhouse, Ashby, Lever, Remotive, and Government of Canada Job Bank feeds—never synthetic demo cards—with resume-grounded **Gemini** tailoring, PDF/DOCX export, and Cloudflare Workers (`D1 + R2`, Drizzle ORM, Next.js 16 / Vinext) alongside a zero-key local **FastAPI + SQLite** reference package.
- **[ConversionCraft](https://github.com/Anwarito-lbd/conversioncraft)** _(Public Showcase)_ · `conversioncraft-prod` _(Private Production Repo)_  
  Full-stack ecommerce growth OS combining a **Next.js / React** product workspace (`Three.js` product canvas) and **FastAPI** backend (`12` Prisma models, `131` OpenAPI paths). The private production repository adds a **15-specialist + CC 3D `Three.js` office (`OfficeTour.jsx`)**, Leaflet sourcing map, Stripe billing + Fernet credential vault, and fail-closed deploy gates (`163` mypy files clean, `187` frontend tests across `23` files).
- **[MatchReady](https://github.com/Anwarito-lbd/MatchReady)**  
  Full-stack LinkedIn portrait & profile studio (**React 19 + Vite + TypeScript + FastAPI + SQLite WAL**) featuring a 5-layer image upload firewall (magic bytes + pixel decode bounds), `isActive` HTTP `403` gating, idempotent credit checkout, and hybrid Gemini Imagen / deterministic Studio DSP (`pytest` `8/8`, `vitest` `5/5`, strict `tsc` clean).
- **[uLink](https://github.com/Anwarito-lbd/Ulink)**  
  Zero-backend opportunity aggregator matching student profiles to `321` normalized Canadian internships, AI roles, and uOttawa/Mitacs scholarships strictly in the browser (`ES Modules + localStorage`, verified with Playwright & Biome; succeeded by **Propel**).

### Robotics, Edge Systems & QA Infrastructure
- **[Agri-Edge](https://github.com/Anwarito-lbd/agri-edge)** · [Ops Station (`agri-edge-web.vercel.app`)](https://agri-edge-web.vercel.app)  
  Unified agricultural RPAS companion-computer and operations platform (**Python 3.12 + MAVLink + Apache-2.0 YOLOX-s ONNX + Next.js 16 / React 19**). Coordinates read-only Pixhawk telemetry, parametric flight/spray physics, fail-closed `TreatmentDecisionEngine` simulation gates (`SIMULATION_ONLY=True`), and Leaflet + ISOXML/Shapefile Ops UI (`2,082` Python tests passing / `40` hardware-gated skips, `124` Web Vitest tests across `7` files, `22` compiled Next.js routes).
- **[Vector Autonomy Lab](https://github.com/Anwarito-lbd/vector-autonomy-lab)**  
  Embodied AI & robotics research stack for Anki/DDL Vector (`track_width = 0.048 m`) pairing a hardware-agnostic `VectorRobotHAL` (`SimulatedVectorRobot` + `WirePodGRPCAdapter`), composable Behavior Trees, Sobel vision + voice-intent routing, Bayesian log-odds occupancy-grid SLAM, and C-space A* (`91.9%` arena coverage across a `640`-tick / `63.9 s` closed-loop episode).
- **[QA Automation Suite](https://github.com/Anwarito-lbd/qa-automation-suite)**  
  4-layer automated test framework targeting **AegisPay** (deterministic FinTech clearing SUT): Layer 1 **FastAPI + Hypothesis** stateful fuzzing (`18` tests), Layer 2 dual-engine **Playwright Chromium + Selenium WebDriver** E2E (`6` tests), Layer 3 **Python Appium/ADB (`4` tests) + Kotlin Appium Java-Client/JUnit5 (`1` test)** mobile QA, Layer 4 **Unreal Engine 5 Gauntlet** CLI & frame/crash gate (`4` tests), plus `Jenkinsfile`, GitHub Actions, and **JIRA REST v3 ADF** failure reporting (`32` pytest passing, `ruff` & `mypy` clean across `43` files, Kotlin Gradle green).

### Quantitative Research & Creative Automation
- **[Quant & FinOps Desk](https://github.com/Anwarito-lbd/quant-finops-desk)** _(Strictly Paper / Analytical)_  
  Unified portfolio risk and corporate FinOps terminal (**Next.js 15 + FastAPI + SciPy/HiGHS**): Markowitz Mean-Variance & Mean-CVaR LP optimization, 2-state Markov Regime-Switching Monte Carlo stress engine, SHA-256 hash-chained `AuditJournal`, 5-repo strategy adapter hub, and SaaS cohort / 5-year DCF valuation (`18` pytest passing, `ruff` clean, `vitest` `2/2`, ESLint `0`, Next build green).
- **[Meme Flight Recorder](https://github.com/Anwarito-lbd/meme-flight-recorder)** _(Strictly Paper-Only)_  
  5-agent paper crypto research desk enforcing a Read-Only Bridge (`write_capable=False`), fail-closed adversarial on-chain risk gates, `L0 / L1 / L2` autonomy ceilings, SHA-256 hash-chained SQLite journal, 13-note Obsidian vault (`0` orphans), and FastAPI `/desk` operator workstation (`672` pytest passing, `ruff` clean; zero signing keys or live orders).
- **[Arbitrage Platform (`arbitrage-`)](https://github.com/Anwarito-lbd/arbitrage-)** _(Simulated Paper Replay)_  
  Cross-venue Kalshi + Polymarket binary arbitrage pricer, L2 VWAP slippage simulator, and FastAPI/WebSocket operator terminal (`28` pytest passing; verified on a `$1,000.00` 60-day `seed=42` simulated replay yielding `+$748.05` / `+74.81%`, `29` round-trips, Sharpe `8.59`, zero live capital).
- **[ClipOps](https://github.com/Anwarito-lbd/clipops)**  
  Short-form (`1080×1920`, `9:16`) editorial video workstation (**FastAPI Dark-Mode NLE Studio + WhisperX / faster-whisper ASR + PySceneDetect + FFmpeg / Remotion**) with 4 mandatory human approval gates before manual publishing (`26` pytest passing including E2E local FFmpeg render).
- **[GitHub-Agent](https://github.com/Anwarito-lbd/Github-agent)**  
  Python CLI for authenticated GitHub REST v3 search, parallel shallow cloning without credential leakage, and offline ZIP bundling, paired with a declarative 5-stage toolchain bootstrap (`44` catalog entries).

---

## Core Engineering Stack

| Domain | Technologies & Tools |
| :--- | :--- |
| **Languages** | Python, TypeScript, JavaScript, SQL, Kotlin, Java, C++, Luau |
| **Web & Mobile** | Next.js (15/16), React 19, Expo / React Native, Vite, Tailwind CSS, Three.js, Leaflet |
| **Backend & Cloud** | FastAPI, Supabase Postgres (RLS + Deno Edge Functions), Cloudflare Workers (D1/R2), Drizzle ORM, Prisma, SQLite WAL, Docker / Kubernetes |
| **QA & Automation** | pytest, Hypothesis, Playwright, Selenium WebDriver, Appium / ADB (Python & Kotlin), Unreal Engine 5 Gauntlet, Vitest, Jenkins, JIRA REST v3 ADF |
| **Applied AI, Media & Quant** | Google Gemini API, Anthropic Claude API, YOLOX-s ONNX, WhisperX / faster-whisper, PySceneDetect, FFmpeg, Remotion, SciPy / HiGHS |

---

## Hackathon Collaborations
- **[NAV CANADA ATC Simulator](https://github.com/OminousOne/NAV-Canada-Simulator)** — **3rd Place @ uOttaHack 8** · Real-time air-traffic conflict-detection simulator in TypeScript ([Live](https://nav-canada-simulator.vercel.app) · [Devpost](https://devpost.com/software/atc-flight-tracker-simulator))
- **[Vocular](https://github.com/omarismail-cs/vocular)** — **cuHacking 7** · Spatial navigation & item memory on QNX 8.0, Raspberry Pi 5, and TensorFlow Lite ([Devpost](https://devpost.com/software/vocular))

---

## Private R&D & Academic Work
- **`conversioncraft-prod`** _(Private)_ · Production ConversionCraft deployment (`OfficeTour.jsx` Three.js 3D office, Stripe webhooks, Fernet vault, Fly.io/Render fail-closed gates).
- **`content-factory`** _(Private)_ · 5-stage multi-model UGC & faceless video workstation (`Next.js 15 + Vitest + FFmpeg`) with cut-timing invariant ad multiplier.
- **`DBTournament`** _(Private)_ · Luau/Rojo arena fighter (`Check-UI`, procedural VFX, Blender mesh pipeline) with CC BY 4.0 Obsidian brain and `export_public_showcase.py`.
- **Coursework** · [`SEG3502-Lab9`](https://github.com/Anwarito-lbd/SEG3502-Lab9) _(Spring Security REST API)_, [`SEG3502-Lab10`](https://github.com/Anwarito-lbd/SEG3502-Lab10) _(Docker/Compose/Kubernetes BookStore)_, plus private uOttawa Angular, Spring, and Firebase labs.
