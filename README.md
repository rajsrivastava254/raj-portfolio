# Raj Srivastava — Portfolio (Frontend)

A lightweight, responsive portfolio site showcasing projects, experience and skills. Built with plain HTML, CSS and vanilla JavaScript.

Live files:
- [index.html](index.html) — main markup
- [style.css](style.css) — styles and theme tokens
- [app.js](app.js) — interactive behavior
- [.dist/](./.dist/) — build / distribution folder (if used)

Quick overview
- Purpose: Personal portfolio for a Backend Java Developer.
- Tech: HTML, CSS (variables + utility classes), vanilla JS.
- UX features: loading screen, floating navbar, particles, typing header, scroll-triggered animations, skill bars, counters, cursor trail, contact form with simulated submit.

Notable JS entry points and behaviour (see [app.js](app.js))
- [`initParticles`](app.js) — generates animated particles in the hero.
- [`initTypingAnimation`](app.js) — types the hero heading text.
- [`initScrollAnimations`](app.js) — intersection observer for fade/slide animations.
- [`animateSkillBars`](app.js) — animates skill progress bars on scroll.
- [`animateCounters`](app.js) — animates numeric stats counters.
- [`initNavbar`](app.js) — shows/hides navbar on scroll.
- [`initBackToTop`](app.js) — toggles back-to-top button and smooth scroll to top.
- [`initContactForm`](app.js) — handles contact form submission UI and notifications.
- [`showNotification`](app.js) — in-page notifications for success/error.
- [`initCursorTrail`](app.js) — desktop cursor trail effect.

How to run locally
1. Clone or copy the repository to your machine.
2. Open [index.html](index.html) directly in a browser OR serve the folder (recommended to avoid resource restrictions):
   - Python 3: python -m http.server 8080
   - Node (http-server): npx http-server -p 8080
3. Visit http://localhost:8080 (or open file://.../index.html).

Customization tips
- Update hero typing text in the DOM: the element with class `typing-text` in [index.html](index.html).
- Adjust colors and tokens in [style.css](style.css) (root variables).
- Edit animations / add sections in [app.js](app.js). Use the functions listed above as starting points.

Accessibility & performance notes
- Animations are CSS/JS driven and can be disabled via prefers-reduced-motion if needed (consider adding a check).
- For production, minify CSS/JS and use the [.dist/](./.dist/) folder for optimized assets.

Contributing
- This is a personal portfolio. For local improvements, edit the files above and preview locally.

License
- Add your preferred license here (e.g., MIT) if you plan to publish this repository.

Contact
- See the Contact section in [index.html](index.html) for the displayed email/phone links.
