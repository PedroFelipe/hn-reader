# Hacker News Reader [![Build Status](https://travis-ci.org/PedroFelipe/hn-reader.svg?branch=master)](https://travis-ci.org/PedroFelipe/hn-reader)

![Hacker News Reader](screenshot.png)

Hacker News Reader is a challenge built in 48h. It consumes [HackerNews/API](https://github.com/HackerNews/API) to create a simple and beautiful interface that provides a nice experience focused on mobile reading.

## Demo
You'll find a demo hosted on Heroku: [nl-hn-reader.herokuapp.com](https://nl-hn-reader.herokuapp.com)

## Running
### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### `npm test`

Launches the test runner in the interactive watch mode.

### `npm run build`

Builds the app for production to the `build` folder.

## Folder Structure

```
hn-reader/
  README.md
  node_modules/
  package.json
  public/
    index.html
    favicon.ico
    manifest.json
  src/
    actions/
    components/
    constants/
    containers/
    css/
    decorators/
    reducers/
    index.css
    index.js
```

## What’s Inside?

* [React](https://facebook.github.io/react)
* [webpack](https://webpack.js.org)
* [Babel](http://babeljs.io)
* [Autoprefixer](https://github.com/postcss/autoprefixer)
* [ESLint](http://eslint.org)
* [Jest](http://facebook.github.io/jest)
* [Bulma](http://bulma.io)

## Features
- [x] Top Stories List
- [x] New, Best, Ask, Show and Job Stories lists
- [x] Single Story
- [x] Show 1st Level Comments

## TO-DO
- [ ] Increase tests coverage to 100%
- [ ] Show Child Comments
- [ ] Improve Placeholder Animation
- [ ] Cache Stories
- [ ] Pagination
