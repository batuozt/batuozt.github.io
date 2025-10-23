# Website Maintenance Guide

This repository contains a Hugo-based website located in the `batuozt-website` directory.

## Building the Website

To build the website locally:

```bash
cd batuozt-website
pnpm install  # Install dependencies (first time only)
hugo --minify  # Build the site
```

The generated site will be in `batuozt-website/public/`.

## Deploying to GitHub Pages

To deploy updates to the website:

1. Make changes to content in `batuozt-website/content/`
2. Build the site: `cd batuozt-website && hugo --minify`
3. Copy generated files to root: `cp -r batuozt-website/public/* .`
4. Commit and push changes to the repository

GitHub Pages will automatically serve the site from the root directory.

## Key Directories

- `batuozt-website/content/authors/admin/`: Your profile information
- `batuozt-website/content/_index.md`: Homepage content
- `batuozt-website/config/_default/`: Site configuration
- `batuozt-website/static/`: Static files (PDFs, images, etc.)

## Adding Content

### Update Biography
Edit `batuozt-website/content/authors/admin/_index.md`

### Update CV
Replace `batuozt-website/static/Batu_Ozturkler_CV.pdf` with the new PDF

### Add Publications
Create new markdown files in `batuozt-website/content/publications/`

### Change Profile Photo
Replace `batuozt-website/content/authors/admin/avatar.jpg`

## Hugo Resources

- Hugo Documentation: https://gohugo.io/documentation/
- Hugo Blox Documentation: https://docs.hugoblox.com/
