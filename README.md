# Aura

A living, generative canvas for iPad. The colors, the flow field, and the serial number are all seeded from your name, so your iPad's Aura doesn't look like anyone else's.

## What it does

- **Fingers** bend the field. Each finger is a vortex that particles swirl around.
- **Apple Pencil** paints glowing ink, and the particles start streaming along your strokes. Pressure and tilt change the line width.
- **Tilt** (tap *Tilt*) steers the whole field with the iPad's motion sensor.
- **Three modes:** Flow, Galaxy, Rain.
- **Remix** makes a new palette that's still seeded from your name. **Save** exports a signed PNG to Photos via the share sheet.
- **Double-tap** hides the controls. **Long-press with two fingers** to change the name.
- Works offline once installed, and opens full screen from the Home Screen like a native app.

## Put it on your iPad

1. Host it with GitHub Pages. On github.com (in Safari, not the GitHub app), go to **Settings → Pages → Build and deployment → Source: Deploy from a branch**, then pick branch `claude/custom-ipad-app-fghm3v` and folder `/ (root)` and tap **Save**. After a minute or two it's live at `https://sam81005.github.io/iPad-custom/`.
2. Open that URL in **Safari** on the iPad.
3. Tap **Share → Add to Home Screen**.
4. Launch **Aura** from the Home Screen and type your name.

Tip: open it in Split View or Stage Manager next to your notes for a desk-toy screen, or use Guided Access to keep it running as an ambient display.

## Files

- `index.html`: the whole app (canvas engine, input, UI)
- `manifest.webmanifest`, `sw.js`: install and offline support
- `icons/`: Home Screen icons
