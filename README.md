# Webpack template
* `src` directory: `index.html`, `index.js`, `style.css`
* `npm init -y` --> installs `package.json`
* `npm install --save-dev webpack webpack-cli` --> installs `webpack` and `webpack-cli` 
* `npm install --save-dev html-webpack-plugin` --> installs `html-webpack-plugin`. Handles HTML
* `npm install --save-dev style-loader css-loader` --> installs `css-loader` and `style-loader`. Handles CSS
* `npm install --save-dev html-loader` --> installs `html-loader`. Handles image files referenced in our HTML template
* `npm install --save-dev webpack-dev-server` --> installs `webpack-dev-server` to handle live changes
* `webpack.config.js` file
* `.gitignore` Node template

Bundle: `npx webpack`
Run: `npx webpack serve`
