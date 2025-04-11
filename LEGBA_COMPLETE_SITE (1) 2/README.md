# LEGBA 🔮

This is the full project setup for LEGBA — a React + Vite + Tailwind app integrated with Deno linting and GitHub Actions.

## 📁 Root Directory
The root directory contains:
- `client/` — Main app source code (React, Vite, Tailwind)
- `.github/` — GitHub Actions workflow for Deno
- `deno.json` — Configuration for linting and formatting
- `README.md` — This file
- `package.json` (inside client)

## 🔨 Build Command
Inside `client/` folder:
```bash
npm run build
```

## 📦 Output Directory
After build, the output directory is:
```
client/dist/
```

## 💻 Install Command
To install dependencies, run:
```bash
cd client
npm install
```

## 🚀 Run Locally
To run the app locally:
```bash
npm run dev
```

## 🌐 Deployment (Vercel or Netlify)

### Vercel Settings
- Root Directory: `client`
- Build Command: `npm run build`
- Output Directory: `dist`
- Install Command: `npm install`

### Netlify Settings
- Build Command: `npm run build`
- Publish Directory: `client/dist`
- Optional File: `client/public/_redirects` for SPA support

## ✅ Features
- React + Tailwind + Vite frontend
- Deno linting + formatting via GitHub Actions
- Ready for deployment

---
Built with ❤️ by Cody AI.
