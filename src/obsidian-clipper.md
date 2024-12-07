---
title: Obsidian Web Clipper
markmap:
  colorFreezeLevel: 2
---

- Source: https://github.com/obsidianmd/obsidian-clipper/tree/main
- Latest release: https://github.com/obsidianmd/obsidian-clipper/releases/tag/0.10.4

# [package.json](https://github.com/obsidianmd/obsidian-clipper/blob/main/package.json)

## 3rd party

### TODO: [@mozilla/readability](https://github.com/mozilla/readability)

### TODO: [DOMPurify](https://github.com/cure53/DOMPurify)

### TODO: [webextension-polyfill](https://github.com/mozilla/webextension-polyfill)

# [webpack.config.js](https://github.com/obsidianmd/obsidian-clipper/blob/main/webpack.config.js)

## plugins

### [copy-webpack-plugin](https://webpack.js.org/plugins/copy-webpack-plugin/)
- Copies individual files or entire directories, which already exist, to the build directory.

### mini-css-extract-plugin

### zip-extract-plugin

## entry

### popup: './src/core/popup.ts'

#### [dayjs](https://day.js.org/)

#### Template, Property, PromptVariable from types/types.ts

#### incrementStat, addHistoryEntry, getClipHistory from utils/storage-utils

### settings: './src/core/settings.ts'

### content: './src/content.ts'

### background: './src/background.ts'

### style: './src/style.scss'

### highlighter: './src/highlighter.scss',

