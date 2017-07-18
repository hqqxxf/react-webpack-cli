# react-webpack-cli

![React](https://img.shields.io/badge/react-%5E15.6.1-brightgreen.svg)
![Redux](https://img.shields.io/badge/redux-%5E3.7.0-brightgreen.svg)
![webpack](https://img.shields.io/badge/webpack-%5E2.x.x-brightgreen.svg)
![MIT](https://img.shields.io/dub/l/vibe-d.svg?style=flat-square)

> A SPA template with React, like vue-cli.


## Features
 - **React 15.6.1**
 - **Redux 3.7.0**
 - **react-redux 5.0.3**, to bind React and Redux.
 - **react-router v4 or v3**, choose the one you are familiar with.
 - **JSX**
 - **PWA**
 - **ES6**, support [`stage-1`](http://babeljs.io/docs/plugins/preset-stage-1/) by default.
 - **webpack 2.x**
 - **Express**, the dev-server.
 - **Hot-Reload**, support both React and Redux!
 - **Proxy**
 - **Environmental value**
 - **ESlint**, with [`standard`](https://github.com/feross/standard/blob/master/RULES.md#javascript-standard-style) and [`standard-react`](https://github.com/feross/eslint-config-standard-react).
 - **Redux-devtools**, to make the stores more clear
 - **bundle-analyzer**
 - **jest** with Enzyme, to make unit test for react components easier.

## Usage

```bash
# install sao first
npm install -g sao

# download the template
sao hqqxxf/react-webpack-cli new-project --install

# if you would like to try React 16
sao hqqxxf/react-webpack-cli#next new-project --install

# install all this dependencies.
cd new-project
npm install

# development, default port: 8080
npm run dev

# production
npm run build

# build with report
npm run build --report

# lint the files (if use eslint)
npm run lint

# run all tests
npm test
```
