# markgazki-vsl

This project is a high-conversion landing page (Video Sales Letter) for **Gazki Ltd**, focused on building international trade deals. It is built with Vue 3, TypeScript, and Tailwind CSS, leveraging Vite for a fast development experience.

## Project Overview

*   **Framework:** Vue 3 (Composition API with `<script setup>`)
*   **Build Tool:** Vite
*   **Language:** TypeScript
*   **Styling:** Tailwind CSS
*   **Key Components:**
    *   `VSLPlayer.vue`: Video player for the main sales letter.
    *   `CalendlyWidget.vue`: Integration for booking calls.

## Architecture & Structure

*   `src/main.ts`: Application entry point.
*   `src/App.vue`: Main layout and section structure.
*   `src/components/`: Reusable UI components.
*   `src/style.css`: Global styles and Tailwind directives.
*   `tailwind.config.js`: Custom theme configuration, including brand colors:
    *   **Primary:** `#D9AD3D` (Gold/Yellow)
    *   **Secondary:** `#1F2C35` (Dark Slate/Blue)

## Development

### Scripts

*   `npm run dev`: Starts the Vite development server.
*   `npm run build`: Runs `vue-tsc` for type checking and then builds the project for production.
*   `npm run preview`: Locally previews the production build.

### Conventions

*   **Components:** Use PascalCase for component filenames and references.
*   **Styling:** Prefer Tailwind utility classes. For recurring patterns, use custom utility classes in `src/style.css` (e.g., `.btn-primary`, `.section-padding`).
*   **TypeScript:** Ensure all components and scripts are type-safe.

## Components Deep Dive

### VSLPlayer.vue
*Handles the embedding and display of the Video Sales Letter.*

### CalendlyWidget.vue
*Handles the Calendly integration for lead capture and call booking.*
