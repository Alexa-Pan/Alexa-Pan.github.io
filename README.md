# alexa-pan.github.io

Personal site, built with [Jekyll](https://jekyllrb.com/) by GitHub Pages. Push to `main` and the site rebuilds in about a minute.

## Writing a post

1. Create a file in `_posts/` named `YYYY-MM-DD-some-title.md`. The date sets the order; the title part becomes the URL, so this example lands at `/blog/some-title/`.
2. Start it with front matter:

   ```
   ---
   title: Some title
   description: One line shown under the title on the blog index. Optional.
   math: true        # only if the post uses LaTeX; omit otherwise
   ---
   ```

3. Write Markdown below the front matter. `_drafts/example-post.md` shows everything that is supported (headings, footnotes, math, code, images, tables).
4. Commit and push, or create the file directly on GitHub in the browser.

Posts dated in the future are not published until that date. Files in `_drafts/` are never published.

## Layout

- `_layouts/default.html`: the shared header, nav and footer.
- `_layouts/post.html`: wraps a post with its date, title and a back link.
- `assets/css/site.css`: all styling.
- `index.html`, `blog.html`, `cv.html`: the three top-level pages.
- `_config.yml`: site settings. Change `url` here if you move to a custom domain.

## Previewing locally (optional)

Requires Ruby 3 (`brew install ruby`). Then, once:

```
bundle install
```

and to serve the site at http://localhost:4000 with live reload:

```
bundle exec jekyll serve --livereload --drafts
```

`--drafts` shows the files in `_drafts/` too.
