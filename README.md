---

# isitworth.it

isitworth.it is a web application built using Astro and JavaScript that helps users compare options and make informed decisions by weighing the pros and cons of various choices.

## Motivation

I've often found myself needing to weigh the pros and cons of various choices, whether it’s evaluating a new technology, making a purchase, or other important decisions. Each time, I had to manually list the advantages and drawbacks to assess them effectively. To streamline this process, I decided to build a tool that makes it easier to compare options and make informed decisions. This tool offers a clear, organized way to outline, compare, and analyze the key factors of any choice—turning decision-making into a more efficient and insightful process.

## How to Use

To get started, click the “App” button on the navigation. You can then add the options you want to compare and the factors you want to evaluate. For each factor, you can assign a weight to indicate its importance. After entering all the necessary information, the tool will calculate the total score for each option based on the factors and their weights. This will help you visualize the differences between the options and make a more informed decision.

## Project Structure

Inside the project, you'll find the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

- **public/**: Contains static assets like images.
- **src/components/**: Contains Astro/React/Vue/Svelte/Preact components.
- **src/layouts/**: Contains layout components.
- **src/pages/**: Contains `.astro` or `.md` files, each exposed as a route based on its file name.

## Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `npm run astro -- --help` | Get help using the Astro CLI                     |

## Technologies Used

The following technologies and libraries are used in this project, as listed in the `package.json` file:

### Dependencies
- **@astrojs/check**: "^0.9.4"
- **@astrojs/tailwind**: "^5.1.2"
- **astro**: "^4.16.6"
- **tailwindcss**: "^3.4.14"
- **typescript**: "^5.6.3"

### DevDependencies
- **prettier**: "^3.3.3"
- **prettier-plugin-astro**: "^0.14.1"

## Want to Learn More about Astro?

Feel free to check [our documentation](https://docs.astro.build) or join [Discord server](https://astro.build/chat).

---
