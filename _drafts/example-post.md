---
title: Example post (a cheat sheet)
description: Everything you can put in a post. Drafts are not published.
math: true
---

This file lives in `_drafts/`, so it never appears on the site. Copy it into `_posts/` with a date in the filename to publish it.

## Headings, emphasis, links

Use `##` for section headings inside a post. *Italics*, **bold**, and [links](https://www.redwoodresearch.org/) work as in any Markdown.

## Footnotes

A claim that needs a source.[^1] Another one.[^note]

[^1]: Footnotes gather at the bottom of the post.
[^note]: Labels can be words, not just numbers.

## Math

Set `math: true` in the front matter and write inline math with single dollars, like $E = mc^2$, and display math on its own lines:

$$
\int_0^1 x^2 \, dx = \frac{1}{3}
$$

## Quotes and code

> A blockquote. Two spaces at the end of a line  
> force a line break, which is handy for verse.

Inline `code` and fenced blocks:

```python
def hello():
    print("hi")
```

## Images

Put the file in `assets/images/` and reference it:

    ![Alt text](/assets/images/photo.jpg)

## Lists and tables

- One
- Two
  - Nested

| Column | Another |
|--------|---------|
| a      | b       |
