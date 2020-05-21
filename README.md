# Tinker Template

This repository is a template for tinkering with frontend projects. It uses [Parcel](https://parceljs.org) to easily bundle up frontend assets that can be deployed to [Zeit](https://zeit.co) for sharing.

It makes use of:

- Plain HTML for HTML
- [Tailwind CSS](https://tailwindcss.com) for CSS
- [Open Color](https://yeun.github.io/open-color/) color variables
- [TypeScript](https://www.typescriptlang.org) for JavaScript

## Use

1. Clone: `git clone https://github.com/jclem/tinker.git` and `cd` into `./tinker`
1. Install dependencies: `npm install`
1. Tinker! Edit `src/index.html`, `src/js/index.ts`, and `src/css/index.styl`.

## Scripts

A number of scripts are in [package.json](package.json) for developing, building, and deploying:

- `npm run dev` This starts a Parcel development server (with live reload, etc.)
- `npm run build` This simply builds to the "public" directory (which is .gitignore-ed)
- `npm run deploy` This deploys the project Zeit
