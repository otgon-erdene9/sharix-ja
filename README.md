# 🍽️ Хоол.МН — Монгол Хоолны Жорны Платформ

Монгол болон дэлхийн хоолны жорнуудыг нэг дороос олоорой.

## ✨ Боломжууд

- 🔍 Хоол хайх функц
- 🗂️ Ангиллаар шүүх (Монгол, Азийн, Европ, Салат, Цөцгий)
- 📖 Дэлгэрэнгүй жор, орцнууд, хийх арга
- 📱 Responsive дизайн
- ⚡ React + Vite

## 🚀 Суулгах заавар

```bash
# 1. Клон хийх
git clone https://github.com/YOUR_USERNAME/khool-mn.git
cd khool-mn

# 2. Хамааралтай пакетуудыг суулгах
npm install

# 3. Хөгжүүлэлтийн сервер ажиллуулах
npm run dev

# 4. Build хийх
npm run build
```

## 🌐 GitHub Pages-д байршуулах

```bash
# 1. Build хийнэ
npm run build

# 2. gh-pages пакет суулгана
npm install --save-dev gh-pages

# 3. package.json дотор scripts-д нэмнэ:
# "deploy": "gh-pages -d dist"

# 4. Deploy хийнэ
npm run deploy
```

Эсвэл **Vercel** эсвэл **Netlify**-д drag & drop хийн `dist` фолдерийг байршуулна.

## 📁 Файлын бүтэц

```
khool-mn/
├── index.html
├── vite.config.js
├── package.json
├── src/
│   ├── main.jsx
│   ├── App.jsx
│   ├── index.css
│   ├── data/
│   │   └── recipes.js       # Хоолны мэдээлэл
│   └── components/
│       ├── Header.jsx
│       ├── Hero.jsx
│       ├── RecipeCard.jsx
│       ├── Modal.jsx
│       └── FoodImage.jsx
└── README.md
```

## 🛠️ Технологи

- **React 18** — UI framework
- **Vite** — Build tool
- **Google Fonts** — Playfair Display + DM Sans

## 📝 Шинэ жор нэмэх

`src/data/recipes.js` файлд шинэ объект нэмнэ үү:

```js
{
  id: 'unique-id',
  emoji: '🍜',
  color: ['#darkColor', '#lightColor'],
  category: 'mongolian', // mongolian | asian | european | salad | dessert
  categoryLabel: 'Монгол',
  name: 'Хоолны нэр',
  desc: 'Товч тайлбар...',
  time: '30 мин',
  serves: '2 хүн',
  diff: 'Хялбар', // Маш хялбар | Хялбар | Дунд | Хэцүү
  calories: '300 ккал',
  featured: false,
  ingredients: ['Орц 1', 'Орц 2'],
  steps: ['Алхам 1', 'Алхам 2'],
  tip: 'Зөвлөмж...',
}
```

## 📄 Лиценз

MIT
