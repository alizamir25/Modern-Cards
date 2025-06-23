**# Modern Cards Section

This project features a modern, responsive card section designed with HTML and CSS. It showcases a set of "creative cards" with hover effects, ideal for displaying services, features, or any key information in a visually appealing manner.

## Table of Contents

- [Modern Cards Section](#modern-cards-section)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Files Included](#files-included)
  - [Usage](#usage)
  - [Customization](#customization)
  - [Responsiveness](#responsiveness)
  - [Live Demo](#live-demo)

## Features

* **Modern Design:** Clean and contemporary aesthetic.
* **Hover Effects:** Interactive visual feedback on card hover.
* **Responsive Layout:** Adapts to different screen sizes for optimal viewing on various devices.
* **Customizable:** Easily modifiable CSS for styling adjustments.
* **Font Integration:** Uses the "Epilogue" font from Google Fonts.

## Files Included

* `index.html`: The main HTML file containing the structure of the card section.
* `style.css`: The CSS file responsible for the styling and layout of the cards and the overall page.

## Usage

To use this card section in your project:

1.  **Clone or Download:** Get the `index.html` and `style.css` files.
2.  **Place in Project:** Put these files in your project directory.
3.  **Link Stylesheet:** Ensure your `index.html` file correctly links to `style.css` (it's already set up in the provided `index.html`).
4.  **Open in Browser:** Open `index.html` in your web browser to see the card section.

## Customization

You can easily customize the appearance of the cards by modifying the `style.css` file:

* **Colors:**
    * `body` background: `--background-color` (currently `#4d4c4c`)
    * `card-details:before` background: `--card-background-color` (currently `#f7f6f2`) and `--card-hover-background-color` (currently `#fffab3`) on hover.
    * `card-icons:before` background and border: `--icon-border-color` (currently `#ffee02`) and `--icon-hover-background-color` (currently `#ffee02`) on hover.
    * `h3 a` color: `--heading-link-color` (currently `#000`).
    * `p` color: `--paragraph-color` (currently `#000000`).
    * `read-more-btn` border and `i` color: `--read-more-btn-border-color` (currently `#ffee02`) and `--read-more-btn-icon-color` (currently `#000`).
* **Fonts:** Modify the `font-family` property in the `body` selector. The "Epilogue" font is imported via Google Fonts.
* **Card Dimensions and Spacing:** Adjust `width`, `height`, `padding`, and `margin` properties for `.card-details`, `.card-icons`, and `.card-column`.
* **Hover Effects:** The `transition` properties control the smoothness of the hover animations.

## Responsiveness

The design is responsive and includes media queries in `style.css` to adjust the layout for different screen sizes:

* **Max-width 992px:** Cards will arrange themselves into two columns.
* **Max-width 480px:** Cards will stack into a single column, and the "Read More" button will always be visible.

## Live Demo

If available, you can view a live demo [here](https://www.fiverr.com/ali_zamir).**
