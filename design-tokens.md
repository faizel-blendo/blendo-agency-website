# Blendo Agency — Design Tokens

## Colour Palette

| Role           | Name             | Hex       | Usage                                    |
|----------------|------------------|-----------|------------------------------------------|
| Primary        | Electric Indigo  | `#364CFF` | Headlines, CTAs, links, primary actions  |
| Accent A       | Neon Green       | `#06D6A0` | Positive stats, success states, highlights |
| Accent B       | Hot Coral        | `#FF6B6B` | Attention points, hover states, secondary CTAs |
| Dark base      | Midnight Navy    | `#0F172A` | Hero backgrounds, dark sections          |
| Light base     | Snow             | `#F8FAFC` | Body backgrounds, light sections         |
| Background     | Off White        | `#F7F7F7` | Alternating section backgrounds          |
| Text (dark bg) | White            | `#FFFFFF` | Body text on dark backgrounds            |
| Text (light bg)| Near Black       | `#0A0A0A` | Headings on light backgrounds            |
| Text secondary | Gray             | `#6B6B6B` | Body text, descriptions                  |
| Text tertiary  | Light Gray       | `#A0A0A0` | Labels, captions, meta text              |
| Borders        | Border Gray      | `#E5E5E5` | Dividers, card borders, rules            |

## Typography

| Role        | Font               | Weight    | Usage                                |
|-------------|-------------------|-----------|--------------------------------------|
| Headings    | Plus Jakarta Sans | 800       | Page titles, section headings, hero  |
| Sub-heads   | Plus Jakarta Sans | 700       | Card titles, accordion headers       |
| Body        | DM Sans           | 400 / 500 | Paragraphs, descriptions, form text  |
| Data        | Space Mono        | 400 / 700 | Stats, labels, tags, monospace accents |

### Font Sizes (reference from mockups)
- Hero h1: clamp(3rem, 7vw, 5.5rem)
- Page h1: clamp(2.8rem, 5.5vw, 4.5rem)
- Section title: clamp(2rem, 4vw, 3.2rem)
- Card title: 1.1rem – 1.3rem
- Body: 0.9rem – 1.15rem
- Labels/tags: 0.65rem – 0.75rem (Space Mono, uppercase, letter-spacing: 2-3px)

## Spacing
- Section padding: 7rem vertical, 3rem horizontal
- Max content width: 1100px
- Card padding: 2rem – 2.5rem
- Grid gaps: 1.5rem – 2rem
- Border radius: 6px – 8px (subtle, not rounded)

## Interactive Patterns
- Scroll reveal: fade up 40px, 0.8s ease, staggered delays (0.1s increments)
- Hover on service rows: indent left 1–1.5rem
- Hover on cards: translateY(-4px to -6px)
- Stat counters: count up animation on scroll into view (1.5s, ease-out cubic)
- Menu overlay: full-screen black, links slide up staggered, 0.5s cubic-bezier

## Design Direction
- Editorial / clean style inspired by dasburo.nl
- Typography and white space do the heavy lifting
- Colour is used as accent, not flood
- Minimal imagery — mock dashboards and abstract visuals over stock photos
- Dark sections for contrast (hero, process, CTA)
- Light sections for content (services, about, blog)
