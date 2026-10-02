# resume-hub

[![Live Site](https://img.shields.io/badge/bryanhamilton.info-00d2ff?style=flat-square&logo=googlechrome&logoColor=white)](https://bryanhamilton.info)
[![License: MIT](https://img.shields.io/badge/license-MIT-3fb950?style=flat-square)](https://opensource.org/licenses/MIT)
[![vCard](https://img.shields.io/badge/vCard-Download-8b5cf6?style=flat-square&logo=contact&logoColor=white)](https://raw.githubusercontent.com/bryanhamiltondev/resume-hub/main/bryan-hamilton.vcf)

**Bryan Hamilton's resume hub** - the landing page that powers [bryanhamilton.info](https://bryanhamilton.info). Same guy. Two ways to hire him.

---

## The concept

This is the anchor of Bryan's professional presence. It's not a resume - it's a **choice point** for whoever lands here:

- **Hiring for an engineering role?** Click the tech door and get a full-stack web engineer with 28 years of production experience, 10 open-source repos extracted from live code, and zero-dependency discipline.
- **Hiring for a retail or service role?** Click the retail door and get a guest-service veteran who's worked registers, prep, and stocking at Walmart, Chick-fil-A, Wawa, Shake Shack, and ShopRite, available 24/7.

Same person. Two completely different resumes. One page that lets you self-select.

---

## What's in here

| File | Purpose |
|------|---------|
| `index.html` | The full landing page - markup, styles, and the 8-act jQuery animation suite all in one file |
| `bryan-hamilton.jpg` | Headshot |
| `bryan-hamilton.vcf` | [Download vCard](https://raw.githubusercontent.com/bryanhamiltondev/resume-hub/main/bryan-hamilton.vcf) - one-tap contact saving |

---

## The animation suite

The page loads with an 8-act jQuery intro sequence that runs once per session:

1. **Particle background** - 70 drifting cyan dots on a canvas with connection lines between nearby particles
2. **Floating gradient orbs** - two blurred color spheres (cyan + orange) that drift slowly across the background
3. **Entrance wiring** - every element starts invisible with a specific entrance direction (fade-down for tagline, fade-up for cards, scale-in for stats)
4. **Typewriter heading** - "Same guy. Two ways to hire him." types out character by character with a blinking cursor
5. **Staggered entrance chain** - tagline, bio, CTA buttons, cards, stats, contact section, footer each animate in sequence with smooth cubic-bezier transitions
6. **3D card tilt** - the two resume cards respond to mouse movement with perspective transforms that follow the cursor
7. **CTA pulse** - the tech button has a gentle breathing glow animation that loops
8. **Smooth scroll** - anchor links scroll instead of jump

All built with jQuery 3.7.1, no plugins, no frameworks.

---

## Why this exists as a repo

All 10 other repos in the [bryanhamiltondev](https://github.com/bryanhamiltondev) portfolio are production-derived *patterns* - reusable components extracted from The DJ Calendar that another developer could drop into their own project.

This one is different. It's the **showcase hub** - the page that ties everything together. It demonstrates:

- **Design sense** - dark theme, cyan/orange accent palette, typographic hierarchy, responsive layout
- **Animation craftsmanship** - jQuery motion design that doesn't feel gratuitous; every entrance has purpose and timing
- **Content strategy** - the "same guy, two ways to hire him" framing is the core idea that makes the whole dual-resume concept work
- **Zero-dependency delivery** - one HTML file, inline CSS, inline JS, no build step, no framework

---

## Related

- [bryanhamilton.info](https://bryanhamilton.info) - the live site
- [The DJ Calendar](https://thedjcalendar.com) - Bryan's flagship product
- [GitHub profile](https://github.com/bryanhamiltondev) - all 10 pattern repos
- [LinkedIn](https://linkedin.com/in/bryanhamilton-nj) - professional profile
- [vCard](https://raw.githubusercontent.com/bryanhamiltondev/resume-hub/main/bryan-hamilton.vcf) - download contact card
