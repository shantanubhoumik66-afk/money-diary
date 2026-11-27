# Money Diary

Personal budget app: Total Credit (morning + night), business, expenses and mutual funds, read from your BUDGETING Excel workbook, with daily entry, charts, PIN lock and encrypted sync between phone and laptop.

## Put it online (GitHub Pages, free)

1. On github.com, create a new repository named `money-diary` (Public is needed for free GitHub Pages; only the app code is in it, never your money data).
2. Open the repository, tap **Add file › Upload files**, and upload everything from this folder: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` and the whole `icons` folder. Tap **Commit changes**.
3. Go to **Settings › Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute, your app is at `https://YOUR-GITHUB-NAME.github.io/money-diary/`

## Install on your phone (no Chrome badge)

1. Open the link in **Chrome**.
2. Tap **Install app** in the app (or Chrome menu ⋮ › **Install app**). Choose *Install*, not *Add shortcut*.
3. The Money Diary icon appears on your home screen and opens full screen.

If you added the old claude.ai link to your home screen before, remove that shortcut.

## Install on your laptop

Open the same link in Chrome or Edge and click the install icon in the address bar (or menu › *Install Money Diary*).

## Sync phone and laptop

1. On your phone: upload your Excel, set your PIN, then open **Settings & sync**.
2. Follow the steps there to make a GitHub token with only **gist** ticked, and tap **Connect**.
3. On your laptop: open the app, set the **same PIN**, and paste the **same token**.

Both devices now share the same data. Only an encrypted copy (locked with your PIN) is stored in a secret gist in your GitHub account.

## Updating the app later

Upload the new `index.html` (and any changed files) to the same repository. The installed app picks up the new version the next time it opens online.
