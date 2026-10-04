<div align="center">

<img src="https://authorche.top/assets/img/authorche-social-card.png" width="100%" alt="AuthorChe — Vadym Yemelianov">

# AuthorChe

### Software, music technology, automation and creative engineering

[![Website](https://img.shields.io/badge/Website-authorche.top-C8A96E?logo=firefox&logoColor=111111)](https://authorche.top)
[![OpenVox](https://img.shields.io/badge/Flagship-OpenVox-2D7D5A?logo=github&logoColor=white)](https://github.com/VadymYem/OpenVox)
[![AuthorBot](https://img.shields.io/badge/Telegram-AuthorBot-26A5E4?logo=telegram&logoColor=white)](https://github.com/VadymYem/AuthorBot)
[![Resume](https://img.shields.io/badge/Profile-Resume-6A5ACD?logo=readme&logoColor=white)](https://authorche.top/resume)
[![Support](https://img.shields.io/badge/Support-Independent_Work-C8A96E?logo=buymeacoffee&logoColor=111111)](https://authorche.top/donate)

**Vadym Yemelianov — AuthorChe**  
Ukrainian developer, musician, vocalist, composer, writer and creative technologist.

I build independent software that connects **engineering, music, privacy, automation and creative practice**.

[Website](https://authorche.top) · [Resume](https://authorche.top/resume) · [OpenVox](https://vadymyem.github.io/OpenVox/) · [Telegram](https://t.me/wsinfo)

</div>

---

## What I build

| Area | Focus |
|---|---|
| **Music technology** | Browser audio, vocal analysis, pitch tracking, DSP, notation, rehearsal and music education |
| **Web products** | Responsive applications, browser APIs, local-first architecture, PWA and offline workflows |
| **Android** | Kotlin, Jetpack Compose, Material 3, OAuth and modern application architecture |
| **Automation** | Telegram userbots, modules, APIs, integrations and background workflows |
| **Privacy-first software** | On-device processing, transparent data flows and reduced backend dependence |
| **Creative technology** | Software connecting music, writing, education, publishing and culture |

> **Technology should expand creative freedom, not replace it.**

---

## OpenVox Studio

<div align="center">

### Flagship open-source project

**Privacy-first browser studio for singers, vocal teachers, musicians, students and choirs.**

[![Source](https://img.shields.io/badge/Source-GitHub-181717?logo=github&logoColor=white)](https://github.com/VadymYem/OpenVox)
[![Live](https://img.shields.io/badge/Live-OpenVox-2D7D5A?logo=googlechrome&logoColor=white)](https://vadymyem.github.io/OpenVox/)
[![PWA](https://img.shields.io/badge/PWA-Ready-5A0FC8?logo=pwa&logoColor=white)](https://vadymyem.github.io/OpenVox/)
[![Languages](https://img.shields.io/badge/UI-EN%20%7C%20UK%20%7C%20DE-111827)](https://github.com/VadymYem/OpenVox)

</div>

**OpenVox** combines real-time vocal analysis, structured training, rehearsal, transcription, notation, multitrack audio, tuning and local project storage in one browser application.

The main audio workflow runs on the user's device and does not require a dedicated server-side audio-processing backend.

### What OpenVox includes

| Area | Capabilities |
|---|---|
| **Live Voice Studio** | Pitch, note, frequency, cents, confidence, microphone calibration and monitoring |
| **Vocal Academy** | Pitch matching, breathing, ear training, rhythm, sight singing and structured exercises |
| **Vocal Analysis** | Range, stability, sustained-note analysis and vibrato metrics |
| **Practice Studio** | Scales, arpeggios, intervals, custom melodies, transposition and microphone scoring |
| **Instrument Workshop** | Chromatic tuner, 20+ tuning presets, custom tunings and reference tones |
| **Backing Track Lab** | Local audio, waveform navigation, speed control, A–B loops and markers |
| **Multitrack Mixer** | Multiple tracks, microphone overdubs, gain, pan, mute, solo and WAV mixdown |
| **Professional Audio Lab** | Filters, gate, compressor, spectrum, oscilloscope, spectrogram and diagnostics |
| **Voice to Score** | Monophonic transcription, tempo estimation, quantization and score transfer |
| **Score Editor** | MusicXML/MIDI import, editing, lyrics, ties and SVG/PNG/print export |
| **Choir Studio** | Ensemble import, part isolation, sectional rehearsal and live scoring |
| **Local Projects** | IndexedDB persistence, recordings, settings and portable `.openvox` archives |

### Architecture

```text
Microphone
  -> MediaDevices
  -> AudioContext
  -> AudioWorklet
  -> signal conditioning
  -> WebAssembly pitch / DSP core
  -> TypeScript analysis and compatibility fallback
  -> training, notation and project logic
  -> React interface
```

### Technology

`React` · `TypeScript` · `Vite` · `Web Audio API` · `AudioWorklet` · `WebAssembly` · `C` · `IndexedDB` · `MediaRecorder` · `OfflineAudioContext` · `MusicXML` · `MIDI` · `PWA`

### Engineering quality

OpenVox includes automated validation, accessibility checks, deterministic installs, CI workflows, dependency review, CodeQL, production-build verification, security documentation and explicit browser/runtime limitations.

→ **[Open OpenVox repository](https://github.com/VadymYem/OpenVox)**

---

## Public projects

### AuthorBot

[![Python](https://img.shields.io/badge/Python-3.10–3.11-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Telegram](https://img.shields.io/badge/Telegram-MTProto%20%2B%20Bot%20API-26A5E4?logo=telegram&logoColor=white)](https://core.telegram.org/)
[![Repository](https://img.shields.io/badge/Source-GitHub-181717?logo=github&logoColor=white)](https://github.com/VadymYem/AuthorBot)

A modular Telegram userbot built around modules, automation and modern Telegram interfaces.

- dynamic module loading and updates;
- inline forms, lists, galleries and callback controls;
- Rich Messages;
- configurable permission model;
- local database with optional Redis;
- backup and restore;
- Termux and Linux support;
- multilingual public companion bot.

→ **[VadymYem/AuthorBot](https://github.com/VadymYem/AuthorBot)**

---

### AuthorOSINT

[![Python](https://img.shields.io/badge/Python-OSINT-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Repository](https://img.shields.io/badge/Source-GitHub-181717?logo=github&logoColor=white)](https://github.com/VadymYem/AuthorOSINT)

A Python toolkit for working with publicly available information and common OSINT workflows.

- web and Wikipedia search;
- phone-number metadata;
- email and domain inspection;
- username discovery;
- WHOIS and IP information;
- DNS and subdomain checks;
- external OSINT integrations;
- AI-assisted workflows.

→ **[VadymYem/AuthorOSINT](https://github.com/VadymYem/AuthorOSINT)**

---

### AuthorMail

[![Kotlin](https://img.shields.io/badge/Kotlin-Android-7F52FF?logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![Compose](https://img.shields.io/badge/Jetpack_Compose-Material_3-4285F4?logo=jetpackcompose&logoColor=white)](https://developer.android.com/compose)
[![Template](https://img.shields.io/badge/Status-Template%20%2F%20Scaffold-C8A96E)](https://github.com/VadymYem/AuthorMail)

An open-source **Android email-client template / scaffold**.

It is a development foundation rather than a finished production mail client.

The project demonstrates:

- Clean Architecture + MVVM;
- Jetpack Compose + Material Design 3;
- Hilt dependency injection;
- Gmail and Outlook OAuth flows;
- Gemini-assisted spam analysis;
- trusted-sender whitelist;
- DataStore-backed settings;
- responsive dark/light UI.

→ **[VadymYem/AuthorMail](https://github.com/VadymYem/AuthorMail)**

---

### CheModules

[![Python](https://img.shields.io/badge/Python-Modules-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Repository](https://img.shields.io/badge/Source-GitHub-181717?logo=github&logoColor=white)](https://github.com/VadymYem/CheModules)

A public collection of Python modules for Telegram automation environments.

The repository contains modules for AI helpers, moderation, media, alerts, VirusTotal, IP tools, Spotify, feedback, inline utilities, customization and other workflows.

→ **[VadymYem/CheModules](https://github.com/VadymYem/CheModules)**

---

### AC-Games

[![Web](https://img.shields.io/badge/Web-HTML%20%2F%20CSS%20%2F%20JS-E34F26?logo=html5&logoColor=white)](https://github.com/VadymYem/acgames)
[![Games](https://img.shields.io/badge/Catalog-~185_games-2D7D5A)](https://vadymyem.github.io/acgames/)
[![Live](https://img.shields.io/badge/Live-GitHub_Pages-181717?logo=githubpages&logoColor=white)](https://vadymyem.github.io/acgames/)

A public catalogue of approximately **185 browser games** available without installation.

- browser-first delivery;
- responsive catalogue;
- mobile/desktop filtering;
- GitHub Pages deployment;
- simplified advertising-free browsing experience.

[Source](https://github.com/VadymYem/acgames) · [Live catalogue](https://vadymyem.github.io/acgames/)

---

### Air Alerts System

[![Live](https://img.shields.io/badge/Live-alerts.authorche.top-C8A96E?logo=googlechrome&logoColor=111111)](https://alerts.authorche.top)

A real-time web interface for monitoring air-raid alerts in Ukraine.

**Focus:** public information, external APIs, dynamic status updates and responsive presentation.

→ **[alerts.authorche.top](https://alerts.authorche.top)**

---

### Perfect Resume Builder

[![Live](https://img.shields.io/badge/Live-Resume_Builder-6A5ACD?logo=readme&logoColor=white)](https://authorche.top/prb)

A browser-based application for structured resume creation and export-oriented professional document workflows.

**Focus:** document generation, structured layouts, responsive editing and browser-native productivity.

→ **[authorche.top/prb](https://authorche.top/prb)**

---

### AuthorChe

[![Website](https://img.shields.io/badge/Website-authorche.top-C8A96E?logo=firefox&logoColor=111111)](https://authorche.top)

My independent digital platform for software, music, poetry, biography, public tools and creative work.

It acts as the public hub connecting my technical and creative projects.

→ **[authorche.top](https://authorche.top)**

---

## Technology

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=111111)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=111111)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

### Web and audio

![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?logo=webassembly&logoColor=white)
![Web Audio](https://img.shields.io/badge/Web_Audio_API-111827?logo=googlechrome&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?logo=pwa&logoColor=white)

### Android and platform

![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=111111)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?logo=jetpackcompose&logoColor=white)
![Material 3](https://img.shields.io/badge/Material_3-6750A4?logo=materialdesign&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-333333?logo=linux&logoColor=white)
![Termux](https://img.shields.io/badge/Termux-000000?logo=gnubash&logoColor=white)

### Delivery and infrastructure

![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white)

---

## Development principles

### Local first where practical

Personal or sensitive data should remain on the user's device whenever local processing can reasonably solve the task.

### Reliability before decoration

Visual design matters, but correct behavior, stability, accessibility, performance and predictable UX matter more.

### Open and inspectable

Public software should be understandable, documented, testable and maintainable.

### Technology with identity

I prefer products with a clear point of view instead of anonymous copies of existing software.

### Cross-disciplinary work

The most interesting systems often appear where different areas meet:

**software + music + education + culture + creativity**

---

## Creative background

Software is one part of my work.

My background also includes:

- formal music education;
- vocal teaching and coaching;
- solo and choral performance;
- composition;
- poetry and literary writing;
- independent digital publishing.

I have published more than **60 poems**, written the novel **“Author i Karoooka”**, and created around **10 original musical compositions**.

This background directly influences the software I build — especially **OpenVox**, where music practice, education and engineering are part of the same product.

---

## Current focus

- expanding **OpenVox** into a broader open-source vocal and music platform;
- improving browser-based audio processing and DSP;
- developing local-first applications;
- building Android projects with modern architecture;
- improving **AuthorBot** and its module ecosystem;
- building automation and Telegram tooling;
- improving accessibility and mobile UX;
- maintaining independent public web tools;
- continuing music, composition, poetry and writing.

---

## Collaboration

I welcome serious collaboration around:

- open-source software;
- music technology;
- Web Audio and DSP;
- Android;
- accessibility;
- educational software;
- automation;
- privacy-first applications;
- creative technology.

For OpenVox:

[![Issues](https://img.shields.io/badge/OpenVox-Issues-181717?logo=github&logoColor=white)](https://github.com/VadymYem/OpenVox/issues)
[![Security](https://img.shields.io/badge/OpenVox-Security-181717?logo=github&logoColor=white)](https://github.com/VadymYem/OpenVox/security)

---

## Author

**Vadym Yemelianov — AuthorChe** is a Ukrainian developer, vocalist, vocal teacher, composer, writer and creative technologist.

His work connects software engineering with music, education, independent publishing and creative practice.

- Website: https://authorche.top
- Resume: https://authorche.top/resume
- GitHub: https://github.com/VadymYem
- Telegram: https://t.me/wsinfo
- Instagram: https://instagram.com/vadym_yem
- X: https://x.com/author_che
- Email: dev@authorche.top

---

## Support

Most public AuthorChe projects are developed independently and released free of charge.

Support contributes to:

- open-source development;
- infrastructure and hosting;
- music-technology research;
- public tools;
- long-term maintenance;
- independent creative work.

<div align="center">

[![Support AuthorChe](https://img.shields.io/badge/Support_AuthorChe-Donate-C8A96E?style=for-the-badge&logo=buymeacoffee&logoColor=111111)](https://authorche.top/donate)

<br>

**AuthorChe**

*Building where technology, music and creativity meet.*

</div>
