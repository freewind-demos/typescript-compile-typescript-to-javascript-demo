Compile TypeScript to JavaScript Demo
============================

如何把一个TypeScript文件编译为JavaScript文件

```
npm install
npx tsc hello.ts
```

There will be a `hello.js` generated, with such content:

```
"use strict";
exports.__esModule = true;
var lodash_1 = require("lodash");
console.log("Hello " + lodash_1.capitalize("typescript") + "!");
```