# Fernando Oliveira — Video Editor & AI Builder

Video editor with 6+ years of experience and 3,000+ videos delivered; former Head of Marketing at V4 Company, leading a
team of 10–12; LL.B. from UEMG (2026).
I build working tools by orchestrating AI agents (Claude Code, ChatGPT, Gemini, Perplexity): I define the problem,
the rules and the acceptance tests, agents write the code, and independent reviewer agents check it before I approve.

[fernandoedits.com](https://fernandoedits.com) · [LinkedIn](https://www.linkedin.com/in/folivernando)

## Things I've built with AI agents

**Agent systems and automation**
- **[ai-agent-workflows](https://github.com/FernandoOliveiraESouza/ai-agent-workflows)**: my Claude Code setup: a rules kernel every agent follows, memory in an Obsidian vault, 6 reusable skills and a quality gate (hooks) that blocks agents from finishing without tests or review; 344-check test battery.
- **[caca-vagas](https://github.com/FernandoOliveiraESouza/caca-vagas)**: job-search assistant for anyone, run with Claude: searches Remotive, Remote OK, Himalayas and Jobicy, tracks applications and sends nothing without approval (Python; job search needs only the standard library).
- **Local code reviewer** (in ai-agent-workflows): runs analyzers on changed lines, parallel reviewer agents and an adversarial verifier; on a real open-source PR it found the 3 bugs GitHub's automated reviewer took 3 rounds to find.
- **Video QA and sound-effect pipeline** (in ai-agent-workflows): one-command delivery check (loudness, black/frozen frames, "rewind" glitches, contact sheet) and peak-based SFX sync.
- **Portfolio brand audit** (private): agents reviewed 163 portfolio files (~140 distinct videos) and confirmed 43 brands for my CV and site.

**Software and products**
- **[Firestudio-Tube-for-Linux](https://github.com/FernandoOliveiraESouza/Firestudio-Tube-for-Linux)**: control panel (DSP mixer, routing, sample rate, buffer) and PipeWire setup for the PreSonus FireStudio Tube on Linux, plus my own ALSA kernel driver for it (private); measured round trip: 6.24 ms at a 64-frame buffer.
- **MixDaw** (private): a DAW in C++20 / JUCE 8 / Tracktion Engine (alpha), with a test suite of 147,863 passing test checks and an out-of-process bridge for Windows plugins built on Wine 11 (median 51–57 µs vs. 62–64 µs for yabridge in my benchmark).
- **Sede** (private, paused): Brazilian virtual office for remote teams (room map, drop-in audio/video, chat) in TypeScript, Fastify, React, LiveKit and PostgreSQL; 117 tests, 64 findings from two independent reviews fixed.
- **FilmCraft contributions** ([filmcraft-contrib](https://github.com/FernandoOliveiraESouza/filmcraft-contrib)): in this open-source Rust video editor by ArtCraft, sped up export from 16.6 to 48.3 fps (3-min 1440p H.264 benchmark) and fixed an NVENC crash on cancelled exports, with a regression test ([PR #2843](https://github.com/storytold/filmcraft/pull/2843), open).
- **[craftlink](https://github.com/FernandoOliveiraESouza/craftlink)**: Rust library for cross-app discovery, live references and a shared extension manifest across the ArtCraft apps (early design, unit tests), with my forks [LightCraft](https://github.com/FernandoOliveiraESouza/lightcraft) (integration branch), [VectorCraft](https://github.com/FernandoOliveiraESouza/vectorcraft), [PhotoCraft](https://github.com/FernandoOliveiraESouza/photocraft) and [EffectCraft](https://github.com/FernandoOliveiraESouza/effectcraft).
- **fernandoedits.com and showreel** (private): portfolio site on Cloudflare and a 60-second showreel animated in code with Remotion, passed through automated video QA.

**Smaller tools and experiments** (private)
- Linux desktop: resource monitor widget (~5% of one CPU core), native animated wallpaper (3440×1440 at 60 fps, 0 dropped frames) and a patched Spotlight-style launcher (file search in 2–30 ms per keystroke over 470k items).
- Market prediction game: hourly direction forecasts for IBOV, S&P 500, USD/BRL and BTC with LightGBM + logistic regression and walk-forward validation (honest result: only BTC above 50%, at 52.1%; no real money).
