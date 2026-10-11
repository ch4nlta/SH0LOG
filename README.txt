SHOWLOG - GitHub Pages setup

1. UNZIP this file first. Upload the files themselves (index.html, sw.js, manifest.webmanifest,
   the 3 .png icons, 404.html, .nojekyll) to the ROOT of your repo, not inside a folder.
   On the GitHub website: Add file > Upload files, drag them in, Commit.
   (If you can't see .nojekyll it's a hidden file; it's optional.)
2. Repo > Settings > Pages > Source: "Deploy from a branch", Branch: main, Folder: / (root). Save.
3. Wait 1-2 minutes. Your app is at https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
   (use that exact address, with the repo name at the end).

Still a 404? The usual causes: the files are in a subfolder, index.html is not named exactly
"index.html" (lowercase), Pages isn't switched on yet, or the repo is private on a free plan.
Your password is unchanged. After updating, close and reopen the app once.
