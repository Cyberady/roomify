# Roomify — AI Architectural Visualization App

Transform 2D floor plans into photorealistic 3D renders using AI.

---

## Tech Stack

- **React + TypeScript** — UI
- **Vite** — Build tool
- **TailwindCSS** — Styling
- **Puter.js** — Auth, file storage, KV database, and AI models
- **Claude / Gemini** — AI rendering

---

## Features

- 2D-to-3D photorealistic rendering
- Persistent file storage with public URLs
- Project gallery with history
- Before/after comparison slider
- Public community feed
- Privacy controls (public/private toggle)
- Export AI-generated renders

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

### Install

```bash
git clone https://github.com/Cyberady/roomify
cd roomify
npm install
```

### Environment Variables

Create a `.env` file in the root:

```env
VITE_PUTER_WORKER_URL=""
```

Get your worker URL by signing up at [puter.com](https://puter.com).

### Run

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

---

## Build for Production

```bash
npm run build
```

## Docker

```bash
docker build -t roomify .
docker run -p 3000:3000 roomify
```
