# HTML Tricks

A small collection of standalone HTML/CSS/JavaScript animation demos.

## Demos

- `index.html` - Morphing text animation using `style/animation.css` and `scripts/text-animation.js`.
- `fireworks.htm` - Pure CSS fireworks effect using `style/fireworks.css`.
- `animate_div.htm` - Full-screen animated color grid using CSS keyframes.
- `div_fun.html` - Interactive expanding quadrant layout powered by jQuery (`scripts/jquery.js`).
- `header_card.html` - Moving/rotating header card animation using CSS keyframes.

## Project Structure

```text
HTML_Tricks/
|-- index.html
|-- fireworks.htm
|-- animate_div.htm
|-- div_fun.html
|-- header_card.html
|-- scripts/
|   |-- text-animation.js
|   |-- jquery.js
|   `-- jquery-ui.js
|-- style/
|   |-- animation.css
|   `-- fireworks.css
|-- LICENSE
`-- README.md
```

## Run Locally

No build step is required.

1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd HTML_Tricks
   ```
2. Open any demo file directly in your browser:
   - `index.html`
   - `fireworks.htm`
   - `animate_div.htm`
   - `div_fun.html`
   - `header_card.html`

For best results, use a modern Chromium, Firefox, or Safari browser.

## Notes

- These demos are intentionally simple and independent, so each file can be tested on its own.
- Some animations use legacy `-webkit-` keyframe syntax for compatibility with older examples.

## License

This project is licensed under the MIT License. See `LICENSE` for details.
