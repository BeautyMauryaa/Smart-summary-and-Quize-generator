# Smart Summary & Quiz Generator — UI Prototype

A React-based interface concept for turning study material into summaries and quiz workflows. The current repository contains the frontend UI and mock data; it does **not** currently contain the separate Node.js/Express upload-processing backend described in earlier notes.

## Screens and components

- Dashboard with summary statistics and recent activity
- Summary creation, list, and detail screens
- Quiz list, creation, taking, and results screens
- History and settings pages
- Reusable UI components for buttons, cards, inputs, selects, and badges

## Tech stack

- React with TypeScript
- Vite
- Tailwind CSS

## Run locally

Requires Node.js and npm.

```bash
cd project
npm install
npm run dev
```

Open the local URL printed by Vite.

Build the frontend:

```bash
npm run build
```

## Project structure

```text
project/
├── src/
│   ├── components/   # Dashboard, summary, quiz, settings, and UI components
│   ├── context/      # App context
│   ├── pages/        # Main screens
│   ├── services/     # Data service and mock data
│   └── types/        # Shared TypeScript types
├── package.json
└── vite.config.ts
```

## Current status

This is a frontend prototype. The data service and mock data are used by the current UI. Real file uploads, document parsing, AI summarization, quiz generation, and backend persistence should not be claimed as implemented until those services are added and tested.

## Author

**Beauty Mauryaa** · [GitHub](https://github.com/BeautyMauryaa)
