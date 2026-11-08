# Analysis of Indonesian/English Speech and Summarization for Banking Phone Calls

**Name:** Lai Yi

**Working with:** Vu Thi Ly (App / Integration)

**FYP ID:** CCDS26-0153

**Project Title:** Full Stack Development and Deployment of Web-based Speech Recognition System — Speech Recognition for Under-resourced ASR (Bahasa Indonesia)

**Supervisor:** Prof Chng Eng Siong

**Co-supervisor:** Dr Hexin

**Cohort:** 2026 S2

**Start Date:** 10 Aug 2026

**End Date:** 12 May 2027 (Oral Presentation)

**Contact:** LAIY0038@ntu.edu.sg | 9086 4206

## Overview

This project is part of the NTU-WeBank Speech-LLM initiative, which explores Speech-LLM technology for under-resourced languages, with a focus on Bahasa Indonesia. The broader goal is to build a full pipeline for banking phone call use cases: transcribing Indonesian/English speech, translating it into English and Chinese, and generating call summaries.

This FYP covers the ASR adaptation, fine-tuning, and evaluation side of that pipeline, together with the full-stack development and deployment of a web-based application that surfaces it — integrating ASR and LLM (translation/summarization) outputs into a usable interface, with dashboards for conversation analytics and support for batch file uploads. Lai Yi is responsible, together with Ly, for the end-to-end pipeline (ASR → translation/summarization → application), with Ly leading the app/integration side.

## Video Updates

Playlist: [FYP Progress Updates](https://www.youtube.com/playlist?list=PLDnI9xxI9SiI) — one short video (≤ 3 min) every two teaching weeks; recess week is not counted.

| Ep | Teaching weeks | Dates (2026) | Topic | Video |
|---|---|---|---|---|
| 1 | Week 1 | 10 – 16 Aug | Kick-off: where my FYP fits | [watch](https://youtu.be/QfJpWQ6qKv0) |
| 2 | Weeks 2–3 | 17 – 30 Aug | Scope fixed, first benchmark set up | [watch](https://youtu.be/SsXY-q9EXn4) |
| 3 | Weeks 4–5 | 31 Aug – 13 Sep | MERaLiON chosen; the real question is the data | [watch](https://youtu.be/qHYxD-pWcpw) |
| 4 | Weeks 6–7 | 14 – 27 Sep | Fine-tuning hurts the benchmarks, but works in-domain | [watch](https://youtu.be/NG9HbYG5rJk) |
| 5 | Recess + Weeks 8–9 | 28 Sep – 18 Oct | Data leakage found; source paper reproduced | [watch](https://youtu.be/Ox6fGsxOVzk) |
| 6 | Weeks 10–11 | 19 Oct – 1 Nov | Hotword biasing for Singapore names: 31.6% → 87.9% | [watch](https://youtu.be/LYNerYbcBUg) |
| 7 | Weeks 12–13 | 2 – 15 Nov | Voice cloning, and a configurable hotword pipeline | after 15 Nov |

First update video (26 Aug 2026): [watch](https://www.youtube.com/watch?v=ReaR2Q8Vnfg)

## Roadmap / Milestones

- **Dataset & baseline construction:** Curate a fixed, versioned evaluation set from the 1,688-hour data pool (1,000h existing GigaSpeech2 corpus + 688h newly scraped/domain-tagged data); build reproducible evaluation scripts (WER/CER/normalized WER); benchmark SOTA open-source and commercial ASR models, including **MERaLiON**, which natively supports Bahasa Indonesia — building on an existing data-selection pipeline already developed by the team rather than starting from scratch
- **Model adaptation & fine-tuning:** Iteratively fine-tune and adapt the strongest baseline model(s), including MERaLiON, using the existing selection pipeline; re-evaluate against the fixed test set each round
- **LLM handoff:** Deliver transcribed text to the LLM team for translation (Indonesian → English/Chinese) and summarization, aligned on required data format; explore MERaLiON's translation/summarization capabilities as part of the banking use case
- **App integration:** Integrate ASR and translation/summarization outputs into a web application, with a dashboard supporting batch upload and conversation analytics (led together with Ly)
- **Deployment:** Assess and set up deployment infrastructure for the system
- **Reporting:** Regular milestone reports and progress updates to Prof Chng, aligned to official FYP dates (Interim Report 25 Jan 2027, Final Report 22 Mar 2027, Oral Presentation 7–12 May 2027)

## Notes

This README follows the team's standard project template and reflects the FYP Proposal (v2) confirmed with Prof Chng. Progress videos are narrated with an AI-generated voice; scripts and slides are drafted with Claude Code from my project records.
