# Mahlaka Youth Centre — Responsive Website Assignment

## Project overview
This is a complete student-friendly website for **Mahlaka Youth Centre**. It is built with plain HTML, CSS and JavaScript so it can run locally without a server, framework or database.

## Files
- `index.html` — home page
- `about.html` — organisation information
- `programmes.html` — programme cards
- `contact.html` — contact details and working form
- `style.css` — external stylesheet and all responsive styling
- `script.js` — mobile navigation, current year and demo form interaction
- `assets/` — local responsive PNG image versions (480px, 800px and 1200px)

## How to run
1. Download/extract the project folder.
2. Open `index.html` in Chrome, Edge or Firefox.
3. Test the navigation links.
4. Resize the browser to desktop, tablet and mobile widths.
5. Open Developer Tools to test responsive device sizes.

No internet connection is required for the website itself.

## Rubric coverage

### 1. Working through feedback from Part 1
A changelog is included below. Because the original Part 1 marked script/feedback was not supplied with this task, the entries describe the corrections implemented for the current submission rather than pretending to quote lecturer comments.

### 2. CSS Styling for Desktop Solution
- **2.1 External stylesheet:** all pages link to `style.css`.
- **2.2 Base style:** reset, font family, colours, spacing and consistent box sizing are defined in the stylesheet.
- **2.3 Typography:** `font-family`, `font-size`, `font-weight`, `line-height` and `letter-spacing` are used.
- **2.4 Layout:** CSS Grid and Flexbox are used for page structure and navigation.
- **2.5 Visual styles:** colour, background, border, box-shadow, hover and focus states are included.

### 3. Responsive Design
- **3.1 Breakpoints:** desktop/tablet/mobile breakpoints are implemented with media queries.
- **3.2 Relative units:** `rem`, `%`, `vw`, `clamp()` and flexible grid units are used.
- **3.3 Responsive images:** `<picture>`, `srcset` and `sizes` are used with three local image sizes.
- **3.4 Testing:** use the checklist below and place screenshots in the submission README if your lecturer requires actual evidence images.

## Changelog
| Change | Reason |
|---|---|
| Created one shared external stylesheet | Keeps styling consistent across all HTML pages. |
| Added CSS reset and base typography | Provides consistent browser styling and readable text. |
| Added Grid/Flexbox page layouts | Creates a clear desktop structure that can adapt to smaller screens. |
| Added hover and focus states | Improves visual feedback and keyboard accessibility. |
| Added mobile navigation | Keeps the menu usable on narrow screens. |
| Added responsive breakpoints | Changes multi-column layouts to single-column layouts on smaller screens. |
| Added `picture`, `srcset` and `sizes` | Provides responsive image options for different viewport sizes. |
| Added form validation and feedback | Makes the contact page interactive for demonstration. |

## Responsive testing checklist
Record screenshots at:
- Desktop: approximately 1440 × 900
- Tablet: approximately 768 × 1024
- Mobile: approximately 390 × 844

For each size, check:
- Navigation is readable and usable.
- Text does not overflow.
- Cards fit inside the screen.
- Images scale without overflowing.
- Buttons remain easy to click.
- Contact form fields fit the viewport.

## Design decisions
The design uses a simple community-focused visual identity:
- Deep green represents growth and community.
- Warm gold is used as an accent.
- Off-white backgrounds separate sections without making the page too busy.
- Rounded cards and generous spacing improve readability.
- Content is kept simple and appropriate for a first-year web development project.

## References
- MDN Web Docs. Responsive design and media queries.
- MDN Web Docs. Responsive images using `srcset`, `sizes` and `<picture>`.
- MDN Web Docs. CSS Flexbox.
- MDN Web Docs. CSS layout.


## Image files
The responsive images are stored locally inside the `assets` folder. They are PNG files rather than remote website images, so the images remain available after the complete ZIP project is downloaded and extracted. The home page uses `srcset`, `sizes` and `picture` to select the appropriate image for the screen size.
