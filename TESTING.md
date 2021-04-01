# Classic Cakes Website - Testing Information

[Main README.md file](/README.md)

[View website in GitHub Pages](https://github.com/LizzieeLovett/classic-cakes)

## Testing

### Validation

- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
- [W3C Markup Validation Service]( https://validator.w3.org/)
- The developer used **W3C CSS Validation Service** and **W3C  Markup Validation Service** to check the validity of the website code.

### Client stories testing:

The typical path through this website would be: 
- Home > Gallery > Contact 
- As the lessons page would not be the most common reason for visiting the site, there is a call to action button on the Home page encouraging users to visit the Lessons page where there is information about the service being offered and a form to fill in.
- Once on the lessons page, there is another call to action to the Contact page to redirect users back onto the typical pathway for making contact with Classic Cakes in the event that the user was simply curious about the lessons and understanding them was not the main purpose of their visit.

### Testing client stories from UX section of README.md

1. As a new visitor to the website, I want to easily navigate around the site so that I can find what I’m looking for as quickly as possible.
    1. The navigation bar has the same design, and can be easily found at the top of each page of the website.
    2. The logo has the same design and can also be easily found, as well as linking to the Home page to reorient any users who want to return to the typical starting point.
    3. The page names used are fairly typical across most websites so users should be able to immediately infer the content each page should contain.
    
2. As a new visitor to the website, I want to view a gallery of prior work so that I can decide if I like the style for myself.
    1. The Home page uses images of prior work to describe the type of product available.
    2. The navigation bar contains clear reference to a Gallery page where users can review images of prior work.
    
3. As a new visitor to the website, I want to see testimonials from other customers so that I can see whether they liked the cakes they purchased and the related service received.
    1. The Home page utilises testimonials from past clients and associates them with the type of product they’re reviewing making them easy to understand.

4. As a new visitor to the website, I want to know what the baking lessons entail and what I can expect to pay so that I can decide if I want to book lessons.
    1. On the Lessons page there are details about the format of the lessons.
    2. Also on the Lessons page there is a pricing table covering all available options.

5. As an interested client, I want to understand how to fill out the lessons form so that I can book in with the owner.
    1. The form on the Lessons page is broken down into common items (First Name, Last Name, Email, etc.) which a typical user should have no problem with, and the less common items (Group Size, Location) are drop down items to make the experience much easier for the user.

6. As an interested client, I want to understand how to fill out the contact form with as much detail as I want to give about my order so that I can get the product I have in mind.
    1. The form on the Contact page allows the user to specify the type of cake they’re interested in as well as providing an “Other Information” section for them to provide as much detail as they like.
    
7. As a returning visitor to the website, I want to easily navigate to the contact page to put details of a new request in so that I can get what I need as quickly as possible.
    1. The navigation bar at the top of the page provides quick and easy access to the Contact page.


### Manual (logical) testing of all elements and functionality on every page.

#### Home Page:

1. Navigation bar:
    1. Go to the Home page from a desktop.
    2. Change the screen size from desktop to tablet to verify that the navigation bar is responsive to the screen width.
    3. Change screen size to mobile and verify that the burger icon appears. 
    4. Click the burger icon to verify that the menu drops down.
    5. Click on the logo text in the navigation bar to verify that it links to the Home page. 
    6. Click on each navigation menu item to verify that it links to the correct page. 
    7. Hover over each navigation menu item to verify that the hover colour change works as expected. 

2. Compelling copy headings section:
    1. Reduce and expand the width of the window to verify that the boxes and text within them in this section respond correctly and look good on all device widths. 
    2. Hover over the "Sign Up!" call to action text in the lessons box to verify the hover colour change works as expected.
    3. Click on the “Sign Up!” call to action text to verify that it links to the correct page. 

3. Hero image:
    1. Go to the Home page from a desktop.
    2. Verify the image is visible on a desktop and fills two thirds of the width of the page. _During testing the hero image wasn’t wide enough to cover the designated area so the margins were adjusted to fix._
    3. Reduce the width of the window to verify that the image fills two thirds of the screen whilst remaining fairly central and then does not appear for mobile screen sizes.
    4. Reduce and expand the width of the window to verify that the overlay on top of the image responds correctly and does not colour any other part of the page.

4. Cake Types and Testimonials:
    1. Reduce and expand the width of the window to verify that the 3 images and testimonials display across the width of the screen on large screens, the testimonials disappear from medium screens down and the images display down the screen on mobile devices.
    2. Hover over each cake type image to verify the size change works as expected.
    
7. Footer: 
    1. Hover over the phone and social media icons to verify colour and size transitions occur as expected. 
    2. Click on the social media icons to verify they open a separate tab for the link.
    3. Reduce and expand the width of the window to verify that the footer is responsive and looks good on all device widths. 

7. Review all functionality and responsiveness on mobile phone and tablet.

#### Gallery Page:

1. Navigation bar: 
    1. Repeat verification completed for the navigation bar on the Home page.
    2. Verify that the navigation bar code is identical on all the html pages.
    
2. Gallery:
    1. View each gallery image to verify they all load correctly.
    2. Check the html code to verify that each gallery image has a descriptive alt attribute. _Titles were deliberately *not* added here as this would have made the page messy. The addition of the alt attribute means the page is still navigable for visually impaired users._
    3. Reduce and expand the width of the window to verify that each row of gallery images behave and centre as expected, and that the grid of images looks good on all device widths.
    
3. Footer:
    1. Repeat verification completed for the footer on the Home page.
    2. Verify that the footer code is identical on all the html pages.
     
4. Review all functionality and responsiveness on mobile phone and tablet.


#### Lessons Page:

1. Navigation bar: 
    1. Navigation bar code is identical on all html pages. Verification already completed.

2. Compelling copy headings section:
    1. Repeat verification steps done for the compelling copy headings on the Home page.
    2. Hover over the "Make it for me!" call to action text in the lessons box to verify the hover colour change works as expected.
    3. Click on the “Make it for me!” call to action text to verify that it links to the correct page. 

3. Hero video:
    1. Repeat verification steps done for the hero image on the Home page. _During testing the hero video was not appearing in the Chrome browser despite appearing fine in the Gitpod IDE. My mentor Miguel helped me fix this as he figured out that although my path to the video was not entirely correct, Gitpod was able to compensate and display the video anyway. I corrected the path and now the video shows in all browsers._
    2. Verify that the video autoplays on mute and continues to loop.

3. Pricing table: 
    1. Reduce and expand the width of the window to verify that the table responds as expected.
    
4. Lessons form: 
    1. Try to submit the empty form to verify that an error message about the required fields appears. _During testing there was no error message, this was fixed by adding required attributes and changing the button type to submit. However, the success modal still appears. Need Javascript to improve the feedback to the user._
    2. Try to submit the form with an invalid email address to verify that a relevant error message appears.
    3. Try to submit the form with all inputs valid and verify that a success message appears.
    4. Reduce and expand the width of the window to verify that the page behaves as expected.
    
5. Footer:
     1. Footer code is identical on all html pages. Verification already completed.
    
6. Review all functionality and responsiveness on mobile phone and tablet.

#### Contact Page:

1. Navigation bar: 
    1. Navigation bar code is identical on all html pages. Verification already completed.

2. Compelling copy headings section:
    1. Repeat verification steps done for the compelling copy headings on the Home page.

3. Hero image:
    1. Repeat verification steps done for the hero image on the Home page.

4. Contact form: 
    1. Repeat verification steps done for the lessons form headings on the Lessons page.
  
5. Footer:
     1. Footer code is identical on all html pages. Verification already completed.
    
6. Review all functionality and responsiveness on mobile phone and tablet.

## Further testing: 

1. Asked friends and family to look at the site on their devices and feedback any issues they find. 
2. I viewed my website on several devices and found no further issues.

