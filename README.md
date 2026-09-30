# TCF Québec Oral Lab

A lightweight static GitHub Pages study app for TCF Québec oral practice.

## Features
- Tâche 2 / Tâche 3 question bank
- Topic categorization and frequency tags
- Three-color learning system:
  - Purple = question / question type / framework
  - Green = reusable answer / universal phrases
  - Orange = learner self-fill / personal version
- Random practice
- Timed practice
- Mock exam
- 14 core reusable phrases
- LocalStorage for completed items, notes, mistakes, and personal phrase examples

## Deploy to GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html`, `style.css`, `data.js`, `app.js`, and `README.md`.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/root`.
5. Save. GitHub will provide the Pages URL.

## Important source note
The current sample questions are based on publicly available 2026 TCF oral topic archives and are labeled with their source month. These public archives are generally candidate-recall / training compilations, not official released exam papers. The reference answers in this app are original study answers and are not official scoring answers.

## Adding more questions
Add objects to `QUESTIONS` in `data.js` using:
- `task`: 2 or 3
- `month`: e.g. `2026-09`
- `category`: topic
- `hot`: 1–5
- `question`: French prompt
- `cn`: Chinese explanation
- `template`: Tâche 2 question framework items
- `answer`: original reusable answer model
- `source`: source label
