# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

## Backend (FastAPI)

The API powering this UI now lives in a separate repository:

- **Repo:** https://github.com/1-WaleedAhmad/AI-Story-and-Poem-Generator
- **Live API (fine‑tuned):** https://WwaleedAhmad-aistorypoem-gpt2-finetuned.hf.space

> The model was fine‑tuned on a custom dataset using a free Google Colab GPU. The fine‑tuned model is hosted in the Space above.

The frontend expects the backend at `http://localhost:8000` when running locally. See the backend repo’s README for setup instructions.

## Frontend

- **Repo:** https://github.com/1-WaleedAhmad/AI-Story-and-Poem-Generator-FRONTEND
- **Live demo:** https://ai-story-and-poem-generator-frontend.vercel.app/

Currently two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type‑aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
