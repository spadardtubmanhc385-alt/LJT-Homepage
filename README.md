# LJT-Homepage

Personal academic homepage of **Junteng Liu**, first-year PhD candidate at the HKUST NLP Group.

This site is a fork of [academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io) and is built with the Academic Pages template (Jekyll).

## Contents

- **About** (`_pages/about.md`, the home page): biography, research interests, education, research experience, publications, skills, honors and awards, and contact information.
- **Publications** (`_publications/`, listed on the Publications page): individual publication entries.

## Configuration

- `_config.yml`: site-wide settings and the author sidebar.
- `_data/authors.yml`: author profile data.
- `_data/navigation.yml`: header navigation (About, Publications).

## Deployment

The GitHub Actions workflow `.github/workflows/jekyll.yml` builds the site with Jekyll on every push to `master` and deploys it to GitHub Pages.

One-time setup required: enable GitHub Pages for this repository under **Settings → Pages → Build and deployment → Source: GitHub Actions**. The workflow's built-in token cannot create the Pages site itself, so this must be enabled once in the repository settings; afterwards every push deploys automatically.

Once enabled, the site will be available at `https://spadardtubmanhc385-alt.github.io/LJT-Homepage/`.
