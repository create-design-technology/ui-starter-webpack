# Wordpress Plugin Boilerplate
Using webpack, babel, SCSS, autoprefixer, and the Redux Wordpress Framework for the admin settings panel.  babel-polyfill is setup so feel free to use async/await, spread operators, import/export, and all the great advantages of ES2017.

## Basic Usage Flow
1. Download or clone file to plugins folder
2. Run webpack using `npm start`
3. SCSS located in the `sass/` folder and compiled using `autoprefixer`.
4. `js/app.js` compiled from `src/js/main.js` using `babel-polyfill` and `uglifyjs-webpack-plugin`
