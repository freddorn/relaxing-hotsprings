# Testing Details

[Main README.md file](https://github.com/freddorn/relaxing-hotsprings/tree/master/README.md/)

View website on [Github Pages](https://freddorn.github.io/relaxing-hotsprings/)

## Testing Tools

* [AutoPrefixer](https://autoprefixer.github.io/)
    - To make sure the css code is valid for all browsers.

* [W3C CSS validation](https://jigsaw.w3.org/css-validator/)
    - To check the the validity of the CSS code. 
    
- [W3C Markup Validation]( https://validator.w3.org/)
    - To check the the validity of the HTML code. 

### Testing of each page

#### Home Page:

1. Navigation bar:
    1. On a desktop, go to the Home page.
    2. Using Chrome Developer Tools, check at different screen sizes and that the hamburger icon appears rather than the full menu bar when at a medium size or smaller screen.
    3. Made sure that there wasnt any overflow. Originally the hamburger icon appeared only on small and extra small screens. Changed it to include medium as menu items were stacking improperly.
    4. Test that logo home link is working, added missing title attribute.
    5. Checked each navigation menu item for proper operation.
    6. Verified that the Book Now link was working properly.
    7. Verified that navigation bar was responsive at each screen size.

2. Image Carousel
    1. Checked that all images are displayed properly.
    2. Verified that it is responsive at different screen sizes.
    3. Verified there was no overflow at the edges.

3. Main section
    1. Confirmed that all headlines and text are centered in their appropriate sections.
    2. Checked that images were the correct size and centered.
    3. Verified that it is responsive at different screen sizes.

4. Book Now button
    1. Verified that button was placed correctly and link is working, while opening a separate tab.

5. Footer
    1. Confirmed that all headlines and text are centered in their appropriate sections.
    2. Verified that the social media icons change color at hover.
    3. Check that the social media icons change size at hover and transition back.
    4. Verified that each social media link is working and opening a separate tab.

#### Contact Page

1. Navigation bar:
    1. It is the same on all pages, verified code was identical.

2. Hero image:
    1. Verified that it is the correct size.
    2. Checked that it is responsive.

3. Contact form: 
    1. Try to submit the empty form and verify that an error message about the required fields appears.
    2. Try to submit the form  without a name entered and verify that a relevant error message appears.
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears.
    4. Try to submit the form without a message and verify that a relevant error message appears.
    5. Try to submit the form with all inputs valid and verify that a success message appears.

4. Footer
    1. It is the same on all pages, verified code was identical.
 
#### Lodging Page
#### Dining Page
#### Hot Springs and Pool Page
