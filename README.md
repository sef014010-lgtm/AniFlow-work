# AniFlow-work — Colab deployment

Google Colab launcher for the upstream **AniFlow** project by [aashish254](https://github.com/aashish254/Aniflow). The upstream repository is not modified.

## Run
1. Open [AniFlow-Colab.ipynb](AniFlow-Colab.ipynb) in Google Colab.
2. Select a GPU runtime if available.
3. Run all cells in order, authorize Google Drive mounting, and open the generated app URL.

The notebook checks out upstream AniFlow at runtime, installs requirements and FFmpeg, starts Ollama, downloads `qwen2.5vl:3b` and `qwen2.5:3b`, then launches the Flask UI.

## Notes
- Existing upstream extractors are reused; sites may block scraping or change their markup. Not every source is guaranteed to work.
- Colab storage is temporary. Save generated media to Drive before ending the session.
- Model performance depends on the assigned runtime.
- Edge TTS requires internet access.
- Follow source-site terms and applicable copyright rules.

Upstream: https://github.com/aashish254/Aniflow
