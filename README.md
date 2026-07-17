# Anniversary Experience

A polished, media-rich anniversary web experience built as a static HTML site and deployed through GitHub Pages. The project combines custom styling, personal image/video assets, music, and interactive presentation states to create a memorable browser-based celebration.

## Overview

This repository contains a self-contained anniversary page designed to run without a backend or build step. The experience is centered around `index.html`, with supporting media stored in `media/` and background audio in `Music/`.

## Key Features

- Static HTML/CSS/JavaScript implementation
- GitHub Pages deployment workflow
- Full-screen romantic visual presentation
- Personal photo and video gallery assets
- Background music support
- Responsive layout for mobile and desktop screens
- `.nojekyll` configuration for reliable static asset hosting

## Repository Structure

```text
.
├── index.html                     # Main deployed experience
├── Happy Anniversary V1.html       # Earlier/alternate version
├── media/                          # Image and video assets
├── Music/                          # Audio asset
├── .github/workflows/pages.yml     # GitHub Pages deployment workflow
└── .nojekyll                       # Disables Jekyll processing on Pages
```

## Running Locally

No package installation is required.

```bash
# Option 1: open directly
start index.html

# Option 2: serve with a local static server
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deployment

The repository includes a GitHub Actions workflow that deploys the full static project to GitHub Pages whenever changes are pushed to `main`.

Workflow file:

```text
.github/workflows/pages.yml
```

## Notes

This is a personal creative web project. Media files are part of the experience and should be handled with privacy and ownership in mind.
