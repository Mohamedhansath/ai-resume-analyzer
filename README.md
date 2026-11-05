# Resumind — AI Resume Analyzer

A responsive, frontend-only resume analysis workspace built with React + Vite.

## Features
- PDF upload and in-browser text extraction (PDF.js).
- Local heuristic resume score, section checks, skill detection, and improvement suggestions.
- Skill overlap matching against illustrative sample job profiles.
- Analysis history, profile settings, saved roles, JSON backup/restore.
- Responsive dashboard, accessible focus states, and reduced-motion support.

## Run locally
```bash
npm install
npm run dev
```
Open the local URL printed by Vite.

## Build
```bash
npm run build
npm run preview
```

## Privacy and limitations
- No backend, account system, external AI API, or server-side storage is used.
- PDF text extraction and analysis run in the browser. Extracted text and reports are saved in this browser's LocalStorage; the original PDF is not uploaded or stored by this app.
- The score is a transparent heuristic indicator, not a real ATS score, hiring prediction, or guarantee.
- Job profiles are illustrative examples, not verified live vacancies. Match scores use exact skill-name overlap, not semantic AI.
- LocalStorage is browser/device-specific and can be cleared by the browser. Export a JSON backup if you want to keep your analysis history.
- Do not use this demo as a secure vault for sensitive personal information.

## Stack
React 18, Vite 6, JavaScript, PDF.js, Lucide React, CSS.