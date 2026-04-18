# STM Firestick

A simple, elegant Smart TV streaming app for **Saint Thomas More Catholic Church**, Glendale, AZ.

## What It Is

A dedicated streaming app that gives parishioners one-tap access to all three STM video streams — no typing, no searching, no YouTube.

## Live URL

https://mixinbeatz.github.io/STMFirestick

## Features

- **Live Mass / Replay** — Sunday Mass livestream and replay
- **Sunday Sermon** — Standalone sermon playback
- **Special Events** — Parish special event streams
- Beautiful splash screen featuring the STM sanctuary
- Works on any Smart TV browser, Fire TV, Google TV, Samsung, Roku

## How It Works

Single HTML file (`index.html`) hosted on GitHub Pages. All three streams are powered by the church's existing **Resi** player embeds — no third-party streaming costs or accounts needed.

## Stream IDs (Resi)

| Stream | ID |
|--------|-----|
| Live Mass / Replay | 8c6cae64-d58a-4753-89be-54a7d8190d56 |
| Sunday Sermon | 541c26ac-3c58-40e6-9899-5cb9bc8ccac2 |
| Special Events | 26e22bda-9ea5-4505-a32c-f2fb92cf26e2 |

If stream IDs ever change, update the `streams` object in `index.html` around line 100.

## Deployment

Currently hosted free via GitHub Pages. For App Store submission:

- **Amazon Fire TV** — Submit as a Web App via the Amazon Appstore Developer Console
- **Google TV** — Submit via Google Play as a Progressive Web App (PWA)
- **Samsung Tizen** — Wrap in a Tizen Web App project
- **Roku** — Submit as a Roku Web App via the Roku Developer Dashboard

All platforms can use this single hosted URL as the source — no separate codebases needed.

## Credits

Designed and built by Mark Ramotowski for the STM parish community.
