# FlyRank Frontend Capstone

## About

**Frontend capstone** for the FlyRank AI Engineering internship track. The app is a single-page experience for exploring and ranking flight options — helping users compare routes, prices, and carriers in a clear, accessible interface.

This repository focuses on building that experience with modern React patterns, disciplined Git workflows, and AI-assisted development in Cursor.

**Capstone goals:**

- Ship a production-quality Next.js frontend with semantic, accessible UI
- Demonstrate clean component architecture and maintainable TypeScript
- Practice Conventional Commits and thoughtful code review habits
- Use Cursor and project rules to accelerate development without sacrificing quality

## Tech Stack

- **Framework:** React / Next.js
- **Styling:** Tailwind CSS
- **Language:** TypeScript
- **AI Toolchain:** Cursor IDE integration

## Prerequisites

- Node.js (v18 or higher)
- npm / yarn / pnpm

## Getting Started

### Installation

```bash
git clone https://github.com/waleeja07-wk/FlyRank-AI_Capstone.git
cd FlyRank-AI_Capstone
npm install
```

### Environment Variables

Create a `.env.local` file in the root directory based on `.env.example`:

```bash
cp .env.example .env.local
```

### Running the Development Server

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

## Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Starts the development server |
| `npm run build` | Builds the app for production |
| `npm run lint` | Runs ESLint |

## Project Structure

```
FlyRank-AI_Capstone/
├── app/          # Routes, layouts, pages
├── components/   # Reusable UI components
├── lib/          # Utilities, types, hooks
├── public/       # Static assets
└── styles/       # Global styles
```

## Status

This project is in active development. Features and architecture are being defined as the capstone progresses — this README will be updated accordingly.

## Author

Waleeja Khan

## License

MIT — see [LICENSE](./LICENSE) for details.
