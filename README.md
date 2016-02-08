# gulp_zero_template
gulp+ bower + npm   template  bs  in box

*Installation
```
to work to put the NODE https://nodejs.org/en/
check out node-v
to execute commands (sudo may not need in windows you have to run the line on behalf of the admin)
sudo npm install gulp --save-dev
bower update
sudo npm update
change bower.json - name avtor
```
* Установка
```
 для работы поставить NODE  https://nodejs.org/en/
 проверить node -v
 выполнить команды (возможно sudo не надо  в windows следует запустить строку от имени админа)
 sudo npm install gulp --save-dev
 bower update
 sudo npm update
 измени bower.json - name   avtor
```

*команды instruction
```
    'html:build',
    'js:build',
    'style:build',
    'fonts:build',
    'fontsbs:build',
    'image:build'
 ```   
 *одна команда для запуска . instruction for start
 ```
 gulp
 ```
 *описание description
 ```
 структура structure
 
 |package.json
 |gulpfile.js
 |bower.json
 |src
 |sprite
 |fonts
 |html
 |images
 |js
 |  |partials
 |  |main.js
 |
 |styles
 |      |partials
 |      |_custom_var.scss
 |      |styles.scss
 
 построение идет в www 
 build to www
 ```
 *проблемы при установке 
 ```
npm update hangs on windows. 
remove node_module folder 
and update all following the instructions 

 npm update зависает на windows 
 и ничего неработает 
  удалить папку node_module 
  и обновить все по одельности 
     npm install gulp --save-dev
     npm update browser-sync 
     npm update imagemin-pngquant
     npm update rimraf
     npm updategulp-autoprefixer
     npm update gulp-concat
     npm update gulp-cssnano
     npm update gulp-imagemin
     npm update gulp-notify
     npm update gulp-rigger
     npm update gulp-sass
     npm update gulp-sourcemaps
     npm update gulp-strip-debug
     npm update gulp-uglify
     npm update gulp-watch
     npm update gulp.spritesmith
 ```
