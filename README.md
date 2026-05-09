# TaskFlow

A modern landing page for **TaskFlow** — a team productivity and project management platform.

## Overview

TaskFlow helps teams manage projects faster and smarter with real-time collaboration, smart task tracking, and productivity analytics.

## Tech Stack

- **HTML5**
- **Tailwind CSS** (via PostCSS)
- **Vanilla JavaScript**

## Features

- Responsive navigation with mobile hamburger menu
- Hero section with call-to-action buttons
- Feature cards highlighting key product capabilities
- CTA section for user conversion
- Footer with product, company, and contact links
- **Dark mode** support via Tailwind's `dark:` variant
- Hover animations (translate, shadow) on buttons and cards
- Keyboard and click-outside handling for mobile menu

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v16+)
- npm

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Jabir-Ahmed-43/taskflow.git
   cd taskflow
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the CSS:
   ```bash
   npm run dev
   ```
   This runs PostCSS to compile `./src/input.css` into `./output/output.css`.

4. Open `index.html` in your browser or use a live server (e.g., VS Code Live Server on port 5501).

## Project Structure

TaskFlow/
│
├── index.html
├── output/
│   └── output.css
├── src/
│   └── input.css
├── images/
└── README.md
