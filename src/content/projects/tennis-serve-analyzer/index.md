---
title: "Tennis Serve Analyzer"
description: "Computer vision project to automatically analyze tennis serves"
date: "Sep 23 2026"
repoURL: "https://github.com/danong/tennis-coach"
---

Tennis Serve Analyzer uses computer vision models to analyze videos of tennis serves. 

It is primarily written in Python and uses MediaPipe and RacketVision to track pose, racket, and ball coordinates, which is then fed into an analysis engine.

## 📋 Features

- From a source containing multiple serve attempts, detect accepted attempts, remove the intermediate footage
- Automatically estimate checkpoints for eight stages: start, release, loading, cocking, acceleration, contact, deceleration, and finish.
- Create a deterministic, body-only measurement record for each attempt, combining 30 fixed interpretable metrics with a [5, 16, 12] phase-aligned motion sequence.

