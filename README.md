# Astro + Tailwind CSS v4 + TypeScript Template

A minimal, modern template for building fast websites using [Astro](https://astro.build/), [Tailwind CSS v4](https://tailwindcss.com/), and [TypeScript](https://www.typescriptlang.org/).

## 🚀 Features

- [Astro v5](https://astro.build/) - Fast static site generation with dynamic islands
- [Tailwind CSS v4](https://tailwindcss.com/) - Utility-first CSS framework
- [TypeScript](https://www.typescriptlang.org/) - Type-safety for your components and pages
- Responsive layouts with clean, semantic HTML
- Dark mode support
- SEO-friendly structure
- Minimal dependencies

## 🧞 Getting Started

### Prerequisites

- Node.js 18.14.1 or higher
- npm or another package manager

### Installation

1. Clone this repository
```bash
git clone https://github.com/yourusername/astro-template.git my-project
cd my-project
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

4. Build for production
```bash
npm run build
```

5. Preview production build
```bash
npm run preview
```

## 📁 Project Structure

```
/
├── public/            # Static assets
├── src/
│   ├── components/    # Reusable UI components
│   │   ├── Card.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   └── Hero.astro
│   ├── layouts/       # Page layouts
│   │   └── Layout.astro
│   ├── pages/         # File-based routing
│   │   ├── index.astro
│   │   ├── about.astro
│   │   └── 404.astro
│   └── styles/        # Global styles
│       └── global.css
├── astro.config.mjs   # Astro configuration
└── tsconfig.json      # TypeScript configuration
```

## 🧰 Customization

### Tailwind Configuration

Tailwind CSS v4 is configured directly in your CSS through `@import "tailwindcss"`.

### TypeScript Support

TypeScript is included and configured for better developer experience. Type-checking is available through:

```bash
npm run check
```

## 📝 License

MIT

```sh
npm create astro@latest -- --template minimal
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/minimal)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/minimal)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/minimal/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
├── src/
│   └── pages/
│       └── index.astro
└── package.json
```

Astro looks for `.astro` or `.md` files in the `src/pages/` directory. Each page is exposed as a route based on its file name.

There's nothing special about `src/components/`, but that's where we like to put any Astro/React/Vue/Svelte/Preact components.

Any static assets, like images, can be placed in the `public/` directory.

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

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
