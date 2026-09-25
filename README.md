# EVTrans Paper Demo

Static GitHub Pages demo for:

**Cross Lingual Video Translation with Talking Face Synthesis: English-to-Vietnamese**

This preview includes a self-contained qualitative landing page for the full
pipeline:

- Static ASR label-versus-hypothesis table for Whisper Tiny/Base/Large v3,
  Hojo ASR V1, and NVIDIA Canary 1B, plus the complete 10-sample report.
- Static MT tables for MarianMT/OPUS, mBART-50, M2M-100, NLLB-600M, Gemini,
  DeepSeek, and Qwen, using shared FLORES-200 samples.
- Five newly generated Vietnamese TTS prompts, each playable for MMS-TTS-VIE
  and VoxCPM2 (10 audio files).
- Three short qualitative lip-sync clips per selected model: IP-LAP, LoRA-Talk,
  Wav2Lip, MuseTalk, LatentSync, and Diff2Lip (18 videos).

Media is intentionally limited to short research excerpts. No checkpoint,
environment file, API key, or training dataset belongs in this repository.

## Local preview

Run this command from this directory, then open the displayed local URL:

```bash
python -m http.server
```

## Deploy

The workflow at `.github/workflows/pages.yml` deploys the repository root when
changes are pushed to `main`. Enable GitHub Pages once in repository Settings
if it has not been enabled yet.
