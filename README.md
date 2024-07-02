# Astro + Vue 3 Static Web Generator

Opinionated Astro + Vue 3 static web generator with Tailwind CSS.

```bash
npx degit acfatah/astro-vue-web my-website && \
  cd my-website && \
  npm install
```

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── components/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

We put our Vue componenets in `src/components/`.

Any static assets, like images, are placed in the `public/` directory.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                       |
| :------------------------ | :------------------------------------------- |
| `npm install`             | Installs dependencies                        |
| `npm run dev`             | Starts local dev server at `localhost:4321`  |
| `npm run build`           | Build your production site to `./dist/`      |
| `npm run preview`         | Preview your build locally, before deploying |
| `npm run lint`            | Run code linter on the project directory     |
| `npm run lint:fix`        | Apply available code fixes using the linter  |
| `npm run astro -- --help` | Get help using the Astro CLI                 |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
