# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Jekyll-based academic personal homepage built on the Minimal Mistakes theme. The site is hosted on GitHub Pages at `https://njuzyh.github.io` and serves as the academic portfolio for Yuhang Zhou, a Ph.D. candidate at Nanjing University.

## Key Features

- **Automatic Google Scholar Citation Updates**: Uses GitHub Actions to crawl Google Scholar data daily and update citation counts
- **Responsive Design**: Built with the Minimal Mistakes Jekyll theme
- **SEO Optimized**: Includes Google Analytics and search engine verification
- **Publication Management**: Displays academic publications with citation counts and links

## Development Environment

### Prerequisites
- Ruby and RubyGems
- Jekyll (via `github-pages` gem)
- Python 3.x (for Google Scholar crawler)

### Setup Commands
```bash
# Install Ruby dependencies
bundle install

# Install Python dependencies for Google Scholar crawler
cd google_scholar_crawler
pip install -r requirements.txt
```

### Local Development
```bash
# Start Jekyll development server with live reload
bash run_server.sh
# or
bundle exec jekyll serve -l --host=0.0.0.0 --port=4000
```

The site will be available at `http://127.0.0.1:4000`

## Build and Deployment

- **Automatic Deployment**: GitHub Pages automatically builds and deploys from the main branch
- **Manual Build**: `bundle exec jekyll build` generates static files in `_site/` directory
- **Google Scholar Integration**: Requires `GOOGLE_SCHOLAR_ID` secret in GitHub repository settings

## File Structure

- `_config.yml`: Main configuration file (site title, author info, plugins)
- `_pages/about.md`: Main content page with academic profile and publications
- `_includes/`: HTML partials and templates
- `_sass/`: SCSS stylesheets
- `assets/`: Static assets (CSS, JS, images)
- `google_scholar_crawler/`: Python script for fetching citation data
- `files/`: Academic papers and documents

## Google Scholar Integration

The repository uses a GitHub Action workflow (not visible in current branch) that:
1. Runs daily at 08:00 UTC
2. Fetches citation data using the Python crawler
3. Stores results in the `google-scholar-stats` branch
4. Updates citation counts displayed on the homepage

## Content Management

- **Publications**: Add new publications to `_pages/about.md` using the provided HTML/Markdown format
- **Profile Information**: Update author details in `_config.yml`
- **Styling**: Modify SCSS files in `_sass/` directory
- **SEO**: Configure search engine verification in `_config.yml`

## Common Tasks

- **Add new publication**: Edit `_pages/about.md` following the existing paper format
- **Update profile**: Modify `author` section in `_config.yml`
- **Change styling**: Edit SCSS files in `_sass/` directory
- **Test locally**: Run `bash run_server.sh` and visit http://127.0.0.1:4000
- **Deploy changes**: Push to main branch (GitHub Pages auto-deploys)

## Dependencies

- **Ruby Gems**: github-pages, jekyll-feed, jekyll-sitemap, hawkins, webrick
- **Python Packages**: scholarly, jsonpickle (for Google Scholar crawler)

## Theme Customization

This site uses the Minimal Mistakes Jekyll theme with customizations in:
- `_sass/`: Custom SCSS styles
- `_includes/`: Custom HTML partials
- `_layouts/`: Custom layout templates

For theme documentation, refer to: https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/