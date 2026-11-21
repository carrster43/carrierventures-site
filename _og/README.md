# Share card source

`card.html` is the source for `../og-image.png` (1200x630, used for og:image and the Twitter card).
GitHub Pages does not serve folders that start with `_`, so this stays private.

Rebuild after editing `card.html`:

    "/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless=new --disable-gpu \
      --hide-scrollbars --force-device-scale-factor=1 --window-size=1200,630 \
      --screenshot=og-image.png "file://$PWD/_og/card.html"

Run from the repo root. Keep it in step with the homepage copy.
