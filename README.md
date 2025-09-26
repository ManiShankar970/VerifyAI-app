# Verify AI — Frontend Pages (Login, Register, Dashboard)

This repository contains a polished frontend scaffold (React + Vite + Tailwind) implementing the UI and pages for the Verify AI project:
- Login page (with client-side mock auth)
- Registration page (creates a mock local user + PIN)
- Dashboard page (responsive, modern UI, summary cards, activity)

**Note:** Backend and AI modules are intentionally left empty as requested. This package focuses on UI and pages only.

## How to run locally

1. Make sure you have Node.js (>=16) and npm installed.
2. Install dependencies:
```bash
npm install
```
3. Start the dev server:
```bash
npm run dev
```
4. Open the URL shown by Vite (usually http://localhost:5173).

## What is included
- `src/pages/` — Login.jsx, Register.jsx, Dashboard.jsx (fully implemented)
- `src/components/` — Navbar and small helpers
- Tailwind CSS configured (`tailwind.config.cjs`, `postcss.config.cjs`)
- Empty folders for backend, ai-models, uploads, logs etc (placeholders to fill later)

## Notes
- Authentication is mocked using `localStorage` for demo purposes. Replace with real API calls to connect to your backend.
- PIN is collected at registration and stored in localStorage (demo only). In production, never store secrets in plain text and use secure backend hashing and storage.

Have fun — unzip and iterate on the UI. If you'd like, I can now:
- add a browser-extension skeleton to intercept uploads,
- connect the UI to a mock backend (Express/FastAPI),
- or convert forms to a design system with Storybook.

