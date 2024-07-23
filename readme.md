## Link to website:
(https://rbtttttt.github.io/Noah-bar/)
(https://github.com/rbtttttt/Noah-bar)

# Noah's Bar - Markdown

## Overview:
 This website is a showcase of cocktails for Noah's cocktail Bar and Restaurant the target audience are consumers who are looking to dine at the bar and to give a more detailed description and story of the product before the consumer arrives at the bar. In This website, the user can find information on the cocktails, recipes, bar name, bar location, creator of cocktail.

 A carousel system has been added into the main page with each signature cocktail displayed each slide. Each slide will have the name of the cocktail and a short description and the background of the page will be changed to an image of the cocktail.

 The website will be multiple pages in one, allowing the user to scroll from the top to the bottom creating an experience like reading a menu from a cocktail bar.

 ### Main Page:
 Carousel system will be used, each slide will represent a specific cocktail from a seasonal collection. (carousel.js , carousel.css)

 ### Logo:
 - Logo will be fixed in the top-middle of the page. (.logo .logo-p1)
   
### Navigation:
 - For both mobile and widescreen there will be NAV for Home and About Us section (.nav , header)
 - Home will take you to main page
 - About us will take you to the end page, the about us page.
 - See more buttons available on each slide of Carousel which will take user to specific cocktail page.

### Styling:
 The color palette used for the webpage:
 - #f1683a
 - #eee
 - #black
 The #f1683a orange color will be mainly used for headers and buzz words.
 The white #eee will be for text
 Background will be primarily black, excluding image backgrounds.
 Font will be consistantly Poppins, except for logo.
 General text size between 1.0 - 1.3em
 Header text size betwen 2.8 - 3em


## (1) Home page - Carousel System 
  A carousel system will be used featuring a different cocktail on each slide, on each slide the background will change into a picture of the cocktail as well as a short description. (.carousel)
  
## Layout:
 ### Background:
 - Background will change during each slide, the image will be of the specific cocktail assigned to that slide.
 - a orange line/ timer will be on top of the page as a timer to indicate when the next slide will change (.time)

### Content (.content):
  - Seasonal collection will be first displayed (spring, summer, winter, autumn) (.title)
  - Name of cocktail will be displayed (.topic)
  - A description of the cocktail will be displayed on each slide under the name (.des)

### Arrows:
- There will be arrows for navigation between each carousel slide (.arrows)

### Thumbnail:
- There will be small thumbnails of the drinks at the bottom of the carousel (.thumbnail)

## (2) Cocktail Pages
A standard cocktail page will be used containing two different containers (.image-container , .text-container)

## Layout:

### Background:
- Black background will be used

### Images:
- image of each cocktail will be shown on thte right hand side of page (.image-container)

### Description:
- Description will be on the left side, this will include the season, cocktail name, and flavor profiles. (.text-container)

### Thumbnails:
- There will be thumbnails on each page, this acts as a smaller image of the cocktail image, for a friendlier mobile experience.


## (3) About Page
About page will be the last page, this contains information about the bar, owner as well as other features like a contact form, a video to showcase the bar as well as a Google Maps location.

## Layout:

### Video:
- First will be a video show casing the bartenders abilities, this will come with a controller as well as an external link to the video (.video-container)

### Content:
- On the right of the video will be the content, this is where the user can find more information about the restaurant / owner

### Contact form:
- A contact form has been created in order for the customers to contact for enquiries (.contact)

### Location:
- A google maps location will be placed in the about section to help customers locate the the bar. (.google-map-container)

## (4) Keyframes / Animations used
- showContent - This is the effect used for carousel for the content / description to appear.
- showImage - This is the fade in effect for the images in the carousel
- showThumbnail - This is the thumbnail change for everytime there is a new slide.
- effectNext - This is the effect for when a user clicks next on the carousel
- contentOut - This is the effect for previous in the Carousel
- runningTime - This is orange line/bar that runs on top of page to indicate when the next slide will appear.
- fadeIn - This is the fade in animation for cocktail pages
- outFrame - The fade out effect when previous button is clicked.


## (5) JavaScript Used

### DOM Selection:
- nextDom - Next button
- prevDom - Previous button
- carouselDom - Carousel
- SliderDom - Slider
- thumbnailBorderDom - thumbnail container
- thumbnailItemsDom - thumbnail img
- timeDom - Timer on top of page.

### Functions:
- Functions have been created (.onclick) for next and previous slide
- A timer has been created for the carousel
- A timer has been created for orange timer above Nav.
- Function with affect to prepend and append carousel slide

## Final Overview:
### Overview:
At the start of this project I wanted to create something much more simple, however I wanted to challenge myself to create something impressive to challenge myself for future projects, I explored more interactive ways to create a website and recreated a carousel effect for my website, I chose this effect because the images I had to work with looks quite nice in this carousel setup with a black background creating nice vibrant feel. I wanted to have a website that is multiple pages but in one, as I want the audience to view it from top to bottom like a menu for a restaurant. 
### Improvements for the future:
- more interactivity with Javascript
- possibly usage of a module / library for better coding experieence
- be more organize with CSS, maybe use more classes to group code
- more navigation for the website


## Sources & Resources used:
### Images for cocktails: https://www.facebook.com/Mr.MonkeyX (permission given)
### Video: https://www.youtube.com/embed/P2EOVODrSzs
### Carousel tutorial: https://www.youtube.com/watch?v=A5CK6Uqe_YU&list=PLwJhhWUZudKq1F7SAvi1uWhzHLeNy21NG



  
