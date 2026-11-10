# Priyanshu Jaglan — Spider-inspired Portfolio

A recruiter-friendly personal portfolio with a cinematic dark interface, original spider/web motifs, subtle CSS motion, and red/blue comic-panel accents.

## Stack

- Next.js 14, React 18 and TypeScript
- Tailwind CSS
- Lucide React
- CSS keyframe animations with reduced-motion support

## Getting started

```bash
npm install
npm run dev
```

Open http://localhost:3000.

## Content source of truth

The latest supplied resume is used when personal details conflict:
- B.Tech CGPA: **8.0 / 10**
- Credit Card Fraud Detection recall: **94%**
- CodeForge Society: **Secretary, 2025–26**
- NexHack 2025: **4th among 108 teams**
- DSA practice: **100+ problems solved**

Older awards not included in the latest resume are omitted from this version.

## Personal photo and resume

The supplied portrait is part of the downloadable project in `public/images/priyanshu.jpg`. The resume PDF is not published as a public download yet; the page currently lets visitors request it by email.

## Before deploying

- Verify that both Streamlit demo links still work.
- Reconcile the resume's 94% recall with the 88% displayed in the Fraud Detection repository/app. The portfolio follows the resume; do not alter the model's own reported metric until its evaluation run is confirmed.
- Rotate the TMDB API key previously found hard-coded in the Movie Recommendation source and use an environment variable.
- Set `NEXT_PUBLIC_SITE_URL` to the deployed Vercel URL.
