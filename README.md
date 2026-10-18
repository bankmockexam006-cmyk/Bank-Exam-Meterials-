# BankReady — ICICI Bank Exam Practice

Responsive practice website with 500 embedded multiple-choice practice questions across Banking Awareness, Aptitude, Reasoning, English, and Customer Service & Sales.

## Run locally
1. Install Node.js LTS from https://nodejs.org/
2. Extract this ZIP and open a terminal in the extracted folder.
3. Run `npm install`
4. Run `npm start`
5. Open http://localhost:3000

## Included
- Name + email + 10-digit phone login form
- Category-wise practice, instant feedback and explanations
- 50-question timed mock test (30 minutes)
- Score summary and question navigator
- Mobile responsive layout
- Browser-local progress storage

## Important limitations
The login is a demo only: it validates fields in the browser and stores a profile locally. It does not verify email/phone ownership, send OTPs, or provide secure account authentication. Progress is saved in the same browser/device only. Production use requires backend authentication, OTP verification, database, secure sessions, rate limiting, and a privacy policy.

Questions are independent practice examples, not official ICICI Bank questions or verified previous-year questions. This site is not affiliated with or endorsed by ICICI Bank. Never enter bank passwords, PINs, OTPs or card details.

## Deployment
Use a Node.js host such as Render or Railway with start command `npm start`. GitHub Pages alone cannot run the Express server. For static hosting, publish the `public` directory, but login and progress remain browser-local.
