# Vult Labs

Production website for **Vult** — a cinematic litigation visualization studio based in San Antonio, Texas.

**Live:** [vultlabs.com](https://vultlabs.com)

## Stack

- [Astro](https://astro.build) — static site generator
- [Vercel](https://vercel.com) — hosting and deployment
- [Bitter](https://fonts.google.com/specimen/Bitter) — serif typeface
- [FormSubmit](https://formsubmit.co) — form handling

## Project Structure

```
src/
├── assets/images/       # Optimized images (Astro Image)
├── components/
│   ├── CaseModal.astro  # Multi-step case intake modal
│   ├── Footer.astro
│   ├── Hero.astro
│   ├── Nav.astro
│   ├── WorkDetailHero.astro
│   └── WorkSection.astro
├── layouts/
│   └── Base.astro
├── pages/
│   ├── index.astro      # Homepage
│   ├── about.astro
│   ├── privacy.astro
│   └── work/
│       ├── crash.astro
│       └── medical.astro
└── styles/
    └── global.css
public/
├── icons/               # SVG logos and arrow icons
├── favicon.svg
└── favicon.ico
```

## Development

```sh
npm install
npm run dev
```

## Build

```sh
npm run build
```

## Deployment

Pushes to `main` auto-deploy to Vercel.
