# IBDS — Integrated Business & Digital Services Portfolio

A modern, luxury-dark portfolio website built with **Next.js 14**, **TypeScript**, and **Tailwind CSS**.

## Pages
- `/` — Home (Hero, Services preview, Why Us, CTA)
- `/about` — About Us (Mission, Values, Business Profile)
- `/services` — Core Services (5 detailed service sections)
- `/contact` — Contact Us (Enquiry form, Company info, FAQ)

## Design
- **Aesthetic**: Refined luxury dark — obsidian black + warm gold
- **Typography**: Cormorant Garamond (display) + DM Sans (body) + DM Mono (accents)
- **Fully responsive**: Mobile-first layout

## Getting Started

### 1. Install dependencies
```bash
npm install
```

### 2. Run development server
```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000)

### 3. Build for production
```bash
npm run build
npm start
```

## Customization

### Colors (tailwind.config.ts)
- `gold` / `gold-light` / `gold-dark` — brand accent colors
- `obsidian` / `carbon` / `graphite` — background tones

### Content
All content is in the page files under `/app`:
- `/app/page.tsx` — Home
- `/app/about/page.tsx` — About
- `/app/services/page.tsx` — Services
- `/app/contact/page.tsx` — Contact

### Fonts
Google Fonts loaded via `app/globals.css`. Change the `@import` URL to swap fonts.

## Deployment

Deploy instantly on **Vercel**:
1. Push to GitHub
2. Import to [vercel.com](https://vercel.com)
3. Deploy

Or deploy on **Netlify**, **Railway**, or any Node.js host.

---
© 2026 Integrated Business & Digital Services
