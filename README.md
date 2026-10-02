# Junior Coach: putting it on iPhone and iPad

This folder is the whole app. You host it free on GitHub Pages, then add it to each device's Home Screen from Safari.

## What's in the folder

| File | What it does |
|---|---|
| `index.html` | The app: formations, subs planner, drills |
| `manifest.webmanifest` | Name, icon and full-screen settings for the Home Screen |
| `sw.js` | Makes the app work offline after the first open |
| `icons/` | App icons |
| `.nojekyll` | Tells GitHub Pages to serve the files exactly as they are |

## 1. Put it on GitHub Pages (about 5 minutes)

1. Sign in at github.com (create a free account if you need one).
2. Create a new repository: click **+** → **New repository**. Name it `Junior-Coach`, set it to **Public**, and click **Create repository**.
   Free accounts need a public repository for Pages. Nobody's names are in these files; the squad is stored on each phone, not on GitHub.
3. On the empty repository page, click **uploading an existing file**. Drag in everything from this folder, including the `icons` folder and `.nojekyll`. Click **Commit changes**.
   If `.nojekyll` doesn't show up (Mac Finder hides files starting with a dot), the app still works without it.
4. Go to **Settings** → **Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main** and folder **/ (root)**. Click **Save**.
5. Wait a minute, refresh the Pages settings page, and it shows your address:
   `https://<your-username>.github.io/Junior-Coach/`
   The part after `github.io/` must match the repository name exactly, capital letters included. Copy the link from the Pages settings page rather than typing it.

## 2. Install on iPhone or iPad

1. Open the address in **Safari**.
2. Tap the **Share** button, then **Add to Home Screen**, then **Add**.
3. Open it from the new **Junior Coach** icon. It runs full screen, and works with no signal once it has been opened once.

Send the same link to other coaches or parents and they can install it too. Each device keeps its own squad and settings.

## Updating the app later

Upload the changed `index.html` to the repository the same way (it replaces the old one). Devices pick up the new version the next time the app is opened with a signal, then close and reopen it once.

## Good to know

- **Screen lock:** the app asks iOS to keep the screen on while the match clock runs. If the screen does lock, the change beep can't sound, but the clock shows the right time when you unlock it.
- **Removing it:** press and hold the icon → **Remove App**. This also deletes the squad saved on that device.
- **Custom address (optional):** in Settings → Pages you can add your own domain if you have one.
