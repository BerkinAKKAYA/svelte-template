# svelte-template
Customized Svelte Template with TypeScript

### Features
* SCSS Support
* TypeScript Support
* Source Maps for only production
* `rollup-plugin-serve` in `rollup.config.js`

---

![SS](https://i.imgur.com/f8NcA12.png)

---

### Notes
* If you use VS Code, use the new Svelte Extension.
* TypeScript might complain about tsconfig.json till you run npm install then restart the editor.
* If you use Windows, replace the build script in package.json with rollup -c *(or replace only `rm -rf` section)*
* If you use VS Code, follow the instructions [here](https://daveceddia.com/svelte-with-sass-in-vscode/) for SCSS support
