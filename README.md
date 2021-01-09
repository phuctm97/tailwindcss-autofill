# 🎨 tailwindcss-autofill

[![npm version][npm badge]][npm url]
[![GitHub license][license badge]][license url]

TailwindCSS variant to style autocompleted form fields.

## Install

```bash
yarn add tailwindcss-autofill
```

Or if you use `npm`:

```bash
npm i --save tailwindcss-autofill
```

## Usage

Add to `plugins` in your **tailwind.config.js**:

```js
module.exports = {
  // ...
  plugins: [
    require("tailwindcss-autofill"),
    // Other plugins.
  ],
  variants: {
    extend: {
      borderColor: ["autofill", "dark"], // Enable `autofill` variant for plugins you want.
    },
  },
};
```

Style your components using `autofill:`:

```jsx
<input className="border border-gray-100 autofill:border-gray-900" />
```

## Requirements

- Node.js 12+

- TailwindCSS 2

---

Made by [@phuctm97].

<!-- Badges -->

[npm badge]: https://img.shields.io/npm/v/tailwindcss-autofill?logo=npm
[license badge]: https://img.shields.io/github/license/phuctm97/tailwindcss-autofill
[npm url]: https://www.npmjs.com/package/tailwindcss-autofill
[license url]: /LICENSE

<!-- Links -->

[@phuctm97]: https://phuctm97.com
