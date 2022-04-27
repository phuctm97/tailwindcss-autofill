# 🎨 tailwindcss-autofill

[![npm version][npm badge]][npm url]
[![GitHub license][license badge]][license url]

TailwindCSS variant to style autocompleted form fields.

## Requirements

- Node.js 12+

- TailwindCSS 2+

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

## Contributing

### Requirements

- Node 12+

- Yarn 1.22+

### Setup

1. Install requirements

2. Clone the repository

3. Run `yarn` to install dependencies

### Develop

- Commit adhering to [Angular commit convention](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#commit), use `yarn commit` or [Code conventional commits](https://marketplace.visualstudio.com/items?itemName=vivaxy.vscode-conventional-commits) to commit interactively

- Submit a PR and make sure required status checks pass

- When a PR is merged or code is pushed to `master`, Github automatically builds and publishes a new release if there're relevant changes

---

Made by [@phuctm97].

<!-- Badges -->

[npm badge]: https://img.shields.io/npm/v/tailwindcss-autofill?logo=npm
[license badge]: https://img.shields.io/github/license/phuctm97/tailwindcss-autofill
[npm url]: https://www.npmjs.com/package/tailwindcss-autofill
[license url]: /LICENSE

<!-- Links -->

[@phuctm97]: https://phuctm97.com
