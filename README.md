# 🗃️ UI Vault

**A hand-picked list of free (or dirt-cheap) resources for building bold, premium, three-dimensional interfaces.**

If you've ever bookmarked a component library, a shader tool, or a scroll-animation repo and then lost track of it three tabs later — this is for you. Everything here was gathered, checked, and organized into one searchable page so you don't have to go digging again.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#contributing)
[![Awesome](https://img.shields.io/badge/inspired%20by-awesome--lists-fc60a8.svg)](https://github.com/sindresorhus/awesome)

### 🔗 [Browse the live site →](https://en970.github.io/ui-vault/)

Search, filter by category/platform/pricing, click through — no build step, no signup.

---

## What's inside

32 categories, 1,169+ resources, almost all free or open-source:

| Category | What you'll find |
|---|---|
| **Component Libraries** | shadcn/ui, Aceternity, Magic UI, daisyUI, Radix, Headless UI, and more copy-paste UI kits |
| **React UI Libraries** | Mantine, MUI, Chakra, Ant Design, HeroUI, React Aria, and the design systems behind GitHub, Adobe, and IBM |
| **Framework-Specific Components** | The Vue, Svelte, Angular, SolidJS, and React Native equivalents of the React-first libraries above |
| **CSS Frameworks & Methodologies** | Tailwind, UnoCSS, Bulma, Pico, classless resets, print stylesheets, and BEM/SMACSS/CUBE |
| **HTML & CSS Templates** | HTML5Up, Cruip, Start Bootstrap, and free admin dashboard templates |
| **Design Systems & Style Guides** | Material, Spectrum, Polaris, Carbon, Primer, Fluent, plus Laws of UX and Checklist Design |
| **Scroll & Animation** | GSAP, Lenis, Motion, AOS, Swiper, three.js, and the libraries behind those buttery scroll effects |
| **Cursor & Micro-interactions** | Custom cursors, hover effects, loaders, toasts, and CSS animation generators |
| **3D / Shader / WebGL** | shadergradient, Spline, react-three-fiber, Vanta.js, and raw shader tools |
| **Free 3D Models for Scroll Effects** | CC0 models and open-source scroll+3D boilerplates |
| **Chart & Dataviz Libraries** | Chart.js, D3, ECharts, ApexCharts, Nivo, and animated data-story tools |
| **Icon Sets** | Lucide, Phosphor, Tabler, Heroicons, Iconify, Simple Icons, and icon fonts |
| **Logos & Brand Assets** | SVG brand logos, payment/browser logo sets, and free logo makers |
| **App Icon Design** | Favicon generators, maskable PWA icons, and Apple's own Icon Composer tooling |
| **Free Illustration Packs** | unDraw, Humaaans, Blush, avatars, vectors, and clip art |
| **Backgrounds, Patterns & SVG Shapes** | Hero Patterns, blob/wave/mesh generators, and section dividers |
| **Free UI Kits & Design Files** | Figma and Sketch freebies, daily UI files, and design-resource feeds |
| **Free Stock Photos** | Unsplash, Pexels, Pixabay, CC0 archives, and placeholder image APIs |
| **Free Stock Video & Audio** | Mixkit, Coverr, Freesound, and royalty-free music libraries |
| **Color & Gradient Tools** | Palette generators, contrast checkers, gradient editors, and brand color references |
| **Typography & Free Fonts** | Google Fonts, Fontshare, open foundries, pairing tools, and fluid-type calculators |
| **Mockup & Promo Video Tools** | Turn a screen recording or screenshot into an Apple-style product visual |
| **Online & Desktop Design Tools** | Figma, Penpot, Photopea, Excalidraw, Blender, Inkscape, and CSS generators |
| **AI Design Tools** | Google Stitch, Leonardo, AI SVG generation, and AI charting |
| **Image Compression & Optimization** | Squoosh, TinyPNG, SVGOMG, and privacy-first client-side compressors |
| **Browser Extensions for Designers** | VisBug, PerfectPixel, WhatFont, ColorZilla, and contrast checkers |
| **Developer Utilities & References** | CodePen, CSS-Tricks, caniuse, cheatsheets, and single-purpose web tools |
| **Design Inspiration Galleries** | Awwwards, Mobbin, Godly, Landingfolio, and other places to steal ideas from (respectfully) |
| **Free Framer Templates** | 3D scroll animations and bold templates from the Framer marketplace |
| **Open-Source GitHub Repos** | Awesome-lists and source code worth starring |
| **iOS Onboarding & Liquid Glass** | SwiftUI onboarding SDKs, Liquid Glass component libraries, Figma templates, and Apple's own WWDC25 Liquid Glass sample |
| **Claude Skills for Onboarding & UI Design** | SKILL.md-based Claude Skills for retention-driven onboarding flows, Apple HIG-compliant UI, and premium design review |

Each entry is tagged **Free**, **Freemium**, or **Mostly paid**, and (where relevant) **Mobile**, **Desktop / Web**, or both — with a favicon so you recognize the site at a glance. Filter by category, platform, or pricing (they combine), search on top of that, or just clear everything with one click.

## Contributing

Found something great that's missing? Or a link that's gone dead? Pull requests are genuinely welcome — no need to overthink it:

1. Open `index.html`
2. Find the right category in the `DATA` array
3. Add your resource (name, url, a short honest description, and pricing)
4. Open a PR

Keep it in the spirit of the list: free, cheap, or open-source, and something you'd actually recommend to a friend.

## A quick note on accuracy

Pricing and licensing terms change. We did our best to verify everything at the time of writing, but always double-check on the source site before you build on top of something.

## Security

This is a static, fully self-contained page (all CSS/JS is inline, no external
requests, no backend, no analytics, no cookies). Hardening in place:

- A strict **Content-Security-Policy** meta tag: `default-src 'none'`, so no
  remote scripts, styles, frames, or network connections can load; only inline
  code and `data:` images are allowed.
- Every outbound link uses `rel="noopener noreferrer nofollow"` and resource
  URLs are runtime-sanitized to `http(s)`/`mailto` only, so a bad `url` value in
  a pull request can't become a `javascript:` injection.
- A `referrer` policy that avoids leaking full URLs cross-origin.

Some protections can only be set as HTTP response headers, not via meta tags.
If you host this behind a platform that supports custom headers (Cloudflare
Pages, Netlify, a reverse proxy, etc.), also set:
`X-Frame-Options: DENY`, `X-Content-Type-Options: nosniff`, and
`Strict-Transport-Security: max-age=63072000; includeSubDomains`.
GitHub Pages does not allow custom headers, but the in-page CSP still applies.

## License

The curation and code in this repo are released under the [MIT License](LICENSE). The linked resources each carry their own separate licenses; check those before using them commercially.

---

<sub>topics: `ui-design` `ux-design` `design-resources` `awesome-list` `free-resources` `webgl` `threejs` `shadcn` `icons` `mockup` `framer` `css-animation` `open-source` `onboarding` `liquid-glass` `swiftui` `claude-skills` `vue` `svelte` `angular` `solidjs`</sub>
