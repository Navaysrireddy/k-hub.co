# K-Hub – Digital Knowledge Platform (Frontend)

## Overview

K-Hub is a digital knowledge platform that connects **students, colleges, and recruiters** in one ecosystem.
This repository contains the **frontend application** built with **React, TypeScript, and Vite**.

The frontend provides the user interface for interacting with the K-Hub platform.

---

## Tech Stack

* React
* TypeScript
* Vite
* HTML5 / CSS3
* Node.js (for development tools)

---

## Project Structure

```
frontend
 ├── public
 │   └── Logo.png
 │
 ├── src
 │   ├── App.tsx
 │   ├── main.tsx
 │   └── index.css
 │
 ├── index.html
 ├── package.json
 ├── tsconfig.json
 └── vite.config.ts
```

---

## Installation

Clone the repository:

```
git clone https://github.com/Navaysrireddy/k-hub.co.git
```

Navigate into the project:

```
cd frontend
```

Install dependencies:

```
npm install
```

---

## Run Development Server

```
npm run dev
```

Application will start at:

```
http://localhost:5173
```

---

## Build for Production

```
npm run build
```

The production build will be generated in the `dist` folder.

---

## Deployment

The frontend can be deployed as a **static site** on platforms such as:

* Render
* Netlify
* Vercel

Typical deployment settings:

Build Command:

```
npm run build
```

Publish Directory:

```
dist
```

---

## Environment Variables

If the frontend connects to a backend API, create a `.env` file:

```
VITE_API_URL=https://your-backend-api-url
```

Access it in the code using:

```
import.meta.env.VITE_API_URL
```

---

## Author

Developed for the **K-Hub Digital Knowledge Platform** project.
