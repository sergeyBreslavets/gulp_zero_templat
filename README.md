# gulp_zero_template
gulp+ bower + npm   template  bs  in box

***
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

*команды
```
    'html:build',
    'js:build',
    'style:build',
    'fonts:build',
    'fontsbs:build',
    'image:build'
 ```   
 *супер команда 
 ```
 просто gulp - запустить только ее и все 
 ```
 *описание 
 ```
 структура
 
 |package.json
 |gulpfile.js
 |bower.json
 |src
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
 
 
 ```
