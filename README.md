# PDCA Consulting — страница-заглушка

Временная страница для сайта [pdca-consulting.ru](https://pdca-consulting.ru) на период реконструкции. Тёмная тема, фирменный логотип, контактные данные.

## Стек

- Статический HTML / CSS, без сборки
- Google Fonts — [Source Sans 3](https://fonts.google.com/specimen/Source+Sans+3) (с кириллическим набором)
- Полностью адаптивная вёрстка через `clamp()` и медиа-запросы

## Структура

```
.
├── index.html               # Разметка страницы
├── favicon.svg              # Фавикон
├── assets/
│   ├── images/
│   │   └── pdca-logo.svg    # Фирменный логотип (горизонтальный, инвертированный)
│   └── styles/
│       └── styles.css       # Стили страницы
└── README.md
```

## Локальный запуск

Достаточно открыть `index.html` в браузере. Для корректной работы относительных путей рекомендуется поднять локальный сервер:

```bash
# Python
python -m http.server 8000

# Node.js (npx)
npx serve .
```

Затем открыть `http://localhost:8000`.

## Контакты

- Телефон: +7 (495) 740-83-40
- Email: info@pdca-consulting.ru
