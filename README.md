# 🎬 LPM – Latest Popular Movies

A modern React web app to browse, search, and save your favorite movies using the [TMDB API](https://www.themoviedb.org/). Built with **Vite**, **React**, and the **Context API**.

🔗 [Live Demo](https://ramteja-16.github.io/LPM/)

---

## 🚀 Features

- 📽️ Fetch and display trending/popular movies
- 🔍 Search for movies by name
- ⭐ Add/remove movies from favorites
- 💾 Persist favorites in `localStorage`
- 📱 Fully mobile responsive
- ⬆️ Scroll to top button

---

## 🛠 Tech Stack

- React (with Hooks)
- React Router DOM
- Context API
- Vite
- Vanilla CSS

---

## 📂 Project Structure

```

src/
├── components/        # Reusable UI elements
├── contexts/          # Global state with Context API
├── pages/             # Home & Favorites pages
├── services/          # API integration with TMDB
├── css/               # Component-level styles
├── App.jsx            # App routing setup
├── main.jsx           # Entry point

````

---

## 🧑‍💻 Getting Started

```bash
git clone https://github.com/Ramteja-16/LPM.git
cd LPM
npm install
npm run dev
````

Build for production:

```bash
npm run build
```

---

## 🌐 Deployment

This project is deployed using GitHub Pages:
📍 [https://ramteja-16.github.io/LPM/](https://ramteja-16.github.io/LPM/)

---

## 📦 Powered by Vite + React

This project uses the official Vite + React template.

> Vite provides fast HMR, optimized builds, and supports plugins like `@vitejs/plugin-react` and `@vitejs/plugin-react-swc`.

### Vite Plugin Info

* [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs)) for Fast Refresh
* [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

### React Compiler (Optional)

React Compiler is not enabled by default due to performance. You can enable it by following [this guide](https://react.dev/learn/react-compiler/installation).

### ESLint Expansion (Optional)

For production apps, consider TypeScript with type-aware lint rules. Explore the [React + TypeScript template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) and use [`typescript-eslint`](https://typescript-eslint.io) for advanced linting.

---

## 🧠 Author

Built with ❤️ by [Ramteja](https://github.com/Ramteja-16)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).


