## Prompt for building The Gallery Journal submission platform

Transform https://sophia860.github.io/the-gallery-journal/ from a static showcase into a fully functioning literary magazine platform with backend services, authentication, submissions, and editorial tools.

**Key goals**
- Add a backend (Node/Express or Python/Flask) deployable on Vercel/Netlify/Heroku with CORS and environment-based secrets.
- Implement auth (Firebase Auth or Auth0) for editor and writer login flows.
- Use a database (Firebase Firestore or Supabase) to store users, submissions, issues, and statuses.

**Submission experience**
- Create `/submit` form: bio, cover letter, categories/tags, up to 5 poem uploads (PDF/DOCX), optional fee via Stripe/PayPal.
- Send confirmation emails, allow status tracking (Received → In Review → Decision), and withdrawal notices for simultaneous submissions.

**Editorial workflow**
- Build `/admin` dashboard: queues, scoring (1–10), tags like Accept/Decline, assignment/round-robin, private notes, bulk actions, CSV export, blind review view.

**Journal management**
- Enable publishing new issues via headless CMS (e.g., Strapi/Contentful), keep gallery navigation, add past-issue archive, RSS feed, sitemap/SEO meta, and guidelines page (themes, limits, deadlines).

**Delivery guidance**
- Proxy frontend API calls to the new backend, seed with dummy data, and keep changes minimal while ensuring functionality.
