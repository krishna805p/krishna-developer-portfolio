# Krishna — Developer Portfolio

A responsive, animated **multi-page** portfolio built with React, Vite, React Router, Tailwind CSS, Framer Motion, and Lucide icons.

## Pages

- `/` — Home
- `/about` — About and education
- `/projects` — Project catalogue
- `/projects/docsensei` — DocSensei case study and live demo
- `/projects/food-navigator` — AI Food Navigator case study
- `/projects/cybercrime-detection` — Cybercrime Detection case study
- `/skills` — Skills and toolkit
- `/contact` — Email, GitHub, and LinkedIn contact methods

Navigation opens independent routes rather than scrolling to sections. The Vercel rewrite in `vercel.json` supports refreshing deep links.

## Featured links

- DocSensei live app: https://docsensei-krishna.streamlit.app/
- DocSensei source: https://github.com/krishna805p/Docsensei_testing
- AI Food Navigator: https://github.com/krishna805p/Food_navigator
- Cybercrime Detection System: https://github.com/krishna805p/AI-Powered-Multi-Source-Cybercrime-Detection-and-Monitoring-System
- GitHub profile: https://github.com/krishna805p
- Email: krishna80540@gmail.com

## Run locally

Install Node.js 20 or newer, then run:

```bash
npm install
npm run dev
```

Vite prints the local URL (typically http://localhost:5173).

## Production build

```bash
npm run build
npm run preview
```

Build output is generated in `dist/`.

## Deploy on Vercel

1. Import `krishna805p/krishna-developer-portfolio` into Vercel.
2. Use the Vite framework preset.
3. Build command: `npm run build`.
4. Output directory: `dist`.
5. No environment variables are required.

## Personalize before publishing

The LinkedIn button currently links to LinkedIn's main site because a personal profile URL was not supplied. Update `LINKEDIN` in `src/App.jsx` to use your profile URL.
