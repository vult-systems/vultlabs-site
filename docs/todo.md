# Vult Labs — Remaining TODO

## Must-Do (Blocking)

- [ ] **Add OG share image** — `public/og-default.jpg` (1200×630px). This is the image that shows when the site is shared on LinkedIn, Twitter, etc. Without it, shared links show a blank preview. Critical for ads.
- [ ] **Add Apple touch icon** — `public/apple-touch-icon.png` (180×180px). Referenced in `<head>` but file doesn't exist yet. Shows when someone saves the site to their phone home screen.
- [ ] **Activate Google Tag Manager** — Create a GTM container at tagmanager.google.com. Replace `GTM-XXXXXX` in `src/layouts/Base.astro` (appears twice — script + noscript). Uncomment both snippets. Once active, you can add Google Ads, Meta Pixel, LinkedIn Insight Tag, GA4, etc. without touching code.

## Should-Do (High Value)

- [ ] **Submit sitemap to Google Search Console** — Verify `vultlabs.com` at search.google.com/search-console, then submit `https://vultlabs.com/sitemap.xml`.
- [ ] **Build a custom 404 page** — Create `src/pages/404.astro`. Currently bad URLs get the default Astro/hosting 404. A branded page with a link back to home takes 5 minutes.
- [ ] **Replace media placeholders** — The Crash and Medical work sections (and homepage cards) use colored placeholder boxes. Swap in real renders/stills when available. Huge for SEO (image search) and conversions.

## Nice-to-Have

- [ ] **Claim LinkedIn company page** — Link back to `vultlabs.com` for domain authority.
- [ ] **Google Business Profile** — If applicable, claim and link for local SEO.
- [ ] **Run Lighthouse audit** — DevTools → Lighthouse tab on the live deployed URL. Will flag hosting-specific performance, accessibility, or SEO gaps.
- [ ] **Per-page OG images** — The `Base.astro` layout accepts an `image` prop. You can pass a unique share image per page (e.g., a crash render for `/work/crash`) for better social click-through.

## Reference

- **Copy source of truth:** `docs/copy.md`
- **GTM location:** `src/layouts/Base.astro` (search for `GTM-XXXXXX`)
- **Sitemap:** `public/sitemap.xml`
- **Robots:** `public/robots.txt`
- **Breakpoints:** 900px (tablet), 640px (phone) in `src/styles/global.css`
- **Form endpoint:** FormSubmit.co → `ops.vult@gmail.com`
