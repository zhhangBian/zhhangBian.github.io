# Zhuohang Bian's Academic Homepage

Personal academic homepage built with Jekyll and deployed automatically through GitHub Actions.

## Editing the homepage

- Main page content: edit `_pages/about.md`.
- Name, email, avatar, CV link, and other profile fields: edit `_config.yml`.
- Top navigation: edit `_data/navigation.yml`.
- Images: add files under `images/`, then reference them with a path such as `images/photo.png`.

You can edit these files either locally or directly on GitHub. A push or web edit committed to `main` automatically starts the Pages workflow.

## Local preview

```bash
bundle install
bundle exec jekyll serve
```

The local site is available at <http://127.0.0.1:4000>. Changes to `_config.yml` require restarting the server.

## Deployment

Every push to `main` runs `.github/workflows/deploy-pages.yml`. The workflow installs the locked Ruby dependencies, runs `bundle exec jekyll build`, uploads `_site`, and deploys it to <https://zhhangbian.github.io/>.

You can also run the workflow manually from **Actions > Build and deploy academic homepage > Run workflow** on GitHub.
