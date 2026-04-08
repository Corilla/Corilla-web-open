# Corilla Website

Marketing site for [corilla.com](https://www.corilla.com), built with [Astro](https://astro.build) and [Tailwind CSS](https://tailwindcss.com), deployed to Vercel.

## Stack

- **Framework:** Astro 6 (static output)
- **Styling:** Tailwind CSS 4
- **Hosting:** Vercel (`@astrojs/vercel` adapter)

## Development

```sh
npm install
npm run dev      # start dev server
npm run build    # build static site
npm run preview  # preview production build
```

## Structure

- `src/pages/` — route-based pages (`index`, `about`, `contact`, `jobs`, `media`, `sitemap`, `thanks`, `404`)
- `src/components/` — reusable Astro components
- `src/layouts/` — page layouts
- `src/styles/` — global styles
- `public/` — static assets served at the site root (favicon, fonts, images, robots.txt)
