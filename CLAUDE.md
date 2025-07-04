# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple webring site (webring.ooo) that displays a list of linked websites. The project consists of a single HTML file with embedded CSS and JavaScript.

## Architecture

- **Single-page application**: `index.html` contains the entire application
- **Static site**: No build process or server-side components
- **Client-side functionality**: JavaScript randomizes the order of webring links on page load
- **Simple styling**: Inline CSS creates a centered, vertical layout

## Key Components

- **Webring list**: Unordered list (`#webring`) containing website links
- **Randomization**: JavaScript shuffles the link order using `Math.random()`
- **Responsive design**: Flexbox layout centers content vertically and horizontally

## Development

To run the site locally with hot reload:
```bash
vite .
```

This will start a development server with hot reload functionality.

## Adding New Sites

New webring sites should be added as `<li>` elements within the `#webring` unordered list in `index.html`.