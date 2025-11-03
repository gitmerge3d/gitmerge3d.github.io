# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static website repository for the GitMerge3D research project - a GitHub Pages site showcasing research on 3D point cloud transformer token merging. The project presents a paper titled "How Many Tokens Do 3D Point Cloud Transformer Architectures Really Need?" by Tuan Anh Tran et al.

## Architecture

The project is a simple static website consisting of:

- `index.html` - Main landing page with complete research presentation including abstract, methodology, results, and citations
- `style.css` - Comprehensive styling with responsive design, gradient backgrounds, and animations
- `assets/` - Directory containing research images, diagrams, and visualizations (PNG files)
- `README.md` - Basic project description

## Development

This is a static HTML/CSS website with no build process or dependencies. All files are served directly.

### Local Development
- Open `index.html` directly in a browser for local preview
- No server setup required for basic development
- For proper local serving with assets, use any static file server (e.g., `python -m http.server` or similar)

### Asset Management
- All research imagery is stored in `assets/` directory
- Images include methodology diagrams, results visualizations, and comparison charts
- Placeholder PDF link exists for the research paper (`gitmerge3d.pdf`)

### Deployment
- Hosted on GitHub Pages
- Direct deployment from repository main branch
- Any commits to main automatically deploy the site

## Content Structure

The website follows academic paper presentation format:
- Header with title, authors, and affiliations
- Abstract and key contributions
- Method overview with visual diagrams
- Results section with computational efficiency metrics
- Acknowledgements and citation information
- Interactive BibTeX copy functionality via JavaScript