
# SVG Icons by Dreamsoftware

[![npm version](https://img.shields.io/npm/v/svg-by-dreamsoftware.svg?style=flat-square)](https://www.npmjs.com/package/svg-by-dreamsoftware)
[![downloads](https://img.shields.io/npm/dm/svg-by-dreamsoftware.svg?style=flat-square)](https://www.npmjs.com/package/svg-by-dreamsoftware)
[![bundle size](https://img.shields.io/bundlephobia/minzip/svg-by-dreamsoftware?style=flat-square)](https://bundlephobia.com/package/svg-by-dreamsoftware)
[![license](https://img.shields.io/github/license/dmitriyg0r/icons?style=flat-square)](https://github.com/dmitriyg0r/icons)

> **Lightweight SVG icon collection for React with zero dependencies**

![Library Preview](https://private-user-images.githubusercontent.com/62027285/466749602-8b0196a4-36c4-4f7b-9751-72d5f4f76e88.png)

## ✨ Features

✅ **13+ Essential Icons** (Arrow, Calendar, Chat, Check, etc.)  
✅ **React Components** & Raw SVG files  
✅ **Customizable** via props (size, color, className)  
✅ **Tree-shakable** - import only what you need  
✅ **TypeScript Support** out of the box  
✅ **Works with** Vite, Next.js, CRA, Gatsby  

## 🚀 Quick Start

### Installation
```bash
npm install svg-by-dreamsoftware
# or
yarn add svg-by-dreamsoftware
```

### Basic Usage
```jsx
import { Search, Profile } from 'svg-by-dreamsoftware/icons-react-dist';

export default function App() {
  return (
    <div>
      <Search width={24} fill="#3b82f6" />
      <Profile className="icon-profile" />
    </div>
  );
}
```

## 🔧 API Reference

### Common Props
| Prop      | Type     | Default | Description                     |
|-----------|----------|---------|---------------------------------|
| `width`   | number   | 24      | Icon width in px                |
| `height`  | number   | 24      | Icon height in px               |
| `fill`    | string   | currentColor | Color value              |
| `className` | string | -       | Custom CSS class                |
| `style`   | object   | -       | Inline styles                   |

## 🎨 Customization Examples

### Change color and size
```jsx
<Calendar width={32} height={32} fill="#10b981" />
```

### Use CSS classes
```jsx
<Settings className="icon-settings" />
```
```css
.icon-settings {
  color: #f59e0b;
  transition: all 0.3s ease;
}

.icon-settings:hover {
  color: #ef4444;
  transform: rotate(45deg);
}
```

### Use as SVG file
```js
import calendarIcon from 'svg-by-dreamsoftware/icons-svg-dist/calendar.svg';
```

## 📦 Bundle Optimization

Import only needed icons to reduce bundle size:
```jsx
import Search from 'svg-by-dreamsoftware/icons-react-dist/Search';
// Instead of:
// import { Search } from 'svg-by-dreamsoftware/icons-react-dist';
```

## 🤔 FAQ

### Q: How to add new icons?
A: Open an issue with your icon request or submit a PR!

### Q: Can I use these in Vue/Angular?
A: Yes! Use the raw SVG files from `icons-svg-dist` folder.

### Q: Why my icons don't change color?
A: Make sure your SVG uses `fill="currentColor"` and you're applying color via CSS or `fill` prop.

## 🌟 Pro Tips

1. **Animate icons** using CSS transitions
2. **Combine with Tailwind** for quick styling
3. **Lazy load** icons for better performance
4. **Use CSS variables** for theme support

## 🤝 Contributing

We welcome contributions! Please follow these steps:
1. Fork the repository
2. Add your new icons to `/src` folder
3. Run `npm build`
4. Submit a PR

See our [contribution guide](CONTRIBUTING.md) for details.

## 📜 License

MIT © [Dmitriy Gordienko](https://github.com/dmitriyg0r)

## 💖 Support the Project

If you find this useful, please consider:
- [GitHub Star](https://github.com/dmitriyg0r/icons)
- [Donate via Donationalerts](https://www.donationalerts.com/r/dmitriygor)
- Share with your colleagues
