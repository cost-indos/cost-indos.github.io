# INDoS COST action

This repository contains the website for the INDoS COST action.

## About

Improving Neuroimaging Data for Sharing (INDoS) is a European [COST Action](https://www.cost.eu) ([CA24161](https://www.cost.eu/actions/CA24148/)) dedicated to transforming how human neuroimaging data is shared, standardized, and reused. Neuroimaging methods like MRI, MEG, EEG, and fNIRS are essential for advancing brain research, but data sharing is often hindered by inconsistent quality standards, missing metadata, unclear legal frameworks, and non-standardized preprocessing. INDoS brings together experts from across Europe and beyond to address these four key challenges: quality assessment and control, metadata standardization, preprocessing pipelines, and ethical and legal guidelines. By strengthening collaboration between researchers, software developers, data stewards, and legal experts, the Action aims to make neuroimaging data more transparent, interoperable, and reusable.

Through coordinated networking, the Action will develop guidelines, tools, training materials, and best practices that support FAIR (Findable, Accessible, Interoperable, Reusable) neuroimaging data sharing. It will build bridges between disciplines, foster a pan-European community, and train the next generation of researchers in open science practices. Ultimately, INDoS will enhance reproducibility, accelerate innovation—including AI applications—reduce research costs, and make neuroimaging research more inclusive and efficient across Europe and beyond.

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

3. Build the site:
   ```bash
   bundle exec jekyll build
   ```

4. Serve locally:
   ```bash
   bundle exec jekyll serve
   ```

5. Visit `http://localhost:4000` in your browser

### Updating Content

Simply edit the markdown files in the root directory, for example:
- `index.md` for the homepage
- `collaborators.md` for the collaborators page
- `work-packages.md` for work packages
- `contact.md` for the contact page

### Styling

The main stylesheet is in `assets/css/style.css`. Modify it to change colors, fonts, or layout.

## Deployment

The site is configured for GitHub Pages. Push to the main branch and GitHub Pages will automatically build and deploy the site.

## License

The content of this website is released under the [Creative Commons Attribution 4.0 International license](https://creativecommons.org/licenses/by/4.0/deed.en).
