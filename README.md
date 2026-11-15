# TaisTalecrafts

Source for [taistalecrafts.com](https://taistalecrafts.com), the portfolio of Taisiia Smirnova, a narrative designer and game writer.

Built with Jekyll and the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) remote theme, and hosted on GitHub Pages.

## Structure

| Path | What it holds |
|---|---|
| `_layouts/home.html` | Home page text (the About page reuses it) |
| `_pages/contact.md` | Contact page (`/contact/`, with a redirect from the old `/hire-me/`) |
| `_published-games/` | One file per game or project. `order:` sets its position on the Games page |
| `_writing-portfolio/` | One file per writing sample. `order:` sets its position on the portfolio page |
| `_includes/contact-cta.html` | The "Have a project or role in mind?" box shown at the end of pages |
| `_data/navigation.yml` | Top menu |
| `_config.yml` | Site title, sidebar bio, social links, preview image |
| `assets/` | Images and the CV PDF |

## Adding images

Keep images at web size (about 1600px wide, JPEG), so pages stay fast to load.

## Running locally

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
