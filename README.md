# Circle

> Stay close to the people who matter, slow as you like.

Circle is a quiet little app for sending voice notes to a handpicked group of 5–10 people. No texting marathons. No read receipts. No pressure to reply right away.

This repo contains the landing page and a working in-browser demo of the Circle app.

## Live

- **Landing page:** [iamporthos.github.io/circle](https://iamporthos.github.io/circle/)
- **App demo:** [iamporthos.github.io/circle/circle_app.html](https://iamporthos.github.io/circle/circle_app.html)

## What's here

| File | What it is |
|---|---|
| `index.html` | The landing page — explains Circle, captures email signups, asks visitors who the first person they'd voice-note would be |
| `circle_app.html` | A working in-browser demo of the app itself — real audio recording, voice messages, hand-picked circle of contacts |

## Status

Pre-launch. Currently validating demand and gathering early-user feedback. The app demo runs entirely in the browser using localStorage — there is no backend yet. Audio is recorded locally and not actually sent anywhere.

## Stack

Just HTML, CSS, and vanilla JavaScript. No frameworks, no build step. Everything runs straight in the browser.

- Typography: [Fraunces](https://fonts.google.com/specimen/Fraunces), [Caveat](https://fonts.google.com/specimen/Caveat), [Inter](https://fonts.google.com/specimen/Inter)
- Audio recording: [MediaRecorder Web API](https://developer.mozilla.org/en-US/docs/Web/API/MediaRecorder)
- Persistence: browser localStorage

## Run locally

Clone the repo and open `index.html` or `circle_app.html` directly in any modern browser. That's it — no build, no server.

```bash
git clone https://github.com/iamporthos/circle.git
cd circle
open index.html
```

For the audio recording in the app demo to work, you'll need to grant microphone permission when prompted.

## Roadmap

- [ ] Hook up real email capture (Formspree / ConvertKit)
- [ ] Real backend with user accounts
- [ ] Server-side audio storage
- [ ] Push notifications
- [ ] iOS / Android native apps
- [ ] SMS-based "send to anyone" feature

## Philosophy

Circle is built around the idea that friendship shouldn't be another job. Every product decision is a deliberate "no" to the things that make modern messaging exhausting:

- **No** read receipts
- **No** streaks or gamification
- **No** reaction emojis
- **No** public profiles
- **No** algorithmic feeds
- **No** follower counts
- **No** "people you may know"

If we ever start chasing time-on-app, we will have failed.

## Contact

hello@circle.app *(coming soon)*

---

*Built in Toronto.*
