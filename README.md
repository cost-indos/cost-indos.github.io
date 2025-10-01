# INDoS COST Action

This repository contains the website for the INDoS COST Action.

## About

Improving Neuroimaging Data for Sharing (INDoS) is a European [COST Action](https://www.cost.eu) ([CA24161](https://www.cost.eu/actions/CA24148/)) dedicated to transforming how human neuroimaging data is shared, standardized, and reused. Through coordinated networking, the Action will develop guidelines, tools, training materials, and best practices that support FAIR (Findable, Accessible, Interoperable, Reusable) neuroimaging data sharing. It will build bridges between disciplines, foster a pan-European community, and train the next generation of researchers in open science practices.

## Local setup for development and testing

### Prerequisites

- Ruby 3.x
- Bundler

### Installation

1. Clone the repository

2. Install dependencies:
   ```bash
   bundle config set --local path 'vendor/bundle'
   bundle install
   ```

3. Build and serve the site:
   ```bash
   bundle exec jekyll serve --incremental --livereload
   ```

4. Visit `http://localhost:4000` in your browser

### Updating Content

Simply edit the markdown files in the root directory, for example:
- `index.md` for the homepage
- `collaborators.md` for the collaborators page
- `working-groups.md` for Working Groups
- `contact.md` for the contact page

### Styling

The main stylesheet is in `assets/css/style.css`. Modify it to change colors, fonts, or layout.

## Deployment

The site is configured for GitHub Pages. Push to the main branch and GitHub Pages will automatically build and deploy the site.

## License

The content of this website is released under the [Creative Commons Attribution ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/deed.en).
