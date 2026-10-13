# Student360

A mobile-first, frontend-only student support dashboard.

## Run
Open `index.html` in Chrome/Edge/Firefox. No backend or API key is required.

## Included
- Problem Solver with category detection and action plans
- Local profile personalization
- Study Planner
- Progress tracking
- Skill Gap Finder
- Emergency Exam Mode
- Demo opportunities directory
- Resume Builder + browser Print/Save as PDF
- Communication practice + speech recognition where supported
- Anonymous local community posts
- Expense tracker
- Notifications
- “What Should I Do Now?” signature action
- Dark/light mode
- localStorage persistence
- Responsive mobile/desktop UI

## AI/API
The first version intentionally uses a local rules-based fallback so it works immediately. For production AI, add a backend/API service layer and keep API secrets server-side; never place a secret API key in `app.js`.
