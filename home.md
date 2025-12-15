# Awesome AI Video Clipping
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of high-quality resources for **AI video clipping / highlight extraction / long-to-shorts repurposing**:
tools, websites, APIs, and open-source building blocks.

This repo is designed to be useful for:
- Creators & marketers (repurpose long videos into Shorts/Reels/TikTok)
- Editors (transcript-first workflows, silence/filler removal, caption packaging)
- Developers (shot/scene detection, video search, indexing, automation pipelines)

---

## Legend
- **(SaaS)** Hosted product
- **(API)** Developer platform / API
- **(OSS)** Open-source
- **(Desktop)** Local application

---

## Table of Contents
- [How to Use This List](#how-to-use-this-list)
- [Long-form → Short-form (Auto Highlights / Auto Clips)](#long-form--short-form-auto-highlights--auto-clips)
- [Transcript-First Editing (Talking-Head Acceleration)](#transcript-first-editing-talking-head-acceleration)
- [Captions & Short-Form Packaging](#captions--short-form-packaging)
- [Gaming & Live Highlights](#gaming--live-highlights)
- [Developer APIs (Understanding / Indexing / Shot Detection)](#developer-apis-understanding--indexing--shot-detection)
- [Open-Source Building Blocks](#open-source-building-blocks)
- [Datasets & Benchmarks (Highlights / Summarization)](#datasets--benchmarks-highlights--summarization)
- [Repo Maintenance (Make It “High-Value” Long-Term)](#repo-maintenance-make-it-high-value-long-term)
- [Contributing](#contributing)
- [License](#license)

---

## How to Use This List
Start with your primary workflow:
1) **Podcast / interview / lecture** → transcript-driven clipping + reframing  
2) **Tutorial / webinar** → chapter/segment detection + captions + formatting  
3) **Gaming / streaming** → event-based highlights + social export  
4) **Enterprise / platform** → APIs for shot detection + indexing + search

Then choose:
- A **SaaS** tool if you want speed.
- An **OSS pipeline** if you want control, privacy, and cost predictability.
- A **developer API** if you’re building a product.

---

## Long-form → Short-form (Auto Highlights / Auto Clips)
Tools that turn long videos into multiple Shorts/Reels/TikToks with automatic highlight selection and formatting.

- [OpusClip](https://www.opus.pro/tools/long-video-to-short-video-ai) (SaaS) — AI repurposing: highlights → short clips.
- [Klap](https://klap.app/) (SaaS) — one-click long video → Shorts/Reels/TikTok.
- [Vizard](https://vizard.ai/) (SaaS) — long-form → short clips, "remove bad takes" workflow.
- [Munch](https://www.getmunch.com/) (SaaS) — AI video repurposing platform for extracting engaging clips.
- [Riverside Magic Clips](https://riverside.com/magic-clips) (SaaS) — generates short clips from recordings; integrates into a recording workflow.
- [WayinVideo Long to Short](https://wayin.ai/tools/long-video-to-short-video/) (SaaS) — 10+ viral clips in 30 seconds with AI moment detection & smart layouts.
- [vidyo.ai / Quso](https://vidyo.ai/features/video-resizing) (SaaS) — long-form → short-form repurposing & resizing workflows.
- [VEED Long Video to Short Video](https://www.veed.io/tools/auto-video-editor/long-video-to-short-video-ai) (SaaS) — repurpose long content into shorts.
- [Short AI (Long → Short)](https://www.short.ai/ai-clip-maker/long-video-to-short-video) (SaaS) — automatic highlight selection for short-form outputs.

---

## Transcript-First Editing (Talking-Head Acceleration)
Text-based editing, filler-word removal, and silence/bad-take cutting for talking-head content.

- [Descript – Remove Filler From Video](https://www.descript.com/tools/remove-filler-from-video) (SaaS) — transcript-first editing + filler removal.
- [Gling](https://www.gling.ai/save-time) (SaaS) — auto remove silences, filler words, bad takes.
- [auto-editor](https://github.com/WyattBlue/auto-editor) (OSS) — command-line auto-cut based on audio loudness.

---

## Captions & Short-Form Packaging
Captioning, animated subtitles, and “viral caption” styling workflows.

- [Kapwing Subtitles](https://www.kapwing.com/subtitles) (SaaS) — auto subtitles + export formats.
- [VEED AI Clip Generator](https://www.veed.io/tools/auto-video-editor/ai-clip-generator) (SaaS) — AI clip generation + web editor.
- [Submagic](https://www.submagic.co/) (SaaS) — captions + b-roll + short-form edits.
- [Zeemo](https://zeemo.ai/) (SaaS) — captions/subtitles workflows and related tooling.

---

## Gaming & Live Highlights
Automatic stream/game highlight extraction and conversion to social formats.

- [Eklipse](https://eklipse.gg/) (SaaS) — AI gaming highlights; export to Shorts/Reels/TikTok.
- [Powder](https://powder.gg/) (SaaS) — AI clipping for gaming; social-ready highlights.
- [WayinVideo Gaming Clips](https://wayin.ai/tools/ai-gaming-clip-generator/) (SaaS) — AI gaming clips with "Find Moments" search & viral score prediction.
- [Streamlabs Cross Clip](https://streamlabs.com/cross-clip) (SaaS) — convert Twitch clips to TikTok/Shorts/Reels formats.

---

## Developer APIs (Understanding / Indexing / Shot Detection)
For building products: shot/scene segmentation, indexing, search, and enrichment.

- [Google Cloud Video Intelligence – Shot Detection](https://docs.cloud.google.com/video-intelligence/docs/shot-detection) (API) — shot change detection / annotation workflows.
- [AWS Rekognition Video – Segment Detection](https://docs.aws.amazon.com/rekognition/latest/dg/segments.html) (API) — segment detection including shot detection.
- [Azure AI Video Indexer – Insights Overview](https://learn.microsoft.com/en-us/azure/azure-video-indexer/insights-overview) (API) — transcripts, OCR, faces, topics, and more.
- [TwelveLabs – Search Guides](https://docs.twelvelabs.io/docs/guides/search) (API) — video understanding/search for finding specific moments.
- [Cloudinary – Content-aware Video Cropping](https://cloudinary.com/documentation/content_aware_video_cropping_tutorial) (API) — automated cropping to keep salient content.

---

## Open-Source Building Blocks
Recommended OSS modules for assembling your own clipping pipeline.

### Speech-to-Text / Alignment
- [Whisper](https://github.com/openai/whisper) (OSS) — multilingual ASR / translation.
- [faster-whisper](https://github.com/SYSTRAN/faster-whisper) (OSS) — Whisper via CTranslate2 for faster inference.
- [whisperX](https://github.com/m-bain/whisperX) (OSS) — word-level timestamps + diarization workflows.
- [whisper.cpp](https://github.com/ggml-org/whisper.cpp) (OSS) — C/C++ port optimized for local inference.

### Shot / Scene / Segment Detection
- [PySceneDetect](https://github.com/Breakthrough/PySceneDetect) (OSS) — shot change detection + optional splitting.

### Clip Generation / Repurposing
- [ClipsAI](https://github.com/ClipsAI/clipsai) (OSS) — transcript-aware long video → clips; includes aspect ratio conversion.

### Editing / Assembly
- [MoviePy](https://github.com/Zulko/moviepy) (OSS) — Python video editing (cut/concat/composite).
- [auto-editor](https://github.com/WyattBlue/auto-editor) (OSS) — remove dead space/silence automatically.

---

## Datasets & Benchmarks (Highlights / Summarization)
Useful for research, evaluation, or building custom highlight selection models.

- [TVSum](https://github.com/yalesong/tvsum) — classic benchmark dataset for video summarization.
- [VideoXum](https://videoxum.github.io/) — cross-modal video summarization benchmark (video + aligned text).
- [Mr. HiSum](https://github.com/MRHiSum/MR.HiSum) — large-scale highlight detection & summarization dataset.

---

## Repo Maintenance (Make It “High-Value” Long-Term)
To keep this list credible and useful over time:
- Use [awesome-lint](https://github.com/sindresorhus/awesome-lint) to enforce Awesome list conventions.
- Add a weekly link checker via GitHub Actions (avoid link rot).
- Require short, factual annotations per item:
  - What it does (one sentence)
  - Category tag (SaaS/API/OSS/Desktop)
  - Primary use case (podcast/talking-head/tutorial/gaming/dev-platform)

---

## Contributing
PRs welcome. Please:
- Add official links whenever possible.
- Provide a one-line description and a category tag.
- Avoid affiliate links.
- Keep the list organized by category.

---

## License
Consider CC0 (public domain) to maximize reuse.
