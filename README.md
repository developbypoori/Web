# DP — Develop by Poori | Portfolio

Responsive personal portfolio for Poori M. Sanj.

## Features
- English-language portfolio for web design, app/UI design, and digital marketing
- Violet/black visual identity, motion graphics, responsive mobile layout
- Embedded SoundCloud player for streaming tracks from Anyma’s profile
- Music player drawer toggled from the ANYMA RADIO button (also keyboard shortcut `M`); autoplay is requested when supported
- Transparent version of supplied DP logo and supplied portrait

## Run locally
Open `index.html` in a modern browser. Fonts use Google Fonts when online.

## Publish with GitHub Pages
1. Create a repository and upload `index.html`, `README.md`, and the entire `assets/` folder.
2. Open Settings → Pages.
3. Select Deploy from a branch, `main`, and `/(root)`, then Save.
4. For a custom domain, set it under Settings → Pages and configure DNS at your registrar.

## Audio
The ANYMA RADIO button opens an embedded SoundCloud player for the Anyma profile (`soundcloud.com/anyma_ofc`). The player requests autoplay after the visitor opens it; browser and provider restrictions may still require pressing play. Audio streams from SoundCloud and is not downloaded or redistributed by the site.


Music update: the player uses the locally bundled `assets/ireflectioni.mp3` file provided for this build. Playback starts at 00:20. Autoplay is attempted on page load; browsers may require a click on the music button or native Play control.
