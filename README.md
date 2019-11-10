# Animal Health Ireland Website Redesign
Stream One Project: User-Centric Frontend Development 

This is a website redesign is to present to my current employer, Animal Health Ireland.  The redesign will include the primary elements of the current website but with a new fresh and easy to navigate feel. Feedback from users on the current website layout is hard to navigate and locate relevant information. 

The website must be user-friendly for all its users which includes staff, stakeholders, industry representatives and the general public. Additional feedback from the company is that the current website is text-heavy, and they would like to see more images through. 

## Demo
A live demo can be found <a href="https://lisaannbyrne1.github.io/MilestoneProject1/">here.</a>


## UX

### User stories
As a staff member, I expect to be able to find essential content quickly and easily.

As a member of the general public, I expect to be able to find out who AHI are and what they do in one click or less.

As a stakeholder or industry representatives, I expect to see a showcase of the programmes operated by the company.

### Strategy 
The goal of this design is to make it as easy as possible for the different types of audience to navigate through the website and find the information they are looking for.  While also providing the company with a modern sleek designed website. 

### Scope
As the website is aimed at a number of audiences, I want to ensure that I provide an easy to navigate landing page which displays all the key areas of the company. 

### Structure
The layout is broken out into sections and in each section, there is a number of box cards which breakdown the sections into summary headers.  This cards then provide a description of the area cover.  Some cards contain shortcut links to contact us and sign up forms. 

### Skeleton
<a href="https://github.com/lisaannbyrne1/MilestoneProject1/blob/master/assets/wireframe/Wireframe.pdf">Desktop and mobile wireframe </a>

### Surface
The agriculturally image backgrounds identify clearly the nature of the website. The darken overlay allows the fonts and cards to stand out and be clearly read. 

## Features
The site includes a sticky navigation bar which will always remind at the top of the page for easy navigation.  The navigation bar is responsive and converts to a burger menu on mobile devices.  The sections cards have an animation property which increases the size when hovered over. 

### Features left to implement
In the future, I would like to develop the site to include additional sub-pages for the current sections. I would also like to make the menu bar decrease in size on scroll so the user can see more of the content but still access the menu bar easily. 

## Technologies

1. HTML
2. CSS
3. Bootstrap (3.3.7)

## Testing
The website was tested against the criteria set out in user stories and it met the criteria by providing a showcase of the company and its key elements. For stakeholder or industry representatives the first section on the page brings them to the about sections which details who the company is and what they do, they then scroll to the next second which is all the current programmes operated by the company.  For staff members and the general public, on landing on the page they are only required one click to review each section that they want to explore.  

The contact us links and email address will open a new email with the subject prepopulated depending on which contact us link is used.

All external links have been tested to ensure they open to the correct destination and all links will open in a new tab using 'target="_blank"'.

The site has been tested across multiple various internet browsers including Firefox, Microsoft Edge, Chrome, Silk and Safari.  It has also been testing for compatibility and responsiveness on mobile devices. During testing I found that the css property background-blend-mode: darken is not currently supported by Microsoft Edge. I decided not to change the current code as it did not effect the overall look of my website. I also found during testing that some of the background images I am using displayed blurry on IOS. On research I found that Safari/IOS have limitationa displaying larger PGN and GIF images. I found by removing backgound-attachement: fixed; the issue was resolved.   

## Deployment
This site is hosted on GitHub pages and was deployed directly from the master branch and the live site updates automatically when new changes are pushed to the repository.


## Credits
All contents on this website have been provided with permission by my employer Animal Health Ireland as part of an inhouse website redevelopment project. 

### Media
All photos were taken from Animal Health Ireland with permission. 

### Acknowledgements
I received inspiration from several sources for this project, they included feedback from users both internal and external to the company.  

Styling of social media icons taken from here.

Styling of social media icons taken from <a href="https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_social_media_buttons2">here.</a>

Tutorial for setting the height and width of the cards based on the content was taken from <a href="https://www.w3schools.com/cssref/pr_grid-template-rows.asp">here.</a>