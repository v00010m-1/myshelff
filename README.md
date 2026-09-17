# my shelf — сайт для GitHub Pages

Это готовый статический сайт без React/Vite/Node: достаточно загрузить папку в GitHub и включить GitHub Pages.

## Структура

- `index.html` — главная
- `films.html` — фильмы
- `series.html` — сериалы
- `games.html` — игры
- `anime.html` — аниме
- `manga.html` — манга
- `books.html` — книги
- `fandoms.html` — мои фандомы
- `about.html` — пустая вкладка «обо мне»
- `assets/style.css` — вся стилизация
- `assets/icons/` — PNG-иконки
- `assets/images/` — картинки фона, персонажей, обложек и т. п.

## Какие PNG добавить

Положи свои изображения с этими именами:

### `assets/icons/`
- `home.png`
- `films.png`
- `series.png`
- `games.png`
- `anime.png`
- `manga.png`
- `books.png`
- `fandoms.png`
- `about.png`

### `assets/images/`
- `home-background.png` — фон главной страницы
- `hero-cat.png` — котик в верхнем блоке
- `sidebar-logo.png` — картинка/логотип в меню
- `fandom-preview.png` — картинка блока «Мои фандомы»
- `player-cover.png` — обложка плеера
- `placeholder-01.png` ... `placeholder-06.png` — обложки карточек на страницах списков
- `fandom-my-little-pony.png`
- `fandom-my-little-pony-collage.png`
- `fandom-zelda-collage.png`
- `fandom-zelda-characters.png`

Если какого-то изображения пока нет, браузер просто покажет пустое место/иконку ошибки — остальные части сайта продолжат работать.

## Как добавить свои фильмы

На странице `films.html` найди карточки с классом `media-card` и поменяй:
- путь к картинке в `<img src="...">`
- `Название`
- описание

Карточки можно копировать сколько угодно.

## Как вставить ссылку на свою библиотеку

В каждом разделе найди:

`<a class="library-button" href="#" ...>`

и замени `href="#"` на свою ссылку. Например:

`href="https://example.com"`

Также можно удалить строку `.edit-note`, когда сайт будет готов.

## GitHub Pages

1. Создай репозиторий.
2. Загрузи все файлы из этой папки в корень репозитория.
3. GitHub → Settings → Pages.
4. В разделе Build and deployment выбери `Deploy from a branch`.
5. Выбери `main` и папку `/ (root)`.
6. Сохрани. Главной страницей будет `index.html`.
