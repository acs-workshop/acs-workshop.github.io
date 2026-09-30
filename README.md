# ACSW website

Jekyll site for the Workshop on Automotive Cyber Security, deployed to GitHub Pages with GitHub Actions.

## Local development

The project targets the Ruby version declared in `.ruby-version` and Jekyll from `Gemfile`.

```bash
bundle install
bundle exec jekyll serve
```

Open <http://127.0.0.1:4000/>.

## Deployment

GitHub Pages must use **Settings → Pages → Source → GitHub Actions**. Every push to `main` builds the site with the Jekyll version from `Gemfile` and deploys `_site`.
