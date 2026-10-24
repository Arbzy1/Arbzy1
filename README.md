## Aden Butt

I build and ship full stack web apps on the cloud, with React and TypeScript front ends and Hono APIs on Cloudflare Workers backed by Postgres. I have taken my own projects from the first commit to live production, with CI/CD pipelines, automated tests and separate staging and production environments.

Computer Science graduate (BSc 2:1, Cardiff University), and I have just finished an MSc in Artificial Intelligence at Cardiff. Based in Epsom, Surrey.

### Live projects

| Project | What it is |
| --- | --- |
| **Locations** · [repo](https://github.com/Arbzy1/locations) · [live](https://locations.aden.website) | A private explorer for your Google Timeline: heatmaps, day views, trips and insights. Runs on Cloudflare Workers (R2, Queues, cron triggers) with Neon Postgres and row-level security, Drizzle, Better Auth, React and MapLibre, and deploys to staging and production through GitHub Actions. I started it and co-develop it with [@Hum2a](https://github.com/Hum2a). My parts include the browser import pipeline, train detection from raw GPS, the privacy controls and the GPX, GeoJSON and CSV exports. |
| **Kerbside** · [live](https://kerbside.aden.website) | A public data explorer for my transport research across twelve UK cities. TypeScript monorepo with a React 19 front end and a Hono API on Cloudflare Workers, reading Neon Postgres through Drizzle. Every change is typechecked, linted and tested with Vitest and Playwright, and every deploy migrates the database and runs a smoke test. Behind it is a Python pipeline (geopandas, OSMnx, scikit-learn) that ran several hundred model configurations over 2,334 Department for Transport count points. The source is private for now. |
| **aden.website** · [live](https://aden.website) | My portfolio. React 19 served from a Cloudflare Worker, with a Hono API and first-party analytics stored in Neon. |
| **location-score-analyzer** · [repo](https://github.com/Arbzy1/location-score-analyzer) | My BSc dissertation. A full stack web app that scores Cardiff neighbourhoods on real journey times, amenity access and the priorities the user sets. React, Flask, Firebase, OpenTripPlanner, OpenRouteService, GTFS and OpenStreetMap. |

### Earlier work

- [vegan-shoes-storefront](https://github.com/Arbzy1/vegan-shoes-storefront): a static storefront in hand-written HTML, CSS and vanilla JavaScript, with product pages, a cart and out-of-stock states. An early self-taught front end project.
- [unity-quiz-game](https://github.com/Arbzy1/unity-quiz-game): a quiz game in Unity and C#, built while learning the editor, scenes and UI scripting.

Some coursework and in-progress work is private.

### Tools I work with

**Web** TypeScript, JavaScript, React, Vite, Tailwind, HTML, CSS

**Back end** Hono, REST APIs, Node.js, Python, Flask

**Data** PostgreSQL (Neon), SQL, Drizzle (schema and migrations), pandas

**Cloud and DevOps** Cloudflare Workers, R2, Queues, GitHub Actions CI/CD

**Testing** Vitest, Testing Library, Playwright

**ML** scikit-learn, PyTorch

**Systems** Windows Server, Active Directory, DNS/DHCP, Git

### Contact

adenreh@gmail.com | [LinkedIn](https://www.linkedin.com/in/aden-butt-24b0a62a8/) | [aden.website](https://aden.website)
