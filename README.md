# Nishaville Residences - Condo Listing Website

A static website showcasing a 2-bedroom condo with sea view in the Nishaville Residences complex. The website features a responsive design, image gallery, and bilingual support (Russian and English).

## Features

- Responsive design that works on all devices
- Image gallery with lightbox functionality
- Bilingual support (Russian/English)
- Contact form
- Google Maps integration
- Detailed property information

## Automatic Deployment with GitHub Pages

This repository is configured to automatically deploy to GitHub Pages whenever changes are pushed to the main branch, using GitHub Actions.

### How it Works

1. When you push changes to the `main` branch, a GitHub Actions workflow is triggered
2. The workflow builds and deploys the website to GitHub Pages
3. The deployed site is available at `https://[your-username].github.io/[repository-name]/`

### Setup Instructions

To use the automatic deployment to GitHub Pages:

1. Make sure your repository is public (or you have GitHub Pro for private repository Pages)
2. Go to your repository's Settings > Pages
3. Under "Source", select "GitHub Actions" 
4. The first workflow run will set up GitHub Pages for your repository
5. After the workflow completes, your site will be published to GitHub Pages

### Workflow Details

The GitHub Actions workflow is defined in `.github/workflows/deploy.yml` and:

- Triggers on pushes to the `main` branch
- Uses GitHub's official Pages deployment actions
- Deploys the entire repository content to GitHub Pages

## Local Development

To work on this website locally:

1. Clone the repository
2. Open `index.html` in your browser
3. Make changes to the HTML, CSS, or JavaScript as needed
4. Push changes to the `main` branch to trigger automatic deployment

No build step is required as this is a static HTML website.
