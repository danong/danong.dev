---
title: "Nightshift"
description: "Schedule your Eight Sleep Pod on Cloudflare"
date: "Sep 28 2026"
repoURL: "https://github.com/danong/nightshift"
demoURL: "https://sleep-demo.danong.dev" 
---

![Nightshift](./nightshift.png)

Nightshift lets you automate your Eight Sleep Pod’s temperature throughout the night without paying for an Autopilot subscription. Define your own nightly schedule, adjust temperatures across multiple stages, and host it for free on Cloudflare.

### Features

- Multi-stage scheduling: Configure temperature changes throughout the night, from bedtime to wake-up.
- Manual override protection: Detect manual temperature adjustments and avoid overriding them with scheduled changes.
- Simple, low-cost hosting: Designed to run on Cloudflare Workers and Durable Objects, with usage that fits comfortably within the free tier.
- No paid Eight Sleep subscription required: Uses the unofficial Eight Sleep API to control your Pod independently of Autopilot.
