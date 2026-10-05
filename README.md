# Salam SiteForge

A small, multi-page website starter built with the [Salam Programming Language](https://github.com/SalamLang/Salam) and its built-in `layout:` DSL.

SiteForge is designed as a practical starter for a portfolio, freelancer profile, small-business site, or landing page. It demonstrates how Salam layout pages can be compiled into HTML/CSS/JS while keeping the source readable and easy to customize.

## Project structure

- `salam.salam` — homepage
- `site/about.salam` — secondary About page
- `examples/portfolio.salam` — reusable portfolio starter
- `docker/` — notes for containerized compiler workflows
- `docker-compose.yml` — placeholder compose configuration

## Build

Install Salam using the official installation instructions, then build the pages from the project root:

```bash
salam layout build salam.salam
salam layout build site/about.salam
```

For a self-contained HTML file, Salam also supports:

```bash
salam layout build salam.salam --inline
```

The official Salam documentation explains that layout projects compile `.salam` pages to HTML, CSS, and JavaScript output. A layout page does not need a `main` function.

## What the project demonstrates

- Multiple Salam layout pages
- Navigation between generated pages
- Responsive service-card layout using grid attributes
- Headers, sections, lists, links, and footers
- A reusable portfolio example
- A realistic multi-file project structure rather than a single Hello World program

## Customizing

Edit the content and layout attributes in `salam.salam`, `site/about.salam`, or copy `examples/portfolio.salam` as a starting point for another page.

## AI-assisted development

AI assistance was used during development. The project is intended to remain understandable, editable, and runnable by a human developer using the Salam toolchain.

## License

MIT.

## Salam

Official repository: https://github.com/SalamLang/Salam
