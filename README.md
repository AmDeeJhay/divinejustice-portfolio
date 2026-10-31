# DivineJustice Samuel · Portfolio

Personal portfolio of a Senior Frontend & Mobile Engineer, built for the **AWS Student Builder Challenge: Build Your Tech Superpower** and hosted on **AWS Amplify Hosting**.

**Live site:** _coming soon (Amplify URL)_

## What's inside

- **About Me**: who I am, what I build, and my experience timeline
- **Skills & Tools**: tech superpowers across web, mobile, and cloud
- **Projects**: featured work on the home page, the full list at `#/projects`
- **Creative feature**: _coming soon_
- Downloadable resume, dark mode, and a contact form that opens your email app

## Tech stack

React 19, TypeScript, Vite, Tailwind CSS v4, and Motion.

## AWS setup

| Service              | What it does here                                                       |
| -------------------- | ----------------------------------------------------------------------- |
| AWS Amplify Hosting  | Builds every push to `main` and serves the site over its global CDN     |

The build is defined in [`amplify.yml`](amplify.yml): install, type-check, build, then serve `dist/`.
Pages use hash routes (`#/projects`), so no rewrite rules are needed.

## Run locally

Requires Node.js 20+.

```bash
npm install
npm run dev      # http://localhost:3000
```

## Scripts

| Command           | What it does                    |
| ----------------- | ------------------------------- |
| `npm run dev`     | Start the dev server            |
| `npm run build`   | Production build into `dist/`   |
| `npm run preview` | Serve the production build      |
| `npm run lint`    | Type-check with `tsc`           |

## Editing content

- Profile, projects, experience, leadership, skills: [`src/data/portfolioData.ts`](src/data/portfolioData.ts)
- Tools grid: [`src/data/tools.ts`](src/data/tools.ts) (logos in `src/assets/tools/`)
- Project and community logos: `src/assets/images/`

## What I learned / challenges

_To be written after the build._
