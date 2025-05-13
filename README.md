# Lab 11 Vue App

## Описание
Простое SPA приложение на Vue.js с использованием Vue CLI и Vue Router. Содержит 4 страницы: Home, About, Contact и Services.

## Требования
- Node.js (>=14)
- npm

## Установка
```bash
npm install
```

## Запуск проекта
```bash
npm run serve
```

Откройте [http://localhost:8080](http://localhost:8080) в браузере.

## Структура проекта
- `src/`
  - `main.js` — точка входа, монтирует Vue-приложение и подключает роутер.
  - `App.vue` — корневой компонент с навигацией и `<router-view>`.
  - `router/`
    - `index.js` — настройка маршрутов.
  - `views/`
    - `Home.vue` — домашняя страница.
    - `About.vue` — страница "О нас".
    - `Contact.vue` — страница "Контакты".
    - `Services.vue` — страница "Услуги".
  - `components/` — папка для отдельных компонентов (пустая).
