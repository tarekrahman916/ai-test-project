# test-project

A Node.js web application built with Next.js and TypeScript. The app lives at the project root — not in a nested subfolder.

## Tech Stack

| Category | Technology |
| -------- | ---------- |
| Runtime | Node.js |
| Language | TypeScript |
| Framework | Next.js (App Router) |
| UI | React, Tailwind CSS, shadcn/ui |
| Package Manager | npm |

## Project Structure

```
test-project/
├── app/              # Next.js App Router pages and layouts
├── components/       # Reusable React components
├── lib/              # Shared utilities and helpers
├── cursor/           # Cursor AI guidelines (not app source code)
│   └── cursor.md
├── package.json
└── README.md
```

## Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- npm (included with Node.js)

## Getting Started

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd test-project
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Available Scripts

| Script | Description |
| ------ | ----------- |
| `npm run dev` | Start the development server |
| `npm run build` | Create a production build |
| `npm run start` | Run the production server |
| `npm run lint` | Run ESLint |

> Scripts such as `dev`, `build`, `start`, and `lint` are available once the Next.js app is scaffolded.

## Environment Variables

Create a `.env.local` file in the project root for local environment variables. Do not commit secrets to version control.

## AI Guidelines

Project-specific rules and conventions for Cursor AI are documented in [`cursor/cursor.md`](./cursor/cursor.md).

## License

ISC
