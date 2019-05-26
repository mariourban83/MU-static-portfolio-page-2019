# Mario Urban - Portfolio page
Milestone project 1 for Code Institute - Frontend Development Module.

This is my portfolio, single page website to introduce myself. The website is fully responsive and the purpose of it is to show and present myself as an experienced web designer, developer and online marketer.


## Live page
Live version of my website deployed to  Google Firebase can be found [here](https://mariourban.net/) or on github pages [here](https://mariourban83.github.io/MU-portfolio/).

![Alt text](assets/images/mario-urban.png?raw=true "Mario Urban portfolio")


## User Experience Design

The website was designed with user in mind. For design and development, I was using mobile first approach, however, I do expect more users to come from desktop pc's. The main goal of the website is to explain in a simple, yet clear way who I am, what I do, what do I know (my skills), to show some of my projects from the past and also to give the user option to contact me if they wish via contact form, email, phone or find more info about me via social links.

I choosed darker theme for design. Contrasting colors, dark background/white text and vice versa improve readability of the content.

The whole website is divided into 7 sections, all noticable by large name at the top of each section.

### 1. Landing view section with navigation and header
Upon landing, I wanted to give user immediately know my name and what I do. Instaed of using logo, I decided to put my name to the top left corner followed with navigation links on the desktop view or menu icon for mobiles on the right. Navigation bar is fixed at top and transparent upon landing, but imediately after scrolling changes to dark to make name, links or menu icon fully visible.
As good practice, name, Mario Urban, acting as logo, is clickable and change color on hover, indicating link, to bring user back to the top of the page. Links will also change color on hover or click.
On mobile version, after clicking on menu icon, dark background menu with white center aligned links will slide down.
After clicking on any link from the menu, user will be directed to the section on the page.

The main header, short and descriptive is letting user know what I do.I choosed white text with linear-gradient background to make it stand out and easier to read.

The background image covers 100% of viewport height. Animated arrow at the center bottom of the page indicating more content bellow.

### 2. About me section
Illustrated image of happy, smiling developer is used instead of picture of me as it is not always good practice to show real photo (wrong judgment based on the picture). However, this will be subject for testing in the future.
Text followed ater the image introduces myself as a freelance web developer and online marketer. The text is short, easy digestible and also points to the modern world problems with websites, apps and technologies. It presents me as a solution to some of these problems and also lay out foundation for the next, What I do section.

### 3. What I do section
This section is divided into 3 topics focusing on my 3 key expertise areas, Design, Development and Marketing. I used card style for separation of each area for easier readability. The text in each area is letting user know further what I do and how I can I be helpful. Icons with smaller headings bellow will aid in description.

Darker background image of server will make the areas in this section more visible. On the desktop, they are positioned beside each other, however when the viewport gets smaller, they stack below each other.

### 4. My Skills section
In my skills section, progress bars are used to visually display my knowledge level and also technologies used for each area mentioned in what I do section. Dark gradient background with white text and coloured progress bar are visualy appealing, easy readable and understandable. By presenting technologies this way, I am not boring the user with too much reading. Each area section is also accompained with a picture related to the topic.

### 5. Portfolio section
In portfolio section, I am presenting some of my previous work. The color of the images is similiar as tha page theme, so they fit nicely to the content and are well separated with plenty of whitespace. To briefly explain what they mean, I put an lighter coloured, semi-transparent background box with cation over the image to let user know more about the particular project.

### 6. Contact section 
This section is giving user oportunity to contact me via preffered contact method. On the desktop view, the form on the left contain only important fields as name, e-mail address and message. The form is validating input in each field, user can't submit the form without filling all of the fields. Also, correct email address must be fill in to submit the form. After clicking submit button, the user will be re-directed back to the top of the page as for now as no backend database is conected to the website now.
The address on the right on the desktop view, bellow form on mobile, is indicating where I am based. The send email link in address section allow user to contact me via e-mail. If configured in user device, clicking on this link will open mailing app. The phone link act same way, after clicking it allows user to directly call if on mobile.

### 7. Footer section
Dark background of the footer section separate the previous section. The links to the social media gives user ability to find more information about me on my social chanel. Font awesome icon are used for labelling these chanels. They are big enough for clicking and all chanells are recognisable. As these are link, they also change color on hover or on click.
I also included links to the Privacy Policy and Cookies pages. These pages will be created later, at the moment, they redirect user back to the top of the page. The section ends with copyright information.

## Technologies used 
1. HTML
2. CSS
3. Bootstrap (4.3)
4. Javascript and Media Queries

## Features
The Javascript code with transition effect is used for changing color from transparent to dark on navbar navigation. By adding this future, the user will always see the name and the links or the menu icon on the top.

## Testing
The website was tested during and after development on multiple devices accross three major browsers, Chrome, Safari and Firefox.
The devices used for testing where mobile phones such as Samsung Galaxy S4, Apple iPhone SE, Sony Experia, Amazon 7" Fire tablet, HP 14" laptop with medium screen resolution and 23" size full hd screen on desktop pc. 
Chrome dev tools and Firefox dev tools were also used for testing responsivness of the website.

Every element and section was adjusted during development stage to respond and adapt to different screen sizes.
Also, Galaxy S4 ADB with Google Chrome inspection tool was also used during development stage.

The website is fully responsive, images scale properly,text resize and adjust to the viewport. Elements are stack and ordered based on the device width. 

Navigation bar with links on desktop collapse to menu icon for devices when screen width gets bellow 991px.
Clicking on the icon will slide down the menu with links.
Text in about me section stays at fixed width of 768px when screen size gets bigger than 992px. This improves readability.
The cards in about me section stay beside each other for devices with width wider than 992px. When screen get bellow this point, the cards stack bellow each other and occupy 85% of viewport.
The collumns in My skills section will take 50% of the viewport,on large devices.When width gets smaller than 768px, they stack below each other. At that size, the order of the collums also change to match the sequence text-image text-image text-image.The images scales properly thanks to fluid container used.
In portfolio section, the images responding to the width and gets also stack below each other when viewport gets smaller than 576px.
In Contact section, contact form width respond to the screen size width. Bootstrap Jumbotron feature is used to achieve full responsivness. At the width smaller than 768px, the contact details section gets below contact form.
In the footer, everything is centered and stays the same independent on the viewport width.

## Deployment
This site is hosted on Google Firebase and also using GitHub pages, deployed directly from the master branch. It updates  automatically upon new commits to the master branch. In order for the site to display correctly on GitHub pages, the landing page is named `index.html`.

To run this repo locally, you can clone this repository directly by pasting `https://github.com/mariourban83/MU-portfolio.git` into your terminal and open it in the code editor of your choice.

## Credits

### Content
All text content on the website was written by me. 

### Media
Background photos, illustrated picture of developer, photos in My skills section are free from https://pixabay.com. 
First photo in Portfolio section was taken from [here](http://www.winnickimarek.com/) with the permission from the author. Free Font awesome icons were also used in design. The rest were created by me using Adobe XD and Adobe Illustrator.

### Acknowledgements
The adjusted code for animated arrow feature was found [here](https://codepen.io/raf187/pen/BvgGRQ) and the credit goes to Rafael Amorim.

#### For educational use.