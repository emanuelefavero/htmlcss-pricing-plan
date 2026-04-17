# HTML/CSS Pricing Plan

> Tip: Code decisions are explained in the [Implementation Notes](#implementation-notes)

Static responsive pricing plan page for a web development course exercise.

## Live Demo

[**View on GitHub Pages &nbsp; 🌐**](https://emanuelefavero.github.io/htmlcss-pricing-plan/)

## Exercise Goal

Match the provided reference layouts using HTML and CSS, with a focus on responsive card layout behavior.

### Reference layouts

#### Mobile

<img src="screenshots/screencapture-mobile.png" alt="mobile reference screenshot" width="400">

#### Tablet

<img src="screenshots/screencapture-tablet.png" alt="tablet reference screenshot" width="400">

#### Desktop

<img src="screenshots/screencapture-desktop.png" alt="desktop reference screenshot" width="600">

## Scope

- Use HTML and CSS
- No JavaScript
- Use a generic sans-serif font
- Prefers `flex` shorthand with `calc()` for cards layout, but CSS grid is also acceptable when it reduces code complexity and achieves the same result
- Prefers only setting a `width` or `max-width` for the cards container or main container, and work with `flex` or `grid` to achieve the desired layout, but media queries are acceptable when necessary
- Mobile layout: pricing cards stacked vertically
- Tablet layout: pricing cards arranged in two columns
- Desktop layout: pricing cards arranged in three columns when space allows
- Bonus: on tablet, make the third card full width
- Bonus: when a card is full width, arrange its feature list in two columns

## Implementation Notes

- Considered creating switch toggles with html/css for interactivity, but decided to use Bootstrap icons for simplicity, as this exercise focuses on layout and responsiveness rather than interactivity
- Used container queries to switch the features list to two columns when the card has enough width, as this allows for a more modular and responsive design without relying on media queries that target specific breakpoints
- Used `flex` with `calc()` and css custom properties to create the responsive card layout, as this allows for a more fluid and adaptable design, no matter the amount of cards.
- Used css custom properties for colors and other values
- Used component classes and css nesting to scope styles to specific components and avoid unintended side effects, as this promotes better maintainability and readability of the code in a small project like this one.

&nbsp;

---

&nbsp;

[**Go To Top &nbsp; ⬆️**](#htmlcss-pricing-plan)
