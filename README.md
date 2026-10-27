# KAZIMIR — SECRET ARCHIVE

**Дело № KZ-001. Расследование формы.**

Учебный проект по дисциплине «Арт-практика / типографика».
НИУ ВШЭ, направление «Дизайн», 2026.
Автор: Во Тху Тхао, группа БД26З09.

## О проекте

Сайт — цифровой архив исследования шрифта **Kazimir** (Илья Рудерман и Юрий Остроменцкий, CSTM Fonts, 2015).
«Секретный архив» здесь — художественная метафора: буквы показаны как улики, а 30 типографических экспериментов — как вещественные доказательства.

Разделы сайта:

- **Case file** — паспорт шрифта и исторический источник;
- **Type analysis** — контраст, засечки, пропорции;
- **Specimens** — алфавит, цифры и знаки;
- **Evidence gallery** — 30 композиций в шести сериях (E-01…E-06);
- **Дело закрыто?** — выводы и ссылки проекта.

## Структура репозитория

```text
kazimir-secret-archive/
├── index.html            ← вся разметка сайта
├── css/
│   └── style.css         ← все стили и анимации
├── images/
│   └── evidence/         ← 30 композиций в формате SVG (900 × 1200)
└── README.md
```

## Технологии

- Чистый HTML и CSS, без JavaScript и без библиотек.
- Шрифты подключены через Google Fonts: Old Standard TT и Inter.
- Анимации на CSS: бегущая строка, красная «копия-ошибка» заголовка, «удар» штампа, заливка кнопок, линия под пунктами меню, засекреченный текст, проявление букв, рамка вокруг улик, появление блоков при прокрутке (Chrome и Edge).
- Адаптивная вёрстка: компьютер, планшет и телефон; на телефоне меню и галерея листаются пальцем вбок.
- Если в системе включено «уменьшение движения», анимации выключаются.

## Шрифт и лицензия

Kazimir — коммерческий шрифт студии CSTM Fonts. Его файлы **не выкладываются** в открытый репозиторий.
На сайте используется свободная замена **Old Standard TT** (SIL Open Font License).
В CSS Kazimir стоит первым в списке шрифтов: если он легально установлен на компьютере зрителя, браузер применит его автоматически.

## Источники

- type.today — Kazimir: https://type.today/en/kazimir
- AIGA Eye on Design — Don't Call It a Revival: https://eyeondesign.aiga.org/dont-call-it-a-revival-kazimir-font-is-inspired-by-type-errors-in-early-russian-printing/
- Fontstand — Kazimir: https://fontstand.com/fonts/kazimir
- Adobe Fonts — Kazimir: https://fonts.adobe.com/fonts/kazimir
- Type Network — CSTM Fonts: https://typenetwork.com/articles/type-network-heads-east-with-cstm-fonts

Дата обращения: 27.10.2026.
