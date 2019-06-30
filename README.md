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


4.1 
gulp-autoprefixer
scss를 구형 브라우져가 알아들을 수 있도록 prefixer를 붙여줌(자동)
.browserslistrc파일을 생성해서 옵션 전달

gulp-csso
css의 공백 제거(minify)


5.0
gulp-bro
node 형식의 명령을 browser에서 실행할 수 있도록 번역.

babelify


6.0
gulp-gh-pages
deploy url: http://tonky0110.github.io/super-gulp