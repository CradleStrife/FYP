# Web-based Speech Recognition System

**Name:** Lai Yi

**FYP ID:** CCDS26-0153

**Project Title:** Full Stack Development and Deployment of Web-based Speech Recognition System — Speech Recognition for Under-resourced ASR (Bahasa Indonesia)

**Supervisor:** Prof Chng Eng Siong

**Co-supervisor:** Dr Hexin

**Cohort:** 2026 S2

**Start Date:** TBD

**End Date:** TBD

**Contact:** LAIY0038@ntu.edu.sg | 9086 4206

## Overview

This project is part of the NTU-Webank Speech-LLM initiative, which explores Speech-LLM technology for under-resourced languages, with a focus on Bahasa Indonesia. The broader goal is to build a full pipeline that transcribes Bahasa Indonesian speech, translates it into English and Chinese, and generates conversation summaries.

This FYP focuses on the full-stack development and deployment of a web-based speech recognition system that supports this pipeline — integrating ASR and LLM model outputs into a usable application, with dashboards for conversation analytics and support for batch file uploads.

## Video Updates

Playlist:

[YouTube Playlist](#)

## Roadmap / Milestones

- **Data curation:** Filter and sample the ~2000 hours of Bahasa Indonesian speech data collected from YouTube (dedup, denoise, sample by domain/accent); define a pilot subset (e.g. 50–100 hours) for early-stage work
- **ASR transcription:** Run existing Qwen-Audio / Whisper models to transcribe the pilot subset into Bahasa Indonesian text; evaluate quality via manual spot-checks
- **LLM handoff:** Deliver transcribed text to the LLM team for translation fine-tuning (Indonesian → English/Chinese); align on required data format
- **App integration:** Integrate ASR and translation outputs into a web application, with a dashboard supporting batch upload and conversation analytics
- **Deployment:** Assess and set up deployment infrastructure for the system
- **Reporting:** Regular milestone reports and progress updates to Prof Chng

## Notes

This README follows the team's standard project template. Start/end dates and the video playlist link are placeholders pending confirmation — please update before publishing to GitHub.
