# 🌸 bloomkey

Type a password and watch a flower grow. A cute, privacy-friendly password strength checker built with plain HTML, CSS and JavaScript.

**Live demo:** https://YOUR-USERNAME.github.io/bloomkey/

## Features
- Plant grows through 6 stages (empty pot → seed → sprout → budding → blooming → full bloom) as password strength improves
- Scores length, character variety, and unique characters
- Penalises very common passwords (including swaps like `p@ssw0rd`), keyboard patterns (`qwerty`) and runs (`1234`)
- Rough crack-time estimate based on password entropy
- Sample passphrase generator using the browser's secure random generator (`crypto.getRandomValues`)
- Customisable: 8 colour themes and 5 flower styles (heart, lotus, sunny, puff, star)
- 0-100 score ring, a 5-point checklist and tips that change as you type
- **100% client-side**: nothing is sent, stored or logged

## Tech
HTML, CSS (custom properties for theming), vanilla JavaScript, inline SVG

## Run locally
Open `index.html` in any browser. No install needed.

## Limitations
Educational project. Scoring is rule-based, and crack time assumes 10 billion guesses/second against a fast hash. Real attackers use smarter guessing, so treat the result as a rough guide.
