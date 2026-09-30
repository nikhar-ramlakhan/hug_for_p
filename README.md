# A hug for Prelize

A reusable, mobile-friendly gift from Nikhar. Animated Portland → Johannesburg map journey, illustrated hug, surprise pink tulips and white lilies, and unlimited replays.

## Preview in VS Code

Open this folder in VS Code. With Python 3 installed, run `npm run dev` (or `python3 -m http.server 3000`) and open http://localhost:3000. Alternatively use VS Code's Live Server extension. No npm dependencies, backend, database, or API keys.

## Deploy to Vercel

Upload this folder to a GitHub repository, import that repository at https://vercel.com/new, choose **Other** as the Framework Preset, leave the Build Command empty, and set Output Directory to `.`. Deploy. The included vercel.json also sets these options.

Alternatively, with the Vercel CLI installed, run `vercel` in this folder and follow the prompts, then `vercel --prod`. Share the resulting link with Prelize. She can bookmark it and use it anytime.

## Continue with Codex in VS Code

Open this folder and ask Codex: “Continue this e-hug app. Preserve the complete journey, both illustrated characters, pink tulips and white lilies, mobile layout, reduced-motion support, and Vercel compatibility.”

## Customize

Edit the `text` object in app.js for messages. Update style.css for colors, typography, and motion. Image assets are local, so the app does not depend on external image services. No original personal photographs are included in the deployed app.

## Assets

Character and flower illustrations generated with OpenAI image generation from user-provided references. Character prompt: storybook chibi couple, man in black suit/black shirt/black tie, woman in burgundy sleeveless outfit, three equal panels showing standing and embracing poses. Bouquet prompt: pink tulips and white lilies in blush wrapping with deep pink ribbon.

Map geometry: Natural Earth 1:110m land data, public domain, https://www.naturalearthdata.com/about/terms-of-use/ . The animated line is a decorative delivery route, not a literal flight itinerary.
