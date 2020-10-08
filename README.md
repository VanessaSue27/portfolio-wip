# Build Your Portfolio
Time flies and we are already working on our portfolio! Exciting times ahead 🎉 This project's goal is not only to put our HTML and CSS skills to the test, but also take the opportunity to get started with accessibility and build websites for everyone 💡

## How I built it - What I learned
- There were two things very clear from the beginning: the site must be responsive and accesible. This encouraged me to be extra careful when writing the HTML skeleton from the get go, since I knew this would play a key role when fixing responsiveness and running all the accessiblity tests 💪👩‍💻
- The portfolio is made up of 8 main sections, which all behave differently. My approach was to use Flexbox where it was needed, and a combination of position: relative or absolute in the header section to get all the elements lined up properly.
- Regarding responsiveness: This time I chose a Desktop first approach, since the site is so complex regarding the amount of elements in it. Then hide elements and change Flexbox direction when necessary when scaling down to smaller devices.

## Accessibility Testing
Here's an overview of all the testing I did on this portfolio project 💥
- Devices: What was accessible to me (iPhone 6 Safari, iPad Safari).
- Chrome, Edge and Firefox: Tested for tab and keyboard browsing and also Enter key to access links.
- HTML Validation: Used Lighthouse in Chrome Dev tools (Scored - 100 Accessibility, 92 Best Pratices and 89 SEO). Also used W3C (validator.w3.org) for validation.
- I've also checked that the HTML structure makes sense without any CSS styling using the Chrome extension Web Developer Toolbar ✨
- Ran an audit using Wave (wave.webaim.org): Brought down my alerts after following their feedback. Also made sure all alt text on non-text elements was coherent.
- Color contrast checked with Chrome Dev Tools elements inspector.
- Screen Reader testing done with ChromeVox classic extension and also on iPhone Speak Screen feature: did some initial read-throughs and made sure to use ARIA attributes to elements that felt relevant and should be read.

## View it live
💕 It's still very much a work in progress, but have a sneak peek at my very own portfolio. Hoping to add more content soon: https://vanessa-portfolio.netlify.app/
