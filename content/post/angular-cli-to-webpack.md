---
date: 2017-03-01T10:16:05+09:00
tags:
- Angular CLI
- Webpack
title: Moved to Webpack from Angular-CLI
---

I recently migrated the Portfolio Manager Angular UI to build using [webpack](https://webpack.js.org/) rather than
Angular CLI as I was having issues with upgrading some of my npm packages and needed more
control over the build process.

Angular CLI was great at bootstrapping me with Angular and getting the project up and
running first, but it is still in beta and perhaps needs a bit more work before I will
consider it for production builds.

Luckily it is pretty easy to extract a webpack configuration from the angular-cli.json by running
`ng eject`, from there you can customise appropriately.
