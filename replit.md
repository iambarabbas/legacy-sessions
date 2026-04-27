# Conversations Captured

A static HTML marketing website for a service that records conversations between people to preserve their voices and stories.

## Project Structure

- `index.html` — Home page
- `about.html` — About page
- `contact.html` — Contact page
- `blog.html` — Blog index
- `blog/` — Individual blog posts
- `images/` — WebP images for hero, gallery, and process sections

## Tech Stack

- Plain HTML + Tailwind CSS (loaded via CDN)
- Google Fonts (Newsreader, Manrope, Material Symbols)
- No build step, no backend

## Development

The site is served as static files via Python's built-in HTTP server on port 5000.

Workflow: `Start application` runs `python3 -m http.server 5000 --bind 0.0.0.0`.

## Deployment

Configured for static deployment with the project root as the public directory.
