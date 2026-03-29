# Brainrot Buzzer

Brainrot Buzzer is a typing-speed game built around cursed meme phrases and instant punishment.

## Live links

- Demo: https://brainrot-buzzer-859414203684.us-central1.run.app
- Repo: https://github.com/sundaiclaw/brainrot-buzzer
- Sundai: https://www.sundai.club/projects/1450f64f-f19d-41c6-a7a9-b6cd24d30b54

## What it does

- generates fresh AI brainrot phrase packs
- runs a timed typing round
- checks the next expected character strictly
- fires a loud synthetic buzzer on every typo
- tracks WPM, accuracy, streak, mistakes, and score

## Stack

- React + Vite
- Express
- Web Audio API
- OpenRouter free model (`arcee-ai/trinity-large-preview:free`)
- OpenSpec + Fabro artifacts

## Run locally

```bash
cd app
npm install
cp .env.example .env
npm run build
npm run start
```

Required env vars:

```bash
OPENROUTER_BASE_URL=https://openrouter.ai/api/v1
OPENROUTER_MODEL=arcee-ai/trinity-large-preview:free
OPENROUTER_API_KEY=your_key_here
PORT=8080
```
