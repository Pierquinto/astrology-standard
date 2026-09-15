# Astrology Standard

An opinionated, dependency-light Astro starter for fast content-first sites. It includes semantic CSS tokens for the Astrology Style Guide, a typed article collection, SEO foundations and a static-first configuration.

## Use it

Create a repository from this GitHub template, then run `npm install` and `npm run dev`.

Use Node 22.12+ and update Astro with `npx @astrojs/upgrade`.

## Principles

- Keep interactivity opt-in: no client framework is shipped.
- Edit `src/styles/tokens.css` for global visual decisions.
- Add content under `src/data/articles/`; validate it through `src/content.config.ts`.
- Use Astro `<Image>` or `<Picture>` for editorial images.
