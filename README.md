# Technical Documentation Page

A simple, responsive technical documentation webpage built with plain HTML and CSS.

## Overview

This project contains a documentation-style layout with:
- A fixed left navigation bar on desktop
- Scrollable main content sections
- Anchor links for section navigation
- A mobile-friendly layout using a media query

## Project Structure

- `index.html` - Page structure and documentation content
- `styles.css` - Layout, typography, navigation, and responsive styles

## Run Locally

No build step or dependencies are required.

1. Open `index.html` in your browser.
2. Or serve the folder with a local static server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Sections Included

- Introduction
- Basic Syntax
- Data Types
- Functions
- Conclusion

## Customization

- Update section content in `index.html`
- Add/remove navigation links in the `#navbar`
- Adjust layout and colors in `styles.css`
- Modify the mobile breakpoint in the media query (`max-width: 768px`)

## License

This project is open for learning and personal use.
