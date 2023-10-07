# Getting Started with Frontend ReactJs

 * step-1 :

### Create a react app with tailwindCSS

1. in the terminal, create react app.
```bash
 npx create-react-app my-project
cd my-project
```

2. Install tailwindcss
Install `tailwindcss` via npm, and then run the init command to generate your  `tailwind.config.js` file.

```bash
npm install -D tailwindcss
npx tailwindcss init
```
3. Configure your template paths
Add the paths to all of your template files in your `tailwind.config.js `file.

```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```









