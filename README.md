# namrasamanta.github.io

Personal site for Namra Samanta — AI engineer working on deepfake forensics,
biometric security, and applied cryptography.

Live at **https://namrasamanta.github.io**

## Structure

```
index.html      the entire site — markup, styles, and scripts in one file
profile.webp    portrait used in the About section
```

There is no build step. Edit `index.html` and push; GitHub Pages serves it directly.

## Notes

- Fonts (Instrument Serif, Archivo, JetBrains Mono) load from Google Fonts.
- Motion uses GSAP + ScrollTrigger, with Lenis for smooth scrolling, all from CDN.
  If any of those fail to load, a fallback strips the hidden states so the page
  still renders fully.
- The five canvas visualisations share a single animation loop and pause whenever
  they scroll off-screen.
- Everything respects `prefers-reduced-motion` and works in both light and dark themes.

## Deploying

Push to the `main` branch of a repository named `namrasamanta.github.io`.
GitHub Pages picks it up automatically — no workflow or configuration needed.
