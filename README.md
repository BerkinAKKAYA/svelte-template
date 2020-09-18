# svelte-template
Customized Svelte Template with TypeScript

### Features
* SCSS Support
* TypeScript Support
* `rollup-plugin-serve` in `rollup.config.js`

---

![SS](https://i.imgur.com/f8NcA12.png)

---

### Notes
* Creates source maps only for development (npm run dev)
* If you use VS Code, use the new Svelte Extension.
* TypeScript might complain about tsconfig.json till you run npm install then restart the editor.
* If you use Windows, replace the build script in package.json with rollup -c