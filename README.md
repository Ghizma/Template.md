# My first project uploaded to GitHub
This project is my work in creating a site with HTML, CSS, JS, SASS (SCSS), and UI Kit for him.

I use ParcelJS, preprocessor SASS(SCSS).

## For notes
Скачайте или склонируйте данный репозиторий. Через терминал выполните команду `npm install` (должен быть установлен NodeJS).

В директории `src` два html-файла. Index.html - для вёрстки макета, uikit.html - для создания UI Kit.

Для запуска режима разработчки в терминале выполните команду:
- `npm run dev` - создастся локальное окружение и запустится виртуальный веб-сервер для содержимого `index.html` (также будет использовано содержимое файла стилей `src/assets/styles/index.scss`)
- `npm run kit` - создастся локальное окружение и запустится виртуальный веб-сервер для содержимого `uikit.html` (также будет использовано содержимое файла стилей `src/assets/styles/uikit.scss`)

Для остановки режима разработки в терминале нажмите сочетание клавиш Ctrl+C.

Для сборки в терминале выполните команду:
- `npm run build` - запусится сборка шаблона, готовые файлы попадут в папку `build/www`
- `npm run build:uikit` - запусится сборка UI Kit, готовые файлы попадут в папку `build/uikit`
Примечание: используйте bash-терминал для корректной работы скрипта.
