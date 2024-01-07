[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=40&pause=1000&random=false&width=1100&height=70&lines=React+Online+Shop+%2B+Vite,+SCSS,+TS+and+React)](https://git.io/typing-svg)

<div align="center">
    <p>Hello, this is my template of online shop, which includes:</p>
    <a href='https://www.w3schools.com/typescript/typescript_intro.php' title="TypeScript" >
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-plain.svg" height="42" width="42" alt="typescript logo"  />
    </a>
    <a href='https://www.w3schools.com/react/react_intro.asp' title="React">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="42" width="42" alt="react logo"  />
    </a>
    <a href='https://www.w3schools.com/sass/sass_intro.php' title="Sass" >
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sass/sass-original.svg" height="42" width="42" alt="sass logo"  />
    </a>
    <a href='https://vitejs.dev/' title="Vite">
        <img src="https://upload.wikimedia.org/wikipedia/commons/f/f1/Vitejs-logo.svg" height="42" width="42" alt="git logo"  />
    </a>
    <a href='https://www.w3schools.com/html/html_intro.asp' title="HTML5" > 
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="42" width="42" alt="html5 logo"  />
    </a>
</div>

## Boring, but important information:

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

### Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
export default {
  // other rules...
  parserOptions: {
    ecmaVersion: "latest",
    sourceType: "module",
    project: ["./tsconfig.json", "./tsconfig.node.json"],
    tsconfigRootDir: __dirname,
  },
};
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

## To set up this project:

If you want to load this project locally, follow these steps:

### First step: Check for `node` and `pnpm`

- To check, run the following commands in your terminal: `node -v` and `pnpm -v`
  - If you don't have `node` on your device, install it [here](https://nodejs.org/en)
  - If you don't have `pnpm`, run this command in your terminal: `npm install -g pnpm`

### Second step: Clone this repository

Run `https://github.com/baidikov-roman-mi/music-player`

And then `cd music-player`

### Third step: Local setup

Run `pnpm install` to install project dependencies

Then `pnpm add -D sass` to add sass

### And finally

Start the development server by running `pnpm run serve`. You'll get a message inside the terminal:

**Server running at http://localhost:5173/**
