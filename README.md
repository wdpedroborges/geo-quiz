![badge](https://img.shields.io/github/watchers/wdpedroborges/geo-quiz?style=social)
![badge](https://img.shields.io/github/stars/wdpedroborges/geo-quiz?style=social)
![badge](https://img.shields.io/github/license/wdpedroborges/geo-quiz)
![badge](https://img.shields.io/badge/powered%20by-vite-blue)
![badge](https://img.shields.io/badge/powered%20by-react.js-blue)
![badge](https://img.shields.io/badge/powered%20by-typescript-blue)
![badge](https://img.shields.io/badge/powered%20by-sass.js-blue)

# Geo Quiz
## A quiz based in the model Better Quiz

Geo Quiz is a quiz for those who have interest in learning more about the world. In this quiz, you will see flags, maps etc. about more than 200 countries.

## Live Demo

wdpedroborges.github.io/geo-quiz

## Features

- Filter questions by categories
- Suggestions
- Configurable timer
- Points counting
- Performance calculation
- Record storage in Local Storage
- Processes text, images, and audio

## Tech

- Vite
- React.js
- Typescript
- Sass

## Installation

Clone the repository:

```bash
git clone https://github.com/wdpedroborges/geo-quiz
```

For production:

```sh
cd geo-quiz
npm install
npm run dev
```

Debug in Typescript:

```bash
tsc --noEmit --watch
```

Build:

```bash
npm run build
```

## Deploy

- Add to vite.config.js:

```bash
base: "/<repo>/"
```

- Then:

```bash
npm install gh-pages --save-dev
```

- Add to package.json

```bash
 "homepage": "https://<username>.github.io/<repo>/",
  ...
  "scripts": {
...
"build": "vite build",
    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist",
...
```

## License

This project is licensed under the MIT License. Please see the LICENSE file for more details.