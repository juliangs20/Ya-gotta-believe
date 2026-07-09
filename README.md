# The 46–24 Watch

A daily tracker for the 2026 Mets playoff chase. Starting from their 38-54 record on July 8, they need to go 46-24 over the final 70 games to reach 84 wins. Ya gotta believe.

## What it does

- Tap **Mets Win** or **Mets Loss** after each game — the run record, overall record, pace math, and the 70-game strip all update instantly
- Tracks wins still needed (of 46), losses to spare (of 24), the required winning percentage the rest of the way, and games behind the third NL wild card
- Editable NL wild card standings with the playoff cut line — the Mets row syncs automatically from your tracker
- Everything saves in your browser (localStorage), so your progress is there when you come back

## Publish on GitHub Pages

1. Create a new repository on GitHub (e.g. `mets-tracker`)
2. Upload `index.html` to the repository root
3. Go to **Settings → Pages**
4. Under "Source," choose **Deploy from a branch**, select `main` and `/ (root)`, and save
5. Your page will be live in a minute or two at `https://YOUR-USERNAME.github.io/mets-tracker/`

No build step, no dependencies — it's a single HTML file.

## A note on saved data

Progress is stored in the browser you use it in. If you open the page on a different device or clear your browser data, the tracker starts fresh (the standings reset to the July 8 baseline). The "Edit records" button lets you catch anything up by hand.
