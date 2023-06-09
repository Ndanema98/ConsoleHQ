# Milestone project 5
# Console HQ

[]() is an ecommerce website designed for people to buy a wide variety of consoles and games.

This website was targeted at people who want to easily purchase any game or console online. Users would be able to select from a wide range of merchandise from the catalogue avaliable on the products page. A search bar and navigation bar will be avaliable enabling users to filter through and locate a specific product. There will also be a shopping bag section, which would allow users to manage the products that they want to buy. A secure payment option would also be, allowing users to safely input their payment details. This will establish trust between the business and its customers. When customers feel confident that their payment information is protected, they are more likely to make purchases and share their sensitive data.

This website was built using knowledge gained from HTML, CSS, JavaScript, Python and Django modules, for the purpose of completing my fifth Milestone Project for the Code Institute's full stack developer course. This website is easy to navigate and easy to read, with a clear goal and aim.

 # User Experience/User Interface (UX/UI)

 - ## User Stories
   ### Developer Goals
   As the developer I want: 
   - to be able to add a console or game to the list. So that I can add new consoles or games to the store.
   - to be able to edit and update a console or game. So that I can change product prices, descriptions, images and other product criteria.
   - to be able to delete a console or game from the list. So that I can remove consoles or games that are no longer for sale.

   
   ### Shopper Goals
   As a shopper I want:
   - to view a list of consoles and games. So that I can select some to purchase.
   - to view individual console and game product details. So that I can identify price, description and product rating.
   - to be able to easily view the total of my purchases. So that I can avoid spending to much.
   - to be able to sort the list of available consoles and games. So that I can easily identify the best rated and priced console.
   - to be able to sort out a specific category of console. So that I can sort the consoles in a specific category by name.
   - to be able to search for a console or game by name or description. So that I can find a specific console or game to purchase.
   - to be able to easily see what I have searched for and a number of results. So that I can quickly decide whether the console I want is available.
   -  to be able to easily select the quantity of consoles or games when purchasing them. So that I can ensure I do not accidently select the wrong quantity.
   - to be able to view the consoles or games selected to be purchased in a bag. So that I can identify the total cost of the purchase and all items to be received.
   - to be able to adjust the quantity of each individual console or game in my bag. So that I can easily make changes to my purchase.
   - to be able to quickly identify deals and special offers. So that I can take advantage on special savings.
   - to be able to sort through multiple categories of consoles simultaneously. So that I can find the best priced and rated products across the categories.
   - to be able to easily enter payment information. So that I can check out with no hassle.
   - to be able to feel like my personal and payment information is safe and secure. So that I can confidently provide the needed information to make a purchase.
   - to be able view an order confirmation after checkout. So that I can verify that I have not made any mistakes. 
   - to be able to receive an email confirmation after checking out. So that I can keep the confirmation of what I have purchased for my records.

   ### Frequent site users Goals
   As a frequent site user  I want:
   - to be able to easily register for an account. So that I can have a personal account and be able to view the profile.
   - to be able to easily log in or log out. So that I can access my personal account information.
   - to be able to easily recover my password in case it is forgotten. So that I can recover access to my account.
   - to be able to receive an email confirmation after registering. So that I can verify that my account registration was successful.
   - to be able to have a personalised user profile. So that I can view my personal order history, order confirmations and payment information.
   - to be able to sort between the categories of consoles and games. So that I can easily locate a game or a console depending on my needs.
   
 - ## Design 
   ### Data Model
   - The main entities in my data models include Order, OrderLineItem, Category, Product, Review, Deals, NewsletterSubscription, Coupon, and UserProfile.
    
   - The Order model represents an order placed by a user and includes details such as order number, user profile, contact information, shipping address, date, and order totals. Each order can have multiple line items, which are captured by the OrderLineItem model. It stores information about the ordered product, quantity, and line item total.

   - The Category model defines different categories for products and has fields for category name and a friendly name. The Product model represents individual products available in my e-commerce system. It includes fields such as product name, description, price, rating, image, and discounted price. Each product can belong to multiple categories through a many-to-many relationship.

   - The Review model allows users to post reviews for products. It includes fields for the associated product, review author, content, date, and an approval status. The Deals model captures special deals or discounts associated with specific categories. It stores the category and the discount percentage.

   - The NewsletterSubscription model represents users who have subscribed to a newsletter. It includes a reference to the associated user, a subscription status, and whether a coupon has been used. The Coupon model stores discount codes assigned to users. It contains the user reference, discount code, discount amount, and a flag indicating if the coupon has been used.

   - Lastly, the UserProfile model maintains user-specific information such as default delivery details. It is linked to the built-in User model through a one-to-one relationship and includes fields for phone number, street addresses, town/city, county, postcode, and country.

   ### Wireframes
   - 

   ### Colour Scheme
   - 

  ## SEO 
   ### Keywords

 # Features
 
 


 # Possible Future Features
   -  
   - 
   -  
    
 # Testing 
 - ## Automated 
  - I have created some python files which automatically test my models.py, my forms.py, my views.py, my contexts.py and my utils.py in my different applications. 

 - ## Manual 
   - This website has been tested using three different browsers (Google Chrome, Firefox, Safari) and I can confirm that it works. 
   - This website has been tested with all the standard screen sizes and I can confirm that it is responsive. 

    ### Navigation Bar
    All Pages:
    TEST            | OUTCOME                          | PASS / FAIL  
    --------------- | -------------------------------- | ---------------


    ### Home Page
    TEST            | OUTCOME                          | PASS / FAIL  
    --------------- | -------------------------------- | ---------------


    ### Add Anime page
    TEST            | OUTCOME                          | PASS / FAIL  
    --------------- | -------------------------------- | ---------------


    ### Add Review page
    TEST            | OUTCOME                          | PASS / FAIL  
    --------------- | -------------------------------- | ---------------


    ### Edit Anime page
    TEST            | OUTCOME                          | PASS / FAIL  
    --------------- | -------------------------------- | ---------------

    ### Delete Anime page
    TEST            | OUTCOME                          | PASS / FAIL  
    --------------- | -------------------------------- | ---------------


    ### Register page
    TEST            | OUTCOME                          | PASS / FAIL  
    --------------- | -------------------------------- | ---------------


    ### Sign in Page
    TEST            | OUTCOME                          | PASS / FAIL  
    --------------- | -------------------------------- | ---------------


 - ## Validator 
   - ### HTML
     - The official ["W3C validator"](https://validator.w3.org/) was used to validate my HTML. 
     
   - ### CSS 
     - The official ["W3C validator (Jigsaw)"](https://jigsaw.w3.org/css-validator/) was used to validate my CSS. No errors were found when my code was input.
     
   - ### Javascript
     - The Javascript file was validated using ["JSHint"](https://jshint.com/) and no errors were found. The New JavaScript features (ES6) option was ticked in the Configure menu.
   
   - ### Python
     - The Python Code was validated using a ["Pep8 python checker"](https://pep8ci.herokuapp.com/#) from code institute and no errors were returned. 
      
  - ## Accessibility 
    ![]()

    - The Lighthouse function in devtools was used to see if the font and the font colours used were easy to read and access. I can confirm that the page on my website passed. 
      
 # Languages used 
   - HTML
   - CSS
   - Javascript
   - Python

 # Technologies Used 
   - Git 
     - Allowed me to add commit and push my code to github for version control. 
   - Gitpod 
     - The programme used to code my website.
   - Github 
     - Allowed me to store my repository and files pushed from Gitpod.
   - Fontawesome 
     - Used to display icons to make my website more visually appealing. 
   - Chrome developer tools 
     - Allowed me to troubleshoot and edit my code.
   - Am I Responsive 
     - Allowed me to check the responsiveness of my website at different screen sizes. 
   - W3C Validator 
     - Allowed me to validate my HTML and CSS code against industry standard. 
   - JSHint 
     - Allowed me to validate my Javascript code against industry standard.

 # Deployment
  - This code was deployed using Code Institute's mock terminal for Heroku. 

  - ## Steps for deployment:
   1. In the top right corner of the page click on the fork button. 
   2. The next page will show a forked version of my project.
   3. Create a new Heroku app.
   4. Set the buildbacks to Python and NodeJS in that order.
   5. Link the Heroku app to the repository. 
   6. Click on deploy. 

 # Credits
 - ## Images
   - All of the images used were found on ["Wikipedia"](https://en.wikipedia.org/wiki/Main_Page)

 - ## Information 
   - All of the information used were found on ["Wikipedia"](https://en.wikipedia.org/wiki/Main_Page)

 - ## Code
   
   - 
    
 # Acknowledgement 
    - The online tutors that Code Institute provides. 
    - My mentor Ben Kav for helping me when I was stuck. 
    - Everybody on slack, for their advice. 