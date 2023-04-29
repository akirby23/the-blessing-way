# The Blessing Way

## Description
This website is aimed at showcasing & promoting the music of the Irish solo-project The Blessing Way. 
Targetted towards heavy metal music fans as well as new & existing fans of the project, the website provides a brief overview on the history of The Blessing Way, an introduction to their discography, information on the upcoming tour and where their music can be streamed.
Users will find this useful to keep up to date with the latest album releases & tour dates. 

![The Blessing Way website on different screen sizes](documentation/am-i-responsive.PNG)

## User Experience
### Features
- Implemented features

  - Header
    - The header contains The Blessing Way’s logo, which decorates each page nicely in line with the theme of the website while also allowing the user to easily navigate back to the home page by clicking on it. 
    - It also contains a responsive navigation bar which features on all 4 pages, allowing the user to easily navigate between pages without the need to use the “back” button to go back to the previous page. 
    - On larger screens, each of the navigation links contains a corresponding icon which contributes to the intuitive design while also making the header more aesthetically pleasing. 

    ![Desktop header](documentation/features/features-header-desktop.PNG) ![Mobile header](documentation/features/features-header-mobile.PNG)

  - Biography section
    - The biography section contains an eye-catching text box that will give the user a brief introduction to The Blessing Way, complimented by a black, white & grey background image of a live concert to match the theme of heavy metal music. 

    ![Desktop biography section](documentation/features/features-biography-desktop.jpg)![Mobile biography section](documentation/features/features-biography-mobile.PNG)
  
  - New album section 
    - The New Album section promotes the release of The Blessing Way’s newest album, Erik’s Lament. 
    - This section informs the user that the album is now available to stream on Bandcamp, Spotify and YouTube. 
    - The accompanying image features the album cover of Erik’s Lament on a mobile device to entice the user to stream the album. 
![Desktop new album section](documentation/features/features-new-album-desktop.PNG) ![Mobile new album section](documentation/features/features-new-album-mobile.PNG)

  - Tour Section
    - This section advertises the upcoming Ireland Tour and contains a list of tour locations, the date & time of the events and the address of the venues. 
    - The locations of each of the events are pinpointed on a corresponding map iframe to allow the user to easily plan their trip and/or navigate to the venue. 

![Desktop tour section](documentation/features/features-tour-desktop.PNG) ![Mobile tour section](documentation/features/features-tour-mobile.PNG)

  - Discography page 
    - The Discography pages provides the user with an overview of all of the albums that have been released by The Blessing Way to date. 
    - The album covers are displayed on the page accompanied by the title of the album, the release date and a description of the album. 
    - The iframes sourced from Bandcamp allow the user to listen to the album directly on the website, or navigate to the Bandcamp website to buy or share the album by clicking on the links within the media player. 
    - For a better user experience, the iframes will not autoplay. 
    - In the interest of maintaining responsiveness on smaller screens, the iframes are not visible on screens 450px wide and below. 

![Desktop discography section](documentation/features/features-discography-desktop.PNG) ![Mobile discography section](documentation/features/features-discography-mobile.PNG)

  - Sign up page
    - The sign up page contains a form that will allow the user to sign up for The Blessing Way’s Newsletter. 
    - The user is just required to fill in their First Name, Last Name & Email Address, making it quick & easy for them to get signed up. 
    - Placeholder text has been placed within the input fields for a more intuitive design. 
    - The input type for the email input box has been set to “email” to prevent the user from inputting invalid data. 

![Desktop form page](documentation/features/features-form-desktop.PNG) ![Mobile form page](documentation/features/features-form-mobile.PNG)

  - Thank you page
    - Upon submission of the form on the sign up page, the user is taken to the Thank You page which thanks the user for signing up to the newsletter, informs them that they have been successful in signing up & that they will be redirected back to the home page.
    - This page is set up to auto-refresh after 10 seconds and redirect the user back to the home page, which prevents the need for the user to press the “back” button to exit it.

    ![Desktop thank you page](documentation/features/features-thank-you-desktop.PNG) ![Mobile thank you page](documentation/features/features-thank-you-mobile.PNG)

  - Footer
    - The footer contains Facebook, Bandcamp, Spotify & YouTube icons which are linked to The Blessing Way’s corresponding pages. Clicking on the icon will open the respective link in a new tab for better user experience.
    - Below the social media links is a disclaimer which lets the user know that the website has been created for educational purposes only.
   - The footer is fixed to the bottom of the page which allows the user to access the social media links any time.  

   ![Desktop footer](documentation/features/features-footer-desktop.PNG) ![Mobile footer](documentation/features/features-footer-mobile.PNG)


### Features left to implement
 - Add the option for users to purchase tickets for the upcoming tour events.

### Design
- Color

![The Blessing Way Colour Palette](documentation/colour-palette/the-blessing-way-colour-palette.png)
- The color palette was generated from the album cover of The Blessing Way’s newest album, Erik’s Lament. 

- As the home page draws the user’s attention to the exciting release of the new album, it felt fitting for the website’s color scheme to match the album cover. 

- Typography

  - Noto Serif Devanagari was used for the main header elements throughout the website, with serif as a fallback, to match the classical feel of the latest album, Erik's Lament. 
  - To compliment the headings, Open Sans with sans-serif as a fallback was used for the rest of the text elements on the website. 
  - The fonts above were imported from Google Fonts. 

## Technologies used

### Languages
- HTML was used to build the content of the website.
- CSS was used to style the content of the website. 

### Frameworks, Libraries & Programs Used
- [CodeAnywhere](https://app.codeanywhere.com/): to write the code. 
- [Git](https://git-scm.com/): to commit & push the code to Github. 
- [GitHub](https://github.com/): to store the code in its repository. 
- [GitHub Pages](https://pages.github.com/): to deploy the website.
- [Chrome DevTools](https://developer.chrome.com/docs/devtools/): for testing responsiveness on various screen sizes & for troubleshooting issues. 
- [Google Fonts](https://fonts.google.com/): to import Noto Serif Devanagari & Open Sans fonts which were used on all HTML pages. 
- [Font Awesome](https://fontawesome.com/): to import iconds to add to the navigation bar & to the tour section for aesthetic & UX purposes. 
- [ImageColorPicker](https://imagecolorpicker.com/): to generate the colour palette for the website. 
- [PosterMyWall](https://www.postermywall.com/index.php/posterbuilder/copy/f5550b1adaac0ea5e27966d9ef9b3af5#.ZEU7i3bMKUk): to generate the image for the New Album section. 
- [Coolors.co](https://coolors.co/241e20-8c6a4f-ffffff-3c5648-76a38f): to generate the colour paletter for the README. 
- [Favicon](https://favicon.io/): to generate the favicon images & to obtain links to add the favicon to all pages. 
- [AmIResponsive](https://ui.dev/amiresponsive): to test the website's responsiveness on screens of different sizes. 

## Testing

### Validator Testing

- No errors were found when the website was run through the [W3C Validator](https://validator.w3.org/)

![Validated HTML from W3C](documentation/html-validated.PNG)

- No errors were found when the website was run through the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)

![Validated CSS from W3C](documentation/css-validated.PNG)

### Lighthouse


## Deployment
The site was deployed to GitHub pages. The steps to deploy are as follows:
 - In the GitHub repository, navigate to the Settings tab.
 - On the left hand side of the page, navigate to Pages. 
 - From the source section drop-down menu, select the Main Branch.
 - Once the main branch has been selected & saved, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

## Credits 

### Code 
- [w3schools.com](https://www.w3schools.com/) & [stackoverflow.com](https://stackoverflow.com/) were consulted regularly for support with both HTML & CSS. 
- [css-tricks.com](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) was consulted for support with implementing Flexbox for responsive styling. 
- HTML to enable smooth scrolling behaviour was obtained from [gomakethings.com](https://gomakethings.com/smooth-scrolling-links-with-only-css/)
- Inspiration for the layout of the Biography section was taken from the Love Running website. 

### Content 
- The Biograpy section as well as the album descriptions in the Discography section were written with the help of Ollie Gill. 
- The rest of the content was written by [Aoife](https://github.com/akirby23). 

### Media 
- The background image from the Biography section was obtained from [RawPixel.com](https://www.rawpixel.com/image/2333597/premium-photo-image-concert-microphone-rock-band)
- The Blessing Way logo image, album cover images & Favicon image were sourced from [The Blessing Way's Bandcamp page](https://theblessingway.bandcamp.com/community). 
- The maps from the Tour section were sourced from [Google Maps](https://www.google.com/maps). 
- The media players from the Discography page were sourced from [The Blessing Way's Bandcamp page](https://theblessingway.bandcamp.com/music). 