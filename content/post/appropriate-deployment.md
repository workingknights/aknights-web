---
date: 2017-03-03T10:29:26+09:00
tags:
- Netlify
- Heroku
title: Appropriate Deployment
---

I just finished splitting up the hosting of the [Portfolio Manager](/project/portfolio-manager) application
so that all my static assets (the Angular UI) are hosted on [Netlify](https://www.netlify.com/) for performance purposes and only the server-side code is hosted on [Heroku](https://www.heroku.com/home).  

This also makes it faster to change, build and deploy just the part of the application I am working on.
