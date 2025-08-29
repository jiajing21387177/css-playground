# Modern CSS & HTML Playground

Welcome to the CSS Playground! This repository is a curated collection of hands-on examples demonstrating modern CSS and HTML features. It serves as a practical companion to the `GEMINI.md` front-end development golden standard, allowing you to see these cutting-edge platform features in action.

## Purpose

The goal of this project is to provide clear, concise, and isolated demonstrations of new web platform APIs and CSS capabilities. Each example is designed to be easy to understand and experiment with, helping developers adopt the modern practices outlined in our development standards.

## How to Use

Simply clone this repository and open the HTML files in your web browser to view the demos. No build step or server is required.

```bash
git clone <repository-url>
cd css-playground
# Open any .html file in your browser
```

## Demos

### Container Queries (`@container`)

- **[Media vs. Container Queries](./container-query/media-query-vs-container-query.html)**: A side-by-side comparison illustrating the power of container queries for building truly modular, self-contained components that respond to their container's size, not just the viewport's.

### Popover API

- **[Popover API Showcase](./popover/index.html)**: Explore the different types of native popovers (`auto`, `hint`, `manual`) for building accessible tooltips, menus, and dialogs with minimal effort.
- **[Popover with Anchor](./popover/popover-with-anchor.html)**: A powerful combination of the Popover API with CSS Anchor Positioning to create perfectly placed pop-ups.

### View Transitions API

- **[Basic Transition](./view-transition/index.html)**: A simple demonstration of the View Transitions API for creating smooth, app-like animations between DOM updates.
- **[Multi-Page App (MPA) Transitions](./view-transition/mpa-1.html)**: Experience seamless transitions between different HTML pages, bringing the fluidity of SPAs to traditional multi-page architectures. (Navigate between `mpa-1.html` and `mpa-2.html`).
- **[Single-Page App (SPA) Transition](./view-transition/spa.html)**: An example of how the API can be used within a single page to animate content changes.