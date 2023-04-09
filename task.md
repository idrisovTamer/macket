## Блок 1.3: Построение сеток + БЭМ именование
[Flex](https://developer.mozilla.org/ru/docs/Learn/CSS/CSS_layout/Flexbox)  
[Grid](https://developer.mozilla.org/ru/docs/Learn/CSS/CSS_layout/Grids)  
[Float](https://developer.mozilla.org/ru/docs/Learn/CSS/CSS_layout/Floats)  
[Документация БЭМ](https://ru.bem.info/methodology/quick-start/) - Первые 4 раздела  
[Доклад по БЭМ](https://www.youtube.com/watch?v=kBgHdSOj33A) ( [Слайды](http://ihorzenich.github.io/talks/bem-frontendweekend/) )  
[Методология БЭМ за 17 минут](https://www.youtube.com/watch?v=HihYQVuH64U)  
[Chrome DevTools](https://ru.hexlet.io/courses/html/lessons/devtools/theory_unit)  
[Новая сетка на inline-block](https://habr.com/ru/post/321718/)  
[CSS Display свойство](https://www.youtube.com/watch?v=uTS7CJ7gDwU&ab_channel=temofart)

#### Доп материалы:
- [Flexbox](https://scrimba.com/learn/flexbox)
- [Grid](https://scrimba.com/learn/cssgrid)
- [CSS Variables](https://scrimba.com/learn/cssvariables)
- [Flexbox Cheatsheet](https://yoksel.github.io/flex-cheatsheet/)
- [Grid game](https://cssgridgarden.com/#ru)
- [* { box-sizing: border-box; }](https://toster.ru/q/520184)
- [CSS Медиа запросы](https://itchief.ru/lessons/html-and-css/css-media-queries)
- [Адаптивный дизайн сайта](https://itchief.ru/bootstrap/responsive-website-design)
- [Основы Figma для верстальщика](https://htmlacademy.ru/blog/html/figma)
- [Подробно о свойстве float](https://habr.com/ru/post/142486/)

#### Примечания:
- На CSS таблицах практику пропускаем, только ознакомьтесь с теорией. По факту используются редко, если что - нагуглите.
- inline-block и float для сеток устарели, но нужны для старых браузеров и саппорта старых проектов
- flex и grid самые актуальная технологии, на данный момент

#### Задание

[Практика](https://webref.ru/practice) - все те же задачки

#### Обязательные задачи которые надо прорешать
- Аудио и видео
- Изображения
- Многоколоночная вёрстка

Сверстать блок из [макета](https://www.figma.com/file/q3FIPZpIAwxM0gzZnTBL5b/%D0%91%D0%BB%D0%BE%D0%BA-1.3%3A-%D0%9F%D0%BE%D1%81%D1%82%D1%80%D0%BE%D0%B5%D0%BD%D0%B8%D0%B5-%D1%81%D0%B5%D1%82%D0%BE%D0%BA-%2B-%D0%91%D0%AD%D0%9C-%D0%B8%D0%BC%D0%B5%D0%BD%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5?node-id=0-494&t=HCT8Kn1in6uMEAB9-4), выложить на Gitlab.
- Это часть макета из блока 1.6, поэтому выделяйте общие элементы исходя из итогового макета.
- Для верстки использовать flexbox.
- Используем подход Mobile First: Сначала верстаем версию на 320px - потом прописываем измнения для остальных экранов
- [Шрифт для макета](https://webfonts.pro/base-web-fonts/sans-serif-grotesque/897-tt-lakes.html)
- Все стили должны быть по БЭМ. Стиль именования - two dashes: `block-name__elem-name--mod-name--mod-val`
- На мобилке меню скроллится с помощью стандартного горизонтального скролла, см. свойство overflow
- На различный порядок и количество пунктов меню не обращайте внимание - меню на всех разрешениях должно быть одинаковым. По непонятным моментам в макете - обращайтесь к однокурсникам или ментору.

#### Темы для ревью:
- Блочная модель документа
- Верстка флоатами и inline-block - их проблемы и способы решения
- Анатомия flexbox
- Гриды
- Особенности кроссбраузерной верстки, поддержка гридов и флексов, вендорные префиксы
- С какими проблемами борется БЭМ
- Термины БЭМ: Блок, элемент, модификатор, микс
- overflow
