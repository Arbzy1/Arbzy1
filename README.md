## Aden Butt

I build and ship full stack web apps on the cloud, with React and TypeScript front ends and Hono APIs on Cloudflare Workers backed by Postgres. I have taken my own projects from the first commit to live production, with CI/CD pipelines, automated tests and separate staging and production environments.

Computer Science graduate (BSc 2:1, Cardiff University), and I have just finished an MSc in Artificial Intelligence at Cardiff. Based in Epsom, Surrey.

### Live projects

| Project | What it is |
| --- | --- |
| **Locations** · [repo](https://github.com/Arbzy1/locations) · [live](https://locations.aden.website/) | A private explorer for your Google Timeline, with heatmaps, day views, trips and insights. Runs on Cloudflare Workers (R2, Queues and cron triggers) with Neon Postgres and row-level security, Drizzle, Better Auth, React and MapLibre. Deploys to staging and production through GitHub Actions. I started the project and built the core website and most of its features, including the browser import pipeline, train detection from raw GPS, privacy controls, heatmaps, journey lines, and GPX, GeoJSON and CSV exports. [@Hum2a](https://github.com/Hum2a) contributed additional features and improvements. |
| **Free parking finder** · [repo](https://github.com/Arbzy1/freeparkingfinder) · [live](https://freeparkingfinder.aden.website) | Published parking restrictions on a map. It reads council parking files for London boroughs, Epsom and Ewell and Cardiff, plus Transport for London red routes, and shows free, pay, permit and no-waiting bays in their own colours. Where a council only publishes a zone, it stays a zone rather than being shown as free parking. React and MapLibre, served from Cloudflare Workers. |
| **Kerbside** · [repo](https://github.com/Arbzy1/kerbside) · [live](https://kerbside.aden.website) | A public data explorer for my MSc transport research across twelve UK cities. TypeScript monorepo with a React 19 front end and a Hono API on Cloudflare Workers, reading Neon Postgres through Drizzle. Every change is typechecked, linted and tested with Vitest and Playwright, and every deploy migrates the database and runs a smoke test. Behind it is a Python pipeline (geopandas, OSMnx, scikit-learn) that ran several hundred model configurations over 2,334 Department for Transport count points; the research code is private for now. |
| **Location Score Analyzer** · [repo](https://github.com/Arbzy1/location-score-analyzer) · [live](https://locationscore.aden.website) | My BSc dissertation, now hosted. It ranks places to live in Cardiff on your own weekly journeys by car, bike, foot and bus, nearby schools, hospitals and supermarkets, and bus access. I moved it from self-hosted OpenTripPlanner and OpenRouteService servers to a Cloudflare Worker with Neon Postgres: bus journeys are pre-computed from Cardiff Bus timetables with RAPTOR, and other routes use openrouteservice. React, Mapbox GL and Firebase Auth. |
| **aden.website** · [live](https://aden.website) | My portfolio. React 19 served from a Cloudflare Worker, with a Hono API and first-party analytics stored in Neon. |

### Earlier work

- [vegan-shoes-storefront](https://github.com/Arbzy1/vegan-shoes-storefront): a static storefront in hand-written HTML, CSS and vanilla JavaScript, with product pages, a cart and out-of-stock states. An early self-taught front end project.
- [unity-quiz-game](https://github.com/Arbzy1/unity-quiz-game): a quiz game in Unity and C#, built while learning the editor, scenes and UI scripting.

Some coursework and in-progress work is private.

### Tools I work with

**Web** TypeScript, JavaScript, React, Vite, Tailwind, HTML, CSS

**Back end** Hono, REST APIs, Node.js, Python, Flask

**Data** PostgreSQL (Neon), SQL, Drizzle (schema and migrations), pandas

**Maps and geodata** MapLibre, Mapbox GL, OpenStreetMap, GTFS, openrouteservice, geopandas, OSMnx

**Cloud and DevOps** Cloudflare Workers, R2, Queues, GitHub Actions CI/CD

**Testing** Vitest, Testing Library, Playwright

**ML** scikit-learn, PyTorch

**Systems** Windows Server, Active Directory, DNS/DHCP, Git

### Contact

adenreh@gmail.com | [LinkedIn](https://www.linkedin.com/in/aden-butt-24b0a62a8/) | [aden.website](https://aden.website)
