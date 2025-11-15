# Agent Guidelines for Account Platform

## Build Commands
- Frontend: `npm run dev`, `npm run build`, `npm run lint`
- API: `cargo build`, `cargo run`, `cargo test`
- Single test: `cargo test <test_name>`

## Code Style
- TypeScript: Strict mode enabled, use `@/*` path aliases
- React: Use functional components with TypeScript types
- Rust: 2024 edition, standard formatting
- ESLint: Next.js config with TypeScript rules
- Tailwind CSS for styling
- Import order: React/Next.js imports first, then third-party, then local imports
- Error handling: Use TypeScript strict types, proper error boundaries in React