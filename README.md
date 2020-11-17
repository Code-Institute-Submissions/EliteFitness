# Elite Fitness

# Project Introduction
This is a website for a gym called Elite Fitness. They specilaise in small group personal trainign which sets them apart from other gyms.

The website's purpose is to provide information to current and new clients about their style of gym and what they offer.

The website shows the user what it is like inside the gym, what the memerbship options are, when the classes are on and what the class options are, it provides contact and address information including a Google Map view. There is also a form for the user to senmd a message to the gym.

I chose to create a website for a gym for this project as exercise is something I enjoy in and would usually go to the gym four or five tines a week. 

The gym this website is based on is the gym I am a member of.

# User Experience (UX)

### User Stories

#### Site Visitor
  1. As a site visitor, I want to learn about the gym and what they do.
  2. As a site visitor, I want to see what it looks like in the gym.
  3. As a site visitor, I want to see when they are open/times of their sessions.
  4. As a site visitor, I want to find out about the cost of a membership.
  5. As a site visitor, I want to find out how I can contact the gym and where it is located and if they have social media.

#### Site Owner
  1. As the site owner, I want to provide information about the gym and what we do to attract business.
  2. As the site owner, I want to show what it looks like inside the gym/during sessions.
  3. As the site owner, I want to provide information about session times.
  4. As the site owner, I want to provide information on membership costs.
  5. As the site owner, I want to provide information on where we are and how we can be contacted and links to our social media.
  
### Wireframes

* [Desktop](https://github.com/HollyC7/EliteFitness/blob/master/assets/wireframes/Elite%20Fitness%20Wireframes%20Desktop.pdf) 
* [Tablet](https://github.com/HollyC7/EliteFitness/blob/master/assets/wireframes/Elite%20Fitness%20Wireframes%20Tablet.pdf)
* [Mobile](https://github.com/HollyC7/EliteFitness/blob/master/assets/wireframes/Elite%20Fitness%20Wireframes%20Mobile.pdf)

#### Deviations From Wireframes On Final Site

* Navigation bar always visible even when scrolling down so the user can easily navigate the website.
* Homepage image carousel takes up entire screen on desktop and half screen on tablet and mobile as I felt this looked better.
* On mentor advice, I added a snippet of text taken from the "About Us" section and added it above the membership options as a tyoe fo marketing banner giving an introduction to the gym.
* Headings added to sections to help define what they are for the user i.e "Take A Look Inside" for the image gallery.
* Six images instead of five for the image gallery as it made better use of the space and also provides more information for the user.
* Image gallery layout 3 x 2 on tablet and as a block on mobile as it looked better.
* No image shown in the "About Us" section as I felt the text was better on it's own.
* Images and paragraps for the gym trainers not represented on a carousel. On large screens and up they remain side by side, on small and medium screens they are shown as a block.
* Cards added above the timetable as I thought it would be good for the user to see what the different options in the timetable were.
* The form is the first section on the "Contact" page so the user could find it immediately if they wanted to contact the gym.
* Social media icons and links are the last item shown on the footer.

### Colour Palette

The colours used can affect how a user responds or feels. I chose colours that suited a gym and this gym's ethos.

* Orange: vibrant, energetic, stimulate, invigorate, health & vitality.
    * A gym is an active and energetic environment and being active can lead to better health.
* Black: power, control, dicipline, luxury, exclusive.
    * Associated with becoming strong, following a plan, beign dedicated to your fitness journey.
    * Ties in with the name "Elite Fitness"
* White: clean, simple, calm
    * A gym should always be clean.
    * The structure of the gym and classes makes it easy to follow foir any fitness level.
    * Exercise releases endorphins which can help lift your mood and make you feel relaxed.

# Features

This is a fully responsive website allowing the user to find out all they need about this gyms

![Image showing site on multiple devices](assets/images/responsive-devices.png)

### Navigation Bar

* The navigation bar is always shown on the top of the screen across all pages and is still shown when scrolling. It has an opacity set so the user can see what is underneath. This is the same on mobile also.
* The name of the business changes colour on hover on desktop.
* The name of the business can be clicked and brings the user back to the home page. 
* The navigation bar contains links to all pages of the site. The active page is coloured on all devices and hovering over the page names on desktop changes the colour.
* The navigation links are in a burger menu on mobile devices.

### Footer

* On all pages the footer shows opening times, contact information and links to social media. 
* Icons are used to represent the three types of information included in the footer next to their respective headings. These icons are hidden when a screen reader is used.
* The social media icons open to the relevant website in a new browser tab.
* On desktop the social links change colour when hovered over.
* If a screen reader is used the social link icons are hidden however the name of the website is displayed instead.
* On mobile devices the information shown in the footer is shown as a block.

### Home

* There is an image carousel depicting images of a gym and equipment. 
* There is a clickable button over the image carousel under a banner that provides an insight into the gym. Clicking this button brings the user to the "About" page.
* On desktop this button changes colour on hover.
* There is a small marketing style introduction giving some information about the gym.
* The membership options are displayed in three cards that are responsive depending on the breakpoint.
* Under the membership cards there is a call to action to contact the gym to find out more. The "Contact us" links to the "Contact page".
* On desktop the "Cntact Us" changes colour on hover.
* There is an image gallery showing some images from inside the gym. The thumbnails can be clicked on which shows the fullsize image and the user can click the arrows to navigate to the next image.

### About 

* There is a section providing the user information about the gym.
* There is information given about the three gym trainers including a photo and a short paragraph about themselves so the user can find out about them.
* On mobile the information about the trainers and their photo is displayed as a block.

### Timetable 

* There are two cards above the timetable that provide information on what is shceduled in the timetable.
* These cards are shown above the timetable so that when a user is viewing on a mobile device they are able to see what each is. If they did not show at the top, the user would be viewing the timetable first and would need to scroll down to see this information and there is a possibility they would not.
* These cards are shown as a block on mobile devices.
* There is a timetable created using a HTML table. This allows the user to scroll horizontally on smaller screen sizes.

### Contact

* There is a form at the top of the page.
* There is a subtitle giving examples of why the user could send them a message.
* The form allows the user to input their name, phone number, email address and the message. Each of these inputs is required and each section is labelled.
* The form will only accept an email address in the email section.
* The send button changes colour on hover on a desktop.
* The bottom section of the page contains address details, contact information and opening hours.
* The bottom section also contains Google Maps. The user can move the map around, zoom in or out and also open in a new browser tab.

# Technologies Used 

* HTML
* CSS
* Bootstrap
* Fancybox
* [Resizeimage.net](https://resizeimage.net/) for cropping and resizing images used in the project

# Testing


### Validation
* CSS tested using the [Jigsaw Validator](https://jigsaw.w3.org/css-validator/). 
    * Errors fixed: invalid value for font weight, also "px" used in font weight and an empty width value removed. Checked CSS in the validator again once these errors were removed and there were no further errors. 
* HTML tested using the [W3C Validator](https://validator.w3.org/).
    * Errors fixed: stray start tag - JS was outside of the body element on all pages, frameborder from iframe was obsolete.
    * Edits based on warnings: headings added into articles and some sections changed to articles.

# Deployment

How the site is deployed

# Credits

### Code 

* Fancybox used for image gallery.
* Bootstrap used throughout website.
* Iframe taken from Google Maps for the map included in the contact page.

### Content 

 * No written content directly taken from other sources however inspiration drawn from the Facebook posts and membership plans from the gym I am a member of, [Rory Skerrit Fitness Limerick](https://www.facebook.com/pages/category/Fitness-Boot-Camp/Rory-Skerritt-Fitness-Limerick-104753844210216/)

### Media 

* Images of the gym, gym trainers and orange background image taken from [Pxhere](https://pxhere.com/) and [Pexels](https://www.pexels.com/).

### Resources

* A github page that contains a [Markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) with tips on how to write Markdown for this README file.
* The Code Institute [README template](https://github.com/Code-Institute-Solutions/readme-template) for the basic structure to follow when creating a README file.
* The Code Institute [Gitpod template](https://github.com/Code-Institute-Org/gitpod-full-template) that installs useful tools into Gitpod.
* [W3schools](https://www.w3schools.com/) for various tutorials on HTML, CSS and Bootstrap
* [Coolors](https://coolors.co/) for colour palette ideas.
* A colour association PDF file created by a Code Insitute student which helped me decide on the colours to use for the website.
* [Bootstrap documentation](https://getbootstrap.com/docs/4.5/getting-started/introduction/) for information on the tools included in Bootstrap
* [Google Maps](https://www.google.ie/maps/place/Skycourt+Shopping+Centre,+Shannon+Town+Centre,+Tullyvarraga,+Shannon,+Co.+Clare/@52.710461,-8.8818376,17z/data=!3m1!4b1!4m5!3m4!1s0x485b41d4fed069cd:0x7897afe26116153b!8m2!3d52.7104578!4d-8.8796489) for the map I used on my contact page.

# Acknowledgements

* I took inspiration for this website and the gym ethos from the gym I am a memeber of, [Rory Skerrit Fitness Limerick](https://www.facebook.com/pages/category/Fitness-Boot-Camp/Rory-Skerritt-Fitness-Limerick-104753844210216/). They specialise in small group personal training. 


