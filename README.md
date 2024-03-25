# Моя литература

Веб-сайт с перечнем книг для прочтения. Проект выполнен с помощью HTML, CSS и JS.

## Цель

Проект выполнен в рамках Всероссийского Фестиваля **«Неделя информатики»** от ВГПУ учеником 9 класса Соляником Георгием (15 лет).

## Организация

Веб-страница и все необходимые для её работы файлы находятся в директории `docs`, чтобы GitHub Pages был подключен к сайту, а не к `README.md`.

В папке `docs` находятся:

* папка `static` со статичными файлами:

  * папка `css` со стилями для страницы;
  * папка `img` с картинками (обложки книг, логотип, скриншоты);
  * папка `js` со скриптами для функционала;

* главный файл `index.html` с разметкой страницы.

## Функционал

На сайте реализованы следующие задачи:

1. **Сортировка** - по двум параметрам: источник получения и дата получения. Книги, сортированные по дате, отображаются от самой старой по самую новую Скрипт JS для сортировки находится по пути [docs/static/js/sort-books.js](docs/static/js/sort-books.js).

2. **Отображение** - три режима: табличный вид (на мобильной версии книги стоят в ряд), список и компактный режим. Скрипт JS для изменения представления книг находится по пути [docs/static/js/manage-books-view.js](docs/static/js/manage-books-view.js).

3. **Адаптация** - шесть условий: от огромных ultra-wide экранов до маленьких размеров (для смартфонов IPhone ранних моделей). Условия находятся в основном файле CSS по пути [docs/static/css/main.css](docs/static/css/main.css).

4. **Увеличенная обложка** - при нажатии на обложку всплывает модальное окно. При повторном нажатии в любую часть экрана, всплывающее окно пропадает. Скрипт JS для управления pop-up находится по пути [docs/static/js/manage-popup.js](docs/static/js/manage-popup.js).

5. **Фильтр** - по двум параметрам: источник получения и предмет. Если ни один из праметров фильтра не выбран, показываются все книги. Скрипт JS для управления фильтрами находится по пути [docs/static/js/manage-filters.js](docs/static/js/manage-filters.js).

Также на сайт добавлены следующие дополнения:

1. **Логотип** - придуман самостоятельно и создан с помощью онлайн-редакотора [Figma](https://www.figma.com/). Логотип добавлен на страницу с помощью `<link>`, png-файл лежит в папке со статикой [docs/static/img/icon.png](docs/static/img/icon.png).

2. **Цвет выделения текста** - стандартный голубой цвет выделения изменен на фиолетовый (один из акцентных цветов).

В будущем планируется доработка следующих функций:

1. **LocalStorage** - локальное сохранение в браузере списка книг, изменений в них.

2. **Добавление книг** - возможность загружать новые книги и информацию о них, добавлять обложку.

3. **Редактирование книг** - возможность редактировать информацию о книгах, добавлять или изменять обложку.

4. **Избранные** - раздел с лучшими книгами, пользователь может добавить книгу в избранное по кнопке.

## Использованные ресурсы

Книги и обложки взяты из онлайн-библиотек и книжных магазинов:

* [Читай-город](https://www.chitai-gorod.ru);
* [Лабиринт](https://www.labirint.ru/);
* [Мишкины-книжки](https://mishka-knizhka.ru).