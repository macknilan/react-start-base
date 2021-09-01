![react-babel-webpack](/covers/react-js-base.png)

### 🎯 Used technologies:

- ReactJS
- Webpack
- Babel
- Eslint
- Prettier
- [Husky](https://typicode.github.io/husky/#/) # TODO
- SCSS
- [file-loader](https://github.com/webpack-contrib/file-loader) # TODO

### 🎯 Plugins Babel

- babel-loader
- @babel/preset-env
- @babe/preset-react
- @babel/core

### 🎯 Plugins Webpack

- css-loader
- mini-css-extract-plugin

### 🎯 Plugins Eslint

- eslint
- babel-eslint
- eslint-config-airbnb
- eslint-plugin-import
- eslint-plugin-jsx-a11y
- eslint-plugin-react

### 🎯 Plugins Prettier

- prettier
- eslint-plugin-prettier
- eslint-config-prettier

### ⚙️ How To Use

To clone and run this application, you'll need **GIT** and **NodeJS** (which comes with npm) installed on your computer. From your command line:

```bash
  # Clone this repository
  $ git clone https://github.com/efrenmartinez/react-js-base.git

  # Go into the repository
  $ cd react-js-base

  # Install dependencies
  $ npm install

  # Run the app
  $ npm run start

  # Open in browser
  # http://localhost:3005/
```

### 🎨 Format code with Prettier

```bash
  # Format code
  $ npm run format

  # output
  > react-js-base@1.0.0 format /home/react-js-base
  > prettier --write '{*.js,*scss,src/**/*.{js,jsx,scss}}'

  src/assets/styles/App.scss 29ms
  src/components/App.jsx 26ms
  src/components/HelloWorld.jsx 8ms
  src/index.js 5ms
  webpack.config.js 12ms
```

### 🚩 Lint project

```bash
  # Lint
  $ npm run lint # TODO
```

### 🚀 Deployment

To deploy this project run

```bash
  # Build
  $ npm run build
```
