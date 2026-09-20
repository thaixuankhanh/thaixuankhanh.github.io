# thaixuankhanh.github.io

Source for my personal academic homepage, built with Jekyll and hosted on GitHub Pages.

## Structure

```
.
├── _data/publications.yml     # publication list
├── _includes/                 # publications.md, experience.md, projects.md
├── _layouts/homepage.html     # page layout
├── _sass/                     # styles (minimal-light.scss controls dark mode too)
├── assets/                    # images, css, js
├── _config.yml                # site metadata and options
└── index.md                   # homepage content
```

## Local development

```bash
bundle install
bundle exec jekyll server
```

Then open <http://localhost:4000>.

## Credits

Built on the [Minimal Light](https://github.com/yaoyao-liu/minimal-light) Jekyll theme.
