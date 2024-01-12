# Ethereal Expressions

This project is to develop a website for the artist Adamma Anwen Lloyd, with the goal of showcasing her work and attracting potential clients or buyers. We aim to include a gallery page with high-quality images of her work, an about the artist page and a contact form for enquiries or purchases. 

As far as the user is concerned, they should be able to view Adamma's work and contact her for any commissions or purchases. This should be covered within our intended site.

In terms of design, there should be a cohesive colour scheme and set of styles across the whole site to reiterate the artist's brand. Site layout should enhance rather than impede the user experience to give a welcoming, intuitive feel. Finally, the site layout should be responsive to enable easy navigation on all devices.

<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/142e1d42-da4d-4aba-a683-342923bc8e1e" style="width:70%;">

## UX Design

### Home Page Wireframe Design
<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/7a577631-48c3-41e1-b3ff-28ff473ac2f0" style="width:70%;">

### About Page Wireframe Design
<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/9f05638c-6ff9-413c-ac5d-20b5dd70235c" style="width:70%;">

### Gallery Page Wireframe Design
<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/126c0d7b-b504-4ca0-8e4d-d149d52c4b13" style="width:70%;">

### Contact Page Wireframe Design
<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/43c32720-3191-4bc7-b94b-56b3765a1351" style="width:70%;">

## User Stories

- As a user, I can use the menu, so that I can navigate the site.
  - The navigation bar feature contains clearly visible clickable links to the different site pages.
- As a user, I would to have easy access to the artist's social media links, so that I can quickly see the relevant pages and explore their art/online presence.
  - Social media links for the artist are visible in the footer on all pages across the website.
- As a user, I can click contact, so that I can contact the artist.
  - The contact page, accessible from any page via its navigation bar link, contains a contact form for users to get in touch. Also provided on this page are the artist's contact details: telephone number and location.
- As a user, I can view the home, so that I can see what the site is about.
  - The home page is the landing page of the site, and introduces the user to the artist using both text and images. This is accessible from other pages via its navigation bar link.
- As a user, I can click on about menu, so that I can understand more about the artist.
  - The about page gives a more complete introduction to the artist so that the user can be more familiar with them and the context of their work.
- As a user, I can click gallery, so that I can see examples of the work.
  - The gallery page displays eight collections, each of four images. The user can click on each image to view the artwork full-size.


## Features

- **Navigation Bar**

Navigation is provided via a bootstrap navbar. CSS code has been added to underline menu items on hover and tint the navbar for each page. Font Awesome icons have been added to each menu item to add visual clues.

<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/6278e0e9-371f-4190-8527-9988f7a4d5c4" style="width:70%;">

- **The Footer**

The page footer is arranged in 2 rows. The first row contains social media links for the site and the second row contains links to the site team's GitHub pages.
The footer layout was created using CSS flex.  

<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/3e936859-663d-4d57-9b4f-38e4c8627a01" style="width:70%;">


### Home Page

<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/aa86ebb5-e68b-4e42-8536-4e605799fa10" style="width:70%;">


### About Page

The About page is compounded by two pictures, followed by two pieces of text. Bootstrap grid has been used to fit them on the page and make them responsive. For smaller devices, the elements collapse one on top of each other, having the images at the top and the bottom, and the text, in the center.  For devices with higher resolution such as tablets, laptops and desk computers, the elements expand evenly in two rows, and each element takes  50 per cent of the space available.

<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/0e44e6d5-6efe-49ae-8c16-ed46b25fc010" style="width:70%;">


### Gallery Page

The gallery page contains eight four-piece collections from the artist, displayed in a grid using Bootstrap CSS. The user can click on any of the pieces to see it full-size, and an on-hover shadow effect highlights image as the mouse passes over them.

<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/5dea4234-8c38-4fd1-8e0c-2e863001c600" style="width:70%;">


### Contact Page

The contact page is comprised of two parts. First, there is a contact form for users to get in touch with the artist. This give options to submit either a general enquiry, a purchase enquiry or to contact about a commission. 

The second part of the page deals with contact details for the artist giving a portrait photo, contact details and an embedded map showing her location.

This page was structured using bootstrap.

<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/35aa091f-62d6-4557-a52a-05a543820609" style="width:70%;">


## Testing

### Lighthouse
The site was tested using Lighthouse with the following results:
<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/ed031055-ecac-4a09-93e0-d9710011e550" style="width:70%;">


### Responsive Testing

Alongside the built in Bootstrap responsive CSS, media queries were used throughout our own CSS to provide a consistent user experience. Chrome dev tools were used frequently to test the site at standard screen sizes and the site was manually viewed on laptops, tablets and phones.

<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/216eaf29-7853-4fe9-b3e1-4ed9ff705c84" style="width:70%;">


### Browser Compatibility
The site was tested on the following browsers:
- Chrome
- Firefox
- Edge
- Opera
<img src="https://github.com/mbriscoe/Ethereal-Expressions/assets/86828720/2104c398-4375-40d0-af15-25cba812c33e" style="width:70%;">


### Validator Testing

- HTML

  - No errors were returned when passing through the official [_W3C validator_](https://validator.w3.org/nu/?doc=https://mbriscoe.github.io/Ethereal-Expressions)

- CSS
  - No errors were found with our own CSS code when passing through the official Jigsaw validator. However, there were many errors found in the Bootstrap CSS code, which is a normal result.

## Bugs
All bug fixes were dealt with efficiently and cleanly.
- BUG: contact page width issue
- BUG: Footer overlapping content
- BUG: Shading display on gallery page

## Deployment

- The site was deployed to GitHub pages from the main branch of the repository early in the developemnt stage for continuous deployment and checking.

- The live link can be found [_here_](https://mbriscoe.github.io/Ethereal-Expressions/)

## Credits

### Content

- The quotation that appears on our home page belongs to Arshile Gorky. We have found it at https://www.azquotes.com/quote/709942?ref=abstract-art
- The icons in the header and footer were taken from [Font Awesome](https://fontawesome.com/)
- The quotes on the home page were create by our team member Martina!

### Media

- For this project, our team has made use of different platforms in order to obtain visual content. The first platform that has been chosen for the content of this website is IDDLE, a platform that belongs to ChatGPT. This platform allows the user to generate images with AI without the need of a copyright license, which was suitable for our project. 

- However, it is worth mentioning that before generating our images, key aspects such as: the colour palette selection, the painting technique and the topics by which the different art collections would inspired,  all of these fundamental points, were the result of a dynamic creative process. Besides, our team was also in charge of the design of our protagonist character, its identity and collections. 

- Apart from using IDDLE for most of the visual elements in the website, as well, our team decided to utilise specific suitable images for our carousel on our home page. Firstly,  we visited the website  Unsplash .com and selected images that could be expanded nicely. With our selected images prepared, our team manipulated their sizes with the help of Adobe Fireworks, an image manipulation program.

