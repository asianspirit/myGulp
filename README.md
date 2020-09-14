# myGulp
# Сборка Gulp4 с плагинами.




Устанвока и запуск сборки 
```sh
$ npm i
$ gulp
```

Сборка дополнительно позволяет:
- создавать svg спрайты;
- форматировать шрифты в нужный формат;


# Установленные плагины и их возможности:

- gulp-sass компилятор для препроцессора scss/sass;
- gulp-clean-css минификация готового css;
- gulp-autoprefixer автопрефиксер;
- gulp-file-include импорт одних файлов в другие, который позволяет собирать html из модулей;
- gulp-uglify-es минификация js
- babel форматирование в стандарт ES5;
- gulp-ttf2woff, gulp-ttf2woff2, 'gulp-fonter конвертация шрифтов из ttf в eot, woff и woff2;
- gulp-imagemin сжатие изображений;
- gulp-rename плагин позвоялет переиминовывать файлы и добавлять .min;
- gulp-concat объединяет js файлы плагинов в один;
- gulp-group-css-media-queries позволяет собирать разбросаныне медиа запросы в 1н файл;
- browsersync для живого обновления страниц;
- gulp-webp-html, gulp-webp-css конвертация растровых изображений в webp и автозамена в html и css ресурсов для загрузки webp и подмены на jpg/png если браузер не понимает.

Так же установлены:
- normalize.css
- jquery.js
