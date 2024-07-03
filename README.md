# THE GARDENING CLUB

The Gardening Club is a club website that can be used to encourage people to join and learn how to garden.

design section (color scheme throughout) highly focused on contrast for colour scheme
typography, why fonts selected and used accessibility (sans/sans-serif)
imagery, different aspects of the website design that are relevant features. 
wireframes across different devices/different perspectives. Mobile, Tablet, Laptop and Desktop.

- - -

## Contents

* [Features](#features)
* [Technologies Used](#technologies-used)
* [Testing](#testing)


- - -
## Screenshots

![responsive design of webpages across devices](documentation/responsive-image.png)
![picture of lettuce bed with kale, chard](documentation/hero-image.png)
![nav bar with club logo included](documentation/nav-bar.png)
![screenshot of about us page](documentation/about-us-page.png)
![screenshot of footer](documentation/footer.png)
![screenshot of form submission](documentation/form-submission.png)
![screenshot of form validation](documentation/form-validator.png)
![screenshots of wireframes created using balsamiq](documentation/wireframe-desktop.png)
![screenshot of quick tips section](documentation/quick-tips.png)

## Features

general features, favicon, headings, navigation on each page this is what they are and what they contain
future implementations, things you want to do but haven't had time or skills to implement.
accessibility! screen readers, colour blindness. font choices. aria labels. alt text on images.

## Technologies used:

languages, HTML, CSS. 

frameworks libraries and programmes used. balsamiq wireframes Google Fonts, amiresponsive, favicon tinypng, Chrome dev tools. github to store files gitpod to edit code.

## Testing

    I manually tested the Website on the Search Engines, Chrome, Firefox, Microsoft Edge. 

    I also confirmed that the project is responsive and has a good consistent aesthetic across many standard screen sizes using the Chrome Devtools Device Toolbar. 

    I tested and confirmed the navigation bar works and is easy to read including the return to home page throguh the use of The Gardening Club logo at the top of the page so that users can always return home. 

    All links open in new windows to avoid losing the webpage when navigating to various external links. 

    I confirmed that the form works and ensured the placeholder text disappears when typing. 
    
    I also confirmed that the form needed to be completed fully in order to be able to submit information through the use of the form validation. 
    
    The submit button also works when all fields are filled out properly.

    wave testing

## Validator Testing

**CSS** 
CSS passed validating testing using jigsaw Ws3 validators no errors. 

**HTML pages**
HTML pages threw up a few errors on initial testing, these were:
 - Stray end tag in index.html (see screenshot) i'd applied an extra "div" closing tag. upon removal index.html validated no errors.
 - In the HTML document, 'about-us.html' I'd made a human error in my code in relation to aria tags and alt tags. I'd also missed a closing "div" tag. on removing the aria and alt tags and adding the closing div element, the HTML document passed with no errors or warnings.
 - In quick-tips.html I had a stray end tag in a line of code within my footer element of the website. 
 - I'd also put in trailing slash characters which were absolute so I removed those and on removal, the code validated. 

**Lighthouse scoring**
for portfolio project one, the main focus was accessibility. The lighthouse scores for this project on mobile are as follows:

- Performance scored 72
- Accessibility scored 100
- Best Practices scored 100
- SEO scored 100. 

To improve the performance score, I would need to further optimize the images selected. 

## Unfixed bugs

## Deployment

local development - Fork/Clone

    The Gardening Club was deployed to Github pages. The steps I took to do this are as follows below: 

    In the GitHub repository, I clicked on the "Settings" tab.
    navigated to the "Pages" tab on the left-hand sidebar.
    Under "Source" click the "None" dropdown and selected the "main" or "master" branch.
    then clicked "Save".
    Once the master branch had been selected and the browser has reloaded itself, the page then provided the link to the live deployed version of the website.

    The live link can be found here - https://beebeebethc.github.io/The-Gardening-Club/

## Credits

**Content**

    The social media code and Media Queries from the love running project was used as a guide to create my own social media links and media queries on The Gardening Club website.

    TinyPNG used to optimise images for web browser purposes and to help support performance status of the website.

    Chrome Devtools used to help identify visual bugs on a live preview.

    Flexbox support gained from:
        Flexbox Froggy - https://flexboxfroggy.com, Flexbox Adventure https://codingfantasy.com/games/flexboxadventure/play and Youtuber Bro Code - Channel https://www.youtube.com/@BroCodez to gain a better understanding of Flexbox, how it's used and how to incorporate it into my website.

**Media**

    About us image of Lavender, taken from Pexels.
    Index image and Hero image are authors own.
    Web Link to Gardeners world website for more gardening tips. 

## Acknowledgements

luke mentor
kera - readme guidance
family and friends for continued support