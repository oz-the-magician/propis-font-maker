# Propis — font maker

Browser app that turns handwriting and drawn symbols into an OTF/WOFF font — Latin, Czech diacritics, Cyrillic.

**Live:** https://oz-the-magician.github.io/propis-font-maker/

## Features

- Draw every glyph on a copybook sheet with guide lines (cap height, x-height, baseline, descender)
- Tools: liner, pressure pen, brush, broad-nib calligraphy pen, dry brush, straight line, eraser; hand stabilizer
- Mask mode: a semi-transparent reference letter under the sheet (grotesque, condensed, old-style and Didone serif, italic, handwriting, calligraphy, mono) with adjustable opacity, color, scale and slant
- Printable A4 template + photo/scan recognition with automatic corner detection
- Vectorization, spacing and per-glyph adjustments with live preview
- Export a ZIP with `.otf`, `.woff` and the project file; open a project, a ZIP or any `.otf/.ttf/.woff` to keep working
- Interface in English, Czech and Russian; opens in your browser's language
- Everything runs locally in the browser, nothing is uploaded

## Run locally

Open `index.html` in a browser. No build step.

Libraries (CDN): [opentype.js](https://github.com/opentypejs/opentype.js), [JSZip](https://github.com/Stuk/jszip).

---

# Пропись — конструктор шрифтов

Браузерное приложение: почерк и нарисованные символы → шрифт OTF/WOFF. Латиница, чешская диакритика, кириллица.

**Открыть:** https://oz-the-magician.github.io/propis-font-maker/

## Возможности

- Рисование каждого знака на листе-прописи с линиями (заглавные, строчные, база, выносные)
- Инструменты: линер, перо с нажимом, кисть, широкое перо, сухая кисть, прямая, ластик; сглаживание руки
- Маска: полупрозрачный образец буквы под листом (гротеск, рубленый, антиква, курсив, рукописный, каллиграфия, моноширинный) с настройкой прозрачности, цвета, масштаба и наклона
- Шаблон A4 для печати и распознавание фото/скана с автоматическим поиском углов
- Векторизация, интервалы и настройка каждого знака с живым превью
- Сохранение ZIP с `.otf`, `.woff` и файлом проекта; открытие проекта, ZIP или любого шрифта `.otf/.ttf/.woff`
- Интерфейс на английском, чешском и русском; открывается на языке браузера
- Всё работает в браузере, файлы никуда не отправляются

## Запуск

Откройте `index.html` в браузере, сборка не нужна.
