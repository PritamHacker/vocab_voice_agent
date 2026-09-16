# Vocab Voice Agent

A simple browser-based voice agent that helps you learn vocabulary.

## Features

- **Learn Mode** – Get a random word with pronunciation and definition
- **Quiz Mode** – Listen to the definition and type the word
- **Speak & Check** – Say the word out loud; the agent checks if you pronounced it correctly
- **Full Lesson** – Agent speaks the word, pronunciation, and definition
- Works offline with 50 curated vocabulary words when APIs are unavailable

## How to use

1. Open `vocab_voice_agent.html` in Chrome or Edge
2. Allow microphone permission when asked
3. Click **New Word** and start learning

## Tech

- Open-source random word APIs (no API key required)
- Browser Web Speech API (text-to-speech + speech recognition)
- Pure HTML/CSS/JS – no build step, no backend

## APIs used

- [Random Words API](https://github.com/mcnaveen/Random-Words-API)
- [Random Word API](https://github.com/RazorSh4rk/random-word-api)
- [Free Dictionary API](https://dictionaryapi.dev/)

## License

MIT
