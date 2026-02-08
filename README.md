# Aisleron Documentation

This repo contains the documentation for Aisleron Shopping List. The site uses the [Just the Docs](https://github.com/just-the-docs/just-the-docs) Jekyll theme.

## Building and Running the Project

See [Just the Docs Template](https://github.com/just-the-docs/just-the-docs-template) for examples of how the theme is set up, build requirements, etc.

### Install required gems
`bundle install`

### Run the site locally
`bundle exec jekyll serve`

With live update:  
`bundle exec jekyll serve --livereload`

The site will run on http://localhost:4000

### Updating Code of Conduct, Contribution Guides, and Privacy Policy

From the root folder of this project, run the below commands in the terminal:

```
curl -o _includes/aisleron_contributing.md https://raw.githubusercontent.com/aisleron/aisleron/main/CONTRIBUTING.md
curl -o _includes/aisleron_code_of_conduct.md https://raw.githubusercontent.com/aisleron/aisleron/main/CODE_OF_CONDUCT.md
cp CONTRIBUTING.md _includes/docs_contributing.md
curl -o _includes/privacy_policy.md https://raw.githubusercontent.com/aisleron/aisleron/main/PRIVACY.md
```

