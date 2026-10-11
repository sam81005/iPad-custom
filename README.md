# Desk

A home screen for your iPad that you'll use every day. Tasks, a focus timer, habits and an Apple Pencil scratchpad, all on one screen. Behind it runs a slow, glowing background generated from your name, so no one else's Desk looks like yours.

## What's in it

- **Today:** a quick task list. Add, check off, clear the finished ones.
- **Focus:** a 25, 50 or 10 minute timer with a progress ring. It plays a chime and starts a break when time's up, and keeps the screen awake while it runs. It also tracks minutes focused today and your day streak.
- **Habits:** tap a day to mark it done for up to 5 habits, Monday to Sunday.
- **Scratchpad:** pressure-sensitive Apple Pencil notes with colors, an eraser, undo, multiple pages, and blank, lined or grid paper. Use **⋯ → Save** to send a page to Photos or Files. Turn on **Pencil-only** in ⚙︎ so your palm doesn't draw.
- **✦ Ambient mode:** the full-screen interactive Aura canvas (`aura.html`). Fingers swirl it, the Pencil paints ink it follows, and tilting the iPad steers it.

Everything is saved on the iPad itself (no account, works offline). Clearing Safari's website data erases it.

## Put it on your iPad

1. **Turn on GitHub Pages.** In Safari (not the GitHub app), open `github.com/sam81005/iPad-custom/settings/pages`. If the page looks cut down, tap **aA → Request Desktop Website**. Set **Source: Deploy from a branch**, pick branch `claude/custom-ipad-app-fghm3v` and folder `/ (root)`, then tap **Save**.
2. After 1–2 minutes, open `https://sam81005.github.io/iPad-custom/` in Safari.
3. Tap **Share → Add to Home Screen**, then open **Desk** from the Home Screen.

## Files

- `index.html`: Desk
- `aura.html`: ambient mode
- `manifest.webmanifest`, `sw.js`: install and offline support
- `icons/`: Home Screen icons
