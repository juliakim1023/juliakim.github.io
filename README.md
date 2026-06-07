# juliakim.github.io

Personal website of Dr Julia Minji Kim — built with [Jekyll](https://jekyllrb.com/) and hosted on GitHub Pages at <https://juliakim.github.io>.

## Editing the content

All text lives in **`_data/cv.yml`**. Edit that file to update any section — you don't need to touch HTML or CSS. Commit and push to `main` and GitHub Pages rebuilds the site automatically (usually within a minute).

## Structure

| File | Purpose |
| --- | --- |
| `_data/cv.yml` | All site content (the only file you normally edit) |
| `index.html` | Page template that renders the content |
| `_layouts/default.html` | HTML shell (head, fonts, meta) |
| `assets/css/style.css` | Styling |
| `_config.yml` | Site title, description, build settings |

## Running locally (optional)

```bash
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000>.

## Privacy note

Some details from the source CV (home address, mobile number, AHPRA registration
number, residency status) were intentionally left off this **public** site. To
add any of them back, edit `_data/cv.yml`.
