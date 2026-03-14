# hcs-llm-autotrainer-web v2 beta

Made with ❤️ by hcsmedia

## Neu in v2
- Anfänger-Workflow (6 Schritte) für einfache Eingaben
- Mehr Quellen: Paste, Files, Wikipedia, WebSearch (DuckDuckGo API)
- Dataset-Builder mit Clean/Dedup/Chunk/Score/Split + Warnungen
- AI-unterstützte Datengenerierung (synthetic data)
- Tokenizer train/import/export + encode/decode preview
- Training mit besseren Visuals:
  - Loss-Chart
  - Throughput-Chart
  - Statuschips (good/stagnating/overfit)
  - Checkpoint-Management
- Trainiertes Modell testen (Generate)
- Run in Baseline „mergen“ (Experiment-Update)
- Compare-View mit Best-Run-Highlight
- EN/DE/FR, Autosave, Import/Export Bundles, mobile-first

## Hinweis zur "AI assisted mit WebGPU LLM"
In dieser Version ist der Assist-Teil device-aware und lokal implementiert.
Die echten WebGPU-Kernel-Dateien (`webgpu/*.wgsl`) bleiben vorbereitet für den nächsten Schritt (echte Compute-Training-Kerne).

## Deploy
GitHub Pages (branch `main`, root `/`).
