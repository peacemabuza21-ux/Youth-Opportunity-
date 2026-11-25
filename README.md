# Youth Opportunity Hub – South Africa

A responsive React/Vite starter interface for a South African youth opportunity discovery platform.

## Included in this starter
- Dashboard for jobs, learnerships, internships and bursaries.
- Opportunity search by keyword, category and South African province.
- Opportunity submission form with closing date, eligibility and official source URL.
- Save-and-apply reminders that direct users to providers' official websites.
- Career guidance interface, CV draft builder and profile form.
- Responsive green, white and lime-green design.

## Run locally
Requires Node.js 18 or later.

```bash
npm install
npm run dev
```

Build for production with `npm run build`.

## Important project status
This repository contains a **front-end prototype**, not yet a production-ready employment platform.

- Data is stored in the visitor's browser using localStorage. It is not shared between users or devices.
- The role selector is a visual demo, not secure role-based access control.
- The career assistant currently provides example guidance, not live AI responses.
- CV drafts are generated in the browser.
- Opportunity submissions are local to the browser and are not independently verified.
- Applications are reminders only; users must complete applications on the official provider website.

Before public production use, add a secure backend and database, real authentication, verified employer/admin permissions, server-side validation, secure file uploads, notifications, audit logs, privacy controls and a properly connected AI service. Never store passwords or sensitive personal information in localStorage.

## Deployment
The Vite frontend can be deployed to a static host such as Vercel or Netlify. GitHub Pages can host the frontend, but cannot run the secure backend, database or AI services required for the complete platform. Configure those services separately.

## Opportunity safety
Do not treat user-submitted listings as verified vacancies. Confirm each opportunity, eligibility requirement and closing date on the official organisation website. The app intentionally starts without fabricated job listings.
