# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static academic website for Nicholas Ramsey (Assistant Professor of Mathematics, University of Notre Dame). Pure HTML/CSS with no build tools, frameworks, or dependencies. Hosted on GitHub Pages.

## Development

- **Preview locally**: Open `index.html` directly in a browser
- **Deploy**: Push to `main` branch; GitHub Pages deploys automatically within minutes

There is no build step, no package manager, no linter, and no test suite.

## Architecture

Single-page static site with two source files:

- **index.html** — All content in semantic HTML sections: header, about, research papers (with arXiv links), talks, and footer
- **style.css** — Responsive layout with three breakpoints (full width at 680px max, tablet at 768px, mobile at 480px)
- **images/** — Tree photographs used as visual dividers between sections

## Design Conventions

- Georgia serif font throughout for academic tone
- Color palette: `#fffef8` background, `#2b2b2b` body text, `#0066cc` links
- Single-column centered layout constrained to 680px max-width
- Custom list bullets using `·` character
- No JavaScript
