# Create React App

Links:

- [Yandex docs](https://tech.yandex.ru/maps/jsapi/doc/2.1/faq/index-docpage/) – yandex api docs.
- [Yandex developer](https://developer.tech.yandex.ru/services/3/stat/) – yandex api developer.
- [Youtube Api yandex](https://www.youtube.com/watch?v=QkfUqb2XFRw) – Использование API Яндекс.Карт на сайте.
- [Yandex sandbox](https://tech.yandex.ru/maps/jsbox/2.1/polygon_with_image)

- [2gis](https://api.2gis.ru/)
- [2gis.maps](http://api.2gis.ru/doc/maps/info/)
- [2gis.docs](http://catalog.api.2gis.ru/doc/2.0/region/quickstart)
- [2gis.new](http://catalog.api.2gis.ru/doc/new/)
- [Habr](https://habr.com/ru/post/204228/) x
- [Youtube](https://www.youtube.com/results?search_query=2gis+%D0%BF%D0%BE%D0%B4%D0%BA%D0%BB%D1%8E%D1%87%D0%B5%D0%BD%D0%B8%D0%B5)


- [Creating an App](#creating-an-app) – How to create a new app.
- [Create react app gh pages](https://www.youtube.com/watch?v=1Y-PqBH-htk) – How ghpages.

- dionisyariopagit
- Ggq93XthpzZCiK9
- 9687429383
- c946cf1b-a7ca-4e53-8b30-402ab78303db

- rujqsv8899

## Quick Overview

```sh
git add .
git commit -m '0.0.1.1 add map'
git push -u origin master
npm run deploy
```

## Workflow

```sh
git init
git add .
git commit -m '0.0.1 init'
git remote add origin https://github.com/Barkarula/maps.github.io.git
git push -u origin master
npm install --save gh-pages
add in package.json "homepage": "https://barkarula.github.io/maps.github.io/"
add in package.json "predeploy": "npm run build",
add in package.json "deploy": "gh-pages -d build",
npm run deploy
add api script of yandex and main script e.t.c.
add main.js
add img, css
```