# Ganesh Portfolio

A personal portfolio project built with React and Vite. The current version is an early-stage foundation for a developer portfolio and already includes a custom loading screen, dark theme styling, and a branded navigation bar.

## Current Status

This repository is still in progress. Right now, the implemented UI focuses on the first layer of the experience:

- Animated loading screen that types `<Ganesh/>`
- Fixed top navigation bar with portfolio branding
- Dark visual theme with `Space Grotesk` typography
- Placeholder section files for `Home`, `About`, `Projects`, and `Contact`

## Tech Stack

- React 19
- Vite 7
- Tailwind CSS via `@tailwindcss/vite`
- ESLint 9

## Project Structure

```text
src/
  App.jsx
  main.jsx
  index.css
  components/
    LoadingScreen.jsx
    Navbar.jsx
    section/
      Home.jsx
      About.jsx
      Project.jsx
      contact.jsx
```

## Getting Started

1. Install the base dependencies:

```bash
npm install
```

2. Install the Tailwind packages used by the current Vite config:

```bash
npm install -D tailwindcss @tailwindcss/vite
```

3. Start the development server:

```bash
npm run dev
```

4. Create a production build when needed:

```bash
npm run build
```

## Notes

- The app entry point is `src/App.jsx`.
- The loading animation lives in `src/components/LoadingScreen.jsx`.
- Navigation branding lives in `src/components/Navbar.jsx`.
- The section components inside `src/components/section/` are currently scaffolds and still need full content.

## License

This project is for personal portfolio use.
