# Qanoon Dost

A responsive, interactive front-end prototype for a Pakistani law study platform.

## Open it

Open `index.html` in a modern browser. No build step is required.

## What works in this prototype

- Searchable law study cards with topic filters and local bookmarks
- Mock LAT practice action
- Student discussion board with question submission
- Author book submission flow with a local review status
- Sign-in and registration interaction, including role selection
- A multilingual study-assistant interface with conservative sample responses
- Responsive mobile navigation and layout

The browser stores prototype bookmarks and submissions in local storage. Authentication is simulated: this does not create secure accounts or send data to a server. The assistant uses local sample responses; it is not connected to an AI provider. The law cards and books are demo placeholders, not authoritative legal material. No Urdu/Sindhi legal translations or statutory text are presented as verified.

## Before production

Connect a backend such as Supabase for authentication, database, and private file storage. Add server-side role checks and Row Level Security, moderation and review queues, legal-source records with version and amendment metadata, copyright/takedown flows, rate limiting, and an AI service that retrieves only reviewer-approved sources. Keep provider secrets on the server. Have qualified reviewers verify original law text and translations before publishing.
