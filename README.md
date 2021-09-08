# Syncro Ireland

## The Home of Ireland's Annual VW Syncro 4x4 Event
Syncro Ireland was built to become the main focal point of an annual Irish event for VW Syncro enthusiasts. The site aims to promote and encourage engagement from the community across the island of Ireland, the UK, and international visitors.  The organiser's goal is to encourge enthusiasts to sign up to receive news regarding Syncro (and other 4x4) events, and to build a cohort of volunteers to ensure the event's continued success.

You can view the Syncro Ireland live site [HERE.](https://davewatters.github.io/syncro-ireland)
<br />
<br />

<!-- Responsive desgin sample image from http://ami.responsivedesign.is/ -->
<h2 align="center"><img src="docs/ci-pp1-syncro-ireland-responsive-mockup.png"></h2>

## - Table of Contents -
* [Purpose](#purpose)
* [User Experience Design (UX)](#user-experience-design)
* [Features](#features)
* [Technologies](#technologies)
* [Testing](#testing)
* [Deployment](#deployment)
* [Credits](#credits)

## - Purpose -
[ This website was created as the first Portfolio Project (PP1) for the Code Institute's Full Stack Web Development course. ]

The site was built to become the main focal point of an annual Irish event for VW Syncro enthusiasts. The target audience are mostly VW Syncro owners, but extends to all other 4x4, off-roading and camper van enthusists. The organisers had been using various other media (Facebook; online club forum) to get information out to the channel, with mixed success. They realised that there was no single online destination to find out about events in Ireland and connect all interested parties. This made it difficult to build momentum for an event idea. It was realised that a registration portal was needed to inform those interested in attending, and, in fact, a register of volunteers was needed to help make the event happen.  This site aims to fulfill those needs for both the organisers and attendees.

## - User Experience Design -

-   ### User stories

    -   ### Design Strategy Goals
        1. Create an online presence to promote the annual Irish event
        1. Site must inform vistors about future and past events
        1. Create a registration form to:
            - capture contact details of those interested in receiving event news
            - capture contact details of those interested in volunteering at events
            - allow the user to submit suggestions or feedback 
        1. Site must be intuitive to read & navigate on both desktop & mobile devices

    -   ### Design Scope to Deliver MVP
        -   #### First Time Visitor Goals
            As a first time user...
            1. I want to easily understand the main purpose of the site and learn more about the organisation
            1. I want to be able to easily navigate throughout the site to find content
            1. I want to find their social media links to follow event news

        -   #### Returning Visitor Goals
            As a returning visitor...
            1. I want to be able to easily register my interest in attending an event
            1. I want to find the best way to get in contact with the organisers with any questions or suggestions I may have
            1. I want to find community links

        -   #### Frequent User Goals
            As a frequent user...

            1. I want to to see if there are any new events happening
            1. I want to to see if there are any updates on a forthcoming event
            1. I want to see any new photos or videos of previous events or realted acitivites

-   ### Design
    -   #### Colour Scheme
        To highight the 'Irishness' of the site a green/white/gold variation was used throughout the site. I chose to base these colours on actual official VW colours as used on the Syncro vans (e.g. VW Escorial Green), so this design choice should also feel familiar to the site's users. The choice for the background was between an off-white VW Pastel White, Ford Polar and a Chrysler Arctic White, all of which have 'AAA' WCAG 2.0 contrast scores when used as text on the green background (i.e in the header & footer). The results of the colour contrast testing are included in the [Testing](#testing) section below.

        - Colour choices
            - Ford Polar White, #eef4f4
            - VW Escorial Green, #344d2c
            - VW Brilliant Yellow, #edda1

        - How colours were used
            - Body: White
            - Header: Green 
            - Footer: Green
            - Content text: Green on White or White on Green, as applicable
            - Hghlights (Active/Selected/Border): Yellow


    -   #### Typography
        -  The Google font, Raleway, was chosen as its unique 'W' bears some resemblance to the W in the iconic VW logo

*   ### Wireframes

    -   ~~Home Page Wireframe - [View](https://github.com/)~~

    -   ~~Mobile Wireframe - [View](https://github.com/)~~

    -   ~~Signup Page Wireframe - [View](https://github.com/)~~

## - Features -

-   Responsive on all device sizes

-   ??? Interactive elements  ????

## - Technologies Used -

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Git](https://git-scm.com/)
    - Git was used for version control and managed via the VSCode terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the project's code after being pushed from Git, and Github Pages used to deploy the live site
1. [Google Fonts:](https://fonts.google.com/)
    - Google font 'Raleway' was imported in the style.css file and used throughout the site.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used to add icons for aesthetic and UX purposes.
1. [Gimp:](https://www.gimp.org/)
    - Gimp was used to edit and retouch photos for the website.
1. [Birme:](https://www.birme.net/)
    - birme.net was used to resize images.
1. ~~[Balsamiq:](https://balsamiq.com/)~~
    ~~- Balsamiq was used to create the [wireframes](https://github.com/) during the design process.~~

## - Testing -

-  ### Code Validation
    The [W3C Markup Validator](https://validator.w3.org/#validate_by_uri) and [W3C CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator/#validate_by_uri) services were used to validate every page of the project for syntax errors. All validation was re-run after fixing the errors shown below to ensure that no futher errors or warnings existed.

    -   index.html Warning: errant `<section>` was replaced with a `<div>` as `hero-section` is for decoration only and has no semantic use
    <h2 align="center"><img src="docs/w3c-validator-html-index.png"></h2>

    -   events.html Error: embeded video link code was actually generated by YouTube, but I removed the attribute to fix this
    <h2 align="center"><img src="docs/w3c-validator-html-events.png"></h2>

    -   signup.html Error: stray tag was deleted
    <h2 align="center"><img src="docs/w3c-validator-html-signup.png"></h2>

    -   style.css: two stray commas were found and deleted
    <h2 align="center"><img src="docs/w3c-validator-css-style.png"></h2>

-   ### User Stories
    Testing User Stories from User Experience (UX) Section
    <!-- How were the User Story goals achieved? -->
    -   #### First Time Visitor Goals

    -   #### Returning Visitor Goals

    -   #### Frequent User Goals

-   ### Responsiveness
    - Chrome DevTools and a Chrome extension, [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB), were used to check responsiveness on various device sizes. Some issues were found at the 320px screen size where the logo and footer elements were breaking the screen width (as shown in the image below). I could see in DevTools that they had `width: 400px` set, and changing the media query for 800px or smaller screens to `width: 320px` would fix the issue. The code was fixed accordingly.
    <h2 align="center"><img src="docs/testing-responsive-320.png"></h2>
-   ### Colour Scheme
    -   The colour scheme was tested using this [Contrast Grid Test](https://contrast-grid.eightshapes.com)
        and, as explained previously in the Design - [Colour Scheme](#colour-scheme) section, my decision was based on the results shown here:
    <h2 align="center"><img src="docs/contrast-grid.png"></h2>

    -   The Website was tested on Firefox, Safari, Chrome and Edge browsers.
    -   The website was viewed on a variety of mobile devices such as iPhone7, iPhone 8 & iPhoneX.
    -   The organiser of Syncro Ireland Events was asked review the site to point out any user experience issues

- ### Bugs

    -   Original supplied videos wouldn't play when embeded due to there being copyrighted music on the sondtrack
    -   In the Signup Form (signup.html) user can't tab from the last text field to the checkbox field
    -   ~~footer slightly off-centre on screens below 320px~~ Fixed with media query edit

## - Deployment -

### GitHub Pages

The project was deployed to GitHub Pages [HERE](https://davewatters.github.io/syncro-ireland)


## - Credits -

### Code

- README.md - The structure was arrived at by examining the Code Institute sample templates and some previous CI users' projects. In particular, the Table of Contents idea came from Daisy McGirr's milestone project [HOTD](https://github.com/Daisy-McG/MilestoneProject-1)

### Content

-   All content created by the site creator [David Watters](https://github.com/davewatters/). Whilst some copy was taken, with permission, from the [Eire Syncro Facebook page](https://www.facebook.com/pages/category/Event/Eire-Syncro-261159948060757/) and the [UK Syncro Club](https://club8090.co.uk/) site, most text was edited and reworded after discussions with an organiser of the Syncro Ireland event, Paul Gillett.
-   All images were either supplied by the Syncro Ireland event organiser, Paul Gillett, or were taken, with kind permission, from the [UK Syncro Club](https://club8090.co.uk/) site.  Some editing, retouching and resizing was done by the site creator. 


### Acknowledgements

-   My mentor [Daisy McGirr](https://github.com/Daisy-McG) for all her helpful feedback.  And for introducing me to the illuminating Chrome extension [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB)!
-   The wonderful Code Institute community on Slack and the CI staff and students - both noobs and seasoned devs alike - for all of their help and support. 
-   And finally... Thanks to fellow student @Stephen_5P for suggesting [Birme](https://www.birme.net/) for bulk resiszing of images - what a time saver it turned out to be!

