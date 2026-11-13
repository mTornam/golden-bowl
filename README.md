# Golden Bowl 🍜

A responsive restaurant website built with React and Vite. Explore the restaurant, browse its menu, view the gallery, and find the reservation form.

**Live site:** [gbres.netlify.app](https://gbres.netlify.app)

## Features

- Restaurant landing page with hero, introduction, and about sections
- Menu and menu-category views
- Photo gallery
- Reservation form interface
- Responsive layout

## Tech stack

- [React 19](https://react.dev/)
- [Vite 7](https://vite.dev/)
- [Tailwind CSS 4](https://tailwindcss.com/) and CSS
- [React Router 7](https://reactrouter.com/)
- [Font Awesome](https://fontawesome.com/)

## Run locally

### Requirements

- Node.js
- npm or pnpm

### Install dependencies

```bash
git clone https://github.com/mTornam/golden-bowl.git
cd golden-bowl
npm install
```

### Start the development server

```bash
npm run dev
```

Open the local URL printed by Vite (usually `http://localhost:5173`).

## Available scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the Vite development server |
| `npm run build` | Create a production build in `dist/` |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint |

## Project structure

```text
src/
├── components/
│   ├── Menu/          # Menu data and menu components
│   ├── Reservations/  # Reservation form
│   └── sections/      # Landing-page sections
├── App.jsx
└── main.jsx
```
