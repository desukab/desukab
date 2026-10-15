<div align="center">

# Bharath Chander Reddy

**Building editorial AI and local-first tooling.**

[![selekyt](https://img.shields.io/badge/selekyt-v0.3.1-blueviolet?style=flat-square&logo=pypi&logoColor=white)](https://pypi.org/project/selekyt/)
[![Repos](https://img.shields.io/badge/repos-27-2ea44f?style=flat-square&logo=github&logoColor=white)](https://github.com/desukab?tab=repositories)

</div>

---

## Featured — [SeleKyT](https://github.com/desukab/selektyt)

**Editorial AI engine. Turns long-form video into publishable short-form stories.**

> AI proposes. The editor decides.

SeleKyT reads an entire recording, identifies moments that *complete a narrative* rather than slicing on arbitrary time windows, ranks them on editorial signals, and hands back an **editable** cut — not a black box.

| | |
|---|---|
| **Demo** | [selektyt-one.vercel.app](https://selektyt-one.vercel.app) |
| **Install** | `pip install selekyt` — v0.3.1 on [PyPI](https://pypi.org/project/selekyt/) |
| **Handoff** | CMX 3600 EDL + FCPXML 1.11 timelines, word-timed captions, 16:9 & 9:16 with vertical reframing |
| **Privacy** | Local Whisper transcription by default. Audio never leaves the machine unless you opt in |

```bash
selekyt ./video.mp4 --make short    # strongest short-form story
selekyt ./video.mp4 --make story    # strongest complete narrative
selekyt ./video.mp4 --limit 6       # multiple highlights
selekyt --doctor                    # verify local environment
```

Every cut ships with provenance — the reasoning behind it — so a disagreement with the ranking is arguable rather than mysterious.

---

## Also building

**Local-first applications**
- [viralclip-android](https://github.com/desukab/viralclip-android) *(Kotlin)* — on-device video repurposing: virality scoring, auto-captions, face tracking
- [dokie](https://github.com/desukab/dokie) — local-first AI document intelligence for Android
- [visual-editor](https://github.com/desukab/visual-editor) *(TypeScript)* — local-first visual editor for Remotion compositions
- [Zipee](https://github.com/desukab/zipee) *(Rust)* — native macOS archive utility: browse, inspect, extract and edit archives without unpacking
- [BLyNC](https://github.com/desukab/BLyNC) *(TypeScript)* — peer-to-peer file transfer with interactive UI

**Data & scraping**
- [clipbaa-scrapers](https://github.com/desukab/clipbaa-scrapers) *(Python)* — e-commerce market-research scrapers with matching and reporting
- [high-throughput-async-scraper](https://github.com/desukab/high-throughput-async-scraper) *(Python)*
- [anti-bot-playwright-scraper](https://github.com/desukab/anti-bot-playwright-scraper) *(Python)*

**Systems**
- [rust-streaming-systems-lab](https://github.com/desukab/rust-streaming-systems-lab) *(Rust)* — async streaming, concurrency, backpressure, benchmarking, fault handling
- [BloopSync](https://github.com/desukab/BloopSync) *(Java)*

---

## Stack

`Rust` · `TypeScript` · `Python` · `Java` · `Kotlin` · `FFmpeg` · `Whisper` · `Remotion` · `Playwright` · `PyTorch`

---

## Reach me

- **Email** — [hello@desukab.run.place](mailto:hello@desukab.run.place)
- **Web** — [selektyt-one.vercel.app](https://selektyt-one.vercel.app)
- **GitHub** — [desukab](https://github.com/desukab)

*Currently seeking feedback on where SeleKyT breaks down against real editorial judgement — footage that matters for reasons the signals can't see.*