# CSS Tutorial

A hands-on HTML & CSS reference covering essential concepts for modern web styling.

## Project Structure

```
css-tutorial/
├── index.html              ← Start here (topic index)
├── css/
│   └── styles.css          ← Shared stylesheet
├── pages/
│   ├── headings.html
│   ├── paragraph.html
│   ├── css-types.html
│   ├── font-related.html
│   ├── class-and-id.html
│   ├── margin-padding-border.html
│   ├── display.html
│   ├── cursor-types.html
│   ├── types-of-tags.html
│   └── audio-video.html
└── README.md
```

## Topics Covered

| Page | What you'll learn |
|------|-------------------|
| Headings | h1–h6 levels, semantic hierarchy |
| Paragraph & Inline Tags | b/strong, i/em, mark, del, sup/sub, abbr, pre |
| Types of CSS | Inline, internal, external — cascade order |
| Font Properties | font-family, font-size, font-weight, font-style, font-variant, font-stretch |
| Class & ID Selectors | `.` vs `#`, specificity, overflow |
| Margin, Padding & Border | Box model, shorthand, border styles, border-radius |
| Display Property | block, inline, inline-block, none, visibility, float |
| Cursor Types | All cursor values with live hover demos |
| Types of Tags | Semantic/non-semantic, block/inline, container/void |
| Audio & Video | `<audio>`, `<video>`, `<iframe>`, `<object>` |

## How to Use

Open `index.html` in any browser — no build step required.
Each topic page links back to the index via a breadcrumb at the top.

## Code Conventions

- All files use consistent 2-space indentation
- Styles are separated from markup: page-specific overrides live in `<style>` blocks; shared base styles live in `css/styles.css`
- Deprecated HTML attributes (`align`, `bgcolor`, `border` on tags) replaced with CSS
- No dead/commented-out code blocks
- Meaningful `<title>` tags on every page
- Semantic HTML throughout (no `align=center` attributes, proper `alt` text on images)
