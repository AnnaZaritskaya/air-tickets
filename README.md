## установить зависимости
npm install

## запустить локальный сервер для разработки
npm run dev

## сгенерировать файлы в продакшен
npm run build



## bloks
## Скрипт  для создания SCSS файлов

Этот скрипт предназначен для автоматизации создания SCSS файлов.

### Использование

1. Убедитесь, что у вас установлена оболочка Bash.

2. Сохраните скрипт в удобное место в проекте. (block)

3. Предоставьте скрипту права на выполнение:

   chmod +x block.sh (через папку и контекстное меню/консоль)

4. Запустите скрипт, передав в качестве аргумента имя параметра:

   ./block.sh имя_параметра

Где имя_параметра - это название файла

5. Скрипт создаст файл с именем _имя_параметра.scss в папке src/scss/blocks, а также добавит импорт в файл _index.scss.

6. Если файл уже существует, скрипт выведет предупреждение.

### Пример

Допустим, вы хотите создать SCSS файл для блока "header". Выполните следующую команду:

./block.sh header

Скрипт создаст файл _header.scss с определением класса и добавит импорт в _index.scss