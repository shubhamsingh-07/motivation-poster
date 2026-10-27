# Motivational Poster

[![HTML5](https://img.shields.io/badge/HTML5-markup-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-styling-blue.svg)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

A simple, static motivational poster made with HTML and CSS. It combines a full-width image inside a bordered frame with a centered motivational headline and supporting text on a dark background.

## Features

- Minimal poster-style composition.
- Image framed with a white border.
- Centered uppercase heading and supporting message.
- Custom typography loaded from Google Fonts.
- CSS-based sizing, spacing, and colors.

## Project Structure

```text
motivation-poster/
├── index.html
├── style.css
├── assets/
│   └── images/
├── goal.png
└── solution/
```

## Run Locally

1. Download or clone the repository.
2. Open `index.html` in a modern browser.
3. Keep the relative image path and `style.css` alongside the HTML file as expected by the page.

No build tools or JavaScript are required. Google Fonts are requested over the internet; local fallback fonts are not configured.

## Learning Outcomes

- Connecting a CSS stylesheet to HTML.
- Styling images and containers.
- Using margins, borders, widths, and text alignment.
- Importing external fonts.

## Notes on Assets

The poster image appears to be third-party anime artwork; its original source and reuse terms are not documented in this repository. Confirm that you have rights to redistribute it before reusing the project publicly. The MIT License below applies to original project material only and does not override third-party asset rights.

## Possible Improvements

- Add responsive styles for narrow screens.
- Add descriptive alternative text to the image.
- Provide a local font fallback.
- Move image dimensions and spacing into responsive CSS rules.

## License

Licensed under the MIT License. See [LICENSE](LICENSE) for details.
