# Your own fonts

Right now the site uses free Google fonts (set in `app/layout.js`).
To use your own fonts from your computer:

1. Copy the font files here (`.woff2` is best; `.ttf` / `.otf` also work).
   Check that your licence (for example Envato) allows **web** use.
2. Ask Claude Code: *"Switch the masthead font to my file public/fonts/MyFont.woff2"*.
   It will use `next/font/local` in `app/layout.js`, which keeps the site fast.
