# YOU Yufa's Academic Homepage

This homepage is built with Hexo using the Redefine theme.

## Local Development

```bash
npm install
npm run server
```

Visit `http://localhost:4000` to preview the site.

## Build

```bash
npm run build
```

The generated site will be in `public/`.

## Structure

```
├── _config.yml                 # Hexo configuration
├── source/index.ejs            # Homepage content
├── source/assets/              # Images, PDFs, videos
├── source/news/                # Legacy news snippets
├── source/css/home.css         # Custom homepage styling
└── themes/redefine/_config.yml # Theme configuration
```

## Notes

- The blog index is moved to `/blog` so the homepage can live at `/`.
- Update content in `source/index.ejs` and assets in `source/assets/`.
