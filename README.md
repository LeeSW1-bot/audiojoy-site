# AudioJoy.uk — updated build

UK queer pop writing project.

## Changes in this build
- Play counter on every Play control (localStorage key `audiojoy-play-count`, increments on successful play start; shown calmly as “X plays”)
- “Listen for free” near Yellow Aura (hero + music card + aura section)
- Line under Music: “Finished songs coming to Spotify soon.”
- Tone kept calm. No external branding.

## Features
- Dark / gold aesthetic (Outfit + Syne)
- Sticky mini-player
- Music section with Yellow Aura demo + Shook By The Look sample
- About + dedication
- Mailing list form (localStorage)
- Fully responsive

## Preview
Open `index.html` in a browser or serve the folder:

```bash
npx serve .
# or
python3 -m http.server 8080
```

## Deploy
Upload the entire folder contents to any static host (Netlify, Vercel, Cloudflare Pages, GitHub Pages, etc.).

Audio files are included (MP3).
