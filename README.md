# Astro Starter Kit: Basics

```sh
npm create astro@latest -- --template basics
```

## 🚀 Project Structure

- To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).
- For more integrations, check out [integrations](https://astro.build/integrations)

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |
| `npx astro add --help`    | View list integrations                           |
| `npx astro add tailwind`  | Add Tailwind                                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).

## Tailwind

To add Tailwind, follow the steps from the [documentation](https://docs.astro.build/en/guides/styling/#tailwind)
Additionally, guide with [Tailwind docs](https://tailwindcss.com/plus/ui-blocks/documentation)

```bash
npx astro add tailwind
```

Import it in your files

```html
---
import "../styles/global.css";
---
```

## Icons

Use SVG icons from [tabler icons](https://tabler.io/icons)
