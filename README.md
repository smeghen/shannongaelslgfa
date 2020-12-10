
# Milestone Project 1
---
## Purpose


This site was designed for the first milestone project in Full Stack Software Development with the Code Institute, based on the learnings from HTML, CSS and User Centric Design modules.

---

## Shannon Gaels LGFA


I decided to create a site for the Shannon Gaels Ladies Gaelic Football Club based on the fact that they currently don’t have a website and being involved in coaching one of the underage teams, I thought it would be a great opportunity to provide more information and hopefully inspire new members to join. In the future I hope to add more features to the site that will benefit both the club and members.

---
### User Experience (UX)

#### User Stories:
*First Time Visitors:*
* I want to immediately understand the nature of the site and learn more about the organisation.
* I want to be able to easily navigate through the site, with the structure of the content easy to follow.
* I want to easily access relevant information.
* I want to be able to access the site from all device types.

*Returning Visitors:*
* I want to be able to contact the Club with questions that I might have.
* I want to be able to access the social media links of the Club.
* I want to be able find the location of the Club grounds.

*Frequent Visitors:*
* I want to be able to access the links for Club membership and for purchasing Club kit.
* I want to be able to see details on the nominated Charity of the Month.
* I want to see recent photos of the club and its players.

#### Structure:
The main aim of this site is to provide details, pictures and links relating to the Shannon Gaels Ladies Gaelic 
Football Club. The site content will be both factual, inspirational and practical for all users. 
This is achieved by providing club history, aspirational pictures of club matches and players. 
Finally, having links to club location and key resources.


With this in mind a single-page layout with easy flow from section to section is best suited to the 
users that will be accessing the site. There will be a navigation menu contained in a fixed top 
header, which means that the user will be easily able to move around the site as needed. 
This will fulfil the user story -
> I want to be able to easily navigate through the site, with the structure of the content easy to follow.


The home page contains a high-quality image with the club name. This is then followed on by the 
About section of the site, which gives details on the club and some history. This will fulfil the user story -
> I want to immediately understand the nature of the site and learn more about the organisation.


The Gallery section will contain several pictures of the club grounds, players and recent matches. 
This will fulfil the user story - 
> I want to see recent photos of the club and its players.


The Contact section will contain a form for contacting the club and it will also 
contain the location of the club grounds on Google Maps. This will fulfil the user stories –
> I want to be able to contact the Club with questions that I might have.

> I want to be able find the location of the Club grounds.


The Information section will have links for Club registration, purchasing club kit and the 
club fundraising site. This will fulfil the user stories –
> I want to be able to access the links for Club membership and for purchasing Club kit.

> I want to be able to see details on the nominated Charity of the Month.


The Footer will contain the links for the club’s various social media accounts. 
This will fulfil the user story - 
> I want to be able to access the social media links of the Club.


It is envisioned that people accessing the site will range from young players, 
parents and interested parties in the community. With this is mind and the fact that 
most access will be by mobile devices; the design will be focused primarily for this 
format. The site will be responsive and the layouts will change dependant on screen size. 
This will ensure that the content of the site will remain appealing and readable on all 
devices. This will fulfil the user story - 
> I want to be able to access the site from all device types.


#### Design:

Colour scheme: 

After consulting with some of the club officials, I decided that the use of the club colours of #d6be0e yellow and #6cba1f green would be the best to emphasise the club brand. The background colour is set as white with the yellow and green being incorporated into Navigation Bar, Footer, Section divider. I had originally thought of using the yellow and green for the background colour, but after trialling found it to be too overpowering and distracted from the content of the site.

Typography:

The main font used throughout the site is Open Sans, which is the official font used by the club. Sans Serif is used as a fallback font.

Imagery:
 
The club has provided me with their Logo, which will be used in the Navbar. Other images of the club sign, grounds, and flags were taken by me and will be used throughout the site, so that users can easily identify with the club.


Wireframes




#### Differences to Design
---
#### Features:
##### Existing Features
##### Features to be Implemented in Future
---
### Technologies Used
* HTML -  HTML is the main language used for the structure of the site.
* CSS - Custom written CSS is used to style the site.
* Bootstrap – The layout and styling of the site was help by the use of Bootstrap framework.
* Google Fonts -The font of Open Sans was imported from Google Fonts.
* Font Awesome – Was used to obtain the social media icons used.
* Balsamiq – Was used to create the wireframes of the site on the various devices.
* Adobe Photoshop Express - Used to resize images used on the site. https://www.adobe.com/ie/photoshop/online/resize-image.html
* Git - Git is used for the version control of changes throughout the project.
* GitPod – was used as the coding space for the project.
* Github - was used to host the project files and publish the live website by using Git Pages.
* Autoprefixer - was used to parse  CSS and add vendor prefixes to CSS rules via https://autoprefixer.github.io/
* W3 HTML Validation was done via https://validator.w3.org/
* W3 CSS Validation was done via https://jigsaw.w3.org/css-validator/

---
### Testing


---
### Deployment
---
### Issues Encountered

*  Having the links to the various sections of the site made the navbar look to busy and cluttered. 
	  Solution – used the navigation drop down menu from Bootstrap to tidy up the navbar.

* Could not change the colour of the navbar drop down menu icon to make the colour scheme of the site. 
After a search on Slack the solution was found to change from the default Bootstrap icon to the Fontawesome icon and styled it using CSS.

* Keeping the text on the hero image when changing from desktop to tablet/mobile.
Solution found on Stackoverflow to use viewport values for text size rather than px. Also, varied the position of the text by use of top and left margin percentages so that it is responsive for all devices. A media query for smaller screens is used to change the margin percentages so that text stays in position.
https://stackoverflow.com/questions/32392383/how-to-center-text-responsive-in-image-using-css-html



* Aligning the images in the Gallery section and keeping them responsive with changes in screen size.
	Code found on w3schools.com for aligning images side by side. I modified this code to make it work for my needs and added the necessary media queries to adjust the images on various screen sizes.
https://www.w3schools.com/howto/howto_css_images_side_by_side.asp


* Wanted to change the highlight colour of the Bootstrap form input fields.
Code found on Stackoverflow to change the colour of the form input highlight when selected. I modified this code to change the colour to match the colour scheme of the site.
https://stackoverflow.com/questions/14820952/change-bootstrap-input-focus-blue-glow


* Was not happy with the alignment of the Bootstrap cards used in the About section. As the images and text cards are different sizes, having them align side by side did not look visually right to me. 	After reading through the Bootstrap documentation and trialing several options, I decided that using “align-self-center” for the text cards work best.

* Google Maps iframe was not responsive using Bootstrap.
Found solution on w3schools.com to make iframe responsive using CSS and code was adjusted to work for this site.
	https://www.w3schools.com/howto/howto_css_responsive_iframes.asp

---

### Credits

Hero Image downloaded from Unsplash, picture taken by Sandro Schuh.

Club photos taken by Deirdre O’Dowd for the Shannon Gaels Club.