# Mypage

This is Yurukatsu's personal website built with React + TypeScript + Vite.

## Technologies

- React 19.0.0
- TypeScript
- Vite (Build tool)
- ESLint (Code linting)
- GitHub Pages (Deployment)

## Installation

To install the dependencies, run:

```bash
npm install
```

## Development

To start the development server, run:

```bash
npm run dev
```

This will start a local development server at `http://localhost:5173/`.

## Building

To build the project for production, run:

```bash
npm run build
```

This will create a `dist` directory with the compiled assets.

## Preview

To preview the production build locally, run:

```bash
npm run preview
```

## Deployment

This project is configured to deploy to GitHub Pages. To deploy, run:

```bash
npm run deploy
```

This will build the project and deploy it to the GitHub Pages site specified in the `homepage` field of `package.json`.

## Project Structure

```
mypage/
├── public/          # Static assets
├── src/             # Source code
│   ├── assets/      # Project assets (images, etc.)
│   ├── App.tsx      # Main application component
│   └── main.tsx     # Entry point
├── index.html       # HTML template
└── package.json     # Project configuration
```

## License

This project is private and not licensed for public use.
