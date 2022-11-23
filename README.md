# We Ride Cycling Club 
#### We Ride Cycling Club is a fictional cycling community for expats in Europe. We Ride Cycling Club matches expats with "Local Leaders" in the city they are moving to. The cyclists can join the group rides lead by the Local Leaders, meet fellow expats and get access to a database of cycling routes to upload to their Garmin to explore solo. 

#### The goal of We Ride Cycling Club website is to help the club build a community network of cyclists across Europe, help expats discover their new home from a local perspective, and provide an easy sign up registration process for cyclists. We Rice Cycling Club wants to make it easy and less daunting for cyclists to discover their new home.

## Table of Contents
1. User Experience
    - Project Goals
    - User Stories
    - Coliur Scheme
    - Typography
    - Wireframes
2. Features
    - General
    - Home Page
    - About Page
    - Join Us Page
    - Contact Page
    - Future Features
3. Technologies Used
    - Languages
    - Frameworks, Libraries and Programmes
4. Testing 
    - Testing User Stories
    - Code Validation
    - Accessibility
    - Tools Testing
    - Manual Testing
5. Finished Product
6. Deployment
7. Credits 
    - Content
    - Media 
    - Code
8. Acknowledgements

## User Experience (UX)
### Project Goals
- Build a clean, modern website for a cycling club with a strong sense of community.  
- Clearly outline how the cycling club works.
- Provide a registration form for cyclists to join the club.
- Provide a contact details for users to be able to ask for more information. 
### User Stories
- As a user, I want to be able to easily navigate the website to discover more about the cycling club. 
- As a user, I want to be able to join the cycling club.
- As a user, I want to be able to find contact information for the cycling club. 
- As a user, I want to be able to find the cycling club on social media. 
### Colour Scheme
#### The colour scheme used was a modern teal green with grey and white. A teal 
### Typography
- Barlow Condensed was used for the logo and headings with sans-serif as the fallback font.
- Montserrat for body/paragraph text with sans-serif as the fall back font.
### Wireframes
- Balsamiq was used to develop wireframes in the planning stage of the website. 

## Features

### General
- The website incorporates a responsive design so it can be used across multiple device sizes. 
- The website uses a consistnet colour scheme across the site. 
- Each page has a responsive navigation bar with the club logo and links the each website page to allow for easy navigation for the user.
- Each page has a repsonsive footer with social media links. Social media links open in a new browser window. 
### Home Page

#### HERO IMAGE
- The homepage has a photograph of three cyclists overlayed with the club tagline, Together We Ride. 
- The section aims to portray a strong sense of community and inclusion being core values of the cycling club. 
#### INTRODUCTION
- This page also has a brief introduction explaining that it is a cylcing club for expats where they can join weekly rides. 
- This section also has a selection of images as a design feature to convery the inclusive, community values. 
#### HOW IT WORKS
- This section explains how the club operates and uses icons to support the explanation. 
#### CTA 
- This section contacts a CTA button that will bring the user to the Join Us page of the website. 

### About Page
- The about page is split into 3 section: Our Story, Our People and Missions and Values.
- The page 
### Join Us Page
- The Join Us page has a photo over cyclists overlayed with a form.
- The form has a brief instruction that tells the user to fill in their information to be matched with a Local Leader. 
- Hover effects have been added to text fields and button to enhance user experience. 
### Contact Page
- The Contact page has a contact form for users to submit any queries or questions they may have. 
- The Contact page also has the club contact details should the user prefer to get in touch directly. 
### Future Features 
- An "Insights" page which would host weekly blogs from We Ride Cycling Club members, articles on cycling trends, and general cycling advice articles. 
- Pre-populated dropdown menu of cities on the Join Us form based on the Country that the user selected. 

## Technologies Used

### Languages 
- HTML 
- CSS 
### Frameworks, Libraries and Programmes 
- Balsamiq: this was used to created wireframes in the planning stage of the project. 
- Fontpair: fontpair was used to find fonts that compliment each other. 
- Google Fonts: this was used to import fonts into the style.css file.
- Font Awesome: this was used to add icons to pages to enhance user experience. 
- Pexals: this was used to find images and videos for the project. 
- Gitpod: this was used to write, commit and to push the code to Github. 
- Github: this was used to host and deploy the finished project. 
- Chrome DevTools: this was used throughout the project to check responsiveness and debug any issues. 
- W3C Markup Validator: this was used to throughout the project to validate HTML code. 
- W3C CSS Validator: this was used throughout the proejct to validate CSS code. 
- Responsive Design Checker: this was used to check responsiveness on various device sizes. 
- Am I Respsonsive?: this was used tp create an image to show how the site looks on different device sizes. 

## Testing

### Testing User Stories
- As a user, I want to be able to easily navigate the website to discover more about the cycling club. 
    - The website menu bar allows the user to navigate through the pages of the website.
    - The website pages have clearly identified sections for the user to be able to scan and digest the information.
- As a user, I want to be able to join the cycling club.
    - The website had a join us registration form.
- As a user, I want to be able to find contact information for the cycling club. 
    - The website has a dedicated contact page where a user can submit a request using the contact form or directly contact the cycling club using the information provided.
- As a user, I want to be able to find the cycling club on social media. 
    - The website has links to the clubs social media pages on the footer of each page. 
### Code Validation
The following validators were used to test the code:
- [W3C Markup Validator](https://validator.w3.org/): No errors were returned when passing the final HTML code through the validator. 
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/): No errors were returned when passing the final CSS code through the validator.
The validators were used throughout the development stage of the website. Examples of errors can be found below: 

### Accessibility
The following tool was used to check accessibility of the website:
- [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/): was used to check accessibility the score of each site page and to see if there were issues. 
    - This tool highlighted an issue with radio button labels on the Join Us page. The wrong "for" value had been assigned to the 80-100km radio button which impacted the accessbility score. After fixing this issue the accessibility score increased from 90 to 100.
- Lighthouse reports:
### Tools Testing
The following tools were used to test the website:
- [Chrome DevTools](https://developer.chrome.com/docs/devtools/): This was used throughout the project to test responsiveness, to de-bug any issues, and to test changes to HTML and CSS before implementing them in Gitpod. 
- [Responsive Design Checker](https://www.responsivedesignchecker.com/): This was used to check the responsiveness of the site on different device sizes.  

### Feature Testing
The following website features were manually tested:
- Clicking on the logo will bring the user to the home page.
- The navigation menu links work on each page and bring the user to the correct page. 
- The join us CTA button on the home page and about page brings the user the to Join Us page.
- When social media icons are clicked the relevant social media page opens in a new window. 
- The submit button on the Join Us form and Contact form does not work until all fields have been filled in by the user. Testing this function revealed that the 'Mobile Number' and 'textarea' fields were not marked as 'required'. This was reolved.  
- The reset button clears the form. 
- The hover effect added to buttons and text fields highlights functionality for the user. 

## Finished Product

## Deployment
The website was developed in Gitpod. It was then commited and pushed to GitHub. 
The finished site was then deployed to GitHub pages using the following steps: 
1. Open GitHub and click on the We Ride Cycling Club repository. 
2. Once inside the repsitory, locate and click on the settings tab. 
3. On the left handside under the 'Code and automation' section, click on Pages. 
4. In the Branch section, locate the dropdown menu and change it from None to Main. 
5. Click save. The page will refresh with a link to your website. 

The live link can be found here: https://orlagh-sweeney.github.io/we-ride-cycling-club/index.html

## Credits
### Content
- All content was written by the developer. 
### Media
- Photos and videos were taken from [Pexals](https://www.pexels.com/):
    - Home page hero image: "Three Men Riding on Bicycles" by Pavel Danilyuk
    - Home page introduction image 1: "Woman Wearing White Helmet" by Kezia Rhesa Arman 
    - Home page introduction image 2: "People Riding Bicycle on the Road" by Samuel Vogl
    - Home page introduction image 3: "Adult cyclist smiling on field by Centre" for Ageing Better
    - Our Story image: "Person in Black Long Sleeve Riding Bicycle on the Road" by Gregory Costa
    - Our People image: "High Angle Shot of Person Riding a Bike" by Niklas Jeromin 
    - Mission and Values image: "Man in Black Shirt Riding Bicycle on Gray Asphalt Road" by Pack2Ride
    - Mission and Values video: "Drone Shot of Cyclists on the Road" by LegioSeven
    - Join Us background image: "Aerial Shot of People Riding Bicycle on Road Between Trees" by Pavel Danilyuk
- Icons were taken from [Font Awesome](https://fontawesome.com/). 
### Code
- [Stackoverflow](https://stackoverflow.com/) and [W3Schools](https://www.w3schools.com/) were used throughout the development to educate myself and to seek help on the following features: 
- I used W3Schools to create the dropdown menu feature on the Join Us. I used the solution on the [HTML Form Elements](https://www.w3schools.com/html/html_form_elements.asp) page. 
- I used Stackoverflow to center the form on the Join Us page, I used the solution shared by [Rhythm Shandlya](https://stackoverflow.com/questions/8097744/how-do-i-center-this-form-in-css).   
- I used W3Schools to find out how to add rounded corner to buttons. I used the solution from the [CSS Rounded Corners](https://www.w3schools.com/css/css3_borders.asp).
## Acknowledgements
- Thank you to my mentor Marcel for his feedback and suggestions at each stage of the project. 