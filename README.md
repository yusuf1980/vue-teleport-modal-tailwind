# vue-components

This template should help get you started developing with Vue 3 in Vite.

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```

### Install Tailwind
    
    npm install -D tailwindcss postcss autoprefixer

### Create Tailwind Config and PostCSS

    npx tailwindcss init -p

Tailwind.config.js
...

    export default {
        content: [
            "./index.html",
            "./src/**/*.{vue,js,ts,jsx,tsx}",
        ],
        theme: {
            extend: {},
        },
        plugins: [],
    }

style.css(src/assets/main.css)

    @tailwind base;
    @tailwind components;
    @tailwind utilities;

    npm run dev

