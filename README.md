# THE GARDENING CLUB

The Gardening Club is a club website that can be used to encourage people to join and learn how to garden.

![responsive design of webpages across devices](documentation/responsive-image.png)

The live link can be found here - https://beebeebethc.github.io/The-Gardening-Club/

## Design and Accessibility
- For the design choices on The Gardening Club website, I wanted to keep my colour scheme throughout and keep it consistent. In order to achieve this I made sure that I had a high contrast and that everything was visible and easy to read and navigate.
- TODO insert colour pallete here
- the colours I chose because although they are green, they are of a high contrast to one another. I also wanted a pop of colour to appear on the nav bar for the selected page and on mouse hover. 


- TODO typography, why fonts selected and used accessibility (sans/sans-serif)
- TODO imagery *see screenshots* different aspects of the website design that are relevant features. 
- TODO wireframes across different devices/different perspectives. Mobile, Tablet, Laptop and Desktop. *bring images across from canva.*

- - -

## Contents

* [Design and Accessibility](#design-and-accessibility)
* [Contents](#contents)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Testing](#testing)
    * [Manual Testing](#testing)
* [Bugs](#bugs)
    * [Bugs Unfixed](#unfixed-bugs)
    * [Bugs Fixed](#fixed-bugs)
* [Deployment](#deployment)
* [Credits](#credits)
    * [Content](#credits)
    * [Media](#credits)

- - -

## Screenshots

TODO *move these to relevant places throughout*
![picture of salad bed with kale, chard, squash and accompanying nasturtium](documentation/hero-image.png)
![nav bar with club logo included](documentation/nav-bar.png)
![screenshot of about us page](documentation/about-us-page.png)
![screenshot of footer](documentation/footer.png)
![screenshot of form submission](documentation/form-submission.png)
![screenshot of form validation](documentation/form-validator.png)
![screenshots of wireframes created for desktop](documentation/wireframes-desktop-3.png)
![screenshots of wireframes created for tablet](documentation/wireframes-tablet-design.png)
![screenshot of wireframes created for mobile](documentation/wireframes-mobile.png)
![screenshot of quick tips section](documentation/quick-tips.png)

## TODO Features

**general features, favicon, headings, navigation on each page this is what they are and what they contain**
**future implementations, things you want to do but haven't had time or skills to implement.**
**accessibility! screen readers, colour blindness. font choices. aria labels. alt text on images.**

## Technologies used:

languages, HTML, CSS. 

**frameworks, libraries and programmes used. Balsamiq wireframes Google Fonts, amiresponsive, Favicon, TinyPNG, Chrome dev tools. Github to store files, Gitpod to edit code.**

## Full Website Testing 

| Website Feature   | Expected Outcome | Testing Performed | Result | Pass or Fail |
| ----- | ----- | ----- | ----- | ----- |
| `Site Navigation` |                  
|  |  |  |  |  |
| The Gardening Club Logo and Title | When clicked the user will return to home page | Clicked logo and title | Redirected to home page | Pass | 
| Home Page Link | When clicked the user will return to home page | Clicked home link | Redirected to home page | Pass |
| About Us Link | When clicked to about-us page | Clicked the about us link | Redirected to about-us page | Pass | 
| Quick Tips Link | When clicked the user will get redirected to quick tips page | Clicked the quick-tips link | Redirected to quick-tips page | Pass |
| `Footer` |
|  |  |  |  |  |
| Social Media Links | When clicked the user will get redirected to the social media sites that open in new tabs| Clicked the social media links | social media links open in a new tab | Pass |
| `About-Us` |
|  |  |  |  |  |  
| Google Map Embed | Map should be responsive when interacted with | Clicked the map | Map zoomed in and out and responded as expected | Pass |
| `Quick-tips` | 
|  |  |  |  |  |  
| Gardener's World Link | When clicked, user will be redirected to a new tab on the Gardener's World Website | Clicked the link | Link opened in a new tab | Pass |
| Sign Up Form | Forms should not validate if left blank | Forms left blank | Form validator flagged up asking for input | Pass | 
| Sign Up Form | Form should not validate if partially filled in | entered full name but no email address | Form validator flagged up asking for email address| Pass | 
| Sign Up Form | Form should ask for a valid email address if no official email address is put in | Plain text put in | Form validator responded by asking for an official email address complete with '@' sign | Pass |
| Sign Up Form | placeholder text must disappear when typing | typed in the form boxes | placeholder text disappeared | Pass |

- - -

Full Testing was performed on a range of personal devices and those belonging to friends and family:

- Mobile devices
    - Samsung Galaxy A33
-  Laptop
    - Huawei Matebook

I also confirmed that the project is responsive and has a good consistent aesthetic across many standard screen sizes using the Chrome Devtools Device Toolbar.  

Testing was also performed on various Web Browsers: 

- Chrome 
- Firefox
- Microsoft Edge

- - -

## Further Testing 

## Wave Testing: 

![accessibility test for main page](documentation/wave-test-1.png)
![accessibility test for about-us page](documentation/wave-test-2.png)
![accessibility test for quick-tips page](documentation/wave-test-3.png)

## Validator Testing
 - the form aspect on this website will not validate unless theres a valid full name and email address written in the form.
 ![no-full-name-validator](documentation/no-full-name-validator.png)
 ![no-email-validator](documentation/no-email-validator.png)
 ![incorrect-email-address](documentation/no-email-address-validator.png)

**CSS**

- CSS passed validating testing using jigsaw Ws3 validators no errors. 

**HTML pages**

HTML pages threw up a few errors on initial testing, these were:
 - Stray end tag in index.html (see screenshot) I'd applied an extra 'div' closing tag. On removal index.html validated no errors.
 - In the HTML document, 'about-us.html' I'd made a human error in my code in relation to aria tags and alt tags. I'd also missed a closing 'div' tag. On removing the aria and alt tags and adding the closing div element, the HTML document passed with no errors or warnings.
 - In quick-tips.html I had a stray end tag in a line of code within my footer element of the website. I'd also put in trailing slash characters which were absolute so I removed those and on removal, the code validated.

**Lighthouse scoring**

The lighthouse scores for Portfolio Project One, are below. The main focus for this project was every aspect of accessibility. 
![Main-page lighthouse scores](documentation/main-page-performance.png)
![About-us lighthouse scores](documentation/about-us-performance.png)
![Quicktips lighthouse scores](documentation/quick%20tips%20performance.png)

## Bugs

**Unfixed bugs**
- Hover button should change colour on the menu on devices over 768px on mouse hover the navigation buttons should change colour to highlight which page you wish to visit. 

**Fixed bugs**
- sticky header achieved, the navigation bar and logo are present at all times. 
- by clicking the logo you can return to home page.
- Footer remains at the bottom of the website at all times. Prior to fixing this the footer would float above the bottom of the page.
- fixed bugs following validator testing and all pages are validated. 

## Deployment

- The Gardening Club was deployed to Github pages. 
- The steps I took to do this are as follows below: 
    - In the GitHub repository, I clicked on the "Settings" tab.
    - I then navigated to the "Pages" tab on the left-hand sidebar.
    - Under "Source" click the "None" dropdown and selected the "main" or "master" branch.
    - Clicked "Save".

- Once the master branch had been selected and the browser has reloaded itself, the page then provided the link to the live deployed version of the website.
    - The live link can be found here - https://beebeebethc.github.io/The-Gardening-Club/

- For local develpoment, If you wish to explore behind the scenes of The Gardening Club, follow these steps below:
    
    - Go to the Repository that you wish to clone (https://github.com/BeeBeeBethC/The-Gardening-Club).
    - Click on the green button with white text that reads 'code'.
    - On the dropdown menu that appears once clicked, select the 'copy URL to clipboard' button (looks like two squares overlaying one another).
    - Open your local coding package, (for myself it's Visual Studio Code).
    - On Visual Studio Code, Click the 'Source Control' button from the left hand side of the screen (the one that can also be used to commit changes).
    - Paste the repository URL into the top navigation bar of Visual Studio Code.
    - Save the Repository to a localised folder where the repository will be stored on your computer.
    - Click on select Repository location. 
    - Let the Repository download and click 'open' when the onscreen prompt appears in the bottom right hand corner of the screen.

## Credits

**Content**

- The social media code and Media Queries from the love running project was used as a guide to create my own social media links and media queries on The Gardening Club website.

- TinyPNG used to optimise images for web browser purposes and to help support performance status of the website.

- Cloudconvert to convert images to WEBP instead of JPG images.

- Chrome Devtools used to help identify visual bugs on a live preview.

- Flexbox support gained from:
    - Flexbox Froggy - https://flexboxfroggy.com
    - Flexbox Adventure https://codingfantasy.com/games/flexboxadventure/play 
    - Youtuber Bro Code - Channel https://www.youtube.com/@BroCodez to gain a better understanding of Flexbox, how it's used and how to incorporate it into my website.

- - -

**Media**

- About us image of Lavender, taken from Pexels.
- Index image and Hero image are authors own.
- Web Link to Gardeners world website for more gardening tips. 

- - -

**Acknowledgements**
 - My family and friends who continually support me.
 - Luke Buchanan, my mentor for his support.
 - Kera Cudmore who helped me navigate through the start of my README documentation.