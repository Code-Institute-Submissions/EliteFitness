# Validation

### CSS 
* Tested using the [Jigsaw Validator](https://jigsaw.w3.org/css-validator/). 
    * Errors fixed: invalid value for font weight, also "px" used in font weight and an empty width value removed. 
    * Checked CSS in the validator again once these errors were removed and there were no further errors. 

### HTML 
* Tested using the [W3C Validator](https://validator.w3.org/).
    * Errors fixed: stray start tag - "script" was outside of the body element on all pages, frameborder from iframe was obsolete.
    * Edits based on warnings: headings added into articles and some sections changed to articles.
    * No further errors found once checked in the validator again.

# User Stories Testing

#### Site Visitor:
  1. As a site visitor, I want to learn about the gym and what they do.
  2. As a site visitor, I want to see what it looks like in the gym.
  3. As a site visitor, I want to see when they are open/times of their sessions.
  4. As a site visitor, I want to find out about the cost of a membership.
  5. As a site visitor, I want to find out how I can contact the gym and where it is located and if they have social media.

#### Site Owner;
  1. As the site owner, I want to provide information about the gym and what we do to attract business.
  2. As the site owner, I want to show what it looks like inside the gym/during sessions.
  3. As the site owner, I want to provide information about session times.
  4. As the site owner, I want to provide information on membership costs.
  5. As the site owner, I want to provide information on where we are and how we can be contacted and links to our social media.

### Solution Provided For User Story Demands:
* Information is given about the gym, what they do as well as the coaches that work there.
* There are photos in an image carousel as well as a gallery that showcase the gym.
* Information is given about times of classes as well as details provided explaining what each is.
* Information is given abotu membership costs and what the membership includes.
* Information is given on multiple ways to contact the gym including a form to send a message, as well as their address and a map.

### User Interaction:
* From the "Home" page the user can see what the gym looks like inside, read a short summary about the gym and also see the membership options. There are two call to action buttons on this page, one invites the user to learn more about the gym by bringing them to the about page, the other invites them to get in touch with the gym about memberships by directing them to the "Contact" page.
* The "About" page tells the user the ethos for the gym and what they do. It also provides information about the coaches there.
* The "Timetable" page provides details of the class options and what they are, as well as a full timetable for the week.
* The "Contact" page contains a form fr the user to send a message and give suggestions of why they may get in touch. This page also tells the user the opening hours, location and contact information. They can also see the location on Google Maps.
* The navigation bar is always visible even when the user has scrolled down so they can easily navigate to another page.
* The footer contains important information that the user may want to find quickly such as opening hours, location or contact details.

# Manual Testing Of Elements On The Site

### Responsiveness:

To check the site was responsive and works correclty I used Chrome developers tools to simulate multiple devices and breakpoints.

#### Devices:
* Moto G4
* Pixel 2
* Galaxy S5
* iPhone 5/SE
* iPhone 6/7/8 & Plus
* iPhone X
* iPad
* iPad Pro

I also checked using different browsers.

#### Browsers:
* Google Chrome
* Microsoft Edge
* Mozilla Firefox

I also used my own mobile device to check the site, and viewed it on a 27" and 24" monitor.

#### Issues Found:
* From viewing on devices I noticed a very small portion of white space between my footer and image gallery. 
    * I added padding to the bottom of the image gallery to fix this.
* On Edge and Firefox I noticed there was white space under the footer on some of the pages. 
    * Padding added to the bottom of the footer fixed this.
* There is also an occasional bug that occurs when viewing any page of the site on using developer tools. It usually occurs when viewing as a mobile device but sometimes on larger screen views. When opening the developer tools in responsive view, occasionally white space is seen running from top to bottom on the right-hand side. If the page is open in developer tools as a large screen size, setting to a mobile device, closing developer tools and then re-opening causes this to appear.
    * This disappears if a site button is selected, the page is refreshed, any change is made in developer tools or navigating
    * I have checked my CSS and HTML and cannot see anything causing this.
    * This does not occur when opening the site in the browser.
    * This does not happen when I view the site on my mobile device. 

### Navigation Bar:
* Hover over the logo "Elite Fitness" to see it change colour.
* The active page is a different colour to the other navigation links as we are currently on that page.
* Change screen size to mobile to see that the navigation menu turns to a collapsible burger menu.
* In mobile open the menu to see that the active page in the menu is a different colour to the other menu links.
* Verify that the navigation bar stays visible on top of the screen when scrolling.

### Footer 
* Three pieces of information available.
* Verify icons next to headings are hidden on screen readers using aria-hidden="true".
* Verify icons used for social media links are hidden on screen readers using aria-hidden="true" and instead show text using a span.
* Change screen size to see the footer is responsive and the layout of information changes on mobiles.

### Home:

#### Image Carousel & Jumbotron
* Click the left and right arrows on the carousel change the image.
* Select the carousel indicators on the bottom of the image to see the image change.
* Select the jumbotron button and redirect to the "About" page.
* Hover over button to see the colour change.
    * When clicked the button turns blue. Have changed this in the CSS file. 
* Verify each image in the carousel has an "alt" attribute.
* Change the screen size to see the images in carousel are not distored on different breakpoints.
* On mobile swipe the image carousel to see the images change. (checked using personal device)

#### Intro Of Gym:
* Legible on all screen sizes.
* Contrast between text and background colour.

#### Membership Options:
* Clearly labeled section. 
* Information displayed on three easy to read cards.
* Hover over "Contact Us" to see the colour change.
* Select "Contact Us" and be redirected to the "Contact" page.
* Changed screen size to see that the card layout is repsonsive based on screen sizes.

#### Image Gallery:
* Clearly labeled section.
* Image thumbnails are appropriate size and image is not distored.
* Select an image to bring up the full size
  * From here the arrows can be selected to navigate through the other images.
  * The option for an image slideshow is available.
  * The images can be viewed in a grid.
  * Using a mouse wheel will navigate to the next image.
  * Selecting "X" will close this view.
* Change the screen size to see that the image gallery is responsive.
* On mobile after selecting on of the thumbnails, swipe to change the image. (checked using personal device)

### About:

#### About Us:
* Clearly labeled section.
* Information is legible with contrast between text and background colour.
    * Spelling mistake found and corrected.

#### Meet The Team:
* Clearly labeled section.
* Change screen sizes to ensure photos are not distored.
* Information is clear and legible.
    * For consistency in this section changed "10" to "ten" in the trainer biography.
* Changed screen sizes to see that this section is responsive and displays differently on mobile.

### Timetable:

#### Timetable Options:
* Clearly labeled section.
* Timetable options clearly defined and explained on easy to read cards.
* Changed screen size to see that this is responsive and displays differently on mobile.

#### Timetable:
* Timetable created using a HTML table is easy to follow and read.
* Contrast between content and background.
* Changed screen size to see timetable scrolls horizontally.
    * Changed left & right padding as timetable was pushed to the right on smaller screens.

### Contact:

#### Form:
* Clearly labeled section.
* Heading subtitle tells users why they might want to send a message.
* Form requires name, email, phone number and message.
* Email will only be accepted when "@" is included.
* Changed screen sizes to see form is responsive and is sized based on screen size.
* On medium and small screen sizes the input for email and phone number are on a separate line.
* Hover over button to see the colour change.
    * When clicked the button turns blue. Have changed this in the CSS file. 

#### Find Us 
* Clearly labeled section.
* Address, contact information and opening hours are easy to read with contrast between text and background.
* Map is clearly visible and can be zoomed and out or can be opened in a new browser tab.
* Changed screen size to see this section is responsive and displays differently depending on screen size.


