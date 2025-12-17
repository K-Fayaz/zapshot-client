# Screenshoots ✅

**Screenshoots** is a client-side web app for creating social-media style screenshots, mock posts, and downloading videos from platforms like Twitter, Reddit and Threads. It's a component-rich frontend built for fast iteration and experimentation with layouts, images and video extraction.

## ✨ Key Features

- Create and preview social-media screenshots and mock posts (Twitter, Instagram, LinkedIn style components)
- Tools for downloading videos from **Twitter**, **Reddit**, and **Threads**
- Banner maker and screenshot export (image & GIF support)
- Reusable UI components for quick prototyping and landing pages

## 🔧 Tech Stack

- **Vite** (development tooling)
- **React** + **TypeScript** (UI + types)
- **Tailwind CSS** + **PostCSS** (styling)
- Utility libraries: `html-to-image`, `html2canvas`, `hls.js`, `gif.js`, `gsap`, etc.
- Routing with `react-router-dom`

> Most dependencies are listed in `package.json`.

## 🚀 Quick Start

1. Install dependencies

```bash
npm install
```

2. Run development server

```bash
npm run dev
```

3. Build for production

```bash
npm run build
```

4. Preview the production build

```bash
npm run preview
```

## 📂 Notable files & folders

- `src/` — main source code
  - `src/pages/` — app pages (e.g. `Screenshot`, `TwitterVideoDownloader`, `RedditVideoDownloader`)
  - `src/components/` — reusable UI components used across the app
- `public/` — static assets (worker scripts, icons, etc.)

## 🤝 Contributing

PRs and improvements welcome — open an issue or submit a pull request if you'd like help adding features or fixing bugs.

---

If you want different wording, or to add badges (license, CI, demo), tell me what you'd like and I can update this README.