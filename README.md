# MiniProject1
This is the repository for my mini project one

QUESTION 1:
What was the requirements gathering and design process? 
- The website was for my mum so I asked her what colour scheme she wanted: She wanted there to be pink
- I also checked in with her multiple times to make sure the font etc looked how she wanted it
- I did some sketches on my ipad
- I wrote the requirements that I wanted 
- I used figma to create a LoFi design to get a better idea of how the website will look and what pages will be there
- I did some research on how to use the Google Maps API and whether I have access to it
QUESTION 2:
Give a high level view of the application and its features:
- The website is a portfolio website for my mum who is an artist. It has 3 pages currently, the home page which has 3 pictures on animations to capture audience attention. The portfolio
page that has each piece of artwork with a brief description. Each piece of art will have a read more button which causes a modal pop up with more infomration and images of that
artwork. The contact page which has a form which the user can fill out and submit, when submitted a modal will pop up saying the form has been submitted, the input fields will
then reset.
The form information is currently sent to the console, the contact page also has a google maps API
showing the location of mums studio.
There is a navbar which can be used to move from page to page
Each page will have the same banner with Sarah Barrett Artist
QUESTION 3:
Where does the data come from?
- The data for the portfolio items is stored in an internal array
- The data for the map on the contact page comes from the Google Maps API
QUESTION 4:
How is the data processed and displayed?
- The portfolio data is processed using the JavaScript addCards function to populate the HTML <template> element
      - The addCard function is called for each item in the array
- The portfolio cards are then displayed in the HTML card template
- The google maps API is processed using the JS function initMap
      - The maps data is displayed HTML div with the id "map"
QUESTION 5:
How can the user interact with the application?
- The user can navigate the pages using the navbar
- The user can click on each of the portfolio cards to show more
- Users can search and filter portfolio items 
- The user can add inputs to the input fields of the contact message
- The user can hover over the sudio location of the map to show the studio location tooltip
QUESTION 6:
What JS techniques have you used?
- An array of objects for the portfolio items
- DOM functions to select specific HTML elements
- cloneNode to clone the HTML template for the portfolio cards
- Loops to loop over the data in the portfolio array to populate the cards
- Conditional statement to add icons to the card
- Event listeners to:
    -   Get more information modal to pop up when button pressed
    -   Get successfully submitted message to pop up when form submitted
    -   Search and filter the portfolio cards 
- functions to:
    -  addCards
    -  filter and search portfolio cards
    -   Display the google maps API
    -   Send the data from the submit form to the console
    -   Show the message submitted modal
QUESTION 7:
What external tools/libraries have you used?
- Bootstrap - to make the website look nice and easily make it responsive - CDN
    - Used the CSS and JS links 
- Google fonts - to link the fonts I wanted to use - CDN link
- Google Maps - to use the maps API to create the map I wanted - API
- Font awesome - to add icons to the portfolio cards - CDN
QUESTION 8:
What kinds of HTML elements have you used?
- link tags for all my CDN links and style sheets
- script tag for the bootstrap JS CDN
- divs for most of my elements
- h1 for headings
- nav for the bootstrap navbar
- i for the icons
- button for the buttons
- ul and li for the list of the navbar items 
- input for the input field of my search bar and the contact form
- select for the drop down select bar for the category filter
- option to display each of the options in the select drop down
- template for the portfolio card template
- p for text
- h2 for smaller headings
- img for images
- span for the additional images in the read more modal so they can sit next to each other
- form for the contact form on the contact page
QUESTION 9:
What kinds of CSS features have you used?
- Animations of the home screen images
- Backgrounds for the portfolio cards and the banner
- font family and sizes to show the fonts i want
- Bootstrap CSS
QUESTION 10:
How might you extend the features of your application in the future:
- I want to add a shop page so that people can buy some of the artwork
- I want to add an instagram API to the home page, but mum doesn't have an instagram yet so I wasn't able to complete this
- Make the submit form go to a server 
