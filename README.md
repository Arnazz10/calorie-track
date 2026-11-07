# daily.

A mobile-friendly, installable calorie and nutrition tracker. The food library includes Indian staples, everyday meals, fruit, vegetables, dairy, meat, vegetarian protein, nuts, and seeds. Saved meals and your calorie goal stay in this browser.

## Get started

Serve this folder from a local or production static web server. The app uses no build step or third-party packages. To use it offline after the first load, open it over HTTPS or localhost and let the service worker finish installing. On a phone, use the browser’s **Add to Home Screen** command to install it.

## Deploy to Vercel

This is a static site; it needs no build command or dependencies. The included `vercel.json` configures clean URLs and the service worker and web manifest headers.

1. In Vercel, choose **Add New → Project** and import `Arnazz10/calorie-track` from GitHub.
2. Keep the project root set to `./`, leave the Framework Preset as **Other**, and leave Build Command and Output Directory empty.
3. Select **Deploy**. Vercel will serve `index.html` from the project root. Future pushes to `main` will trigger deployments.

Alternatively, from the project root run `npx vercel` and follow the prompts, then run `npx vercel --prod` to publish to production.

Nutrition values are estimates per labelled serving. Home-cooked recipes, brands, ingredients, and preparation methods can substantially change calories and macros; use package labels or weighed recipe ingredients for higher accuracy.
