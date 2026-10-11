# Splot (English prototype)

A static prototype. No build step: upload these files to the root of a GitHub repository and turn on GitHub Pages (Settings -> Pages -> Deploy from a branch -> main / root).

Files: `index.html` (the app), `profiles.json`, `manifest.webmanifest`, `sw.js`, and 3 icons.

## Editing dummy profiles for every phone
Edit `profiles.json` on GitHub (pencil icon -> Commit changes). The app downloads it each time it opens (changes show up after 1-3 minutes). Keys are profile numbers; you can set `name`, `age`, `pron`, `bio`, `job`. `was` is only a label for you. Use `He`, `She`, `They`, `No pronouns` joined with `/` (e.g. `She/They`). The `lines` array holds the first messages sent after a match. Placeholders: `{name}` `{myname}` `{interest}` `{job}`. A typo in the JSON makes the app ignore the file and use the built-in values.

## Install on a phone
iPhone: open in Safari -> Share -> Add to Home Screen. Android: open in Chrome -> menu -> Add to Home screen / Install app.
