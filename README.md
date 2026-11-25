# Personal portfolio starter

A responsive personal portfolio built with Jekyll for GitHub Pages. The page includes an introduction, skills, three project cards, personal highlights, a project-pitch video link, and contact links. All sample copy is intended to be replaced.

## Personalize the template

Edit [`_data/portfolio.yml`](_data/portfolio.yml) to add your name, initials, role, background, skills, contact links, and project details. Replace each sample repository URL with a public GitHub repository that has its own README. Add a live demo URL or project-pitch video URL if you have one; leave those fields empty to hide the links.

Update the site title and description in [`_config.yml`](_config.yml). The visual design is in [`assets/css/style.css`](assets/css/style.css).

## Publish with GitHub Pages

1. Push these files to the repository’s default branch.
2. In the repository, open **Settings → Pages** and choose **Deploy from a branch**, the default branch, and the repository root (`/`).
3. If this is a project site (rather than a `username.github.io` site), set `baseurl` in `_config.yml` to `"/repository-name"`.
4. Wait for the Pages deployment, then open the URL shown under **Settings → Pages**.

GitHub Pages builds the site with Jekyll. To preview changes locally, install Ruby and Jekyll, then run `jekyll serve` from this folder.
