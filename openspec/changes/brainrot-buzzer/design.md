# Design: Brainrot Buzzer

## System
- React client for game loop and audio feedback
- Express server for AI phrase generation
- Web Audio API for synthetic buzzer sound
- Strict JSON phrase pack response from OpenRouter free model

## Flow
1. User starts a run.
2. App fetches or reuses a phrase pack.
3. User types phrase-by-phrase.
4. Wrong character triggers immediate buzzer and accuracy penalty.
5. Timer ends with score summary.
