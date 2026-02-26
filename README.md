# Brainwidth

**Brainwidth** presents an essay about the effective cognitive capacity available for reasoning, decision-making, creativity, and problem-solving in dynamic environments. The term serves as an integrative lens combining working memory, cognitive load, attention economics, and neuroplasticity.

The concept is presented as a heuristic model to encourage interdisciplinary dialogue rather than to replace established constructs such as working memory capacity, cognitive load, or executive control. The website/article addresses the definition of brainwidth, theoretical foundations (working memory, Cognitive Load Theory, attention and executive control, scarcity, neuroplasticity), brainwidth in the digital age, measurement proxies, practical implications for education, productivity, mental health, and technology design, and cited references (Baddeley, Sweller, Kahneman, Mullainathan & Shafir, among others).

## Project structure

```
brainwidth/
├── public/           # Static assets (favicon, etc.)
├── src/
│   ├── components/   # Astro components (e.g. Head.astro)
│   ├── layouts/      # Main layout (Layout.astro)
│   ├── pages/        # Pages and articles (index.md, helper.md)
│   └── styles/       # Global CSS (reset.css)
├── astro.config.mjs
├── package.json
└── README.md
```

---

## Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/whosramoss/brainwidth
cd brainwidth
npm install
```

## Development

Start the development server with hot-reload:

```bash
npm run dev
```

The site will be available at `http://localhost:4321` (or the port shown in the terminal).

## Build and preview

Production build:

```bash
npm run build
```

Output goes to `dist/`. To preview the build locally:

```bash
npm run preview
```

## License

[MIT](LICENSE)

## Author

[Gabriel Ramos](https://github.com/whosramoss/)
