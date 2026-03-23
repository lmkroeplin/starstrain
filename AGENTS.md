# STARS Training

## Purpose
STARS - Safety Training and Response Strategies, LLC — business website.

## Stack
- **Type:** Static HTML site

## Architecture
- Static HTML pages with images

## CI/CD
CI runs on push/PR to `main`: html-validate, axe-core accessibility. All steps use `continue-on-error: true`.

## Testing
No test suite — CI validates HTML structure and accessibility automatically.

## Deploy
Pushes to `main` auto-deploy via Cloudflare Pages.
