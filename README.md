# Super Gulp

Learn Gulp by building an awesome development environment


0.3 const gulp = require('gulp'); //예전 방식.
0.4 babel을 이용한 gulp호출.
gulpfile.js --> gulpfile.babel.js
.babelrc
    {
        "presets": ["@babel/preset-env"]
    }
yarn add @babel/register @babel/core @babel/preset-env --dev
yarn global add gulp-cli


1.0 Pug build
1.1

2.0
yarn add -D gulp-webserver

2.1 
gulp watch

3.0
gulp image

4.0
scss
yarn add -D node-sass gulp-sass
