# David Muñoz - Developer Portfolio

Welcome to the source code of my personal portfolio. Built with a focus on modern web standards, this project serves as a showcase of my technical skills, mixing a highly optimized static site generated architecture with a distinct "Dark Code Editor / API Console" aesthetic.

## 🚀 Tech Stack

- **Framework**: [Astro](https://astro.build/) - For shipping zero JS by default and ultra-fast static rendering.
- **Styling**: Vanilla CSS3 + PostCSS - Clean, custom utility classes leveraging modern CSS variables for a strict dark-editor aesthetic.
- **Components**: Astro UI Components - Component-based architecture for clean code separation.
- **Deployment**: Vercel / GitHub Pages.

## 💡 Key Features

- **Terminal Simulator**: The Hero section mimics a fully functional macOS Bash terminal, executing a mock `curl` request that outputs syntax-highlighted JSON data with calculated network latency and typing animations.
- **Interactive API Console**: The Projects section is built as an interactive API testing tool. Clicking endpoints (e.g. `/solbabackups`) fires simulated network requests, calculating latency and rendering project data dynamically.
- **Code Editor Layout**: The "StoryLine" acts as a strict code indentation guide that follows the user on scroll (using `IntersectionObserver`), triggering VS Code style file-tab panels (`.md` extensions) for each life chapter.
- **Performance First**: 100% Lighthouse scores. Relying on Astro's static generation ensures the page loads instantly.

## 📁 Project Structure

```text
/
├── public/                 # Static assets (images, CV, icons)
├── src/
│   ├── components/         # Reusable Astro components (TerminalHero, ApiConsole, etc.)
│   ├── layouts/            # Global page layouts (Layout.astro)
│   ├── pages/              # Route entry points (index.astro)
│   └── styles/             # Global CSS variables and utility classes
├── astro.config.mjs        # Astro configuration
└── package.json            # Project dependencies
```

## 🛠️ Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Davidcode-ai/portfolio-2026.git
   ```
2. **Install dependencies**:
   ```bash
   npm install
   ```
3. **Run the development server**:
   ```bash
   npm run dev
   ```
   The site will be available at `http://localhost:4321`.

## 🤝 Let's Connect

- [LinkedIn](https://www.linkedin.com/in/david-mu%C3%B1oz-vald%C3%A9s-8b26932b8/)
- [GitHub](https://github.com/Davidcode-ai)
- [WebDavid](https://webdavid.es)

---

*Drawn with code \& caffeine. © 2026 David Muñoz.*
