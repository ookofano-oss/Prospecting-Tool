# Host the Prospecting Workspace on GitHub Pages

Do steps 1–7 once on your computer; step 8 is on the iPhone.

## On the computer
1. Go to **github.com** and sign in (or create a free account — a personal one is fine).
2. Top-right **+** → **New repository**.
3. Repository name: `prospects` (anything works). Set it to **Public**. Leave everything else default. Click **Create repository**.
   - *Public just means the app file is reachable by URL. None of your prospect data is in the file — it stays in your phone's browser — so nothing sensitive is exposed.*
4. On the new repo page click **Add file → Upload files**.
5. Drag **`prospecting-dashboard.html`** (from your Prospecter folder) into the box. Wait for it to finish, then click **Commit changes**.
6. Click the **Settings** tab (top of the repo) → in the left sidebar click **Pages**.
7. Under **Build and deployment → Source** choose **Deploy from a branch**. Set **Branch** to **main** and folder **/ (root)**, then **Save**. Wait about a minute.

Your site URL will be:

```
https://YOUR-USERNAME.github.io/prospects/prospecting-dashboard.html
```

(Replace `YOUR-USERNAME` and `prospects` if you named them differently. If you see a 404 at first, give it a minute and refresh.)

## On the iPhone
8. Open that URL in **Safari** → tap **Share** (square with up-arrow) → **Add to Home Screen** → **Add**.

Done — the magnifier icon appears on your home screen and opens the app full-screen, working offline.

## Later, to update the app
When the dashboard changes, in the repo do **Add file → Upload files**, drag the new `prospecting-dashboard.html` (same name) → **Commit changes**. Reopen the home-screen icon and it loads the new version.

## Moving your data to the phone
The phone starts empty. On the computer use the **Send** icon (💼/🏠) to email yourself the `.json` backup, open it on the phone, and use **Sync** to import — same flow you use between home and work.
