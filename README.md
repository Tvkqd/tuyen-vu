# tuyen-vu

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup
1. Create a repo and clone it to local
2. Create a project and copy it to the git folder
   
```sh
npm create vue@latest
npm install
```
3. Commit and push all the changes
   
### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production
1. Adding base path inside vite.config.js - export default defineConfig()
   base: "/REPONAME/",
```sh
npm run build
```
2. Adding dist folder (-f is for removing dist from .gitignore)
```sh
git add dist -f
```
4. Commit the changes
```sh
git commit -m "Adding dist"
```
6. Creating gh-pages subtree
```sh
git subtree push --prefix dist origin gh-pages
```
