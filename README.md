<img width="581" height="544" alt="image" src="https://github.com/user-attachments/assets/8b0196a4-36c4-4f7b-9751-72d5f4f76e88" />
# SVG Icons by Dreamsoftware

Универсальная коллекция SVG-иконок для React-проектов. Все иконки доступны как готовые React-компоненты.


## Установка

```sh
npm install svg-by-dreamsoftware
```

## Использование в React

Импортируйте нужные иконки напрямую из пакета:

```jsx
import { Calendar, Profile, Search, Trash } from 'svg-by-dreamsoftware/icons-react-dist';

function App() {
  return <Calendar width={32} height={32} />;
}
```

## Список иконок

- Calendar
- Profile
- Search
- Trash
- ... (и другие, смотрите содержимое папки icons-react-dist)


## Важно для пользователей

- Все иконки уже собраны в обычный JS (без JSX) — работают с любым сборщиком (Vite, CRA, Next.js и др.).
- Импортируйте только из `svg-by-dreamsoftware/icons-react-dist`.

## Пример SVG

```svg
<svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path d="M12 2L15 8H21L16.5 12L18 18L12 14.5L6 18L7.5 12L3 8H9L12 2Z" fill="currentColor"/>
</svg>
``` 
