# Golden Bowl 🍜

Golden Bowl is a React + Vite restaurant landing page for a modern dining brand. The app includes a marketing-style homepage, menu browsing, gallery, and reservation form, and is designed as a responsive single-page experience.

**Live demo:** [gbres.netlify.app](https://gbres.netlify.app)

## Stack

- React 19
- Vite 7
- Tailwind CSS 4
- React Router 7
- Font Awesome
- ESLint

## Project overview

The app is organized as a front-end landing page with reusable section components and data-driven menu rendering. It uses a component-based structure to keep content modular and easy to extend.

## Getting started

### Prerequisites

- Node.js 18+
- npm or pnpm

### Install

```bash
git clone https://github.com/mTornam/golden-bowl.git
cd golden-bowl
npm install
```

### Run locally

```bash
npm run dev
```

The Vite dev server will print a local URL, typically:

```text
http://localhost:5173
```

### Production build

```bash
npm run build
```

Generate a production bundle in the `dist/` directory.

### Preview production build

```bash
npm run preview
```

### Linting

```bash
npm run lint
```

## Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the Vite dev server |
| `npm run build` | Build the app for production |
| `npm run preview` | Serve the production build locally |
| `npm run lint` | Run ESLint on the project |

## Structure

```text
golden-bowl/
├── public/                 # Static assets
├── src/
│   ├── components/
│   │   ├── Menu/           # Menu categories, items, and data
│   │   ├── Reservations/   # Reservation form logic and UI
│   │   └── sections/       # Landing page sections
│   ├── App.jsx
│   ├── main.jsx
│   ├── App.css
│   └── index.css
├── index.html
├── package.json
├── vite.config.js
├── eslint.config.js
├── README.md
├── package-lock.json
└── pnpm-lock.yaml
```

## Notes for contributors

- The app is intentionally front-end focused; most updates happen in `src/components` and `src/App.jsx`.
- Menu content is kept separate in the `Menu` module for easier maintenance.
- Styling is handled primarily through Tailwind and component CSS.
- For UI changes, prefer updating the section-level components rather than creating one-off inline styles.

## License

This project is open source and available under the MIT License.
