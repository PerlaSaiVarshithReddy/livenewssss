# Live News Fetcher

This repository hosts a static GitHub Pages site for the Live News Fetcher app.

## GitHub Pages setup

The site is configured for GitHub Pages using the `main` branch and a GitHub Actions workflow in `.github/workflows/gh-pages.yml`.

## Custom domain

The repository includes a `CNAME` file with the custom domain:

- `saivarshithreddy.com`

## Required DNS records

To make the custom domain work, add these DNS records at your domain provider:

- `A @ 185.199.108.153`
- `A @ 185.199.109.153`
- `A @ 185.199.110.153`
- `A @ 185.199.111.153`

If you also want `www.saivarshithreddy.com` to work, add:

- `CNAME www PerlaSaiVarshithReddy.github.io`

## Notes

- DNS changes can take a few minutes to a few hours to propagate.
- GitHub Pages deployment also requires the workflow to succeed.
- If the site still does not appear after DNS propagation, verify that the custom domain is configured in the repository settings.
