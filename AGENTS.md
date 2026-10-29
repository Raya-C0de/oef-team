
# AGENTS.md

## Project

- Website for Creative Coding Kortrijk (CCK), a community where art and code meet.
- Audience: artists, designers, programmers and curious people, from beginners to professionals, who want to join workshops, meetups and events.
- Pages: home (`index.astro`), news (`news.astro`) and about (`about.md`).
- Content: workshops (pen plotter, p5.js, Max/MSP), foundations (the community's pillars) and team members.

## Stack & constraints

- Astro 7 (`astro` is the only framework dependency).
- Content collections in `src/content.config.ts` with the `glob` loader and zod schemas:
  - `workshops`: `title`, `image`
  - `team`: `name`, `function`, `bio`, `pic`
  - `foundations`: `title`, `description`
- Content lives as Markdown in `src/content/<collection>/`.
- Components in `src/components/`, layouts in `src/layouts/` (`Base.astro`, `Markdown.astro`).
- Plain CSS, no CSS framework: `src/styles/reset.css`, `global.css`, `markdown.css` plus scoped `<style>` in components, using CSS custom properties (e.g. `--sp-l`, `--fs-5`).
- Font: Space Grotesk via `@fontsource-variable/space-grotesk`.
- Scripts: `npm run dev` (with `--host`), `npm run build`, `npm run preview`.
