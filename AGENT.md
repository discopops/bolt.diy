# AGENT.md

## Repository Overview

bolt.diy is an AI-powered, open-source full-stack web development environment operating directly in the browser, enabling users to choose their preferred Large Language Model (LLM) for coding tasks. It integrates a wide array of AI providers and offers comprehensive tools for code generation, project deployment, and efficient project management.

## Key Technologies & Frameworks

- **Core Languages/Runtimes**: TypeScript, Node.js
- **Frontend**: Remix, React
- **Package Management**: pnpm
- **AI Integration**: Vercel AI SDK, extensive support for 19+ LLM providers (OpenAI, Anthropic, Google Gemini, Groq, etc.)
- **Deployment**: Cloudflare Pages, Netlify, Vercel, GitHub Pages
- **Database**: Supabase
- **Desktop Application**: Electron
- **Containerization**: Docker
- **Testing**: Vitest
- **Code Quality**: ESLint, Prettier
- **Virtual Environment**: WebContainers API

## Main Features

- **AI-Driven Development**: Full-stack web development with customizable LLM integration.
- **Multi-LLM Support**: Compatibility with over 19 diverse AI providers.
- **Integrated Tooling**: Terminal, Git integration, codebase search, diff views, file locking.
- **Deployment & Portability**: Direct deployment to various platforms and project download/snapshot features.
- **Rich UI/UX**: Data visualization, image attachment to prompts, voice prompting, project snapshot restoration.
- **Extensibility**: MCP (Model Context Protocol) for enhanced AI tool integration.
- **Platform Agnostic**: Available as a web application and an Electron desktop app.

## Architectural Patterns

- **Full-Stack Application**: Combines frontend and backend logic for in-browser development.
- **Client-Server Architecture**: Browser-based client interacting with various APIs and backend services.
- **Extensible Provider Model**: A modular design for integrating diverse AI models and services.
- **Microservices/API-Driven**: Relies on interactions with external LLM APIs, Supabase, and deployment services.
- **Desktop Adaptation**: Electron framework extends the web application to a native desktop experience.
- **Containerization**: Utilizes Docker for isolated development and production environments.
- **Monorepo Structure**: Manages multiple related projects (app, electron, functions) within a single repository.
