
# Сайт готелю "Міміно"

Pixel Perfect верстка проекта с использованием Pug, Scss, jQuery, Webpack

**Цель:**
- Попробовать pug, jquery
- Научиться pixel-perfect верстке
- Создать webpack конфиг для многостраничного сайта

## Быстрый старт
Підготовка
Перш ніж приступити до встановлення багатоцільового шаблону HTML, необхідно підготуватися. Рекомендується виконати наступні кроки:
програмне забезпечення
Ми рекомендуємо завантажити все необхідне програмне забезпечення для редагування шаблону веб-сайту. Необхідне програмне забезпечення вказано на сторінці попереднього перегляду шаблону.

Технічні вимоги можуть відрізнятися в залежності від конкретного шаблону, тому ми наведемо найосновніші з них:

По-перше, вам знадобиться відповідне програмне забезпечення для розархівування для захищених паролем джерел_##########.zip. Ви можете використовувати WinZip 9+ (Windows) і Stuffit Expander 10+ (Mac). Це обов’язкове програмне забезпечення.
Вам також може знадобитися Adobe Photoshop (версії CS3 або новішої). Він використовується для редагування вихідних файлів .PSD і необхідний у разі зміни графічного дизайну або редагування зображень шаблонів.
Ви також повинні використовувати редактор коду, т. e. Sublime Text, Notepad++, Atom тощо для редагування вихідного коду файлів шаблонів.
Для завантаження файлів на сервер FTP також знадобиться менеджер, наприклад FileManager на панелі керування хостингом або настільні програми, такі як Total Commander, FileZilla, CuteFTP тощо.
Ми настійно рекомендуємо вам використовувати LibSass для компіляції SCSS, наприклад. програма Prepros.
Хостинг
Ви можете просто запустити файл index.html безпосередньо з папки сайту, але це не дозволить вам вивчити всі функції шаблону. Вам слід завантажити шаблон на сервер хостингу, щоб повністю відображати повністю працюючий веб-сайт.

Якщо у вас уже є сервер, перевірте, чи відповідає він вимогам веб-сайту. Єдиною вимогою є версія PHP 5.2+.

Ви також можете встановити шаблон веб-сайту на свій комп’ютер локально за допомогою localhost. Щоб налаштувати локальний сервер, ви можете використовувати WAMP, AppServ, MAMP або будь-яке подібне програмне забезпечення. Усі вони встановлюються так само, як і звичайні програми.

Посібники щодо налаштування локального сервера:
Як встановити середовище веб-розробки AppServ
Як встановити середовище веб-розробки WAMP
Як встановити середовище веб-розробки XAMP

Вам потрібно завантажити всі файли сайту/папки з вашого локального хосту на хостинг.

#### `npm i` – установить зависимости проекта

#### `npm run dev` – запуск devServer на http://localhost:8081/

## Скрипты

#### `npm run dev` – запуск devServer на http://localhost:8081/

#### `npm run build` – production сборка проекта

#### `npm run puglint` – запуск линтера для файлов pug

## Используемые библиотеки

- [air-datepicker](https://github.com/t1m0n/air-datepicker)
- [ion.rangeSlider](https://github.com/IonDen/ion.rangeSlider)
- [jQuery-Mask-Plugin](https://github.com/igorescobar/jQuery-Mask-Plugin)
- [normalize.css](https://github.com/necolas/normalize.css)
- [slick-carousel](https://github.com/kenwheeler/slick)
- [material-design-icons](https://github.com/google/material-design-icons)

## Макеты

<table>
  <tr>
    <th><a href="https://chrisryana.github.io/toxin/" target="_blank">Landing Page</a></th>
    <th><a href="https://chrisryana.github.io/toxin/search" target="_blank">Search Room</a></th>
    <th><a href="https://chrisryana.github.io/toxin/room" target="_blank">Room Details</a></th>
    <th><a href="https://chrisryana.github.io/toxin/registration" target="_blank">Registration</a></th> 
    <th><a href="https://chrisryana.github.io/toxin/signin" target="_blank">SignIn</a></th> 
  </tr>
	
  <tr valign="top">
    <td>
      <a href="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Landing%20page.jpg?raw=true" target="_blank">
        <img src="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Landing%20page.jpg?raw=true" width="250" alt="Главная страница">
      </a>
    </td>
    <td>
      <a href="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Search%20room/Filter.jpg?raw=true" target="_blank"><img src="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Search%20room/Filter.jpg?raw=true" width="250" alt="Страница поиска"></a>
    </td>
	<td>
      <a href="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Room%20details.jpg?raw=true" target="_blank"><img src="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Room%20details.jpg?raw=true" width="250" alt="Страница номера"></a>
    </td>
  <td>
      <a href="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Registration.jpg?raw=true" target="_blank"><img src="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Registration.jpg?raw=true" width="250" alt="Страница регистрации"></a>
    </td>
  <td>
      <a href="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Sign%20in.jpg?raw=true" target="_blank"><img src="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Sign%20in.jpg?raw=true" width="250" alt="Страница авторизации"></a>
    </td>
  </tr>
  
  <tr>
  <th><a href="https://chrisryana.github.io/toxin/colors-types" target="_blank">Colors & Types</a></th>
  <th><a href="https://chrisryana.github.io/toxin/form-elements" target="_blank">Form Elements</a></th>
  <th><a href="https://chrisryana.github.io/toxin/cards" target="_blank">Cards</a></th>
  <th><a href="https://chrisryana.github.io/toxin/headers-footers" target="_blank">Headers & Footers</a></th>
  </tr>
  
  <tr valign="top">
    <td>
      <a href="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Colors%20&%20Type.jpg?raw=true" target="_blank">
        <img src="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Colors%20&%20Type.jpg?raw=true" width="250" alt="Страница цветов и шрифтов">
      </a>
    </td>
    <td>
      <a href="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Form%20Elements.jpg?raw=true" target="_blank"><img src="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Form%20Elements.jpg?raw=true" width="250" alt="Страница с элементами форм"></a>
    </td>
  <td>
      <a href="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Cards.jpg?raw=true" target="_blank"><img src="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Cards.jpg?raw=true" width="250" alt="Страница карточек"></a>
    </td>
  <td>
      <a href="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Headers%20&%20Footers.jpg?raw=true" target="_blank"><img src="https://github.com/chrisryana/toxin/blob/master/src/pixel-perfect/Headers%20&%20Footers.jpg?raw=true" width="250" alt="Страница с шапками и футерами сайта"></a>
    </td>
  </tr>
</table>

### Структура проекта

```
├── src/                             # Исходники
│   ├── assets/                      # Подключаемые ресурсы
│   │   ├── fonts/                   # Шрифты используемые в проекте
│   │   ├── img/                     # Изображения используемые в проекте
│   │   └── styles/                  # Стили
│   │       ├── theme/               # Папка с темой проекта
│   │       │   ├── colors.scss      # Файл с переменными цветов
│   │       │   ├── fonts.scss       # Файл с подлючаемыми шрифтами
│   │       │   └── spaces.scss      # Переменные отступов
│   │       └── main.scss            # Файл в который импортируются все стили
│   ├── blocks/                      # Папка с блоками проекта
│   ├── favicons/                    # Фавиконки для разных браузеров
│   ├── layouts/                     # Папка с шаблонами разметки
│   ├── pages/                       # Папка страниц проекта
│   └── pixel-perfect/               # Скриншоты для сверки Pixel Perfect
├── .babelrc                         # Конфигурация компиляции Javascript в es5
├── .eslintrc.json                   # Конфигурация проверки JavaScript в ESLint
├── .gitignore                       # Список исключённых файлов из Git
├── .pug-lintrc                      # Конфигурация проверки pug-файлов
├── package.json                     # Список модулей и прочей информации
├── postcss.config.js                # Конфигурация компиляции стилей
├── README.md                        # Документация шаблона
├── webpack.base.conf.js             # Базовая конфигурация Webpack.js
├── webpack.build.conf.js            # Конфигурация Webpack.js для production сборки
└── webpack.dev.conf.js              # Конфигурация Webpack.js для dev сборки
```
