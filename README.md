# Scribe Legal

GitHub Pages site for Scribe legal and privacy information.

## Local development

Use Ruby 3.3, install the GitHub Pages gem bundle, then serve the site locally:

```sh
bundle install
bundle exec jekyll serve
```

The privacy policy is available at the site root.

## Deployment

The site deploys through GitHub Actions from the `main` branch. In the repository settings, set Pages to use GitHub Actions as the source.
