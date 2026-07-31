---
title: "Мастер-руководство по Tailwind CSS v4 Engine"
tags: [tailwind, css-first, vite, postcss, theme, migration]
date: 2026-07-31
status: ✅ Активен
category: "Vibe Design / Skills / Tailwind"
---

# 🚀 Tailwind CSS v4 Engine — Полный Справочник

## 📌 Архитектура CSS-First в v4

Tailwind CSS v4 отказывается от конфигурационного файла `tailwind.config.js` в пользу декларативной настройки через директиву `@theme` прямо в CSS.

### 1. Подключение в Vite
```bash
npm install tailwindcss @tailwindcss/vite
```

```typescript
// vite.config.ts
import { defineConfig } from 'vite'
import tailwindcss from '@tailwindcss/vite'

export default defineConfig({
  plugins: [tailwindcss()],
})
```

### 2. Главный CSS файл (`src/index.css`)
```css
@import "tailwindcss";

@theme {
  --font-display: "Outfit", sans-serif;
  --font-body: "Inter", sans-serif;

  --color-primary: #6366f1;
  --color-primary-hover: #4f46e5;
  --color-dark-bg: #090d16;

  --breakpoint-3xl: 120rem;
}
```

---

## ⚡ Ключевые возможности

1. **Zero-Config Сканирование шаблонов**: Больше не нужно указывать пути `content: [...]` — Tailwind сканирует файлы автоматически.
2. **Переменные CSS по умолчанию**: Любой токен из `@theme` доступен и как утилита (`bg-primary`), и как переменная `var(--color-primary)`.
3. **Контейнерные запросы (`@container`)**: Адаптивность элементов относительно ширины своего родителя.
