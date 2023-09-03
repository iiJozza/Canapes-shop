# Ms Hors D'oeuvre

Ms hors d'oeuvre is a site that brings catering to an easily navigatable site where people can see 
what is on offer and to what price. This will also make ordering much easier and leads existing and new customers to their own "hub", instead of going to multiple sites. Having multiple steps in your ordering process opens the opportunity for the customer to reconsider and consequentially or order nothing. An example of this is going to instagram for the food/reviews and as an extra step place an email order, which makes the ordering process more time consuming. And time is not something people want to waste.

![Responsive Mockup](https://github.com/iiJozza/Canapes-shop/blob/main/assets/images-readme/readme-mockup.png)

## Features

An overview of all my existing features, what I want to improve and features I want to implement in the future.

### Existing Features

- __The Navigation Bar__

  - Identical on all pages and offers  easy navigation to the different portions of the site -- Home, Shop and Feedback.
  - The current page is displayed on the navigation bar in bold text and when hovered over the text turns red. This makes it much easier for the user to understand where in the website they are positioned.
  - Different navigation bars have been created depending on and to accomodate for various screensizes.

![Nav Bar](https://github.com/iiJozza/Canapes-shop/blob/main/assets/images-readme/nav-bar.png)

- __The Landing Page__

  - The landing page image for mobiles introduces the user to a playful wibe and enables them to experience food with artistic content.  
  - The image offered on larger screens is more inviting and gives a more direct feeling that this webpage is about food.
  - The text showcases the company's branding style and brings focus to the products, the company's vision and their luxury-orientated concept.


![Landing Page](https://github.com/iiJozza/Canapes-shop/blob/main/assets/images-readme/pictures-hero.png)

- __The Events Section__

  - The events section lets the uninformed user know the best occasion to buy canapes.
  - This will give the user a push when organising get-togethers or a larger events. This section is intended to give inspiration on ways to prepare and impress ones guests with a high quality option.

![Events](https://github.com/iiJozza/Canapes-shop/blob/main/assets/images-readme/readme-event-photo.png)

- __The Footer__

  - In the footer section, you will find links to Ms hors d'oeuvre's associated social media platforms. These links are designed to open in a new tab for convenient user navigation.
  - The footer links are useful tools to redirect engagment to the page via social media. 

![Footer](https://github.com/iiJozza/Canapes-shop/blob/main/assets/images-readme/readme-footer.PNG)

- __The Shop__

  - The shop gives the user a large selection of what is offered. 
  - The images of our inventory provides the user inspiration for their event and suggest what may best suit their purposes.
  - It also showcases the chef's craftmanship and artistry. 

![Shop](https://github.com/iiJozza/Canapes-shop/blob/main/assets/images-readme/readme-shop.PNG)

- __The Feedback Page__

  - This page allows the user the opportunity to express their opinions, rate their experience and read previous customer responses.
  - This gives the user piece of mind when buying products from a new provider.
  - The likelyhood of coming back to the page increases if the option to comment is available. This drives traffic (via reviews/comments) and also inspires new purchases and future engagment.

![Feedback](https://github.com/iiJozza/Canapes-shop/blob/main/assets/images-readme/readme-feedback.PNG)

- __The Thank You Page__

  - This page gives confirmation to the user that their comment has been accepted and received.
  - This allows the customer to feel that their opinions matter and are appreciated which opens up to an overall more positive experience.

## Testing

- I have tested the site by going through the different aspect ratioes provided in devtools.
- Changing the size of the browser manually.
- Browsers I have tested on is microsoft edge, chrome, mi browser, safari and mozilla firefox without it differing too much.
  - In the mi browser the background color and the text color changed. Though readabilty is unaffected.
- I have tested it by using different phones.
  - Iphone 11, Redmi 8, Laptop and a Large Wide Screen (Unfortunately I don't have the measurements).  
- Using different validators for all the html and css pages.

### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fiijozza.github.io%2FCanapes-shop%2F)

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://imgur.com/a/bOiXqRU)

- WAVE
  - Some minor issues but nothing major arose. The page is accomodated for individuals with sight impairments. [Wave validator](https://wave.webaim.org/report#/https://iijozza.github.io/Canapes-shop)

### Unfixed Bugs

- Found a bug where the feedback textarea would cover the comments if the width is longer than 768px but the height shorther than 555px.
  - I didn't fix this bug due to time constraints
- Found a bug in mi browser where some pink text changed to white and the background color changed from white to black.
  - I am not sure how I can change this as it is possibly due to the phones dark mode.

## Features Left to Implement

Unfortunately there is a lot that I would love to implement and redo, but due to time constraint can't. 

- Shop Improvements
  - One of the major implementations I would do is to change the whole shop page. It is currently more of a gallery but I tried to make an interactive shop before I understood it was not possible due to lack of time. The idea I had was that the food items would align underneath each other one by one (2 by 2 or 3 by 3 on larger sceeens)
  - Clicking the picture would open up a dropdown list revealing the ingrediences.
  - Add a title on top of each image and a small icon that provides information if it's gluten-free, vegan, vegeterian and/or lactos-free. 
  - The image should also go down in opacity after 70% of the image width, revealing the price/10. 
  - Scaling the images to be the same sizes in the shop.
  - Add more images to the site that is currently on the menu. 
  - Add a shopping cart icon that sticks to the bottom right of the page and lets you buy the things you have selected.

- Footer
  - Currently the footer is very bare. I want to implement a contact list with email, telefonnumber, name of the company and adress with a google maps embedded. 

- Index
  - I wanted the images in the event section to go zig-zag on larger screens, making the site more appealing.
  
- Hero image
  - I accidently downloaded the wrong size for my background image making it stretch way too much on screen-sizes larger than mobiles, since the height of said image is so much longer than the width.
  - Consistent hero image. Currently there are a two which is very confusing and can cause people to back out of the site due to not recognising the background.

- Feedback
  - Push the title down a bit. 
  - My feedback page is unfortunately not that resposive and the feedback section goes into the comments if you reduce the screen height below 555px. 
  - I want to implement a real comment section where comments show up in real-time with their names attached to them. The styling is also something I would change but have no ideas as of yet.
  - Comments should have the option to reply. 

- Deleting The Thank You Page
  - There is no reason to have a page like that if the feedback page controls that issue.

- New Pages
  - I want to add a real gallery. How it looks now is ok, but I want it to have a more apealing look to it.
  - I want to implement a new "about us page" as well where it describes its journey, present the workers and shows all its accolades.
  - A page where you pay for what you have selected in the shop.

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

## Credits

Here is all the materials I used for my project.

### Content

- The fonts used throughout the website is taken from [Google fonts](https://fonts.google.com/?preview.text=Ms%20Hors%20D%27ourve&preview.text_type=custom)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- Content inspired by the Love Running tutorial on code institute [Course literature](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LR101+2021_T1/courseware/4a07c57382724cfda5834497317f24d5/f2db5fd401004fccb43b01a6066a5333/) 

### Media

- The photos used on the home page is from (https://unsplash.com/)
  - Image for afterwork is by Marten Bjork and taken from here: (https://unsplash.com/photos/6dW3xyQvcYE)
  - Image of the wedding ring is by Beatriz Pérez Moya and taken from here: (https://unsplash.com/photos/M2T1j-6Fn8w)
  - Image of the student party is by Priscilla Du Preez and taken from here: (https://unsplash.com/photos/W3SEyZODn8U)
- The images used for the landing image is from (https://stocksnap.io/) and (https://www.mshorsdoeuvre.se/)
  - Image of the hero section for mobil is made by Salma Nasreldin and is available on (https://www.icanvas.com/)
  - Image of the hero image for webpages is by Mali Maeder and is available on (<https://stocksnap.io/photo/food-ingredient-FRG8VCQFP2>)
- The images used for the gallery is from Canape Queen and can be found on (<https://www.instagram.com/canapequeen.se/>)