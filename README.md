# Jarvis (Android, local-first)
Open in Android Studio, sync, run. Then:
1. Put a Gemma `.task` model at Android/data/com.jarvis.app/files/model.task (else keyword fallback is used).
2. Tap "Enable WhatsApp link" and grant notification access. Message the Jarvis (clone) number once so a reply action exists.
3. Add the widget from the home screen.
Phase 2 (not included): Shizuku auto-answer + speaker call loop, Piper/Kokoro voice, Whisper STT.
Build in the cloud: push to GitHub, open Actions > Build APK > download the Jarvis-apk artifact.
