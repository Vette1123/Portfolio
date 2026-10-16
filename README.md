# 🗂️ Old Portfolio

> Mohamed Gado's first portfolio site (2022). Superseded by [the current portfolio](https://mohamedgado.com) — kept here for archival.

![React](https://img.shields.io/badge/React-17-61DAFB?logo=react&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript&logoColor=black)
![Sass](https://img.shields.io/badge/Sass-CC6699?logo=sass&logoColor=white)

### 🔗 [View the live site →](https://gado-portfolio.vercel.app)

> **Heads-up:** This is the archived 2022 version. The current portfolio lives at **[mohamedgado.com](https://www.mohamedgado.com)**.

A single-page React portfolio with a sidebar layout, letter-by-letter intro animations, a projects showcase, and a contact page with an interactive map and email form.

## ✨ Features

- **Animated letter intro** — name and tagline reveal one character at a time
- **Sidebar navigation** — persistent layout with icon-based routing (Home / About / Portfolio / Contact)
- **Projects showcase** — `/portfolio` page listing past work
- **Contact form** — wired to [EmailJS](https://www.emailjs.com/) for direct messaging
- **Leaflet map** — location pin on the contact page via `react-leaflet`
- **Page loaders** — spinner transitions between routes (`react-loaders`)
- **FontAwesome icons** — solid + brand glyphs throughout

## 🛠️ Tech Stack

- **Framework** — React 17 (Create React App)
- **Routing** — React Router v6
- **Styling** — Sass + `animate.css`
- **Map** — React Leaflet
- **Email** — EmailJS
- **Animation helpers** — GSAP, `loaders.css`

## 📖 Getting Started

```bash
npm install
npm start
```

The app runs at <http://localhost:3000>. To enable the contact form, add a `.env` with `REACT_APP_PUBLIC_KEY=<your-emailjs-key>`.

## 🙌 Credits

Built by [Mohamed Gado](https://mohamedgado.com).
