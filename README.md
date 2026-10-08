# Milo | AI Agent Team

> **Can an AI agent run ComfyUI without a local GPU? Yes — one image cost us about $0.024 in settled Modal usage on a cached rerun (Meta Muse, 2026-10-03).** Our first Claude Code run made 15 images for about $0.13 (2026-09-30).
> We measured actual usage on a rented Nvidia L4 via Modal ($0.0173 GPU + $0.0056 CPU + $0.0012 RAM, cached rerun on 2026-10-03).
> This repository contains free skill files and the measured bills behind each episode, for developers and non-technical creators building with AI agent teams.

**Website & Pricing Breakdown:** [https://miloagents.shop](https://miloagents.shop) | [ComfyUI Cloud Pricing Comparison](https://miloagents.shop/comfyui-cloud-pricing/)  
**YouTube Channel:** [@miloagents](https://www.youtube.com/@miloagents)  
**Last updated:** 2026-10-08

---

## What is in this Organization?

Every episode on the Milo YouTube channel documents one person and an AI agent team accomplishing a concrete real-world task, publishing the exact prompts, skill files, and verified bills:

| Project / Skill | Solves This Question | Measured Cost / Benchmark | Link |
|---|---|---|---|
| **[miloagents.shop](https://miloagents.shop)** | Free Starter Kits & Bill Dissections | Starter kits + measured bills | [Get Kits](https://miloagents.shop/kits/) |
| **[niche-hook-miner](https://github.com/miloagents/niche-hook-miner)** | How to validate a short-video niche before filming? | 4-signal HHI & breakout score | [Repo](https://github.com/miloagents/niche-hook-miner) |
| **[youtube-niche-validator](https://github.com/miloagents/youtube-niche-validator)** | How to check if a YouTube niche is saturated? | Dual-slice denominator sampling | [Repo](https://github.com/miloagents/youtube-niche-validator) |
| **[vertical-video-converter](https://github.com/miloagents/vertical-video-converter)** | How to reframe horizontal 16:9 video to 9:16 Shorts/Reels? | 1080x1920 with background blur | [Repo](https://github.com/miloagents/vertical-video-converter) |
| **[tiktok-hook-trend-engine](https://github.com/miloagents/tiktok-hook-trend-engine)** | How to write viral TikTok hooks in seconds? | 3-layer opening + trend fit check | [Repo](https://github.com/miloagents/tiktok-hook-trend-engine) |
| **[short-form-video-script-writer](https://github.com/miloagents/short-form-video-script-writer)** | How to turn an idea into a 15–60s video script? | Hook + value beats + text overlay | [Repo](https://github.com/miloagents/short-form-video-script-writer) |

---

## Quick Start: Run ComfyUI on Modal with an Agent

1. **Set a usage limit in Modal before anything runs** (we set ours to $30; Modal's Starter plan included $30 of monthly credits when we checked on 2026-10-06, and a card on file is required for GPUs).
2. **Give this paragraph to Claude Code or Meta Muse**:
   ```text
   My laptop has no GPU. Use Modal to run ComfyUI with the Krea 2 Turbo model on a cheap GPU.
   Keep the model weights in a Modal Volume so they only download once.
   Then generate one image from this prompt and save it to ./outputs:
   "a vintage film camera on a wooden desk by a window, soft morning light, real photograph, 85mm lens".
   When you're done, shut everything down and report the settled cost.
   ```
3. Full checklist and Python scripts are available in the free starter kit at [https://miloagents.shop/kits/](https://miloagents.shop/kits/).
