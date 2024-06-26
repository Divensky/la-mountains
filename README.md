﻿# LA Mountains Landing Page

✨ This is a landing page that features a responsive carousel and mobile tabs that convert to an accordion. 

## How to run this project

⚙️ Unpack the zip and open the HTML file in your browser.

The full code version is available through a link in the email. 

## How I worked on this project

🏹 The instructions were:

"Goal is to convert this into a single page response site. The carousel should be responsive. On mobile, the tabs should be converted to an accordion. History, team - these are internal links in the page to their respective sections."

🛠️ I built this website the way I would have done this at my job.

- I used Vite as a lightweight build tool.
- I used SCSS BEM-style and TypeScript; I am open to using other tools if needed.
- I exported the images from the PSD file.
- I used responsive design techniques, including media queries, fluid typography, variable widths and heights, etc.
- I used relevant ARIA roles, alt attributes, semantic HTML tags, etc. to make the website accessible.

### Additional tools I used

- I installed the Swiper.js library to take care of the carousel.
- In building the tabs that convert to accordion on mobile, I adapted the code from https://www.gsarigiannidis.gr/tabs-on-desktop-accordion-on-mobile/ and https://codepen.io/gsarig/pen/ExKJEoM.

## Challenges and how I overcame them

- The hero text that is partially covered by the mountains at the bottom. I kept the text within the image for consistent scaling. However, this did not work on mobile due to the aspect ratio. So for the mobile, I put the text over the image, sacrificing its nicely designed bottom in favor of readability. Alternatively, a picture with a different aspect ratio might have been requested from the designer.
- Creating tabs that convert to an accordion on mobile. I adapted the codepen referenced above by introducing a config to determine when tabs should convert based on screen width, ensuring readable text and converting on screens approximately 600px wide.

## Suggestions for improving design:

💡 If I was working on this project in collaboration with a designer and a project manager, I might bring up these suggestions:

- Consider changing the "team" nav link to "climb" to match the title of the section it leads to.
- Improve contrast for carousel inactive buttons.
- Improve text contrast in the History section for better readability on mobile.
- If feasible, review the logo: it appears to resemble an upset face from afar.
- Optimize images for mobile aspect ratios.

I would implement accepted suggestions upon feedback.

## Notes on implementation:

- Where the size of a jpg image was nearly the same as that of a webp image, I used jpg.
- If I had more time, I would refactor more of the tabs-to-accordion code and set up tests and continuous integration to run the tests on every pull request.

## Summary

✨ It was a lot of fun to work on this project! I would appreciate any feedback on it.
