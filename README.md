# Prisma Prompt Studio

A cinematic, full-stack prompt generator themed in dark cream tones. Turn plain English into polished, production-ready prompts for 12 AI tools across Image, Language, and Code categories.

## Features

- **12 LLM Tools** — Midjourney, DALL·E 3, Stable Diffusion, Flux, Ideogram, ChatGPT, Claude, Gemini, Llama, Mistral, Copilot, Cursor, Codex
- **3 Modes** — Image, LLM, Code — auto-switches when you pick a tool
- **Rich Prompts** — per-tool strengths, tips, technical parameters, system personas
- **Cinematic UI** — dark theme, warm cream palette, Almarai font, 3D particle background, noise textures
- **Auth** — LocalStorage-based sign in / sign up
- **100% Local** — No data leaves your machine

## Run

```bash
python3 -m http.server 8080
# Open http://localhost:8080
```

Or serve with any static file server.

## Stack

Vanilla HTML/CSS/JS + Three.js (3D bg) + framer-motion-style CSS transitions.
