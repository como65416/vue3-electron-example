## Vue 3 + Electron JS (透過 vue-cli)

1. [使用 Vue cli 建立 vue 3 專案](https://github.com/como65416/vue3-electron-example/commit/a0d0fcb3ff35ef08435502421835e73fb96a8cc9)

※ [Vue Cli](https://cli.vuejs.org/) 這邊示範版本是 `@vue/cli 4.5.11`

```sh
vue create vue3-electron-project
```

2. [升級 vue 3 版本](https://github.com/como65416/vue3-electron-example/commit/b2ba308d3ff2994acf5a93532d450b8cfc17defa)

```sh
npm install --save vue@next
```

3. [安裝 Vue CLI Plugin Electron Builder](https://github.com/como65416/vue3-electron-example/commit/a3b6c922c42ee6c186987d484105deac1db45b7e)

Vue CLI Plugin Electron Builder：[連結](https://nklayman.github.io/vue-cli-plugin-electron-builder/)

```sh
vue add electron-builder
```

4. [升級 electron 版本](https://github.com/como65416/vue3-electron-example/commit/2f7af408d0b565623fe00a83f8755692bead6413)

```sh
npm install --save-dev  electron@latest
```

5. [非必要] [webpack 設定 electron-renderer, background.js 啟用 nodejs 功能與關閉 CORS 檢查](https://github.com/como65416/vue3-electron-example/commit/652e04ef2ee705553aa01e97b2306bc2229c75b0)

- 可以使用 Node.js 相關功能
- call API 不會因 CORS 而被擋下

6. [安裝 Element UI Plus](https://github.com/como65416/vue3-electron-example/commit/dec5bb45b74f98748428c9e1ca5685c8e7117b67)
