# Danil Cherdantsev — Portfolio

Персональный сайт-портфолио в стиле терминала.

## Стек

- [Astro](https://astro.build/) — статический генератор сайтов
- TypeScript
- Кастомный CSS (terminal theme)

## Требования

- Node.js 18+
- npm

## Установка

```bash
npm install
```

## Запуск (dev)

```bash
npm run dev
```

Откроется на http://localhost:4321

## Сборка

```bash
npm run build
```

Результат в папке `dist/`.

## Preview

```bash
npm run preview
```

## Деплой

Сайт деплоится на GitHub Pages: https://x1dg.github.io/portfolio

## Структура

```
src/
├── layouts/
│   └── Layout.astro    # Основной лейаут с окном терминала
├── pages/
│   └── index.astro     # Контент главной страницы
├── components/         # Переиспользуемые компоненты
└── styles/             # Глобальные стили
```

## Автор

Даниил Черданцев — [.NET Backend Developer](https://github.com/x1dg)
