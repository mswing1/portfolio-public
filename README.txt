Michael Swingler - landing page
================================

Open index.html in a browser. It is a static page: no build step, no dependencies.
Keep the assets/ folder next to index.html.

assets/face-logo.svg          Face logo, exported from Figma (#EFB400)
assets/michael-swingler.svg   "Michael Swingler" wordmark, exported from Figma (#EFB400)
assets/photo-1400.webp        Portrait (used on large screens)
assets/photo-900.webp         Portrait (smaller copy for phones)
assets/plus.svg               The plus tile from Figma (the page draws its grid itself)
assets/source/                The original full-size portrait PNG from Figma

Colors:  ink #20283B, gold #EFB400, white #FFFFFF
Type:    "Proxima Nova" if installed, otherwise Figtree (loaded from Google Fonts).
         To use a licensed Proxima Nova, add an @font-face for it in index.html;
         the font stack already lists it first.
Plus grid: 12px plus marks on a 92px grid at 30% opacity, as in the Figma frames.
