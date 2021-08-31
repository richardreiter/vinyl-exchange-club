# Vinyl Exchange Club

[Vinyl Exchange Club](https://richardreiter.github.io/vinyl-exchange-club/) is a website dedicated to LP aficionados, who are looking into engaging with other vinyl collectors. The website will be targeted at people who own vinyl records, so these like-minded people can meet, explore new music, genres, artists and bands - all in a sustainable way - swapping their record collection among each other during events/meetups.

![Responsive Vinyl Exchange Club](docs/screenshots/vec-responsiveness.png)

Visit the live project [here](https://richardreiter.github.io/vinyl-exchange-club/)

## Features

### Existing Features

- __Navigation Bar__

  - Navigation is a fully responsive feature on all three pages, it includes links on the site's Logo (displaying to the left within the bar), Home, Photos and Contact pages.
  - It looks the same in each page to allow for easy navigation (without the user having to use the ‘back’ button), taking the user through a logical journey.
  - This section makes it easy for the user to learn more about the site's different sections and contents.

![Navigation Bar](docs/screenshots/vec-navbar.png)

- __Hero image/cover text__

  - Landing page/hero image features a picture of a vinyl record and needle, including a cover text overlay to welcome the user and let them know in a sentence what the site is about.

  - It also features a backwards animation aiming to catch the user's attention.

![Hero Image](docs/screenshots/vec-hero.png)

- __Mission/Intentions Section__

  - The mission section is going to clarify to the user the perks/gains of joining the Vinyl Exchange Club community. 
  - This section should inspire the user to contemplate engaging with the site's community, as they could potentially make new friends, hear new music, save money and help the environment, all in a sustainable way.

![Mission](docs/screenshots/vec-mission.png)

- __Footer__

  - The footer area consists of five social links of the club (Instagram, Facebook, Spotify, Mixcloud and Soundcloud - all of them if clicked, open on a separate tab).
  - Like the navigation section, the footer looks the same in each page (and features in all of the pages) to allow for easy navigation, taking the user through a logical journey.

![Footer](docs/screenshots/vec-footer.png)

- __Photos Page__

  - The photos page features a series of high quality images which can aid the users to have an idea of how the club hang outs are.
  - Users may find this section in particular beneficial, as they will have a visual idea of what the club appears to be and how members engage.

![Photos Page](docs/screenshots/vec-gallery.png)

- __Contact Page__

  - The contact page is going to present the user with the opportunity to contact the club to join the Vinyl Exchange Club and hear more about future meetups/events.
  - The contact form features three fields, two mandatory ("Name" and "Email Address") and an optional one ("Mobile"), as well as a submit button.

![Contact Page](docs/screenshots/vec-contact.png)

- __Spotify iFrame__

  - The Spotify iFrame section precedes the footer section on the contact page.

  - This section features an inline frame where the user will have the opportunity to initiate the action of playing music (only if they click on the play button) from the club's Spotify playlist that is embedded.

![Spotify iFrame](docs/screenshots/vec-spotifyiframe.png)

### Features Left to Implement

- __Hamburger menu__

  - Implementing a hamburger menu/icon for mobile devices would be a positive future addition to perhaps keep in mind, in case the number of pages within the website grow (as in that case the current header navbar might become too busy without a hamburger icon).

- __Forum/Members Area__

  - Implementing a forum/members area in the future could be really beneficial for the Vinyl Exchange Club community, so the users would be able to post vinyl records that they are willing to exchange and also let other users know which records they'd be looking for.

## Testing

### Validator Testing

- HTML
  - No errors/warnings were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Frichardreiter.github.io%2Fvinyl-exchange-club%2F)

  ![Index Page W3C validation result](docs/validation/index-validation.png)
  ![Photos Page W3C validation result](docs/validation/photos-validation.png)
  ![Contact Page W3C validation result](docs/validation/contact-validation.png)

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Frichardreiter.github.io%2Fvinyl-exchange-club%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

  ![CSS Jigsaw validation result](docs/validation/css-validation.png)

### Google Lighthouse

- Google's Lighthouse was used for measuring the quality of the pages.
  - Index Page (desktop) result:
  ![Index Lighthouse PC result](docs/lighthouse/index-lighthouse-desktop.png)

  - Index Page (mobile) result:
  ![Index Lighthouse PC result](docs/lighthouse/index-lighthouse-mobile.png)

  - Photos Page (desktop) result:
  ![Index Lighthouse PC result](docs/lighthouse/photos-lighthouse-desktop.png)

  - Photos Page (mobile) result:
  ![Index Lighthouse PC result](docs/lighthouse/photos-lighthouse-mobile.png)

  - Contact Page (desktop) result:
  ![Index Lighthouse PC result](docs/lighthouse/contact-lighthouse-desktop.png)

  - Contact Page (mobile) result:
  ![Index Lighthouse PC result](docs/lighthouse/contact-lighthouse-mobile.png)

### Color Contrast Accessibility Checker

- [a11y Color Contrast Accessibility Validator](https://color.a11y.com/) was used to analyse the contrast of the pages and make sure it complies with website accessibilities regulations.
  - Index Page result:
  ![Index contrast result](docs/contrast/index-contrast.png)

  - Photos Page result:
  ![Index contrast result](docs/contrast/photos-contrast.png)

  - Contact Page result:
  ![Index contrast result](docs/contrast/contact-contrast.png)

### Responsive Testing

- __[Am I Responsive?](http://ami.responsivedesign.is/)__
  - This design tool was used to show how responsive the website is and looks across 4 different viewports (Desktop, Laptop, Tablet and Mobile):
![Responsive Vinyl Exchange Club](docs/screenshots/vec-responsiveness.png)

### Device Testing

- The Vinyl Exchange Club website was tested on several devices/environments (without any issues), including:
  - MacBook Air 13.3" M1 2020 (macOS Big Sur 11.5.2)
  - Lenovo 5i i5 15" (Windows 10 64x)
  - iPad 8th generation
  - iPhone 6
  - Xiaomi Mi A3 (Android 11)

### Browser Testing

- The Vinyl Exchange Club website was tested on several browsers (without any issues - across different devices), including:
  - Google Chrome (92.0.4515.159 (Official Build) (arm64))
  - Mozilla Firefox (91.0.2 (64-bit))
  - Safari (Version 14.1.2 (16611.3.10.1.6))
  - Microsoft Edge
  - Brave (Version 1.28.106 Chromium: 92.0.4515.159 (Official Build) (arm64))
  - Vivaldi (4.1.2369.21 (Stable channel) (arm64))

### Features Testing

- Navigation bar:
  - The navbar can be found at the top of all pages (common website convention) and is fully responsive on all viewports.
  - All links were tested on every single page by clicking on them (making sure no broken links are found).
  - The menu links are displayed under the logo on tablet/mobile devices.

- Gallery:
  - The photo gallery is fully responsive (the column count for laptop/desktop is three photos, tablets is two pictures and for mobile is one photo).

- Contact Form:
  - The contact form has validation for the email and mobile fields.
  - The submit button sends a post request to Code Institute's form dump (https://formdump.codeinstitute.net/).

- Spotify iFrame:
  - The Spotify iFrame doesn't auto-play music and is fully responsive on all viewports.

- Footer:
  - The footer can be found at the bottom of all pages (common website convention) and is fully responsive on all viewports.
  - All links were tested making sure they are corret and open on a new tab.


### Unfixed Bugs

## Deployment

## Credits 

### Content 

### Media