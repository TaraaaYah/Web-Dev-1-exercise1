[README (5).md](https://github.com/user-attachments/files/26675154/README.5.md)
# Cooking with Andy

A simple, clean recipe website built with semantic HTML and CSS. Designed for readability with a minimal black-and-white layout, structured recipe content, and a handy tip box for ingredient substitutions.

## Features

- **Clean minimal design** — white background with light grey accents for header, aside, and footer
- **Recipe-focused layout** — structured sections for ingredients, instructions, and tips
- **Tip callout box** — grey `<aside>` element highlights useful substitution notes inline with the recipe
- **Readable typography** — Arial font constrained to 900px max-width for comfortable reading
- **No dependencies** — pure HTML and CSS, no frameworks or build tools required

## Structure

```
index.html        # Main page (header, recipe content, footer)
styles.css        # All styles (sourced from Cooking_with_Andy.txt)
```

## Layout Overview

### Header
Light grey background (`#dddddd`) with the site title (`h1`) and navigation links using default browser blue and purple for visited links.

### Main Content
Constrained to `max-width: 900px`. Contains the recipe title (`h2`), section headings for Ingredients and Instructions (`h3`), an unordered list for ingredients, and an ordered list for method steps.

### Aside (Tip Box)
Grey box (`background-color: #dddddd`) used to highlight ingredient substitution tips or cooking notes directly alongside the recipe content.

### Footer
Matching grey background (`#dddddd`), left-aligned, with top margin to separate it from the main content.

## Colours

| Use | Value |
|---|---|
| Page background | `#ffffff` (white) |
| Body text | `#000000` (black) |
| Header / aside / footer | `#dddddd` (light grey) |
| Nav links | `#0000ee` (browser blue) |
| Visited links | `#551a8b` (browser purple) |

## Typography

| Element | Font | Size |
|---|---|---|
| H1 (site title) | Arial | `2rem` |
| H2 (recipe title) | Arial | `1.5rem` |
| H3 (section headings) | Arial | `1.3rem` |
| Body / lists | Arial | `1rem` |

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/cooking-with-andy.git
   ```
2. Open `index.html` in your browser — no build step required.

## License

© Cooking with Andy. All rights reserved.
