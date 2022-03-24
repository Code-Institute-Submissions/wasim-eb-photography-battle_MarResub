# Photography Battle
The Photography Battle website is a photography meet-up. In this event, photographers will enter a competition that takes place in three different locations in a city. A new city is picked every week and this week's pick is "Stockholm". Photographers who wins the battle will earn prices, such as camera gear. In addition to that, all photographers, or competitors will get recognized on our instagram page during the competition.
In order to participate in this challenge, users will use the sign up form to get a chance to compete against other photographers. The given time and the exact location for the first meet-up will be sent via an email. You can access the website here: [Photography Battle](https://wasim-eb.github.io/photography-battle/)



![responsive design](assets/images/responsive.png)


## Technologies Used

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
    - Used as the basic building block for the project and to structure the content.
- [CSS](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)
    - Used to style all the web content across the project. 
- [Google Fonts](https://fonts.google.com/)
    - Used to obtain the fonts linked in the header, fonts used were Lato and Oswald
- [Font Awesome](https://fontawesome.com/)
    - Used to obtain the social media icons used in the footer
- [Google Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
    - Used as a primary method of fixing spacing issues, finding bugs, and testing responsiveness across the project.
- [GitHub](https://github.com/)
    - Used to store code for the project after being pushed.
- [Git](https://git-scm.com/)
    - Used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
- [Gitpod](https://www.gitpod.io/)
    - Used as the development environment.
- [Tiny.png](https://tinypng.com/)
    - Allowed me to compress my images so that the page would load faster.
- [Color Contrast Accessibility Validator](https://color.a11y.com/)
    - Allowed me to test the colour contrast of my webpage.
- [W3C Markup Validation Service](https://validator.w3.org/) 
    - Used to validate all HTML code written and used in this webpage.
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input)
    - Used to validate all CSS code written and used in this webpage.
- [AmIResponsive](http://ami.responsivedesign.is/)
    - Used to generate responsive image used in README file.


## UX
---
### **Strategy**

Considering the core UX principles I first started to think about the strategy for this website and defined who the target users would be and what features/technologies they would want. 
The thought behind this project was also very simple and also inspired from the movie Need for Speed. All racers would receive a Location pinpoint in which they had 45 hours to reach.
The user is able to grasp the necessary information pretty quickly. More inspiration and media will be found on the social media platforms.

Photography Battle's target users are:
* All ages
* Photographers

What these users would be looking for:
* An adventure
* Meeting new people
* Recognition in photography

### **Scope**

In order to achieve the beneficial goal, the following features will be included in this release:

- Header and menu bar, to navigate to various sections of the page
- Information section to introduce the event
- Newsletter sign up form
- Footer containing links to social media


## Features

This is a fully responsive website. The page is divided into the four sections listed in the navbar. Where a colour background has been used it has a nice fitting color and the text is white. All of the headings used the font Lato and I feel this consistency has been used across the website to create a coherent design. I have chosen a picture that fits the theme of the webpage and gives it a nice contrast combined with the other elements.


### Navigation bar

The navigation bar at the right top of the page is used to navigate through the different sections on the website.
The font for the navigation bar is the same font being used throughout the whole website to keep everything stylish and fitting with the theme.
The navigation bar is easily visible and makes it easier to navigate through the website without having to scroll down to your desired section. When viewed on a smaller screen, the navigation bar turns into a Hamburger menu. 



![nav-bar](assets/images/navbar.png)



### The About Page

This is where I introduce the event and all the information needed before and during the event. I also included a "Rules" section at the end of the page. 



![aboutpage](assets/images/aboutpage.png)



### This Week's Location

This section shows us the city of the current week's Challenge. I have included the name of the city
in the header. Below the header, we get to see a picture and name of each of the locations where different stages of the challenge will take place. I wanted to keep this section as clean as possible,
and my choice of pictures will be representing the previous winners of each of the locations.



![locations](assets/images/locations.png)


### Signup Form And Footer

The sign up form is used by the participants to sign up for the event. Eight participants are
randomly picked to join the Challenge. The participants will then receive all the necessary information for their next event. I was inspired by the movie "Need for Speed" where the competitors
for the Car race are randomly picked, and who then has 45 hours to reach the picked location.
The footer is very simple with the social media buttons. The background is a grayish color which I think fits in with the stylish background of a bridge in Stockholm.


![signup](/assets/images/signupfooter.png)



## Testing

* I experimented with the webpage on different browsers such as: Chrome(main), firefox, and safari. 
* I also tested the webpage on the [Responsive Design](http://ami.responsivedesign.is/) platform. 
* I made sure to test it live on different mobile phones aswell to see if how responsive the website is, also how it would look on different screens.
* I confirmed that the website works in function and in looks.


## Bugs

* I experienced a problem when attempting to view my webpage live. Some pictures were not showing. I corrected this error by adding a dot in the img code:

Before:


![without-a-dot](./assets/css/readme/s6.png)



After:


![with-a-dot](./assets/css/readme/s8.png)

* The sign up form was visible at the center of the big image while viewing it on my laptop, but it was moved to the left while viewing it on my mobile phone.
* I fixed this by playing around the margin and padding codes. I am still struggling a little bit with this part in coding but I'm getting there.


## Validator testing

* The end result shows no errors in the HTML code. Check the results here: [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fwasim-eb.github.io%2Fphotography-battle%2F)
* The CSS code is is also validated. Check the results here: [Jigsaw Validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fwasim-eb.github.io%2Fphotography-battle%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=es)
* No errors were found neither in the HTML nor the CSS code. 
* I used lighthouse in the dev tools in Google Chrome to confirm the accessibilty on both mobile devices and desktops.
---- Screenshot of the lighthouse performance ----

## Unfixed bugs
No unfixed bugs.

# Deployment 
This project was developed using [Gitpod](https://gitpod.io/workspaces), committed to git and pushed to GitHub using git commands. 

To deploy this page to **GitHub Pages** from its [GitHub repository](https://github.com/TNamdarian/saranamdarian), the following steps were taken:

1. Log into [GitHub](https://github.com/).
2. From the list of repositories on the screen, **select saranamdarian**.
3. From the menu items near the top of the page, select **Settings**.
4. Scroll down to the **GitHub Pages** section.
5. Under Source click the drop-down menu labelled None and select **Master Branch**. Then **Save** it. 
6. Wait for a few minutes of the website to be deployed.
7. Scroll back down to the **GitHub Pages** section to access the link to the deployed website.

### Run this project locally
- Select the Repository from the GitHub Dashboard.
- Click the green button labelled 'Code'.
- Click 'Download ZIP'.
- Extract ZIP file on your computer.
- Open folder and open index.html in web browser.

### Clone this project
- Select the Repository from the GitHub Dashboard.
- Click the green button labelled 'Code'.
- To clone the repository using:
    - HTTPS: under "Clone with HTTPS", click checklist icon.
    - SSH: click Use SSH, then click checklist icon.
- Open Git Bash.
- Change the current working directory to the location where you want the cloned directory.
- Type 'git clone', and then paste the URL you copied earlier.
- Press Enter to create your local clone.

## Credits

### Coding content
* Most of my coding was used by myself.
* The idea behind the webpage was inspired by a photographer name Northborders on instagram.
* I took a lot of inspiration from the Love Running project.
* I used [W3Schools](https://www.w3schools.com/) as my main source for codes.
* I had to go back a few times and look at older coding from the previous lessons.

### Media
All of my pictures were downloaded from [Unsplash](https://unsplash.com/)



