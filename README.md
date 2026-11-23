# Cloud Interview Arena — AWS Edition

Free, static AWS interview scenario quiz designed for students. Includes 300 questions, random quiz sessions, difficulty selection, scoring/streaks, explanations, timed play, and a copy-result feature.

## Publish with GitHub Pages (free)
1. Create a GitHub account if needed and create a new repository named `aws-interview-quiz`.
2. Upload **index.html**, **style.css**, **app.js**, and **questions.js** to the repository root.
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose `main` and `/ (root)`, then Save.
6. Wait a minute or two; GitHub will show the public website URL in the Pages section.
7. Share that URL with students.

## How to play
Students enter a name, choose question count (10, 20, 30, 50, 100, or 300) and difficulty (All/Easy/Medium/Hard), then start. Questions are randomized. Correct answers earn 100 XP plus streak bonuses. Students can copy their results to send to you.

## Important limitation
GitHub Pages hosts static files only. Scores are **not centrally collected**; results remain in the student's browser session until they copy/share them. A central instructor dashboard would require a database or external collection service.

## Files
- `index.html`: site entry point
- `style.css`: responsive design
- `app.js`: game logic
- `questions.js`: question bank (300 questions)

The question bank follows the AWS bootcamp curriculum areas: cloud fundamentals, IAM/security, networking, storage, compute, load balancing/Auto Scaling, databases, serverless, application integration, analytics, AI/ML, migration, architecture, and Well-Architected concepts.
