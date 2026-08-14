# Human Prescription Rx — website

Hand-coded static site (plain HTML/CSS/JS). Edit `index.html` directly — no build step,
no Claude Design. Works like your other sites.

## Add the 3 real photos
The `images/` folder currently holds temporary colour placeholders. Replace them with the
real photos, keeping the exact same filenames:

- `images/dr-pragnya-hero.jpg`   → blue-suit photo holding the "Dr Pragnya" neon sign (hero)
- `images/dr-pragnya-red.jpg`    → red-suit standing photo (biography section)
- `images/podcast-cover.jpg`     → yellow "Human Prescription Rx" cover art

## Deploy (same as your other sites)
1. Create a GitHub repo, upload `index.html` + the `images/` folder (with the real photos).
2. Connect the repo to Vercel → it deploys automatically.
3. Any future change: edit `index.html`, commit, Vercel auto-deploys.

## Notes
- Fonts (Inter + Poppins) load from Google Fonts.
- The newsletter and contact forms currently show a thank-you message but don't send
  anywhere yet. To make the contact form actually email drpragnya@humanprescription.com,
  wire it to a form service (e.g. Formspree) — quick to add.
- The small hero graphic is a clean static brand mark (the animated fingerprint→brain from
  the old compiled version couldn't be extracted; can be refined if wanted).
