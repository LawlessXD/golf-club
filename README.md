# Grange Castle Golf Club - Milestone One Project

You can view the finished website [here](https://lawlessxd.github.io/golf-club/index.html)!

***

The purpose of this project is to create a static website for a golf club using a mobile-first design approach. The website is a single page design using HTML, CSS, and Bootstrap technologies learned throughout the first five modules in the Full Stack Web Developer course with Code Institute.

Grange Castle Golf Club was selected as the existing official website is not mobile user friendly.  

![Am I Responsive Image](https://github.com/LawlessXD/golf-club/blob/master/assets/images/am-i-responsive.jpg "Am I Responsive")

***

## UX

The objective of this website is to provide information to members of the public about the golf course, where the course is located and cost to play a game of golf. The site also provides information on the membership options available and a call to action button on the homepage to become a member.

### Strategy

Build a static front-end website for a local golf club using a mobile-first approach. As a user of the golf club, I found it frustrating that I couldn't use the current website without zooming in on the content. 

The primary audience for the website are members of the public looking to play a game of golf, get information about the course with the possibilty of becoming a member. 
- As a potential new Customer, I want to be able to find out information about the course.
- As a potential new Customer, I want to be able to find out the current green fees.
- As a potential new Customer, I want to be able to find out where the course is located.
- As a potential new member, I want to be able to view the different types of membership available.
- As an existing Customer, I want to be able to book a tee time.

The management of the golf club want to create an online presence for the club and provide information about the course with the objective to get additional Customers both as occasional golfers and to increase the total number of members.  
- As manager of the golf club, I want to increase the number of members at the club.

To meet the objectives of the golf club and needs of the target audience, I wanted to create a simple but attractive landing page.

The list of opportunites are presented below and rated in terms of importance, viability and feasibilty.

Letter|Opportunity    |   Importance     |    Viability / Feasibilty|
:----:|---------------|:----------------:|:------------------------:|
A|Create an online presence  |5|5|
B|Provide Course Information  |3|5|
C|Social Media Presence  |4|5|
D|Create an online booking system  |4|1|
E|Increase club members  |4|4|
F|Create a members only section    |4|1|

![Feasiblity Matrix](https://github.com/LawlessXD/golf-club/blob/master/assets/images/feasibility-matrix.jpg "Feasiblity Matrix")
### Scope

The scope of the project is derived from the needs of the user outlined in the strategy plane above. At this stage of the UX process, we decide what features will be provided now and what will be provided at some point in the future. The online booking system and members only section have been omitted at this stage as they require a backend to fulfil the functional requirement.

### Structure

The structure chosen is a one page site with different sections that provide the user with information on the course, green fees, membership options available, the location of the course and a contact form should the user want to submit a message to the golf club.

### Skeleton 

The structure plane is concerned with intuitive navigation throughout the site and how the content is presented to the user. Navigation is provided via a fixed navigation bar at the top of site which remains visible throughout the different sections of the site. The user has the ability to navigate through the site using the nav bar or by scrolling throughout the one page design. At this stage, wireframes were created using a combination of Balsamiq and MS Excel for some of the content (e.g. tables, cards). 

Wireframes can be viewed [here](https://github.com/LawlessXD/golf-club/blob/master/assets/wireframes/golf-club-wireframes.pdf "Wireframes")

### Surface 

The colours and fonts to be used for the project were chosen at the stage of the UX process. The primary colour selected is the navy background colour for the navigation bar which is derived from the background of the logo on the left of the navigation bar. The logo used is from the official [twitter](https://twitter.com/grangecastlegc "Grange Castle GC Twitter") page for Grange Castle Golf Club. 

The logo was opened in MS paint which allowed the RGB values (45,48,101) to be obtained using the eyedropper tool. The HEX value #2D3065 was obtained using https://www.rgbtohex.net/

The remaining colours selected throughout the site were generated using the Adobe colour wheel https://color.adobe.com/create to compliment the primary colour.

The font selected for use throughout the site is the Google Font Lato as this is easy on the eye and the text is readable from a user perspective. Google Font Oswald is used for the overlay text on the landing page.

___

## Features

### Navigation Bar
The navigation bar is displayed at the top of the viewport and has a fixed position to allow the user easily navigate throughout the site content without scrolling. The navigation bar collapses into the hamburger icon on screens less than 992px. The toggle was further customised by modifying the RGB values in the SVG file and creating a custom class .custom-toggler below.

The approach used in this [example](https://www.geeksforgeeks.org/how-to-change-hamburger-toggler-color-in-bootstrap/ "How to change hambuger toggler icon") was reused to achieve the desired result. 

### Zoom Effect

