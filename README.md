# electron-first-app

>A modern Electron application scaffolded with Electron Forge and Vite.

## Project Overview

**electron-first-app** is a cross-platform desktop application built with Electron, TypeScript, and Vite. It features a simple window displaying a homepage for "Luz Y Vida Hogar" (a residential home for seniors).

## Features
- Electron 38
- Vite-powered development and build
- TypeScript for main, preload, and renderer processes
- Hot reload for renderer
- Windows, Linux, and macOS packaging

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18 or newer recommended)
- [npm](https://www.npmjs.com/)

### Installation
```sh
git clone https://github.com/sofowest/electron-first-app.git
cd electron-first-app
npm install
```

### Running in Development
```sh
npm start
```
This will launch the Electron app with Vite dev server for hot reload.

### Building for Production
```sh
npm run make
```
The output installers/packages will be in the `out/` directory.

