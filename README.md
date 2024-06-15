# React Configuration | Webpack + Babel

#### If you don't want to make create-react-app or build vite or others builds you can setup react + webpack + babel to has the total control

### step 01

```console
npm install -D babel-loader css-loader html-webpack-plugin style-loader webpack webpack-cli webpack-dev-server
```

### explanation
#### You will install webpack , webpack-cli , webpack-dev-server to has a server and bundler to load all files
#### You will install css-loader , style-loader as loaders for a css
#### You will isntall babel-loader as webpack loader for load babel for transpilling ecnascript language and react langauge
#### Finally you will install html-webpack-plugin as a webpack plugin for show html files



### step 02

```console
npm install @babel/core @babel/preset-env @babel/preset-react
```

#### You will install babel transpiling , preset-env to transpiling ecmascript , preset-react transpiling react



### step 03

```console
npm install react react-dom
```
#### You will install react javascript library and react dom for jsx

### step 04 | Configuration files
#### create .babelrc into root to config babel and presets
#### create index.html file into root to show application
#### create webpack.config.js into root to config webpack include webpack server, webpack loaders, webpack plugin
#### create a source (src) folder
#### create a index.js file into source (src) folder

### step 05 | create scripts into package.json
#### Inside scripts key write: "start": "webpack-dev-server --mode development --open --hot",
#### Inside scripts key write: "build": "webpack"
#### You will build application and you start the webpack server

```console
npm run build
npm run start
```

### Webserver with React start http://localhost:9000