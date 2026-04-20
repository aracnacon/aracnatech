# AracnaTech

Custom software consulting site for AracnaTech — built with vanilla HTML, CSS, and JavaScript.

**Live site:** https://aracnacon.github.io/aracnatech

## Pages

| Page | Description |
|------|-------------|
| `index.html` | Homepage — services, tech stack, value props |
| `webcompare.html` | Interactive legacy vs modern UI comparison demos |
| `contact.html` | Contact form (Web3Forms) with social links |
| `thanks.html` | Post-submission redirect |

## Tech

- Vanilla HTML/CSS/JS — no frameworks, no build step
- 5-theme switcher (Midnight Blue, Ember, Forest, Arctic, Miami Glow) with localStorage persistence
- GSAP ScrollTrigger for scroll-reveal animations and parallax backgrounds
- Typewriter effect on page headers
- Hexagon grid tech stack display
- Responsive design (mobile-first breakpoints)
- Web3Forms for contact form submission

## Structure

```
css/style.css            Shared styles + theme variables
js/theme-switcher.js     5-theme cycler with persistence
js/typewriter.js         Character-by-character header animation
js/scroll-animations.js  GSAP ScrollTrigger reveals + parallax
js/skills.js             Dynamic hex grid loader
data/skills.json         Tech stack categories and icons
images/profile/          Profile photo
images/backgrounds/      Page + theme background images
```

## Related

- **Portfolio site:** https://aracnacon.github.io
- **Source repo:** Private (`aracnacon/JobAgent`)
