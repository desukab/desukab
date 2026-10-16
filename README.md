<div align="center">

# Bharath

**Independent builder · AI systems · Developer tools**

[Portfolio](https://desukab.github.io/) · [GitHub](https://github.com/desukab) · [PyPI](https://pypi.org/project/selekyt/) · [AI Agent Builder Program](https://forms.gle/bsrh67bR46iqvXp96)

</div>

---

I build software to understand what's possible — from AI-assisted editorial workflows to local-first applications and developer tools. I'm especially interested in making coding agents more useful through clear specifications, structured execution, automated tests, and honest verification.

## Featured project

### [SeleKyT — AI-native editorial engine](https://pypi.org/project/selekyt/)

**Turn long-form video into structured stories, social cuts, captions, and editable timeline artifacts.**

> AI proposes. The editor decides.

SeleKyT is my flagship project: a Python CLI and editorial pipeline that combines transcription, story-unit selection, video rendering, captions, and timeline exports. It is published on PyPI.

```bash
pip install "selekyt[transcription]"

# Inspect your local environment
selekyt --doctor

# Create a first-pass edit from a local video
selekyt ./video.mp4 --limit 6
```

- **Outputs:** video cuts, captions, editorial reports, and EDL/FCPXML timeline artifacts.
- **Workflow:** local transcription by default, with optional bring-your-own-key cloud providers.
- **Engineering focus:** reproducible CLI behavior, tests, packaging, and explicit validation of generated artifacts.

[Install from PyPI ↗](https://pypi.org/project/selekyt/) · [Project updates ↗](https://x.com/SeleKyT)

## More projects

| Project | What it explores |
|---|---|
| [Dokie](https://github.com/desukab/dokie) | Android document intelligence: local document workflows, OCR integration, page-aware search, and grounded Q&A. |
| [Dasha News](https://github.com/desukab/dasha_news) | A regional news experience built with Flutter and a backend service. |
| [Clipbaa](https://github.com/desukab/clipbaa) | Video and media tooling. |
| [Clipbaa Scrapers](https://github.com/desukab/clipbaa-scrapers) | Scraping and data collection workflows. |
| [Visual Editor](https://github.com/desukab/visual-editor) | A local-first visual editor for Remotion compositions. |
| [ViralClip Android](https://github.com/desukab/viralclip-android) | Android video repurposing experiments. |
| [Zipee](https://github.com/desukab/zipee) | A Rust-based archive utility experiment. |

Project maturity varies; repositories and package pages reflect the current public state.

## How I build

My working loop is simple:

1. **Specify** the problem, scope, constraints, and acceptance criteria.
2. **Plan** small tasks that can be completed and checked independently.
3. **Delegate** bounded work to AI coding agents with the right repository context.
4. **Build** incrementally instead of generating an entire application blindly.
5. **Verify** with tests, real outputs, and explicit checks.
6. **Ship** useful artifacts, document limitations, and iterate.

I use tools such as Claude, OpenCode, Codex, and ChatGPT as collaborators — not substitutes for engineering judgment.

## Stack & interests

**Languages:** Python · Rust · TypeScript · Dart/Flutter · Kotlin  
**Engineering:** Git · GitHub Actions · pytest · Cargo · CLI design · packaging  
**AI & media:** LLM APIs · agent harnesses · transcription · FFmpeg · editorial pipelines  
**Interests:** local-first software · AI developer tools · mobile apps · reliable automation

## Building with students

I'm putting together an **AI Agent Builder program** for students who want to learn LLM fundamentals, agent harnesses, and how to build a project from scratch to MVP with AI coding tools. We'll also explore eligible student benefits from cloud and developer platforms, with an emphasis on building responsibly within free tiers and credits.

[Join the AI Agent Builder program ↗](https://forms.gle/bsrh67bR46iqvXp96)

## Find me

- **Portfolio:** https://desukab.github.io/
- **GitHub:** https://github.com/desukab
- **SeleKyT on PyPI:** https://pypi.org/project/selekyt/
- **X:** https://x.com/SeleKyT

---

*Specify → Build → Verify → Ship.*
