# OMNIFOOD

> :globe_with_meridians: [На русском](/README-RU.md)

'Omnifood' is a study project I'm did on ['Build Responsive Real-World Websites with HTML and CSS' course by Jonas Schmedtmann](https://www.udemy.com/course/design-and-develop-a-killer-website-with-html5-and-css3/).

---

[LIVE DEMO : https://schemingcate.github.io/omnifood/](https://schemingcate.github.io/omnifood/)

---

<img width="720" alt="First screen of Omnifood webpage" src="https://user-images.githubusercontent.com/90343424/200433183-e98410de-0938-4b04-bf30-896724af1d65.png">


## Technologies / methodologies

- HTML (semantic HTML);
- CSS (flexbox, grid);
- JavaScript (DOM-manipulation basics)

## About the project

'Omnifood' is a landing page for a food subscription service. The page tells the user about the service and its benefits and encourages to try it by filling out a simple subscription form.
The website is responsive and looks good on most screen sizes - from small phones to large desktop monitors.
The project is written on HTML and pure CSS, with a couple lines of JavaScript code for finishing touches.

### Valid semantic markup

The HTML markup of the page is using modern semantic tags: 
- `<header>`, `<main>` and `<footer>`;
- `<nav>` for navigation in the header as well as in the footer;
- `<address>` for contact info;
- the main content divided into sections (`<section>`) each with individual heading;
- `<figure>` for illustrating the food Omnifood makes and testimonials;
[Go to testimonials section](https://schemingcate.github.io/omnifood/?#testimonials)
- `<blockquote>` for the text of clients' testimonials etc.

The markup has no errors and is valid, according to https://validator.w3.org/:
<img width="467" alt="Screenshot 2022-11-08 at 02 09 12" src="https://user-images.githubusercontent.com/90343424/200434660-7646f83d-d71e-47ca-94ab-8fd221cb4e43.png">

//TODO readme - sticky footer - (demo and mentioning js)

//TODO readme - animations (demo)

//TODO readme - form

//TODO readme - media q

//TODO readme - mobile menu

### Accessibility

Every `img` has a descriptive `alt` text, `aria-label` is used where it is necessary. All buttons and links are focusable with tab and have bold but beautiful custom focus, suitable for the page's design: 

<img width="285" alt="Illustration of the custom focus" src="https://user-images.githubusercontent.com/90343424/200436587-48f436c1-6732-472a-ade3-e951e3d2eb5b.png">

//TODO readme - favicon
