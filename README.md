![badge](https://img.shields.io/github/watchers/wdpedroborges/geo-quiz?style=social)
![badge](https://img.shields.io/github/stars/wdpedroborges/geo-quiz?style=social)
![badge](https://img.shields.io/github/license/wdpedroborges/geo-quiz)
![badge](https://img.shields.io/badge/powered%20by-vite-blue)
![badge](https://img.shields.io/badge/powered%20by-react.js-blue)
![badge](https://img.shields.io/badge/powered%20by-typescript-blue)
![badge](https://img.shields.io/badge/powered%20by-sass.js-blue)

# Geo Quiz
## A quiz based in the model Better Quiz

The quiz app made in React.js and Typescript is an excellent resource for those who want to learn more about the countries of the world. The app offers a wide range of quizzes that cover various topics related to different countries, including geography, history, culture, and more. Whether you are a student, a teacher, or just someone who loves learning, this app is a great way to expand your knowledge of the world and its many diverse cultures.

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