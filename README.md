# Sam OS

Single-file playground: open `samos.html` in a browser (same folder as `samos-wallpaper.png`).

The **`aurora/`** folder is a production copy of **[aurora-screensaver](https://github.com/sambrott/aurora-screensaver)**. After ~**60 seconds** without pointer/keyboard/wheel activity, Aurora fills the viewport **below the menu bar** as an in-browser “screen saver.” Move the mouse (on the translucent wake layer), click, scroll, or press a key to return. Dock **Aurora** and **Go → Aurora Screen Saver** open it manually. To refresh assets after changing the aurora repo: run `npm run build` there, then replace `sam-os/aurora/` with that `dist/` output.

