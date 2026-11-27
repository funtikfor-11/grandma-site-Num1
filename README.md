# Grandma's Corner (Est. 1998)

A single-file retro personal homepage built with plain HTML and CSS. No JavaScript, no build tools, and no tracking cookies—unless Grandma baked them.

## How it works

All interactivity is handled through native HTML elements and CSS `:has()` selectors:

- **Tab navigation & quiz state:** Driven by hidden `<input>` radios and `:has()` rules. Getting all three quiz questions right unlocks an honor certificate at the bottom of the page.
- **No Glasses Mode:** A toggle in the header that scales the root font size up to `26px` and flips the palette—including inline SVG strokes and fills—into a high-contrast black-and-yellow theme.
- **Custom cursors:** Inline SVG data URIs replace the default cursor with a sewing needle and turn hovered interactive elements into a ball of red yarn.

## Sections

- **Recipe Box:** Index cards with collapsible ingredient lists and notes built with `<details>` and `<summary>`.
- **1998 Photo Album:** Dated entries paired with inline SVG sketches.
- **90s Memory Quiz:** Three trivia questions with instant green/red CSS feedback.

## Running locally

No dependencies or dev server needed:

```bash
git clone [https://github.com/funtikfor-11/grandma-site-Num1.git](https://github.com/funtikfor-11/grandma-site-Num1.git)
```

Open `index.html` in any modern browser (Chrome 105+, Firefox 121+, Safari 15.4+, or Edge 105+ for `:has()` support).
