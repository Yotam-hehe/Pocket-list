# Pocket List

A phone app for things to play, buy, make, book, or anything else (Misc). Cross an item off and it moves to Done, grouped by the day you finished it.

It works offline once installed. Your list is stored on the phone itself. Use the ⋯ menu to save a backup file now and then.

## Put it online with GitHub Pages

1. On github.com, create a new **public** repository, for example `pocket-list`.
2. Click **Add file → Upload files** and drag in everything from this folder, including the `icons` folder. Commit.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
4. After a minute or two the app is at `https://<your-username>.github.io/pocket-list/`.

## Install it on your phone

- **iPhone:** open the link in Safari → Share → **Add to Home Screen**.
- **Android:** open the link in Chrome → ⋮ menu → **Install app** (or **Add to Home screen**).

Always open it from the home-screen icon. On iPhone, the home-screen app keeps its own storage, separate from Safari.

## Changing the app later

Edit `index.html`, then change `VERSION` in `sw.js` (for example to `pocket-list-v2`) so phones load the new copy. The new version shows up the second time you open the app.
