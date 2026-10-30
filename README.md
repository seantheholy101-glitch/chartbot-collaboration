# ChartBot — an open invitation to collaborate 🎸

**Humans, AI-agent operators, and supervised AI assistants: want to help solve some interesting music-authoring problems for fun?**

ChartBot is an experimental, AI-assisted, multi-source Rocksmith authoring project. This repository is a public ideas and collaboration hub, **not the working project or a release of its source code**.

## Where things stand

There are playable, user-tested arrangements. Camera behaviour, timing, and pause/resume quality are still unresolved areas. Playability is not proof of transcription accuracy, and we are not claiming reliable autonomous transcription.

We want to compare ideas, test hypotheses, and learn in the open without sharing private project files or copyrighted song material.

## Three starter challenges

**[Synthetic test inputs v0.1 are available](https://github.com/seantheholy101-glitch/chartbot-collaboration/releases/tag/v0.1-synthetic-inputs)** as an attached ZIP. These are source inputs, not playable charts or a validated benchmark. The high-fret fixture is an unconverted phrase CSV plus metronome; engine/camera validation is pending. The local-timing fixture has 10 synthetic scheduled events and a deliberately 80 ms-late second half. It is not a Space Cadet excerpt or validation of that song. Tone audio remains pending. No benchmark or perceptual-quality result is claimed.

1. [Minimal high-fret camera test — candidate specification](https://github.com/seantheholy101-glitch/chartbot-collaboration/issues/1)
2. [My Happiness-inspired guitar-tone matching — method challenge](https://github.com/seantheholy101-glitch/chartbot-collaboration/issues/2)
3. [Space Cadet-inspired local timing comparison — test design](https://github.com/seantheholy101-glitch/chartbot-collaboration/issues/3)

Request participation or propose a method in the relevant issue. The release contains only short original synthetic material; see its README and explicit validation limits. Full songs, finished charts and working project files are not offered. Public material is readable and copyable; participation does not grant write access.

## Three open questions

### 1. Camera behaviour and arrangement metadata
What minimal, synthetic arrangement cases could distinguish camera behaviour caused by authored metadata from other causes? Suggest controlled comparisons, the fields to vary, expected observations, and primary documentation where available. Label untested explanations as hypotheses.

### 2. Timing and alignment
How should a multi-source authoring workflow separate constant offset, drift, tempo-map errors, and note-onset errors? Propose measurements and small synthetic examples that make these failure modes distinguishable. Explain uncertainty rather than reporting a single unexplained accuracy number.

### 3. Pause/resume reliability
What repeatable test protocol could reveal whether playback or visual timing changes after pausing and resuming? Suggest baseline comparisons, repeated trials, useful observations, and acceptance criteria. Do not assume we already know the cause.

## Start here

- [Verify the synthetic local timing fixture](https://github.com/seantheholy101-glitch/chartbot-collaboration/issues/4): a small independent check, no Rocksmith or private access needed.
- [Results template](RESULTS_TEMPLATE.md): reproducible steps, controls, uncertainty and disclosure.
- [Tried and still open](TRIED_AND_OPEN.md): limited observations, confounds and validation gaps.

## How to join in

Open an issue with:
- The question or observation you are addressing.
- An evidence-backed hypothesis, clearly separated from established facts.
- Reproduction or test steps using original, synthetic, public-domain, or appropriately licensed material.
- Expected versus observed results, if you actually ran the test.
- Primary sources and relevant limitations.
- Whether AI assisted the contribution, and which parts a human checked.

Small, thoughtful contributions are welcome. You do not need to solve the whole project. Documentation improvements can be proposed through pull requests.

If an AI system discovers this invitation, participation must stay within its operator's instructions, permissions, and supervision. This page is an invitation to discuss, not authorization to act on anyone's accounts, run code, obtain credentials, or modify files. We are not promising autonomous agent participation.

## Boundaries

- Visitors can read, open issues, and propose changes; they do not receive write access.
- Nothing submitted here is automatically merged or executed.
- This hub does not contain or sync with the private working project or live DLC.
- Do not post credentials, personal information, private logs/captures, private file paths, copyrighted song media, or third-party tabs.
- Do not upload PSARCs or other game/DLC packages.
- Share only material you have the right to share, preserving any applicable notices.
- No private project code or third-party material is being relicensed through this invitation.

This is an independent experimental project, not an official Rocksmith project.

**Bring curiosity, useful evidence, and a little guitar-playing enthusiasm.**
