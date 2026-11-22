🎬 Clipwise

Clone your editing instincts, not your footage.

Clipwise is an AI-powered video editor that takes multiple raw clips, cleans them up, understands what's being said, and automatically edits them into one polished, entertaining video. Just talk, and Clipwise handles the cuts, captions, memes, and overlays.

Why Clipwise

Video editing is slow and repetitive: merging clips, cleaning audio, timing captions, finding the right moment for a meme. Clipwise automates all of it. You upload raw clips; it listens to the speech, plans the edit, and renders the final video.

✨ Features

1. Multi-clip upload

Drop in several separate recordings. Clipwise merges them into one timeline automatically.

2. AI audio enhancement

Background noise is reduced and voice clarity is boosted, so every clip sounds consistent.

3. Speech understanding

The AI transcribes and understands the actual conversation: who says what, and when, down to the moment key words are spoken.

4. Automatic visual overlays

When an important word or brand is mentioned, Clipwise adds animated text or visuals at the exact moment it's said.Example: someone says "OpenAI" and an animated OpenAI caption appears on screen.

5. Meme and sound effects

The AI detects funny or highlight-worthy moments and adds fitting meme sounds and effects automatically.Example: an unexpected statement triggers a vine boom at the perfect time.

6. Voice-controlled editing agent

Edit by voice. Tell the agent what you want ("make that part funnier", "add a caption when he says X") and it does the rest, keeping the human in control where it matters.

7. One-click export

Review the AI's edit plan, tweak anything you like, then export the final video.

🔄 How it works

Upload clips → Clean the audio → Transcribe + understand speech
→ AI builds an edit plan → Render overlays, captions, effects
→ Merge clips → Export the final video

Ingest — clips are normalized and merged into a timeline.

Listen — speech-to-text with word-level timing.

Reason — an LLM turns the transcript into a structured edit plan (JSON).

Render — overlays, sound effects, and captions are applied frame-accurately.

Export — the final video, with the human always in control of overrides.

🧠 Under the hood

Voxtral (Mistral) — speech-to-text with timestamps

Mistral chat models — transcript understanding and edit-plan generation

Tool-calling agent — voice-command editing

FFmpeg — audio cleanup, merging, and rendering (local and free)

Node.js / TypeScript

🚀 Getting started

(in active development)

🗺️ Roadmap

Multi-clip ingestion and merging

Audio noise reduction and enhancement

Transcription with word-level timestamps

AI edit plan generation

Animated text overlays at mention moments

Meme sound effect library and triggers

Voice-controlled editing agent

Desktop app with live preview

📄 License

All rights reserved. (pick one before making the repo public)
