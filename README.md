# Blendo Agency — Website

Website design mockups, content, and brand reference for [blendoagency.com](https://blendoagency.com).

## Structure

```
blendo-website/
├── mockups/              ← HTML/CSS mockups (open in any browser)
│   ├── index.html        ← Landing page linking to all mockups
│   ├── homepage.html     ← Homepage (v4 — with visuals + animations)
│   ├── services.html     ← Services hub with accordion sections
│   ├── about.html        ← Brand-focused about page
│   ├── work.html         ← Case study listing + single template
│   ├── contact.html      ← Contact form + Calendly placeholder
│   └── blog.html         ← Blog listing + newsletter signup
├── content/              ← Extracted copy (edit text here)
│   ├── homepage.md
│   ├── services.md
│   ├── about.md
│   ├── work.md
│   ├── contact.md
│   └── blog.md
├── brand/                ← Brand guide + design tokens
│   ├── brand-guide.docx  ← Full brand identity & voice guide
│   └── design-tokens.md  ← Colours, fonts, spacing, patterns
└── README.md
```

## Quick Start

1. Open `mockups/index.html` in your browser to see all pages
2. Edit copy in the `content/` markdown files
3. Reference `brand/design-tokens.md` for colours, fonts, and spacing

## Deploy Mockups (optional)

Push this repo to GitHub and connect to [Netlify](https://netlify.com) or [Vercel](https://vercel.com):
- Set build directory to `mockups/`
- No build step needed — it's static HTML

## Production Build

The production site will be built with **Astro** + **Tailwind CSS** using these mockups as the design reference. The Astro project will be added to this repo when development begins.

## Brand Quick Reference

| Token          | Value                  |
|----------------|------------------------|
| Primary        | `#364CFF`              |
| Accent Green   | `#06D6A0`              |
| Accent Coral   | `#FF6B6B`              |
| Dark base      | `#0F172A`              |
| Light base     | `#F8FAFC`              |
| Headings       | Plus Jakarta Sans 800  |
| Body           | DM Sans 400/500        |
| Data/mono      | Space Mono 400/700     |

## Status

- [x] Brand identity & voice guide
- [x] Homepage mockup (v4)
- [x] Services page mockup
- [x] About page mockup
- [x] Case studies page mockup
- [x] Contact page mockup
- [x] Blog page mockup
- [x] Content extracted to markdown
- [ ] Copy review & refinement
- [ ] Astro production build
- [ ] Deployment
