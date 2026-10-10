# shuklaji — the anatomy of a curious mind

Personal portfolio for [shuklaji.org](https://shuklaji.org): one hand-drawn thread that wanders through UPSC, code, crypto, products and philosophy, then drops you down the rabbit hole into all the work.

Design and code are based on the open-source [portfolio-template](https://github.com/SomehowLiving/portfolio-template) by Nidhi (MIT). The story, text and images here are Shuklaji's own.

## Run it

```
npm install   # or bun install
npm run dev
```

## Where to edit

- `src/routes/index.tsx`: the story, the talking objects, the featured work, contact links
- `src/routes/work.tsx`: all projects (the "more rabbit holes" page)
- `src/lib/seo.ts`, `public/llms.txt`, `public/sitemap.xml`: name, bio, email, site URL
- `src/assets/me.webp`: **placeholder silhouette. Replace with your own transparent cutout** with one hand raised at about 41% across / 2% down (that is where the thread ties on)
- `src/assets/project-*.webp`: placeholder cards for the three featured projects (1200×912)
- `public/og.png`, `favicon.ico`, `apple-touch-icon.png`: placeholders

## Content notes

- The timeline uses "chapter" labels instead of years. Reorder or add years in `timeline` in `index.tsx`.
- Social links: only Vocademy and the Vocademy app are linked. Add Telegram, GitHub or X in `LINKS` and the contact section of `index.tsx`.
