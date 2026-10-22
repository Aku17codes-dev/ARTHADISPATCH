# The Artha Dispatch — Daily Auto-Updating Newspaper Web App

## How Daily Updates Work Automatically
1. **Zero-Config Browser Auto-Sync (Works With or Without GitHub)**:
   Every time you open the site (and every 30 minutes while open), the app automatically fetches the latest RSS dispatches from:
   - **The Hindu** (`thehindu.com/news/national/feeder/default.rss`)
   - **Mint** (`livemint.com/rss/markets`)
   - **Business Standard** (`business-standard.com/rss/markets-106.rss`)
   - **Financial Express** (`financialexpress.com/market/feed/`)
   - **Wall Street Journal** (`feeds.a.dj.com/rss/RSSMarketsMain.xml`)
   It scores each new article using your Personalisation Tuner weights and merges them to the top of your Daily Broadsheet.

2. **Deploy Without GitHub**:
   Run `npx vercel --prod` inside this folder.

3. **Deploy Via GitHub**:
   Upload `index.html` and `vercel.json` to a GitHub repo and import the repo on Vercel.
