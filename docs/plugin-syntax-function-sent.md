---
id: babel-plugin-syntax-function-sent
title: babel-plugin-syntax-function-sent
sidebar_label: syntax-function-sent
---

## Installation

```sh
npm install --save-dev @babel/plugin-syntax-function-sent
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["@babel/plugin-syntax-function-sent"]
}
```

### Via CLI

```sh
babel --plugins @babel/plugin-syntax-function-sent script.js
```

### Via Node API

```javascript
require("@babel/core").transform("code", {
  plugins: ["@babel/plugin-syntax-function-sent"]
});
```

