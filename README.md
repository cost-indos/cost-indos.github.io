# cost-indos.github.io
Website for the INDoS COST action

## About

This is a Jekyll-based website for the INDoS COST Action - Information Network on Data-driven Optimization and Simulation. The website features a modern, clean design with a focus on content pages rather than blog posts.

## Features

- **Homepage**: Welcome message and project overview
- **Collaborators Page**: Who is who - key members and their roles
- **Work Packages Page**: Description of research work packages
- **Contact Page**: Contact information and ways to get involved
- **Logo Support**: The header supports displaying a logo on all pages (see configuration below)
- **Responsive Design**: Mobile-friendly layout
- **Modern UI**: Clean, simple design with gradient hero section

## Setup

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

## Configuration

The site configuration is in `_config.yml`. Key settings:

- **Logo**: To add a logo, add the following line to `_config.yml`:
  ```yaml
  logo: /assets/images/logo.png
  ```
  Then place your logo image in the `assets/images/` directory.

- **Site Title**: Change the `title` field
- **Email**: Update the `email` field
- **Description**: Modify the `description` field

## Structure

- `_layouts/`: Page layouts
  - `default.html`: Main layout with header and footer
  - `page.html`: Layout for content pages
- `_includes/`: Reusable components
  - `header.html`: Site header with navigation
  - `footer.html`: Site footer
- `assets/`: Static assets
  - `css/style.css`: Main stylesheet
  - `images/`: Image assets (place logo here)
- Content pages:
  - `index.md`: Homepage
  - `collaborators.md`: Collaborators page
  - `work-packages.md`: Work packages page
  - `contact.md`: Contact page

## Customization

### Adding a Logo

1. Add your logo image to `assets/images/` (e.g., `logo.png`)
2. Add this line to `_config.yml`:
   ```yaml
   logo: /assets/images/logo.png
   ```
3. Rebuild the site

### Updating Content

Simply edit the markdown files in the root directory:
- `index.md` for the homepage
- `collaborators.md` for the collaborators page
- `work-packages.md` for work packages
- `contact.md` for the contact page

### Styling

The main stylesheet is in `assets/css/style.css`. Modify it to change colors, fonts, or layout.

## Deployment

The site is configured for GitHub Pages. Push to the main branch and GitHub Pages will automatically build and deploy the site.

## License

This website is for the INDoS COST Action project.
