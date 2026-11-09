# Studyflow PWA

A local-first adaptive study planner. No account or paid API required.

## Run locally
Open `index.html` in a browser. Core features work, but PWA installation and offline caching require HTTPS or localhost.

## Deploy free
1. Create a GitHub repository and upload these four files.
2. Import the repository into Vercel (Hobby plan) or use another static HTTPS host.
3. Deploy. Open the HTTPS URL in Safari on iPhone/iPad.
4. Safari Share → Add to Home Screen.

## Features
- Add assessments and tasks with deadline, estimated hours, completed hours, difficulty, importance.
- Add recurring and one-time commitments.
- Deterministic adaptive weekly scheduler with daily cap, session lengths, lunch break, blocked-time avoidance and overload warnings.
- Log study sessions; completing a planned block updates remaining task effort and records the session.
- Dashboard, workload by course, upcoming deadlines, progress and JSON backup/restore.

## Data & limitations
Data is stored in localStorage in this browser/device. There is no cloud sync, account system, LMS/calendar integration, push reminder service, or AI API in this version. Export JSON backups. The scheduler is deterministic and explainable; it is not a language model. Verify all deadlines and timetable details yourself.
