# Kids Champion — Automated Educational Video Pipeline (Veo 2.0 -> Alter -> Drive)

An end-to-end automation pipeline designed for educational YouTube Shorts & Instagram Reels creators. Specifically tailored for the channel **Kids Champion** (target audience: kids aged 8–15 years).

## Workflow
1. Topic / Prompt Generation
2. Google Veo 2.0 Video Generation (9:16 vertical)
3. Video Alteration (FFmpeg: Branding, Hooks, Key Facts, Audio)
4. Google Drive Sync (Auto-upload)
5. Manual Publishing Kit (Shorts & Reels metadata)

## Installation
```bash
git clone https://github.com/ryxmarcus/veo-pipeline.git
cd veo-pipeline
pip install -r requirements.txt
export GEMINI_API_KEY="your-api-key"
python kids_champion_pipeline.py --topic "Why is Mars Red?"
```
