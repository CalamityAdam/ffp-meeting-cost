# Meeting Cost-o-Meter

A single-page meeting cost calculator. $40/minute, ticking in real time, with an escalating mood that goes from ☕ to 🔥 as the dollars pile up.

Open `index.html` in a browser, or deploy the folder as a static site (Vercel, Netlify, GitHub Pages — no build step).

## Stack

Zero dependencies. One HTML file with inline CSS and JS. `requestAnimationFrame` + `performance.now()` so the counter updates ~60× per second off real elapsed time.
