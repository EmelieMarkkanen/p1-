python3 -m http.server

# Stockholm Spa Hotel

## Milestone project 1

Stockholm Spa Hotel is a static front end website aimed to show the technologies I have learned so far during the Code Institute fullstack developer course, in this case using HTML and CSS. 

I have decided to create a website for a fictional hotel, Stockholm Spa Hotel. The website is built using what I’ve learned during the course so far and based on the priciples of good user experience to create a responsive and functional website. 

The website consists of a landing page with an introduction to the hotel and a link to a booking form. It also have links to three separate pages with information about the hotels room options, restaurant and bar options, and spa experience. 

## Live project website
[View live website here](https://emeliemarkkanen.github.io/p1-stockholm-spa-hotel/)

## ReadMe table of contents

- [Milestone project 1](#milestone-projekt-1)
- [Live projekt website](#live-projekt-website)
- [Screenshots of website](screenshots-of-webiste)
- [User stories](#user-stories)
- [Typography and color scheme](#typography-and-color-scheme)
    - [Typography](#typography)
    - [Color scheme](#color-scheme)
    - [Imagery](#imagery)
- [Features](#features)
    - [Responsive](#responsive)
    - [Booking](#booking)
    - [Social](#social)
    - [Information](#information)
- [Wireframes](#wireframes)
- [Technology](#technology)
    - [Languages used](#languages-used)
- [Testing](#testing)
    - [Guest experience](#guest-experience)
    - [Code testing](#code-testing)
- [Credits](#credits)
    - [Content](#content)
    - [Acknowledgement](#acknowledgement)
    - [External sources used](#external-sources-used)


## Screenshots of website
###Landing page
![Landing page](https://github.com/EmelieMarkkanen/p1-stockholm-spa-hotel/blob/main/assets/images/Screenshots/Stockholm-spa-hotel-screenshot.jpg)

###Booking form
![Booking form](https://github.com/EmelieMarkkanen/p1-stockholm-spa-hotel/blob/main/assets/images/Screenshots/Booking-form-screenshot.jpg)

###Restaurant
![Restaurant](https://github.com/EmelieMarkkanen/p1-stockholm-spa-hotel/blob/main/assets/images/Screenshots/eat-screenshot.jpg)

###Rooms
![Rooms](https://github.com/EmelieMarkkanen/p1-stockholm-spa-hotel/blob/main/assets/images/Screenshots/sleep-screenshot.jpg)

###Spa 
![Spa](https://github.com/EmelieMarkkanen/p1-stockholm-spa-hotel/blob/main/assets/images/Screenshots/relax-screenshot.jpg)

Screenshots created using [Am I Responsive](https://ui.dev/amiresponsive)

## User stories

The prospective guest

- As a prospective guest I would like to be able to read information about the hotel and the experience it offers.
- As a prospective guest I would like to be able to book a room at the hotel. 
- As a prospecive guest I would like to be able to see images of the hotel rooms, prices and what they contain.
- As a prospective guest I would like to see images and find information about the hotel restaurant and it’s menu.
- As a prospective guest I would like to see images and find information about the hotel spa experience and examples of treatment options. 
- As a prospective guest I would like to see contact information to the hotel such as address, email and phonenumber to the hotel. 

## Typography and color scheme 

### Typography
The typography used on the website consists of two fonts, Domine for headings and Lato for paragraph text, imported from [Google fonts](https://fonts.google.com/).
I’ve used Domine to highlight the headings and logo of the hotel and complementing that with Lato for the overall text, to give a nice contrast between the two.

For the PDFs in the README.md and on the website I used the fonts Aldhabi for headings and Arial Nova for paragraphs. 

I have also used some symbols from [Font Awesome](https://fontawesome.com/) for decorative and social media links and the hotel logo on smaller screens.

### Color scheme
I’ve used a color scheme of four main colors through out the website. I chose the color scheme to reflect the content of the website and the overall inspiration of the hotel, eg the Stockholm archipelago. 
The color scheme consist of two hues of green, #5f7161 and #6d8b74, a hue of gray, #d0c9c0 and a hue of beige, #efead8. 
The overall background and some text of the website is beige, while the gray is used for the footer and the booking form hover link. The green hues are used for background in some sections, text and links. Different hues of green is used to highlight hovering over links. 
The color scheme suggestion was found at [Colorhunt](https://colorhunt.co/palette/5f71616d8b74efead8d0c9c0). 

### Imagery
I wanted the imagery of the webiste to reflect the content and give a feeling for the inspiration of the hotel, eg the Stockholm archipelago. I've used images that give a sense of the sea and forest, with the images matching the color scheme of the website. 
Each page have one or several images to convey what the section is about. 
I have used [Pexels](https://www.pexels.com/sv-se/) as a source for images. 

## Features

### Responsive
The website is responsive to all screen sizes.

### Booking
The website contain a booking form for potential guests to send a reservation.

### Social
The website contain links to social media sites and a travel guidance site

### Information
The website contain information about the hotel, location, restaurant options, room options and information about the spa. There are links to PDF:s containing a menu for the restaurant and a list of spa treatments. 

## Wireframes

I created the wireframe for this project using Balsamiq.
<br>
[View PDF of wireframe here](https://github.com/EmelieMarkkanen/p1-stockholm-spa-hotel/blob/main/assets/images/pdf/Stockholm%20spa%20hotel%20wireframe.pdf)

## Technology

### Languages used
For this project I’ve used HTML5 and CSS. 

- [HTML5](https://sv.wikipedia.org/wiki/HTML5)
- [CSS](https://sv.wikipedia.org/wiki/Cascading_Style_Sheets)

## Testing

### Guest experience

### Code testing

Code validated trough W3C CSS and HTML validator
- CSS [result](assets/images/Screenshots/css-validation.jpg)
- HTML 
    - Landing page [result](https://github.com/EmelieMarkkanen/p1-stockholm-spa-hotel/blob/main/assets/images/Screenshots/index-validation.jpg)
    - Booking form [result](https://github.com/EmelieMarkkanen/p1-stockholm-spa-hotel/blob/main/assets/images/Screenshots/form-validation.jpg)
    - Thank you reply [result](https://github.com/EmelieMarkkanen/p1-stockholm-spa-hotel/blob/main/assets/images/Screenshots/thankyou-validation.jpg)
    - Eat [result](https://github.com/EmelieMarkkanen/p1-stockholm-spa-hotel/blob/main/assets/images/Screenshots/eat-validation.jpg)
    - Sleep [result](https://github.com/EmelieMarkkanen/p1-stockholm-spa-hotel/blob/main/assets/images/Screenshots/sleep-validation.jpg)
    - Relax [result](https://github.com/EmelieMarkkanen/p1-stockholm-spa-hotel/blob/main/assets/images/Screenshots/relax-validation.jpg)
    - 404 [result](https://github.com/EmelieMarkkanen/p1-stockholm-spa-hotel/blob/main/assets/images/Screenshots/404-validation.jpg)

All pages pass through Lighthouse with a score of 93 or higher. 

### Known issues

- W3C validator gives a warning that the booking form page section don't have a h1-h6 heading. 
- W3C validator gives a warning that the index page have empty h1 tags, though they contain symbols from Font Awesome and I've chosen to ignore this. 

### 404
I created a 404.html file with a message and a link back to the landing page if a user should enter an invalid url. The 404 page also contains a header and navbar.

## Credits

### Content 
All content is written by me

### Acknowledgement
- Code institute for excellent teaching
- My mentor Rohit for valuable input
- Caliban cat for emotional support and cuddle breaks

###  External sources used: 
- [Pexels](https://www.pexels.com/sv-se/) - Images
- [Colorhunt](https://colorhunt.co/palette/5f71616d8b74efead8d0c9c0) - Color scheme suggestion
- [w3resource](https://www.w3resource.com/icon/font-awesome/brand-icons/tripadvisor.php) - Tripadvisor icon
- [Font Awesome](https://fontawesome.com/) - Icons
- [Google Fonts](https://fonts.google.com/) - Fonts
