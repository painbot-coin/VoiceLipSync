# Voice Lip Sync

Talking-head stack on Wav2Lip. Streamlit UI records or uploads speech, runs STT/TTS, detects the face, and lip-syncs the video.

## What is in here

- `APP.py` / `APP_test.py` Streamlit apps
- Wav2Lip models, SyncNet, face detection
- Train and inference scripts
- Dockerfile

Set `OPENAI_API_KEY` in the environment if you use the speech path.

## Stack

Python, Streamlit, Wav2Lip, OpenCV
