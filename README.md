<div align="center">

# 𝕏 / Twitter UI Clone

**A pixel-perfect, fully responsive, high-performance web frontend clone of Twitter / X.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)

[Live Demo](#) · [Report Bug](https://github.com/visheshio/Twitteruiclone/issues) · [Request Feature](https://github.com/visheshio/Twitteruiclone/issues)

</div>

---

## 📖 Table of Contents
- [About The Project](#-about-the-project)
- [Key Features](#-key-features)
- [Responsive Breakpoints](#-responsive-breakpoints)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running Locally](#running-locally)
- [Project Structure](#-project-structure)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🌟 About The Project

This project is a modern, high-fidelity UI clone of the official **Twitter / X web client**. Built from the ground up using **Vanilla HTML5**, **CSS3**, and **Tailwind CSS v4**, bundled with **Vite** for blazing fast performance.

It recreates the real Twitter / X experience with extreme attention to detail, including authentic dark mode aesthetics (`#000000` pitch black background), sticky headers with glassmorphism blur effects, interactive post hover actions with exact color coding, responsive column collapsing, and a native-feeling mobile experience with a bottom navigation bar.

---

## ✨ Key Features

- ** authentic 3-Column Desktop Layout**:
  - **Left Sidebar**: Sticky navigation menu, official X brand mark, Post action button, and account profile quick-card.
  - **Main Feed**: Sticky tabs (*For You* / *Following*) with active pill indicator, interactive post composition box with media attachment toolbar, and dynamic post timeline.
  - **Right Sidebar**: Instant Search input, *What's Happening* (Trending topics with category labels & post counts), *Who to Follow* suggestions with instant Follow buttons, and footer copyright links.
- **📱 Fully Responsive Design**:
  - **Desktop (1280px+)**: Full 3-column experience with expanded navigation labels.
  - **Tablet (1024px – 1279px)**: Icon-only sidebar navigation to maximize feed visibility.
  - **Mobile (<500px)**: Bottom Navigation Bar with touch-friendly icons, floating action button (FAB) for composing tweets, single-column focus layout.
- **🎨 Rich Post Feeds**:
  - Multiple distinct post formats: **Image post**, **Pure Text post**, and **UI/UX showcase post**.
  - Authentic engagement action bars: **Replies**, **Retweets**, **Likes**, **Views**, **Bookmarks**, and **Shares** with exact Twitter hover color dynamics (Blue, Green, Pink).
  - Verified blue badges for authenticated profiles.
- **⚡ Modern CSS Architecture**:
  - CSS variables for theme tokens (`--x-blue`, `--x-border`, `--x-card-bg`, etc.).
  - Glassmorphic backdrop filters for sticky header bars.
  - Native custom scrollbars hidden for seamless native app feel.

---

## 📐 Responsive Breakpoints

| Screen Size | Layout State | Features |
| :--- | :--- | :--- |
| **> 1280px** | 3 Columns | Full Sidebar (Icons + Labels), Center Feed (600px max-width), Right Sidebar (Trending & Follow cards) |
| **1024px – 1279px** | 3 Columns (Compact) | Icon-only Sidebar, Center Feed, Right Sidebar |
| **500px – 1023px** | 2 Columns | Icon-only Sidebar, Expanded Center Feed, Hidden Right Sidebar |
| **< 500px** | Single Column | Hidden Sidebar, Full-width Feed, Mobile Bottom Nav Bar, Floating Action Button (FAB) |

---

## 🛠️ Tech Stack

- **HTML5**: Semantic tags (`<aside>`, `<main>`, `<header>`, `<article>`, `<nav>`)
- **CSS3 / Tailwind CSS v4**: `@theme` definitions, flexbox & grid responsive utilities
- **Vite 8**: Next-generation frontend build tool
- **Node.js**: Modern Javascript execution environment

---

## 🚀 Getting Started

Follow these steps to set up the project locally on your machine.

### Prerequisites

Ensure you have **Node.js** (v18.0.0 or higher) installed on your system.

```bash
node -v
npm -v
```

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/visheshio/Twitteruiclone.git
   cd Twitteruiclone
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

### Running Locally

Start the Vite development server:

```bash
npm run dev
```

Open your browser and navigate to `http://localhost:5173` (or the URL displayed in your terminal).

### Building for Production

To create an optimized production build:

```bash
npm run build
```

---

## 📁 Project Structure

```
Twitteruiclone/
├── public/              # Static assets & favicons
├── src/
│   ├── index.html       # Main application markup (Semantic HTML structure)
│   ├── input.css        # Tailwind CSS imports & Twitter UI styles/variables
│   ├── main.js          # Main JS entry point
│   └── output.css       # Compiled Tailwind CSS output
├── package.json         # Project dependencies and scripts
├── vite.config.js       # Vite configuration with Tailwind CSS v4 plugin
├── README.md            # Comprehensive project documentation
└── .gitignore           # Git ignore file
```

---

## 📸 Screenshots

<div align="center">
  <h3>Desktop Layout (Dark Mode)</h3>
  <p>Full 3-column view featuring Sidebar, Feed with multi-format posts, and Right Panel</p>
  <img width="947" height="430" alt="image" src="https://github.com/user-attachments/assets/1a4bff46-48ba-4a9a-979e-b54fc813cb08" />

</div>

---

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<div align="center">
  Crafted with ❤️ by <a href="https://github.com/visheshio">Vishesh</a>
</div>
