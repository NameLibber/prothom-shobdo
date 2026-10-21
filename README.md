# Prothom Shobdo · প্রথম শব্দ

A free, offline-friendly web app that helps Bengali speakers learn everyday English for life abroad — words, travel phrases, real dialogues, and a sentence builder, each with Bengali meaning and pronunciation, plus text-to-speech playback.

**Live app:** _add your deployed link here after hosting_

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/NameLibber/prothom-shobdo)

## Features

- **শিখুন · Learn** — a searchable, categorized word list (900+ words) with Bengali meaning, phonetic pronunciation, and audio.
- **কার্ড · Cards** — flip-style flashcards to drill vocabulary.
- **পরীক্ষা · Quiz** — multiple-choice quiz on word meanings.
- **ভুল শব্দ · Review** — words missed in the quiz automatically collect here for focused re-practice, until marked as learned.
- **ভ্রমণ · Travel** — ready-made phrases for situations abroad (airport, hospital, shopping, etc.).
- **কথোপকথন · Talk** — full two-person dialogues for real situations.
- **বাক্য বানান · Build** — a sentence-pattern builder to assemble custom sentences.
- Large-text and slow-speech accessibility toggles; progress and preferences are saved locally on the device (no account needed).

## Project structure

```
index.html   markup
style.css    styles
app.js       data (vocabulary/phrases/dialogues) + app logic
```

No build step, no dependencies — it's a static site. Open `index.html` directly in a browser, or serve the folder with any static file host.

## Running locally

Just open `index.html` in a browser, or serve it:

```
npx serve .
```

## Deploying

This is a static site, so it deploys to [Vercel](https://vercel.com) with zero configuration: import this repository on vercel.com/new and deploy. Every push to the main branch redeploys automatically.
