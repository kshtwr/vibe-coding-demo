# Boba Picker: Vercel demo

A single-file web app used to show how GitHub + Vercel deployment works at Vibe Coding 101 (Berkeley AI Affinity Group). No build step, no dependencies: Vercel serves `index.html` as a static site.

`PRD.md` and `DESIGN.md` are the example docs this app was built from: paste both into Claude and ask it to build the app.

## Run it locally

Double-click `index.html`. It opens in your browser. That's your local demo.

## Deploy it

1. Push this folder to a GitHub repo (or upload the files on github.com: **Add file → Upload files**).
2. Go to vercel.com/new and sign in with GitHub.
3. Import the repo. Keep the default settings (no framework needed).
4. Click **Deploy**. You get a live `.vercel.app` link in under a minute.

## Show auto-redeploy

1. On GitHub, open `index.html` and click the pencil icon.
2. Change `--accent` near the top (try `#3b7ea1`), then commit to `main`.
3. Vercel builds the new version automatically. Refresh the live link.
