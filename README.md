# GymBeam

[Visit the website here](https://jakbul.github.io/GymBeam/)

![](assets/documentation/mockup.png)

Created to represent local fitness centre in London and provide more information for users. This website was made for educational purposes only.

This website is made up of the following sections:

1. Home/Introduction
2. Students
3. Gallery
4. Contact

The business goals for this website are:

1. To promote our brand in the online world
2. To inspire users to visit the gym and furthermore get new costumers
3. To be reachable for customers with contact form
4. To build a database of users to send future information & content to, build an audience

The user goals of this website are:
1. As a first-time visitor, I want to easily find useful information about the gym, classes and facilities
2. As a recurring or first-time visitor, I want to be able to sign up to directly receive content via newsletter
3. As a first-time visitor, I want to be able to contact the gym with any further question
4. As a first-time visitor, I want to easily find information about special offer for students
5. As a recurring or first-time visitor, I want to be able to see how the gym looks like thanks to the gallery section

## UX

### **Strategy**

Considering the core UX principles I first started to think about the strategy for this website and defined who the target users would be and what features/technologies they would want.

GymBeam target users are:
* Aged 15-60
* Gym lovers trying to discover their potential
* People interested in fitness, healthy diet, martial arts, running or bycicle sessions
* Have an interest to reach new goals, motivation to reach a higher level of themselves

What these users would be looking for:
* Clear and easy-to-find information
* Beautiful photos that provide inspiration and make the destinations look desirable
* Facilities, special offers and classses to try use to

This website will offer all of these things whilst also allowing for intuitive navigation and comfortability of use. An effort was taken to not provide an overwhelming amount of information at first glance as this is often the reason people are put off with local gyms.

Due to the age group of the users, it is assumed that most users will be viewing the site not only on their mobile phones, but also on the tablets or computers. Therefore, creating something responsive is integral to the design.

### **Scope**

In order to achieve the desired user & business goals, the following features will be included in this release:

- Logo, header and menu bar, to navigate to various sections of the page
- Hero image section with inspirational quote
- Discover section below including short information about the gym
- Personal training section with desirable text
- Section with offer and pop-up window to sign up for newsletter
- Section with facilites and popular classes
- Follow up section with button linked to contact page
- Footer with brief information, quick links and opening times
- Dedicated webpage for students offer
- Dedicated webpage for gallery of images from the gym
- Dedicated webpage for contact form with address and phone number
- Links to affiliate social media pages in the footer

### **Structure** 

This is a multi-page website to give more space for dedicated pages. 

Users can simply scroll through the information as it is displayed or they can use the navigation bar at the top which allows them to easily move to whatever webpage of the site they are interested in. I chose the following order for the information 'Home > Students > Gallery > Contact', as I felt this would allow the information to be digested in the best way. The text blocks are enriched with images to ensure interest is kept and there is no information overload at any point. Finally, there is a simple contact form for users to be able to reach us with any questions.

### **Skeleton**

Whilst building the website I felt that there were sections with too much information about prices, classes and coaches. For this reason, I shortened or deleted some of the content of sections and simply added section with facilities using FontAwesome icons, newsletter section and follow-up contact us section. I felt it provides the user a positive user experience, it's easier to 'digest' the content while scrolling through images with less text information.

However, if user needs additional information before visiting us, he can simply contact us thanks to contact page where we can briefly answer any questions.

I also decided to resize my images in gallery by 50% to make them smaller and change their format to webp, as I felt it looked cleaner and improved the loading phase of our page. It also allowed for better responsiveness and the images looked better.

### **Surface**

I chose a colour palette based around white & black as these colours are elegant and simple to implement into design with more images on the webapge. I paired these with a lighter red colour to show appropriate contrast. 

- `#000000` used for primary text or background
- `#fafafa` used for secondary text
- `#ec5353` used for primary highlights
- `#f5634b` and `#fe9418` for hover effects
- `93c3c3` for footer

I used [coolors.co](https://coolors.co/000000-fafafa-ec5353-93c3c3-f5634b-fe9418) to help me generate my colour palette.

![screenshot](assets/documentation/coolors.png)

I used Google fonts 'Raleway' to design logo of website. I felt leaving font 'sans-serif' was a simple choice and stood out on the page in uppercase style.

- [Raleway](https://fonts.google.com/specimen/Raleway) was used for the logo.

- [sans-serif](https://fonts.google.com/knowledge/glossary/sans_serif) was used for all other secondary text.

- [Font Awesome](https://fontawesome.com) icons were used throughout the site, such as the facility section or social media icons in the footer.

## Features

This is a fully responsive website that was designed mobile-first as this is the most likely way it will be viewed; the page is divided into four pages listed in the navbar. Where a colour or image background has been used, it has a slightly transparent opacity and the text is white, or red color used throughout the project which highlights the keywords. All of the headings the body text use font sans-serif in uppercase, this consistency has been used across the website to create a coherent design. Headings, buttons and hover effect use similar colors to build an easy-to-follow apperance.

### Existing Features

- **Navbar**

    - the navbar is placed on top of a responsive image which acts as a header. It includes our logo on the left side. Aswell, it immediately shows on which page the user currently is thanks to underline effect and red color. Last but not least, the navbar doesn't discourage the user to get stuck thanks to matching black color with hero image below, so it's easy to follow to another section. When viewed on smaller screens, I opted for the menu to collapse into a toggler red icon with help of Bootstrap, as seen below on second screenshot. Navbar is used on all webpages and contains the same information

![screenshot](assets/documentation/navbar.png)

![screenshot](assets/documentation/navbar1.png)

- **Main Section**

    - this section continues after navbar with black background and contains hero-image of woman coach watching at a catchy quote. I used H1 element as it's main quote of the whole website. I used our red color to highlight the keyword "your dream body" as it's goal of our user - to strive for getting better and achieving the dream body

![screenshot](assets/documentation//hero-image.png)

- **Details**

    - this section introduce users more information about our gym. However, I try to keep this part clean and don't overload with unnecesary details. I decided to use two cards with separate headings and add nice hover effect, as visible in screenshot below. The background color changes to white for better vissible appearance

![screenshot](assets/documentation/details.png)

- **Personal Training**

    - this section starts with H2 heading and is followed by paragraph containing information about possibility to work with our personal training staff. It's short, easy to read and catch the attention with image of our personal trainer with his client

![screenshot](assets/documentation/PT.png)

- **Discover**

    - this part of website contains background image with lower opacity and heading H1 offering free first training when user signs up for our newsletter. That's important part of online business - to get e-mail of potential future customers and be able to navigate them throughout content with good e-mail marketing. Goal of section is motivate user to click on button 'Sign up' which will open the pop up window and user can sign up

![screenshot](assets/documentation/discover.png)

- **Facilities**

    - section contains H1 heading of our highlight red color, and text with images using free FontAwesome library which shows what services can visitor expect to use in our gym. I added simple black&white colors with background to show contrast in flow of the whole website

![screenshot](assets/documentation/facilities.png)

- **Classes**

    - this sections contains H1 heading of our highlight red color, and 3 cards that shows the top popular classes in GymBeam - with name of coaches, time of sessions and image. I decided to include this part in the project to show visitor of the website examples of training provided by our personal trainers team

![screenshot](assets/documentation/classes.png)

- **Contact follow-up**

    - last but not least, I added follow-up contact part of the page before footer to remind user that he can contact us with any question regarding to our service. It's a simple section which contains background image and H1 heading with follow up question. User will be redirected to "Contact" webpage after clicking on button "Contact us"

![screenshot](assets/documentation/contact-follow-up.png)

- **Footer**

    - last section is our footer - with logo and short information, links to social media websites where user can find us (with hover effect which we also used before), quick links to easily navigate throughout website and opening times (with nice transition and hover effect too). Background is slightly grey to distinguish the section from others. Footer is used on all webpages and contains the same information

![screenshot](assets/documentation/footer.png)