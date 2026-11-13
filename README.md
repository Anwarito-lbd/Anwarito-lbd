## Hi, I'm Anwar Issaoui

Software Engineering student at the University of Ottawa (BASc, expected May 2028), based in Ottawa, Canada.
I build AI products, mobile apps and real-time systems, and I work in English and French.

- 3rd place at **uOttaHack 8** (NAV CANADA challenge) with a real-time air-traffic simulator, built by a team in 36 hours
- Built **Vocular** at **cuHacking 7** for the QNX challenge: spatial navigation and item memory for people with visual impairment
- Looking for **software engineering co-op and internship** roles

[![Portfolio](https://img.shields.io/badge/Portfolio-anwar--issaoui.vercel.app-111?style=flat-square)](https://anwar-issaoui.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Anwar%20Issaoui-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anwar-issaoui-b25402244)
[![Devpost](https://img.shields.io/badge/Devpost-hackathons-003E54?style=flat-square&logo=devpost&logoColor=white)](https://devpost.com/issaouianwar2020)

### Languages

| | |
|---|---|
| **Programming** | Python, TypeScript, JavaScript, Java, Kotlin, C++, Luau, SQL (PostgreSQL), HTML/CSS |
| **Spoken** | English (fluent), French (fluent) |

### Core stack

| Area | Tools |
|---|---|
| Web and 3D | Next.js, React, Tailwind CSS, Three.js (React Three Fiber) |
| Mobile | React Native, Expo |
| Backend and data | FastAPI, Supabase (Postgres, Auth, Edge Functions), Prisma, Redis, Celery |
| Edge, AI and media | Raspberry Pi 5, MAVLink, ONNX, WhisperX, FFmpeg, Remotion |
| Game dev | Roblox Studio, Rojo, Blender |
| Tooling and infra | Docker, Git, GitHub Actions, Playwright, Linux |

---

### Featured projects

#### Rota: peer-to-peer outfit rental app · [Site](https://therotaapp.com) · [Repo](https://github.com/Anwarito-lbd/rota)

**Problem:** good clothes sit unused while other people buy outfits they wear once.
**What it does:** people rent out pieces from their wardrobe. Renters discover looks in a feed, tap a piece, book dates and pay in the app.

- **Bookings that can't collide:** a Postgres exclusion constraint makes double-booking impossible at the database level, not just in the UI
- **Payments and trust:** Stripe Checkout, Connect payouts to lenders, Identity checks before anyone can rent or list, and listing review before the feed
- **Privacy:** "near me" shows only a ~550 m grid, never an address
- **By the numbers:** 53 database tables, all with row-level security · 12 Supabase Edge Functions (payments, webhooks, moderation, try-on)

`Expo` `React Native` `TypeScript` `Supabase` `Stripe`

#### Agri-Edge: onboard computer for crop-scouting drones · [Site](https://agri-edge-web.vercel.app) · _repos private_

**Problem:** farm drones capture images, but deciding which images are usable and what they show happens much later, back at the office.
**What it does:** a Raspberry Pi 5 rides next to the drone's autopilot. It captures geotagged images, checks their quality as they're taken, runs optional AI detection, and queues everything for upload when a connection is available.

- **Safe by construction:** the Pi can only *read* from the autopilot, never send flight commands, and a test enforces that
- **"A model is a sensor, not a decision":** a detection is never allowed to drive spraying unless it has been validated locally
- **Ops Station web app:** Next.js site with field maps, alerts, and spray prescriptions an agronomist approves, exported as ISOXML or shapefile. Its API proxy refuses any vehicle-command path
- **By the numbers:** 1,900+ automated tests, run on a laptop with no hardware attached

`Python` `Raspberry Pi 5` `MAVLink` `ONNX` `Next.js` `TypeScript`

#### ConversionCraft: growth platform for online stores · [Repo](https://github.com/Anwarito-lbd/conversioncraft)

**Problem:** small ecommerce brands juggle separate tools for research, product pages, ads and optimization.
**What it does:** one app that analyzes competitors, generates offers and product pages, runs A/B tests, and launches and optimizes campaigns on Shopify, Meta and TikTok.

- **Multi-tenant from the start:** organizations, role-based access on every protected route, encrypted token storage, audit logs
- **Reliable integrations:** OAuth connectors plus signature-verified, idempotent webhooks, so a retried event is never processed twice
- **3D product viewer:** a Three.js scene (React Three Fiber) that loads a product's GLTF model with orbit controls
- **By the numbers:** 135 API endpoints in the FastAPI worker

`Next.js` `TypeScript` `Three.js` `FastAPI` `Python` `Prisma`

#### DBTournament: Roblox arena-fighter prototype · _repo private while third-party assets are removed_

**Problem:** Roblox games usually live inside one binary place file, which makes them hard to version, review or test.
**What it does:** a playable fighting-game prototype (lobby, arena, training areas) where all gameplay is plain Luau in Git, synced into Studio with Rojo.

- **Effects built in code:** combat VFX are generated at runtime from parts, beams and particles, not baked animations
- **Testable game logic:** stats, Elo ratings, quests and training math are pure modules unit-tested with the Luau CLI outside Studio
- **Asset pipeline:** a Python script drives Blender to import, decimate (characters under 20k triangles, props under 10k) and export game-ready models
- **By the numbers:** 168 Luau files · 28 procedural VFX modules · 23 shared logic modules · 11 test files

`Luau` `Rojo` `Roblox Studio` `Python` `Blender`

#### ClipOps: short-form video production console · _private repo_

**Problem:** cutting long videos into good vertical clips by hand is slow and repetitive.
**What it does:** transcribes footage, finds scene changes, generates 10–20 candidate clips, ranks them down to the best 3–5, and renders 9:16 videos with animated captions.

- **Media pipeline:** WhisperX transcription with fallbacks, PySceneDetect scene cuts, FFmpeg cutting, Remotion caption overlays
- **Human in control:** approving, posting, submitting and cashing out are four manual gates that are never automated

`Python` `FastAPI` `Celery` `WhisperX` `FFmpeg` `Remotion` `Next.js`

#### Propel: AI career platform · [Live](https://propelapply.vercel.app)

Resume parsing, applications tailored to each job posting, and voice mock interviews. Co-built with Omar Bouchiba.

`Next.js` `React` `AI APIs`

<details>
<summary><b>More projects</b></summary>

- **[NAV CANADA ATC Simulator](https://github.com/OminousOne/NAV-Canada-Simulator)** (team). A real-time air-traffic simulator with a TypeScript conflict-detection engine, built in 36 hours. 3rd place at uOttaHack 8 · [Live](https://nav-canada-simulator.vercel.app) · [Devpost](https://devpost.com/software/atc-flight-tracker-simulator)
- **[Vocular](https://github.com/omarismail-cs/vocular)** (team). Spatial navigation and item memory for people with visual impairment, on QNX 8.0, Raspberry Pi 5 and TensorFlow Lite. cuHacking 7 · [Devpost](https://devpost.com/software/vocular)
- **[uLink](https://github.com/Anwarito-lbd/Ulink)**. Students build a profile once and get matched to opportunities. It aggregates 321 opportunities from 3 sources (Canadian internships, AI jobs, scholarships), and scoring runs entirely in the browser · JavaScript, Playwright
- **[Github-agent](https://github.com/Anwarito-lbd/Github-agent)**. A Python CLI that searches GitHub by keyword, clones the top repos in parallel and packages them for offline research, plus a 5-stage toolchain bootstrap checked in CI
- **[meme-flight-recorder](https://github.com/Anwarito-lbd/meme-flight-recorder)**. A paper-only crypto research recorder with fail-closed evidence checks and a tamper-evident, hash-chained event journal. It cannot sign transactions · Python, FastAPI

</details>

<!--
Optional stats card. Left off on purpose: with few stars and followers it draws
attention to small numbers instead of the projects. Uncomment once the profile has more activity.

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Anwarito-lbd&layout=compact&hide_border=true)
-->
