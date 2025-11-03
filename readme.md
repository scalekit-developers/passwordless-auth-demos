# Scalekit Passwordless Auth Demos

This repository contains a collection of **passwordless authentication** demo applications using [Scalekit](https://scalekit.com). Each subproject demonstrates how to implement secure, modern passwordless login flows (such as magic links) in different frontend and backend frameworks.

Explore how to build seamless passwordless authentication experiences using Scalekit in React, Next.js, Vue, SolidJS, and Express.js apps.

## Overview

The demos in this monorepo showcase real-world passwordless authentication flows powered by **Scalekit**. Each project provides a reference implementation for secure, user-friendly login without passwords, including email magic links, session management, and best practices for modern web apps.

## Example Use Cases

These demos highlight various passwordless authentication flows using **Scalekit**:

- **Magic Link Authentication**: Let users log in securely via a link sent to their email.
- **Frontend & Backend Integration**: See how to connect frontend frameworks (React, Next.js, Vue, SolidJS) with backend auth APIs.
- **Session Management**: Handle secure sessions, token storage, and logout.
- **Rate Limiting & Security**: Implement rate limits and security middleware for production-ready flows.
- **Docker Support**: Run backend demos easily with Docker Compose.

## Getting Started

To explore and run a demo project:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/scalekit-developers/passwordless-auth-demos.git
   cd passwordless-auth-demos
   ```

2. Navigate to a demo folder (for example, React client):

   ```bash
   cd react-passwordless-auth/client
   pnpm install
   pnpm run dev
   ```

   Or for Express backend:

   ```bash
   cd express-passwordless-auth
   npm install
   npm run dev
   # or
   docker-compose up
   ```

3. Follow the specific **README** inside each project folder for detailed setup and usage instructions.

## Project Structure

```text
passwordless-auth-demos/
|-- express-passwordless-auth/         # Express.js backend demo
|-- nextjs-backend-passwordless-auth/  # Next.js backend demo
|-- nextjs-passwordless-auth/          # Next.js frontend demo
|-- react-passwordless-auth/           # React frontend demo (with client/server)
|-- solid-passwordless-auth/           # SolidJS frontend demo
|-- vue-passwordless-auth/             # Vue/Nuxt frontend demo
|-- LICENSE
|-- readme.md
```

## Documentation & Support

- Read the official Scalekit documentation: [Scalekit Docs](https://docs.scalekit.com/)
- Need help? Open an issue in this repository or contact the Scalekit support team.
