# svelte-template

Customized Svelte Template

### Features

-   SCSS Support
-   TypeScript Support
-   Source Maps for only development mode
-   `rollup-plugin-serve` in `rollup.config.js`

---

![SS](https://i.imgur.com/f8NcA12.png)

---

### How To Use

-   Run `npx degit berkinakkaya/svelte-template PROJECT_NAME`

### VS Code Notes

-   Install [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) extension or remove the `.prettierrc` file
-   Use the new [Svelte Extension](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode).
-   Set `Svelte > Language Server: Runtime` path for SCSS support ([Tutorial](https://daveceddia.com/svelte-with-sass-in-vscode/))
-   If you use Prettier, set Default Formatter on VS Code as `esbenp.prettier-vscode` and enable `Format On Save`

### Notes

-   TypeScript might complain about `tsconfig.json` till you run `npm install`, then restart the editor.
