# Putting the Prospecting Workspace on your iPhone

The dashboard is now an installable web app: it has a proper app icon, launches full-screen (no Safari bars), and runs offline because everything it needs is inside the one file.

There's one step only you can do: the page has to be opened **in Safari on the iPhone** before you can "Add to Home Screen". Two ways:

## Option A — Host it once (recommended: reliable + offline + keeps your data)
1. Put `prospecting-dashboard.html` on any free static host and **rename it `index.html`**. Easiest options: GitHub Pages, Cloudflare Pages, or Netlify (all free; a personal account is fine — nothing work-related).
2. Open the resulting `https://…` link in **Safari** on your iPhone.
3. Tap the **Share** button (the square with the up-arrow) → scroll down → **Add to Home Screen** → **Add**.
4. You'll get a home-screen icon (the magnifier logo). Tapping it opens the app full-screen, and it works with no signal.

Privacy: only the empty app *shell* is hosted. None of your prospect or client data is uploaded — it lives solely in your iPhone's browser storage for that link.

## Option B — No hosting (quick, but less reliable)
1. The file is already in your OneDrive folder, so open the **OneDrive app** on the iPhone and find `prospecting-dashboard.html`.
2. Open it and choose **Open in Safari** (via the share menu).
3. Then **Share → Add to Home Screen**.

Caveat: apps launched from a file (rather than a web link) can be flaky on iOS about staying offline and keeping your data between launches. For daily use, Option A is worth the few minutes.

## Important: your data won't auto-sync between computer and phone
The phone copy starts empty — your prospects live on whichever device you entered them on. To move data across:
- On the computer, tap the **Send** icon (💼/🏠) or use the data backup, email yourself the `.json`, open it on the phone, and use **Sync** to import.
- Do the same in reverse to push phone changes back.

That's the same Sync flow you already use between home and work — the iPhone is just another device in that loop.

## Updating the app later
- Option A: when I change the dashboard, replace the hosted `index.html` and reopen the icon — it loads the new version.
- Option B: re-open the new file in Safari and Add to Home Screen again.
