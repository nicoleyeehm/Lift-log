# Lift Log

Your workout log, set up to run from GitHub Pages as a home-screen app.

Your workouts are saved on the phone you use it on, not in this repository. Anyone can see the code here, but nobody can see your workouts.

## Set it up (about 5 minutes, all on your phone)

1. **Unzip.** In the Files app, tap `lift-log.zip`. A `lift-log` folder appears with 8 files.
2. **Make a GitHub account** at github.com if you don't have one.
3. **Create a repository.** Tap **+** → **New repository**. Name it `lift-log`, choose **Public**, then tap **Create repository**.
4. **Upload the files.** On the new repository page, tap **uploading an existing file** (or **Add file → Upload files**). Choose all 8 files from the `lift-log` folder, then tap **Commit changes**.
   If you don't see an upload option, tap **aA** in Safari's address bar → **Request Desktop Website**, then try again.
5. **Turn on GitHub Pages.** Go to **Settings → Pages**. Under *Build and deployment*, set **Source** to *Deploy from a branch*, **Branch** to `main` and the folder to `/ (root)`, then tap **Save**.
   After 1–2 minutes your link shows at the top of that page: `https://YOUR-USERNAME.github.io/lift-log/`
6. **Add it to your home screen.** Open the link in **Safari** → **Share** → **Add to Home Screen** → **Add**.
   It opens full screen with its own icon, and it works offline at the gym.

## Bring your history over from the Claude version

1. In the Claude version, open the **Log** tab and scroll to **Your data**. Tap **Export backup** and save the file to Files.
2. In your new home-screen app, tap **Import backup** and pick that file.

## Keep it safe

Use **Export backup** every few weeks and keep the file in iCloud Drive. If you clear Safari's website data or change phones, **Import backup** brings everything back.

## Making changes later

1. Ask Claude for the change and attach your current `index.html`.
2. In your repository, tap **Add file → Upload files**, upload the new `index.html` (same name), then **Commit changes**.
3. The site updates in 1–2 minutes. Your workouts aren't affected.

Keep the same address (`…github.io/lift-log/`). A different address starts with an empty log.

## Files

| File | What it does |
|---|---|
| `index.html` | The app |
| `manifest.webmanifest` | App name, icon and full-screen setting |
| `sw.js` | Lets the app open without signal |
| `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` | Home-screen icons |
| `README.md` | These instructions |
