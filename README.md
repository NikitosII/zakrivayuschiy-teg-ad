# Закрывающий тег

Учебный проект курса «Веб-разработчик» на Яндекс Практикуме.

## Ссылка на сайт

[https://nikitosii.github.io/zakrivayuschiy-teg-ad/](https://nikitosii.github.io/zakrivayuschiy-teg-ad/)

## О проекте

Лендинг в виде ленты карточек — личного дневника прохождения курса. Каждая карточка отражает один из спринтов обучения: от первого знакомства с HTML до сложных концепций JavaScript.

Ключевые фичи:

- анимированная иконка сердца с hover, active и is-liked состояниями
- модальный диалог «Сохранить на память» на нативном `<dialog>`
- CSS-фильтры на изображениях (contrast, brightness, hue-rotate, sepia, saturate, grayscale)
- кнопки с анимацией заливки через `::before` и `mix-blend-mode: difference`
- адаптивная вёрстка под ширину 375px

## Технологии

- HTML5 (семантическая разметка, `<dialog>`, SVG-спрайты через `<symbol>` / `<use>`)
- CSS (переменные, `font-variation-settings`, `clamp()`, `mix-blend-mode`, CSS-анимации, `@supports`, `@media`)
- JavaScript (нативный DOM, `showModal()` / `close()`)
- Шрифты: Inter Variable, Press Start 2P

## Структура

```
├── fonts/              — шрифты (.woff2, .woff)
├── images/             — изображения карточек и фавиконы
├── scripts/
│   └── like.js         — логика лайков
├── styles/
│   ├── animations.css  — анимации сердца
│   ├── globals.css     — сброс стилей
│   ├── style.css       — основные стили
│   └── variables.css   — CSS-переменные
├── svg/
│   └── floppy.svg      — SVG-спрайт дискеты
└── index.html
```
