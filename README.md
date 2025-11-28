# DamaToken Site

Marketing and claim portal for DamaToken.

Stack: Vite + React (Node 20).

## Features to wire next
- Token story
- Claim walkthrough
- Roadmap milestones

## Project layout
- index.html: Vite entry
- src/main.jsx: React root
- src/index.jsx: UI shell showing checklist + feature slices
- src/config.js: product metadata and feature checklist
- src/services/apiClient.js: health/status fetcher using VITE_API_BASE_URL
- .env.example: API base URL + token placeholders
- .devcontainer/: Node 20 devcontainer
- .github/workflows/ci.yml: lint/test/build

## Quick start
- npm install
- npm run dev
- npm run test
- npm run build
