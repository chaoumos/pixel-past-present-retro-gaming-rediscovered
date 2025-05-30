
# Pixel Past Present: Retro Gaming Rediscovered - An AI Generated Astro Site

This Astro site was generated by an AI assistant for AstroHost.

## Theme & Objective
Discover hidden gems and forgotten lore in retro video games. Reviews, history, and community for classic gaming enthusiasts.
User Prompt: Design a retro-themed website called 'Pixel Past Present'. The site should be dedicated to retro video games from the 70s, 80s, and 90s. Include a prominent 'Reviews' section with detailed critiques and gameplay footage (placeholder images). A 'History' section should feature articles about the evolution of gaming. Also, a 'Community' forum or social media link page is a must. The visual style should emulate classic arcade cabinets and early computer interfaces, using pixel art, vibrant colors, and chiptune sound effects (optional). Target audience is nostalgic gamers and retro enthusiasts.

## Setup & Run

1.  **Install Dependencies:**
    ```bash
    npm install 
    # or yarn install, or pnpm install
    ```

2.  **Run Development Server:**
    ```bash
    npm run dev
    ```
    Open your browser at `http://localhost:4321` (or the port Astro assigns).

3.  **Build for Production:**
    ```bash
    npm run build
    ```
    The static files will be in the `dist/` directory, ready for deployment to Cloudflare Pages or other static hosts.

## Images
The articles currently use placeholder images from `https://placehold.co`. You should replace these with actual images relevant to your content.
The frontmatter of each article in `src/content/blog/` contains an `image` field with a `dataAiHint` attribute:
```yaml
image:
  url: 'https://placehold.co/800x400.png' # Update this to /images/your-image.jpg after placing it in public/images
  alt: 'Descriptive alt text for your image'   # Update this
  dataAiHint: 'relevant keywords' # This hint describes the intended image. Use it to find or generate a replacement.
```
Place your actual images in the `public/images/` directory and update the `url` in the frontmatter to be like `/images/your-image.jpg`.

## Cloudflare Pages Compatibility
This site is configured for static output by default (`output: 'static'` in `astro.config.mjs`), making it ready for deployment on Cloudflare Pages.
If SSR with Cloudflare was explicitly requested and the `@astrojs/cloudflare` adapter is included in `astro.config.mjs` and `package.json`, follow Cloudflare's instructions for deploying Astro SSR sites.

## Customization
- Explore `src/pages/` for page structure.
- Modify layouts in `src/layouts/`.
- Add or edit components in `src/components/`.
- Blog posts are in `src/content/blog/` (MDX or Markdown).
- Site configuration is in `astro.config.mjs`.
- Dependencies are in `package.json`.
- Tailwind CSS configuration is in `tailwind.config.mjs`.
- Global styles (if any beyond Tailwind) could be added in `src/styles/global.css` and imported in `BaseLayout.astro`.

Happy coding with your AI-generated Astro site!
  