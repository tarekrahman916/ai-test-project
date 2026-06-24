# Cursor AI Guidelines

This file provides context and instructions for Cursor AI when working on this project.

## Project Overview

- **Project:** test-project
- **Root:** `f:\AI\test-project` — the Next.js app lives here directly, not in a nested subfolder
- **Type:** Node.js web application

## Project Structure

- Application code (`app/`, `components/`, `lib/`, `package.json`, etc.) goes in the **project root**
- The `cursor/` folder is for AI guidelines and docs only, not application source code

## Tech Stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Next.js (App Router preferred unless the project already uses Pages Router)
- **UI:** React, Tailwind CSS, shadcn/ui
- **Package Manager:** npm

## Coding Standards

- Write all application code in TypeScript with strict, explicit types
- Use Next.js conventions: Server Components by default, Client Components only when needed
- Follow the root-level Next.js folder structure (`app/`, `components/`, `lib/`, etc.)
- Keep components small, reusable, and well-typed
- Prefer async/await and modern Node.js APIs
- Add comments only when logic is non-obvious

## Workflow

- Prefer reusing existing functions and components over duplicating logic
- Run `npm run lint`, `npm run build`, and tests when available before finishing a task
- Do not commit changes unless explicitly requested

## Notes

Add project-specific rules, architecture notes, and conventions here as the project grows.
