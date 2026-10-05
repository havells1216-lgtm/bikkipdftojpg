# PDF to JPG Studio

A real static PDF-to-JPG website.

## Features
- Upload a PDF in the browser
- Convert every page to JPG
- Control JPG quality
- Control render scale for sharper output
- Download each page separately
- Download all pages as a ZIP

## Tech
- PDF.js for PDF rendering
- JSZip for batch ZIP downloads

## Deploy
You can deploy this folder directly to:
- Vercel
- Netlify
- GitHub Pages
- Cloudflare Pages

## Important
This is a front-end-only website, but it uses CDN-hosted browser libraries. That means the deployed site needs internet access so PDF.js and JSZip can load in the user's browser.
