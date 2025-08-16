# ForgeX AI Studio

**All-in-one Python-powered creative suite** for text, image, video, and music generation—built on **Gemini API + Local LLMs**. Designed for creators, developers, and entrepreneurs seeking a **market-ready, production-grade content engine**.

---

##  Core Features

- **Text Generation**
  - High-quality writing via Gemini models
  - Structured JSON output for automation
  - Seamless integration with local/user LLM API keys (Ollama, OpenAI, Anthropic, etc.)

- **Image Generation**
  - Output ultra-high fidelity with advanced image models
  - Control aspect ratio, style, and batch generation
  - Built-in prompt optimizer for polished results

- **Video Generation**
  - Generate cinematic clips (e.g. 8s @720p)
  - Support text→video and image→video workflows
  - Async generation with automatic `.mp4` export

- **Music Generation**
  - Real-time, streaming AI composition
  - Interactive playback controls
  - Export in WAV and MP3 formats

- **Document Understanding**
  - Process PDFs: summarize, extract structured data, auto-convert to eBook text
  - Integrated into the creative pipeline for seamless conversion

- **Training & Fine-Tuning**
  - Lean pipelines with LoRA/QLoRA (PyTorch Lightning)
  - Accept `.jsonl` or `.txt` datasets
  - Fine-tune custom models for specialized creative styles

- **Logging & Monitoring**
  - BigQuery logging integration (via Vertex AI)
  - Privacy-first local logging option for sensitive workflows

---

##  Quick Start

### Prerequisites
- Python 3.10+
- Gemini API Key (via Google AI Console)
- Optional: Local LLM runtime (Ollama, LM Studio, etc.)

### Installation
```bash
git clone https://github.com/id01tsoftwaresgit/ForgeXAIStudio.git
cd ForgeXAIStudio
pip install -r requirements.txt
python forgex.py
````

---

## UI Overview

* Tabbed interface: **Text** | **Image** | **Video** | **Music** | **Docs**
* Each tab includes:

  * Prompt input area
  * Configuration sliders (e.g., temperature, image style, BPM)
  * Preview window with live output
  * Export button for respective formats:

    * Text → PDF/EPUB
    * Images → PNG/JPG
    * Video → MP4
    * Music → WAV/MP3

---

## Monetization Strategy

* **Free Tier**: Daily usage limits—ideal for trials
* **Pro Tier**: Full API access, priority generation, batch processing capabilities
* **SaaS Model**: Deployable with subscription—revenue-ready

---

## Packaging for Distribution

* Cross-platform builds (`.exe`, `.app`) via PyInstaller
* Includes professionally designed transparent PNG icon
* Ready for deployment on platforms like **Ko-fi**, **Gumroad**, and **Google Books**

---

## Vision

ForgeX AI Studio is more than a tool—it's a **creative OS**. By uniting text, visuals, video, and music generation in a single app, it empowers users to build polished digital products and campaigns at scale.

---

## Author

**Guillaume Lessard** — *iD01t Productions*
Your creative automation partner.

```

