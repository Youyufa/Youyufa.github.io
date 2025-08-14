# YOU Yufa's Academic Homepage

A clean academic homepage built with Jekyll and GitHub Pages.

## Quick Start

### Local Development

```bash
# Clone the repository
git clone https://github.com/Youyufa/Youyufa.github.io.git
cd Youyufa.github.io

# Install dependencies locally (避免权限问题)
bundle config set --local path 'vendor/bundle'
bundle install

# Serve locally
bundle exec jekyll serve --incremental
```

Visit `http://localhost:4000` to see your site.

### Deploy to GitHub Pages

Simply push to the `main` branch - GitHub Pages will automatically build and deploy your site.

## Features

### Academic Focus
- **Publications**: Automatically generated from BibTeX files in `_bibliography/papers.bib`
- **News**: Research updates and achievements in `_news/` folder
- **Projects**: Showcase your research work
- **Clean Design**: Professional academic layout

### Customization
- Edit `_config.yml` for site settings
- Modify `_pages/home.md` for homepage content
- Add publications to `_bibliography/papers.bib`
- Update author info in `_data/coauthors.yml`

## File Structure

```
├── _config.yml          # Site configuration
├── _pages/home.md       # Homepage content
├── _bibliography/       # Publications (BibTeX)
├── _news/              # News items
├── _data/              # Author and venue data
├── assets/             # Images, CSS, JS
└── Gemfile             # Ruby dependencies
```

## License

MIT
