# My Backend

A Node.js + Express.js backend application built with TypeScript.

## Features

- **Express.js** - Fast, unopinionated, minimalist web framework
- **TypeScript** - Static type checking for JavaScript
- **Hot Reload** - Development server with automatic restart on file changes
- **Production Build** - Compiled JavaScript for production deployment

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Install dependencies:
```bash
npm install
```

### Development

Start the development server with hot reload:
```bash
npm run dev
```

The server will start on `http://localhost:3000`

### Production

Build the project:
```bash
npm run build
```

Start the production server:
```bash
npm start
```

### Available Scripts

- `npm run dev` - Start development server with hot reload
- `npm run build` - Build the project for production
- `npm start` - Start the production server
- `npm run clean` - Clean the dist folder

## API Endpoints

- `GET /` - Hello World message
- `GET /api/health` - Health check endpoint

## Project Structure

```
src/
├── index.ts        # Main application file
dist/               # Compiled JavaScript files (generated)
package.json        # Dependencies and scripts
tsconfig.json       # TypeScript configuration
nodemon.json        # Nodemon configuration
```
