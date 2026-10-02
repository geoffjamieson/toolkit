# 🧰 @geoffjamieson/react-toolkit

![React](https://img.shields.io/badge/react-18.x-blue.svg)

Reusable React components for building clean, flexible, and modern UIs.  
All tools are lightweight, customizable, and Tailwind-friendly by design.

This toolkit currently includes unstyled UI components, with plans to expand into animations, utilities, and more.

---

## 📦 Installation

```bash
npm install @geoffjamieson/react-toolkit
```

---

## 🎨 Import Styles

To use built-in styles like transitions and utility classes, manually import the toolkit's CSS in your app's entry file:

```tsx
// main.tsx or App.tsx
import '@geoffjamieson/react-toolkit/dist/react-toolkit.css'
``` 

---

## 🚀 Quick Usage

Import and use any component:

```tsx
import { RotatingWords } from '@geoffjamieson/react-toolkit'
```

```tsx
<RotatingWords
  staticTextBefore="I'm a"
  words={['Developer', 'Designer', 'Creator']}
  staticTextAfter="and I love it."
  animation="slide-left"
/>
```

---

## 📚 Documentation

Full documentation is available for each component.

- [All Components](https://github.com/geoffjamieson/toolkit/blob/main/react-toolkit/lib/docs/index.md)
  - [RotatingWords](https://github.com/geoffjamieson/toolkit/blob/main/react-toolkit/lib/docs/components/RotatingWords.md)
  - [Modal](https://github.com/geoffjamieson/toolkit/blob/main/react-toolkit/lib/docs/components/Modal.md)

---

## 🧪 Local Development

This repo includes a `/src` playground to test and iterate on components locally.  

⚠️ The /src playground is for local development only and is not included in the published npm package.

```bash
npm install
npm run dev
```

---

## 🙌 Contributing

Feel free to submit issues or pull requests if you'd like to improve or add new components!
