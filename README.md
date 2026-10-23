# BLEPT English Majorship Reviewer

An interactive study platform for the **Board Licensure Examination for Professional Teachers (BLEPT)** — English Majorship strand.

## What's inside

- **8 subject areas** covering the full BLEPT English majorship syllabus
- **400 multiple-choice questions** (50 per subject) — 20 LOTS + 30 HOTS each, with full explanations
- **30-Day BLEPT Climb** — a gamified daily challenge ladder with badges and streaks
- **In-depth study notes** in bullet form with ~100 worked examples across all subjects
- **Reflection prompts** with email submission to the teacher
- **Colorful, interactive design** with confetti, progress tracking, and mobile-responsive layout
- **Progress saved locally** — no database or backend required

## Subjects covered

1. Remedial Instruction in English
2. English for Specific Purposes (ESP)
3. Introduction to Linguistics
4. Structure of English & Stylistics
5. Literary Criticism
6. Teaching Literature & Macro-Skills (Mythology, Afro-Asian, Philippine)
7. Campus Journalism, Instructional Materials & Assessment
8. Language Research, Translation, Speech Arts & Creative Writing

## Tech stack

- **Next.js 16** (App Router) + **TypeScript**
- **Tailwind CSS 4** + **shadcn/ui** components
- **lucide-react** icons
- Progress saved to **localStorage** (no backend needed)

## Getting started (local development)

```bash
# Install dependencies
bun install

# Run the dev server
bun run dev

# Open http://localhost:3000
```

## Before you deploy

**Set your teacher email** so student reflections reach you:

```
File: src/components/reviewer/ReflectionForm.tsx
Line ~24: const TEACHER_EMAIL = "your.real@email.com";
```

## Deploy to Vercel (recommended)

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → Sign in with GitHub
3. Click "Add New Project" → Import your repository
4. Vercel auto-detects Next.js → Click "Deploy"
5. Your site is live at `your-project.vercel.app`

To add a custom domain: Vercel Project Settings → Domains → Add domain

## License

For educational use. Always consult official PRC materials and current DepEd issuances for the actual BLEPT.
