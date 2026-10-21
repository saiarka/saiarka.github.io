# dotslashread

A small static website built with plain HTML and CSS. There is no framework, package manager, build step, or server-side code.

## Files

- `index.html` — home page with recent post links
- `about.html` — about page
- `posts/first-note.html` — example individual post
- `styles.css` — shared site-wide styles

## Preview locally

Open `index.html` in your browser. You can also use a local development server if you prefer, but it is not required for this site.

## Add a post

1. Copy `posts/first-note.html` and give the copy a descriptive filename, such as `posts/notes-on-learning.html`.
2. Update its `<title>`, description, date, heading, and body.
3. Keep the stylesheet path as `../styles.css` for pages inside `posts/`.
4. Add a new post preview to `index.html`, linking to the new file. Put newest posts first.

For now, the home page list is maintained by hand. That keeps the site easy to understand; if maintaining the list becomes tedious, we can revisit that later.
