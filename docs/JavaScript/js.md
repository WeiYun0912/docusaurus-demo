---
title: js (title)
description: A short description of this page
keywords: [keywords, describing, the main topics]
---

In JavaScript, trying to access properties on `null` will error.

```js
//highlight-next-line
const name = null;
//error
console.log(name.toUpperCase());
// Uncaught TypeError: Cannot read properties of null (reading 'toUpperCase')
```
