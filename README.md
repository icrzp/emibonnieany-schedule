[README.txt](https://github.com/user-attachments/files/35095333/README.txt)
EMIBONNIEANY SCHEDULE — Static website package

DEPLOY
1. Upload index.html to the root of a static website host (Netlify, GitHub Pages, Cloudflare Pages, etc.).
2. Set the site's publish directory to the directory containing index.html, if asked.
3. Open the published URL to view the site.

IMPORTANT LIMITATIONS
- This is a browser-only prototype. Events, artists, cover photos, theme colors, and other edits are stored in each visitor's browser localStorage. They are NOT shared across devices or users.
- Admin authentication is performed entirely in browser JavaScript. The credentials are visible to anyone who views the source and do not protect data. Do NOT treat this as secure access control on a public website.
- Use a database and secure server-side authentication (e.g. Supabase) before relying on this for production admin editing and shared event data.
- Export CSV to back up locally stored event records.
