
# React + Vite

## Environment Variables

To use the resume enhancement features, you must provide a Gemini API key.

1. Create a `.env` file in the project root (if it doesn't exist).
2. Add the following line to your `.env` file:

```
VITE_GEMINI_API_KEY=your-gemini-api-key-here
```

Replace `your-gemini-api-key-here` with your actual Gemini API key.

The app will automatically use this key for Gemini API requests.

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript and enable type-aware lint rules. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
