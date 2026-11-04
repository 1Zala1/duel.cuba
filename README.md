# DUEL CUBA — Free Vercel deployment

This is a static website with head-to-head voting and personal Elo rankings.

## Deploy without coding
1. Create a free GitHub repository and upload `index.html` and `vercel.json` to its root.
2. Sign in to https://vercel.com with GitHub.
3. Select **Add New → Project**, import the repository, choose **Other** framework, and click **Deploy**.
4. Vercel will give you a free `*.vercel.app` URL. You can customize the project name if the name is available.

## Important limitations
- Personal votes are saved only in the visitor's browser using localStorage.
- Global rankings require a hosted database and vote API; the Global tab is a placeholder.
- Artist photos load on demand from Wikipedia and may be unavailable for many artists; photos require an internet connection and may have separate reuse/license requirements.
- This is a prototype, not a production-ready multiuser voting service.
