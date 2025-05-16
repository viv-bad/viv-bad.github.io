# Personal Portfolio Website

This repository contains the source code for my personal portfolio website, built with Jekyll and hosted on GitHub Pages.

## Website Link

[https://viv-bad.github.io/](https://viv-bad.github.io/)
(Replace with your actual GitHub Pages URL. If it's a project site, it will be `https://viv-bad.github.io/repository-name/`)

## About This Site

This website showcases:

- An introduction about myself
- My projects
- My publications
- My CV
- A blog/news section (optional)

## Local Development

To run this site locally:

1.  **Prerequisites:**

    - Ruby (see [.ruby-version](/.ruby-version) if you add one, or check Jekyll docs for recommended version)
    - Bundler (`gem install bundler`)

2.  **Clone the repository:**

    ```bash
    git clone [https://github.com/viv-bad/yourrepository.git](https://github.com/viv-bad/yourrepository.git)
    cd yourrepository
    ```

3.  **Install dependencies:**

    ```bash
    bundle install
    ```

4.  **Serve the site:**

    ```bash
    bundle exec jekyll serve
    ```

5.  Open your browser and navigate to `http://localhost:4000`.

## Structure

- `_config.yml`: Site-wide configuration.
- `_data/`: Contains YAML files for projects and publications.
- `_includes/`: Reusable HTML snippets (header, footer, navigation).
- `_layouts/`: HTML templates for different page types.
- `_posts/`: Blog posts (if used).
- `assets/`: CSS, JavaScript, images, CV PDF.
- `pages/`: Markdown files for main site pages (Projects, Publications, CV).
- `index.md`: The homepage.

## Customization

- Update `_config.yml` with your personal details, social media links, etc.
- Replace content in `_data/projects.yml` and `_data/publications.yml`.
- Edit Markdown files in `pages/` and `index.md` for your content.
- Modify `assets/css/style.scss` to change the visual appearance.
- Add your CV PDF to `assets/cv/` and your profile picture to `assets/images/`.

## Deployment

Pushing to the `main` (or `master`) branch of this repository on GitHub will automatically build and deploy the site via GitHub Pages. Ensure your repository is named `viv-bad.github.io` for a user/organization site, or that GitHub Pages is enabled for the project repository (usually from the `main` branch and `/ (root)` folder).

---

This should give you a complete, functional starting point! Remember to replace all placeholder content with your own.
