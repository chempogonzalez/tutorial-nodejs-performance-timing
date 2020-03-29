# Tutorial NodeJS Performance Timing

[![standard-readme compliant](https://img.shields.io/badge/readme%20style-standard-brightgreen.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
[![Twitter: JoseJ_PR](https://img.shields.io/twitter/url?color=1991DA&label=Twitter%20%40JoseJ_PR&logo=twitter&logoColor=FFFFFF&style=flat-square&url=https%3A%2F%2Ftwitter.com%2FJoseJ_PR)](https://twitter.com/JoseJ_PR)
[![Github: Sponsors](https://img.shields.io/twitter/url?color=032f62&label=Github%20Sponsors%20%40JoseJPR&logo=github&logoColor=FFFFFF&style=flat-square&url=https%3A%2F%2Fgithub.com%2Fsponsors%2FJoseJPR)](https://github.com/sponsors/JoseJPR)

![Banner](./assets/banner.png)

## 🔖 Description

The **⏳Startup Time** for an HTTP server is very important. The time it takes for the NodeJS application to be running will also depend on the time it takes to import the modules that the application needs.

The Performance Timing API provides an implementation of the W3C Performance Timeline specification. The purpose of the API is to support collection of high resolution performance metrics.

With this Tutorial you can create a NodeJS Application CLI for get the time that the require function need for each module.

Official Documentation: [NodeJS | Performance Timing API](https://nodejs.org/api/perf_hooks.html)

## 📹 Video Demo

The following video shows how you can get the time that the require function need for each module.

[![Video](./assets/youtube.svg)](https://youtu.be/XXXXXXXXXXXXXX)

## ⛅️ Develop in the Cloud

You can run this project in Gitpod, a one-click online IDE for GitHub:

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/JoseJPR/tutorial-nodejs-performance-timing)

## 📌 Methodologies and Guidelines

List of methodologies and tools used in this project for compliance with Quality Assurance Code (QAC)

* ESTlint, tool for identifying and reporting on patterns found in ECMAScript/JavaScript code. \
  [NPM ESLint](https://www.npmjs.com/package/eslint) \
  [NPM ESLint | Airbnb](https://www.npmjs.com/package/eslint-config-airbnb)

## ✅ Prerequisites

In order to work with this project, your local environment must have at least the following versions:

* NodeJS Version: 13.xx
* NPM Version: 6.12.0

## 📐 How to work with this project

You have to do the following steps to be able to work with this project.

### 1️⃣ Install NodeJS Dependencies

To work with this project locally it is necessary to install the NPM dependencies.

```bash
# Install npm dependencies
$npm i
```

### 2️⃣ Run

```bash
# Run Application
$npm run start
```

## 📂 Code scaffolding

```any
/
├── assets 🌈               # Images Sources.
├── src 📦                  # Main App with Server and Client.
|   ├── first-demo          # Demo with broadcast demo server sending randoms message to all clients.
|   ├── second-demo         # Demo with a client sending random message via server to all other clients.
|   └── ...
└── ...
```

## ⛽️ Review and Update Dependences

For review and update all npm dependences of this project you need install in global npm package "npm-check-updates" npm module.

```bash
# Install and Run
$npm i -g npm-check-updates
$ncu
```

## License

[MIT](LICENSE.md)

## Happy Code

Created with JavaScript, lot of ❤️ and a few ☕️

## This README.md file has been written keeping in mind

[GitHub Markdown](https://guides.github.com/features/mastering-markdown/) \
[Emoji Cheat Sheet](https://www.webfx.com/tools/emoji-cheat-sheet/)