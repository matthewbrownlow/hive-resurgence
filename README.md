# Hive Resurgence

 > [Click here to view the live website on GitHub Pages]() Please note: To open any links in this document in a new browser tab, please press `Cmd ⌘ + Click` (Mac) or `CTRL + Click` (Windows/Linux)

## **Introduction**

Hive Resurgence is a site all about raising awareness around the bee crisis here in the UK, alongside some lighthearted fun facts. The site is targeted towards people with an interest in local and global crisis awareness mainly towards bees. Hive Resurgence will be useful as a reference for those seeking information around the current UK bee crisis.

![screenshot of am i responsive website displaying the hive resurgence home page on four different devices](assets/images/README.md/amiresponsive-displays.png)

## **Common Features**

### Navigation Bar

![screenshot of the hive resurgence navigation bar](assets/images/README.md/header-logo-nav.png)

- The navigation bar features a consistent design across all four pages keeping with convention with a logo on the left hand side and the navigation links to the right when the screen width is above 1200px wide to allow for easy of navigation.

- This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.

- The navigation bar sticks to the top of the web page regardless if you scroll down. This is achieved by using the `position: sticky;` declaration, accompanied by the `top: 0;` and `z-index: 1;` declarations to specify where to stick to, and to come on top over any `position: absolute;` items.

- The logo has a link to the home page `index.html` when clicked on to allow the user to navigate back to the home page no matter where they're at on the website.

- The navigation bar is fully responsive; for smaller screens (500px down), the format of the bar changes to a column orientation with the logo at the top centered on the page and the title links vertically aligned underneath. For tablets and screens in between (800px down), there is a staggered change through the use of media queries in order to maximise its size.

- All features of animation the navigation bar includes are highlighted `#daa520` text and an increase in text scale size (zoom) when you hovering over the navigation list items.

### Footer

![screenshot of the hive resurgence footer](assets/images/README.md/footer-social-networks-legal.png)

- The footer features an array of socila network icons from awesome font; each icon has the same highlighted `#daa520` text animation as the navigation links, when you hover over them. The social network icons, when clicked, take you to the corresponding social platforms in a new tab.

- The footer is valuable to the user as it encourages them to keep connected via social media. 

## **Home Features**

### Hero Image

![screenshot of the hive resurgence hero image](assets/images/README.md/home-hero-image.png)

- The home page includes a photograph of a bee hovering above a white blossom with a predominantly white and light background matching the clean white look of the website.

### Resurgence Definition Section

![screenshot of the hive resurgence resurgence definition break in between the hero image and about section](assets/images/README.md/home-resurgence-definition-break.png)

- I have used the definition of the word resurgence to give the user an understanding of the meaning and why its important to the brand.

### About Section

![screenshot of the hive resurgence home page about section](assets/images/README.md/home-about-section.png)

- The about section is here to help the user understand the target of the website and the aims we want to achieve. Its placed at the forefront of the website to provide the user with a brief summary of the overall informing projectives.

- The Issues button is located at the end of the text to give the user the option to jump straight into the Issues section of the website and is place here for ease and convenience. The button also highlighted `#daa520` when you hover over it. 

## **Issues Page Features**

### Issues Sections and Breaks

![screenshot of the hive resurgence issues page](assets/images/README.md/issues-sections-breaks.png)

- Text

## **Resolution Page Features**

### Resolution Sections and Breaks

![screenshot of the hive resurgence resolution page](assets/images/README.md/resolution-sections-breaks.png)

- Text

### Know Your Bees Section

![screenshot of the hive resurgence know your bee section on the resolution page](assets/images/README.md/resolution-know-your-bees-section-wwf-bee-id-chart-link.png)

- Text

### Charity Section

![screenshot of the hive resurgence charity section on the resolution paage](assets/images/README.md/resolution-charity-bee-sover-kit-donate-links.png)

- Text

## **Newsletter Sign-Up Page Features**

![screenshot of the hive resurgence lewsletter page](assets/images/README.md/newsletter-page.png)

- Text

### Newsletter Sign-Up Confirmation Page Features

![screenshot of the hive resurgence newsletter sign-up hidden confirmation page](assets/images/README.md/newsletter-page-confirmation.png)

- Text

## **Validator Testing**

### [W3C Markup Validator](https://validator.w3.org/#validate_by_input)

- Issue found:

    - Text

- Solution Used:

    - Text

### [W3C CSS Validatior](https://jigsaw.w3.org/css-validator/#validate_by_input)

- All pages tested, no issues found via file upload.

    ![CSS validator badge](https://jigsaw.w3.org/css-validator/images/vcss)


### Lighthouse

- Text

### Desktop Report

![screenshot of the lighthouse desktop report results](assets/images/README.md/lighthouse-desktop-report.png)

### Mobile Report

![screenshot of the lighthouse mobile report results](assets/images/README.md/lighthouse-mobile-report.png)

## **Deployment**

- The site was deployed to GitHub pages. the steps to deploy are as follows:
    - In the GitHub repository, navigate to the settings tab
    - Select the pages link from the setting menu on the left hand side
    - Under the GitHub Pages from the source section drop-down menu, select the main branch
    - Once the main branch has been selected, the page will be automatically refreshed with a detailed ribbon display the indicate the successful deployment

> [Click here to view the live website on GitHub Pages]() Please note: To open any links in this document in a new browser tab, please press `Cmd ⌘ + Click` (Mac) or `CTRL + Click` (Windows/Linux)

## **Bugs**

- **Bug #1**

    - **Issue:** I have a navbar with with `position: sticky;`. I have a div with `position: relative;` and a div nested inside that div with `position: absolute;`. When scrolling, the div with `position: relative;` puts itself above the navbar.

    - **Fix:** I added `z-index: 1;` to the header. I found the answer here: [Stack Overflow: Z-Index](https://stackoverflow.com/questions/66292396/is-it-possible-to-keep-relative-elements-below-a-sticky-navbar)

- **Bug #2**

## **Credits**

### Content

- The icons used for the logo, bookmark links, and other various buttons throughout the website were taken from [Font Awesome](https://fontawesome.com/)

- The font used throughout the website was imported from [Google Fonts](https://fonts.google.com/)
    - Oxygen - Light 300
    - Lato - Light 300

- Text

### Media

- For all the images used throughout the website, I collected the content from the following websites:
    - [PxHere](https://pxhere.com)
    - [Pexels](https://www.pexels.com)
    - [Unsplash](https://unsplash.com)
    - [Pixabay](https://pixabay.com)

- Text