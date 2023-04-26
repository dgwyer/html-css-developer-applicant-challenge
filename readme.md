# Developer Applicant Challenge

## Viewing the Project

For convenience you  can view the live finished project via [GitHub pages here](https://dgwyer.github.io/html-developer-challenge-gwyer/).
## Installation

To install the project locally, run `npm i` to install the package dependencies and then run `npm start` to watch files and start the Browsersync server. Then goto http://localhost:3000/ to view the `index.html` page.
## Notes

For this project I used [Node-sass](https://www.npmjs.com/package/node-sass) to compile SCSS to CSS, and [Browsersync](https://www.npmjs.com/package/browser-sync) to live reload multiple browser instances of the HTML page instantly via changes to HTML/SCSS code. Each browser instance was set at a different width to be able to quickly test responsive styles.

Using Browsersync also allows for easier cross-browser testing. Each browser instance synchronizes scrolling too, so all other browser instances scroll together which is a useful feature.

The project assets Zip file was downloaded and extracted to the `./assets` folder. I noticed that the pro badge SVG had a different color to the Figma mockup so I changed it to match.

I obtained the button hover color and timed fade in from the main [WPForms](https://wpforms.com) website.

## Responsive Behaviour

- The video play button SVG reduces in size as the browser width reduces. 