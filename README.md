# vueBootstrap
 学习使用 vue 和 bootstrap 进行前端开发

## 安装
1. npm init vite `project-name`
2. cd `project-name` (如果是当前目录就不用)
3. npm install
4. 新版本 npm 会报 Error: esbuild: Failed to install correctly错误，解决办法：执行 `node node_modules/esbuild/install.js`
5. npm run dev
6. 安装 bootstrap，执行： `npm install bootstrap jquery popper.js -s`
7. 在 main.ts 中引入
```import "jquery"```
```import "bootstrap"```
```import "bootstrap/dist/css/bootstrap.min.css"```
8. 在 components 里面创建模板
9. 在 App.vue 中引入模板
10. 安装 scss功能：`npm install scss -s`
11. 在 main.ts 引入 scss 文件













# Vue 3 + Typescript + Vite

This template should help get you started developing with Vue 3 and Typescript in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur). Make sure to enable `vetur.experimental.templateInterpolationService` in settings!

### If Using `<script setup>`

[`<script setup>`](https://github.com/vuejs/rfcs/pull/227) is a feature that is currently in RFC stage. To get proper IDE support for the syntax, use [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) instead of Vetur (and disable Vetur).

## Type Support For `.vue` Imports in TS

Since TypeScript cannot handle type information for `.vue` imports, they are shimmed to be a generic Vue component type by default. In most cases this is fine if you don't really care about component prop types outside of templates. However, if you wish to get actual prop types in `.vue` imports (for example to get props validation when using manual `h(...)` calls), you can use the following:

### If Using Volar

Run `Volar: Switch TS Plugin on/off` from VSCode command palette.

### If Using Vetur

1. Install and add `@vuedx/typescript-plugin-vue` to the [plugins section](https://www.typescriptlang.org/tsconfig#plugins) in `tsconfig.json`
2. Delete `src/shims-vue.d.ts` as it is no longer needed to provide module info to Typescript
3. Open `src/main.ts` in VSCode
4. Open the VSCode command palette
5. Search and run "Select TypeScript version" -> "Use workspace version"
