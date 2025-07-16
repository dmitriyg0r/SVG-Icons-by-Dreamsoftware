<img width="581" height="544" alt="image" src="https://github.com/user-attachments/assets/8b0196a4-36c4-4f7b-9751-72d5f4f76e88" />


# SVG Icons by Dreamsoftware

[![npm version](https://img.shields.io/npm/v/svg-by-dreamsoftware.svg)](https://www.npmjs.com/package/svg-by-dreamsoftware)
[![downloads](https://img.shields.io/npm/dm/svg-by-dreamsoftware.svg)](https://www.npmjs.com/package/svg-by-dreamsoftware)
[![license](https://img.shields.io/github/license/dmitriyg0r/icons)](https://github.com/dmitriyg0r/icons)

> **Современная коллекция SVG-иконок для React**

Универсальная библиотека иконок для ваших проектов. Все иконки доступны как готовые React-компоненты и как отдельные SVG-файлы. Легко интегрируются, кастомизируются и подходят для любых задач.

![Иконки](https://private-user-images.githubusercontent.com/62027285/466749602-8b0196a4-36c4-4f7b-9751-72d5f4f76e88.png)

---

## 🚀 Возможности

- Более 10 популярных иконок (Arrow, Calendar, Chat, Check, Download, Pencil, Plus, Profile, Search, Send, Settings, Trash, Update)
- Готовые React-компоненты (JS, без JSX)
- Легкая кастомизация размеров и цвета через props
- Поддержка любых сборщиков (Vite, CRA, Next.js и др.)
- Импорт только нужных иконок для оптимизации размера бандла
- Можно использовать как отдельные SVG-файлы

---

## 📦 Установка

```sh
npm install svg-by-dreamsoftware
```

---

## 🛠 Использование в React

Импортируйте нужные иконки напрямую из пакета:

```jsx
import { Calendar, Profile, Search, Trash } from 'svg-by-dreamsoftware/icons-react-dist';

function App() {
  return (
    <>
      <Calendar width={32} height={32} fill="#4F46E5" />
      <Profile width={24} height={24} style={{ color: 'tomato' }} />
    </>
  );
}
```

**Кастомизация:**
- `width`, `height` — размеры
- `fill` или `style={{ color: ... }}` — цвет

---

## 📁 Список иконок

- Arrow
- Calendar
- Chat
- Check
- Download
- Pencil
- Plus
- Profile
- Search
- Send
- Settings
- Trash
- Update

_(Смотрите содержимое папки icons-react-dist для полного списка)_

---

## ⚡ Пример SVG

```svg
<svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M12 2L15 8H21L16.5 12L18 18L12 14.5L6 18L7.5 12L3 8H9L12 2Z" fill="currentColor"/>
</svg>
```

---

## 🤝 Вклад в проект

Будем рады вашим PR и идеям! Открывайте issues или предлагайте новые иконки.

---

## 📜 Лицензия

MIT

---

## 💜 Поддержать проект

[Donationalerts](https://www.donationalerts.com/r/dmitriygor)

[GitHub проекта](https://github.com/dmitriyg0r/icons)
