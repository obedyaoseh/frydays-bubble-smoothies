# Frydays Bubble & Smoothies Bar

A modern Next.js 16 marketing website for **Frydays Bubble & Smoothies Bar**, located in Teshie, Accra, Ghana.

## Stack

- **Framework**: Next.js 16 (App Router, Turbopack)
- **UI**: React 19, Tailwind CSS v4, shadcn/ui components
- **Animations**: Framer Motion, Lenis smooth scroll
- **Fonts**: Axiforma for brand/display type and Neuzeit for supporting copy (with system fallbacks until licensed font files are added)
- **Language**: TypeScript

## Brand

| Token | Value | Usage |
|-------|-------|-------|
| Forest Green | `#09403B` | Primary accent, dark sections, text |
| Warm Cream | `#F2DBB2` | Background, light sections, text on dark |

## Pages

| Route | File | Description |
|-------|------|-------------|
| `/` | `app/page.tsx` | Home — hero, menu carousel, bento grid, offerings, testimonials, gallery, footer |
| `/about` | `app/about/page.tsx` | About Us — story, mission, values, timeline |
| `/blog` | `app/blog/page.tsx` | Frydays Journal — stories, thoughts, community, ingredients, and discoveries |
| `/contact` | `app/contact/page.tsx` | Contact — form, map, opening hours, social links |
| `/esg` | `app/esg/page.tsx` | ESG — environment, health benefits, social pledge |
| `/order` | `app/order/page.tsx` | Product ordering — cart, quantities, pickup/delivery preference, order request |
| `/franchise` | `app/franchise/page.tsx` | Franchise and investment opportunities |

## Key Components

- `components/navigation.tsx` — Fixed nav with Frydays logo image, links to all pages
- `components/hero-section.tsx` — Landing hero with product image and stats
- `components/flavor-carousel.tsx` — Animated 5-item menu carousel
- `components/bento-grid.tsx` — 4-card feature grid (why Frydays)
- `components/activations-section.tsx` — Services/offerings cards
- `components/lifestyle-section.tsx` — Customer testimonials
- `components/social-section.tsx` — Gallery grid + Instagram CTA
- `components/footer.tsx` — Full footer with newsletter and links
- `components/about-content.tsx` — About page content
- `components/blog-content.tsx` — Frydays Journal content
- `components/contact-content.tsx` — Contact form + map
- `components/esg-content.tsx` — ESG/sustainability content
- `components/cart-provider.tsx` — Shared cart state persisted in localStorage
- `components/franchise-content.tsx` — Franchise and investment page

## Images

All brand images live in `public/images/`:
- `frydays-black.png` / `frydays-cream.png` — Brand logo variants for light and dark backgrounds
- `drink1.png` – `drink5.png` — Product photos (bubble tea, smoothies)
- `signature-*.jpg` — New signature drink and ingredient imagery for the homepage

## Running

```bash
npm run dev -- -p 5000
```

The dev server runs on port 5000. Workflow: **Start application**.

## User Preferences

- Maintain cream (#F2DBB2) and forest green (#09403B) brand palette
- Keep all design changes responsive
- Axiforma is the brand/display font; Neuzeit is the supporting/body font
- Location context: Teshie, Accra, Ghana
