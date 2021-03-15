# Usage
you can see the configuration [here](https://kodai3.github.io/tailwind-config/)

```
npm install @kodai3/tailwind-config
```

If you want to extend the existing config:

```js
// tailwind.config.js

module.exports = {
  presets: [require("@kodai3/tailwind-config")],
  theme: {
    extend: {
      padding: {
        4: "4px",
      },
    },
  },
};
```

If you want to use the config as is:

```js
// tailwind.config.js

module.exports = {
  presets: [require("@kodai3/tailwind-config")],
};
```
