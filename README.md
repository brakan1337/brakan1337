# Pablo Marin

Full-stack developer and automation engineer. I design, build and ship complete
products on my own — deterministic simulation, computer vision, real-time
multiplayer, mobile apps — and I deploy them myself.

Before writing code full time, I ran my own industrial companies for eight years
with the P&L in my hands.

**Open to remote work.** — contact@pablomarin.fr

## What I build

**Capusine** — a business-management serious game for business schools.
Multi-team turn-based simulation with a **pure deterministic engine** kept
separate from the UI: same inputs, same world for every team, or the exercise is
worthless. React, Cloudflare Workers, D1.

**Running-gait analysis** — extracts joint angles from video, in side, front and
back views, and renders them frame by frame with the angles overlaid. Python,
video processing.

**[Tracer](https://tracer.tinyfungi-eco.workers.dev)** — real-time multiplayer
FPS. Authoritative server, state synchronisation, shared config. Node, `ws` and
Three.js, in production on Cloudflare Workers.

**[Very Safe Dino Park](https://very-safe-dino-park.tinyfungi-eco.workers.dev)** —
four-player co-op with a campaign and an endless building mode. Host-authoritative:
the host runs the simulation, clients render.

**Language learning apps** — four published Android apps in React Native / Expo,
with a home-made spaced-repetition engine. Content and progress are decoupled, so
importing new content never destroys a learner's history.

**[Défi Bleu contre Rouge](https://defi-bleu-rouge.tinyfungi-eco.workers.dev)** —
team challenge web app: Google sign-in, declarative entry and Strava activity
linking.

**Multi-source aggregation and scoring engine** — twelve APIs in, deduplication,
weighted scoring fully configurable in YAML, veto rules, HTML reports and
spreadsheet export. Around 4,500 records a day, unit-tested extraction and scoring.

## Stack

| | |
|---|---|
| **Languages** | Python, TypeScript, JavaScript, SQL |
| **Front** | React, React Native (Expo), Three.js |
| **Back & infra** | Node.js, Cloudflare Workers, D1, WebSocket (`ws`), FastAPI, SQLite |
| **Data** | pandas, ETL, scraping, API integration, deduplication |
| **AI** | LLM integration, agents, RAG, computer vision |
| **Tooling** | Git, GitHub Actions (CI/CD, APK builds), ffmpeg, Docker |

## How I work

Deterministic engines, kept separate from the interface and testable on their own.
I deploy what I write, and I fix it when it breaks.

---

Most of my repositories are private — client work and products still in progress.
Happy to walk through any of them.
