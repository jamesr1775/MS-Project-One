# Donut Disturb

A Donut Store located in Dublin City Centre whose goal is to create and sell the best, most delicious desert in Dublin.
The website is deployed and can be viewed here [Donut Disturb](https://jamesr1775.github.io/MS-Project-One/).
## UX

### Project Goals
    * The goal of this project is to establish a brand by building a website for a Donut Store in Dublin City Centre.
    * The website will provide information about the stores products, location and contact details.
    * The website will provide the visitors with social media links to receive news/offers.
    * This Website will be:
        * Easy to navigate on a desktop, tablet and smartphone.
        * Contain pictures of all our Products, their prices and ingredients/allergens.
        * Provide the visitor contact and location information via phone, email, forms and maps.
### Business Goals
    * There are not many Donut Stores in Dublin  but they're becoming extremely popular so thats where the Donut Disturb Store comes in.
    * This website will provide an online presence to the Store.
    * This website will build brand awareness.
    * This website will showcase all the amazing, delicious products we sell and their prices.
    * Grow a brand and reputation and create a chain of stores throughout Dublin City Centre and large shopping malls.

### Customer Goals
    * Allow the customer to see our range of products, prices and ingredients.
    * Allow customers with allergys to see a products ingredients and in general preparation and cooking steps.
    * offer a range of products that can suit the majority of potential customers.

### User Stories
1. As a potential Customer that loves Donuts/ Pastries, I would like to see Current Donuts and prices, so that I can know what to expect when I visit the store.
2. As a new visitor, I would like to seemlessly navigate the website and browse your Donut products, contact page etc.,  so I may find what I am looking for efficiently.
3. As a potential Customer, I want to be able to find your social media, so I can know more about the company news and upcoming events or offers. 
4. As a potential Customer, I want to know the ingredients/allergens of your products, so I may know if they are certain allergy friendly products (e.g gluten, lactose, nuts etc). 
5. As a potential Customer, I want to be able to find the location of your stores, so I may visit in person.
6. As a potential Customer, I want to be able to contact the company, so I may request an item or ask questions like customizable products (e.g company logo or birthdays).
7. As a Job seeker, I want find information to contact/apply for a job at the company, so I may get hired.

### Wireframe mockups: 
- [Home](https://github.com/jamesr1775/MS-Project-One/blob/master/assets/wireframes/Home.png)
- [Our Donuts Gallery](https://github.com/jamesr1775/MS-Project-One/blob/master/assets/wireframes/Our_Donuts.png)
- [Contact Us](https://github.com/jamesr1775/MS-Project-One/blob/master/assets/wireframes/Contact_Us.png)

## Features
1. Every page should have a responsive **navigation bar** with the company name and logo in the top left.
2. Each page has a **footer** with **copyright information** and **social media icons** linking to the stores social media pages. ​
3. Every page features its own **hero image** at the top, detailing a the cafe and or products that we sell.
4. The images and how they are displayed will be **responsive** for different **screen resolutions**.
### Home
    1. A Hero image of the Shop will be under the navigation bar.
    2. There will be information on the companys passion and skills along with pictures to compliment our products.
    3. The Home page will contain recent customer reviews.
    4. There will be a disclaimer about the ingredients  we use and our kitchen standards particularly for allergies.
### Our Donuts Gallery
    1. The gallery page will contain rows and columns of images of all our products.
    2. The ingredients, allergies and pricing information will be displayed next to the  relevant product.
    3. The gallery will be responsive to different screen resolutions and clearly show product information such as allergies and pricing clearly particularly on smaller screens. 
### Contact Us    
    1. The contact page has a form to contact us that allows users to reach us via email. 
    2. This page will provide the store address alongside a map widget that shows our location.
    3. It will provide an business email address and phone number to use alternatively.
    4. The page will also provide an email address for career opportunities.  
    5. There will be a section with the store opening times for customers.

### Existing Features
- NavBar- The navbar is responsive and allows the user to navigate the website intuitively. The company logo is also present and can be used to bring the user back to the home page if clicked.
- The Footer presents the user with the company's social media accounts, and states copyright info also.
- The Home page [Home Page](https://github.com/jamesr1775/MS-Project-One/blob/master/index.html) and the [Our Donuts Page](https://github.com/jamesr1775/MS-Project-One/blob/master/ourDonuts.html) have a hero image / video that are both eye catching and draw the customers attention.
- All of the website pages are responsive and the elements fold appropiately for mobile, tablet and desktop screen sizes.
- The color scheme was selected using [Canva](https://www.canva.com/colors/color-palettes/pastel-dreams/). The theme was selected to fit the donut store.
- Our Donuts gallery and information is presented and is responsive along with relevant allergens.
- The [Contact Page](https://github.com/jamesr1775/MS-Project-One/blob/master/contact.html) provides the customer with the stores location, opening times, a contact form and other relevant contact information.

### Features Left to Implement
- A Basket and ability to order from the website.
- Create your own donut flavour from a list of options.
- A Subscription service / offer using a modal.

## Technologies Used

The Technologies used in this project are the following:

1. [Bootstrap 5.0:](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
2. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the wireframes.
2. [Hover.css:](https://ianlunn.github.io/Hover/)
    - Hover.css was used on the main nav bar and footer links for improving UX.
3. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Roboto' and the 'Exo' font into the style.css.
4. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used throughout to add icons a more pleasing UX.
5. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the navbar responsive.
6. [GitPod](https://gitpod.io/)
    - GitPod was used as my Editor/ Development Environment.
7. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
-

### Media
- The photos used in this site were obtained from ...
- [Pexels](https://www.pexels.com/photo/donuts-and-bagel-display-205961/)  -  Photo by Igor Ovsyannykov from Pexels.
- [Pexels](https://www.pexels.com/photo/woman-wearing-sweater-covering-her-eyes-with-doughnuts-2234709/)  - Photo by Mahima from Pexels.
- [Pexels](https://www.pexels.com/photo/close-up-photography-of-man-wearing-sunglasses-1212984/)  - Photo by Daniel Xavier from Pexels.
- [Pexels](https://www.pexels.com/photo/man-preparing-dough-for-bread-3218467/)  - Photo by Vaibhav Jadhav from Pexels.
- [Pexels](https://www.pexels.com/photo/food-party-sugar-colorful-5570880/)  - Photo by Jeswin Thomas from Pexels.
- [Pixabay](https://pixabay.com/photos/donuts-pastries-kringel-cake-candy-4633040/) - Photo by Alexas_Fotos from Pixabay.
- [Pexels](https://www.pexels.com/video/food-hands-sugar-colorful-4686906/)  - Video by cottonbro from Pexels.
- [Canva](https://www.canva.com/colors/color-palettes/pastel-dreams/)   - Color theme idea for the website.

### Acknowledgements
- Got some understanding of the bootstrap class for inline list items from - [stackoverflow](https://stackoverflow.com/questions/45650184/bootstrap-4-inline-list/45650251).
- Used bootstrap forms and mashed some examples together for my contact form - [getbootstrap](https://getbootstrap.com/docs/4.0/components/forms/).
- I received inspiration for this project from [The Rolling Donut](https://www.therollingdonut.ie/).
- Got the idea of using box shadows for some of the elements on the home page from [freefrontend](https://freefrontend.com/css-border-examples/).
- Good reminder about the grid model from [w3schools](https://www.w3schools.com/bootstrap/bootstrap_grid_large.asp).
- Needed to make some text more visible when images are behind the text. Used some shadows and got some information from [w3schools](https://www.w3schools.com/cssref/playit.asp?filename=playcss_text-shadow).
- Got info about hiding elements on screen sizes from [w3schools] (https://getbootstrap.com/docs/5.0/utilities/display/).
- Had some trouble with horizontal dividers adding white space above the divider line [stackoverflow](https://stackoverflow.com/questions/41411155/does-bootstrap-4-have-a-built-in-horizontal-divider). Got some info on bootstraps style for the **hr** element but figured out to set margin and padding to 0 via the chrome tools to get what I wanted.