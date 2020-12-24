         ___        ______     ____ _                 _  ___  
        / \ \      / / ___|   / ___| | ___  _   _  __| |/ _ \ 
       / _ \ \ /\ / /\___ \  | |   | |/ _ \| | | |/ _` | (_) |
      / ___ \ V  V /  ___) | | |___| | (_) | |_| | (_| |\__, |
     /_/   \_\_/\_/  |____/   \____|_|\___/ \__,_|\__,_|  /_/ 
 ----------------------------------------------------------------- 


# E-commerce store
Hello, My name is Saleka and through this project I am excited to present to you
another in a series of web applications on my journey through code institutes Full-Stack web development program. Welcome to fullstack frameworks with django.
This project is an application which allows the user to create a profile, and was intended so the user to be able to  purchase a product from the site using stripe payments. 
This application provides a realistic e-commerce patform that allows for the owner of the site to earn money, 
while the user is able to find the most exciting products at the click of a button.
I created this project in order to produce a functional e-commerce platform that utilizes django and stripe payments to process oders.
Welcome to my portfolio Full-Stack Frameworks with Django!

Hi my name is saleka

 
## UX
 
This website is designed for the to be user focused allowing the user to really take advantage of the website, by adding to basket, removing items, and seeing their

checkout total in real time. Thus allowing for full crud functionality.


 A list of user Stories:

<a href= "files/Conceptual design soundable.pdf">Conceptual design pdf</a>
- As a user type, I want to perform an action, so that I can achieve a goal.
- As a user I want to listen to buy books
- One book many has many users to buy digital downloads
- A user can create a profile
- A user can buy many books
- Each profile has a user which stores their downloaded purchased books
- A user can purchase many books, but each book can only be purchesed by one user


## Features

This section describes the different parts of my e-commerce digital download platform:
The all products page allows you to view a single book or many books and all the information related to that title.
The books page is simply the combination of all the books from a broad variety of categories across the website, you can view our enitre library from this page. Also it allows for 
filtering on a high level depending on how many fields of filtering are selected. Can use the search bar to filter your search results.
The base page is the base template for the websites look and feel which was inspired by <a href= "https://www.chapters.indigo.ca/">Indigo</a>.
Then we have the books section which consists of a books page and call to action banner to recieve a special prmotion offer.
The profile page contains the user registration information where they fill their personal information.
The categories page is further brocken down into several different genres that the user can further explore  including mystery, self-help, thriller, fiction, non-fiction and of course romance.
Lastly the special offers page includes ongoing promotion that the user can browse by section specicfically tailered to their interest, including but not limitied to new arrivals all the way to special offers.
Finally we have the login and logout functionalities which give acces to other options, only once the user is logged in.

### Existing Features
- Feature 1 - allows users to preview books from various authors for sale
- Feature 2 allows users to browse and search, for a particular book throughout various genres
- Feature 3 allows users to update their profile and information 
- Feature 4 allows users to view the price and rating of the current book title they are previewing
- Feature 5 allows users to have an acccount in order to track their purchases 
- Feature 8 A place where users can upload books with easy navigatgion

### Features Left to Implement
- Feature to pay with stripe (TBA)
- Upgraded user interface which impliments  gsap technology animations 
- Add a section where users can preview a book and download a snippet (similar to amazon.com functionality)

- Form validation to return error message when registration form is not completed properly
- View downloads and uploads in user profile page (keep counts and names)
- send automatic followup marketing email content to all subscibers, providing deals of the week through a blog page intergration for additinal user engagement

## Technologies Used

- [JQuery](https://jquery.com) library
- HTML, used to dictate the structure of my web application
- python used as the primary backend language inside django framework
- CSS, used to style my pages 
- Heroku, used to deploy the project to the live server for viewing by the public
- The project uses **JQuery** to simplify DOM manipulation.
- Django framework, used as backend framework
- Bootstrap v4.0.0  used for website cross campatibility across devices
- Fontawsome used for fonts
- SQLite3, used to access my database from the console
- JavaScript, used for front end password verification
- Stripe used for payment services 
- MySQL  is a relational database management system 



## Testing

The testing process for this project was ongoing throughout, I made use of unit testing in a variety of scenerios,.
Ensuring that books were being shown most popular home page section.


1. All Product page:
    1. Go to the "Products" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears
2. Login/Logout
    1.Confirm that login works and login validation message is displayed on the home page
    2.Try access profile without logining in
    3.Try to fill out registration form with incomplete fields and verify it does not create a user account
    4.Try to logout and login using and different password but same username and verify that display message is; your password is incorrect!
3.Registration
    1. Try to see if I can register without filling the form and verify its not possible by submiting
    2. Try to register again if I already have an account
4.Books
    1.Try to submit a incomplete song form verify it doesn't submit
    2.Try to unsubmit my song by going back on the page link (browser navigation)
5.Edit profile
    1.Try Django templating form, verify it is updating registration information on click of submit
    2.Try user profile and make sure song information and user information are the same 
    3.Verify user profile is being saved inside the Django admin panel
6.Search
    1.Try the filtered search feature by genre,mood,soundslike,type,gender,tempo.

I have also tested my project on various screen sizes from a laptop to a desktop.Ensuring that bootstraps intelligent sizing features have adjusted the page size.
Everything is able to collapse neatly when on a phone screen to yield a functional user interface wich cleanly represent the e-commerce brand.

Here is a list of bugs encountered and their solutions during the development process:

1. error-


2. error-

3. error-


4. error-


5. password errors-



6. How to filter-

7. order objects by date-


## Deployment
Process to deploy:
- This project has been deployed to heroku
- Different values for environment variables/Heroku Configuration varibales were set
- Created requiremnent.txt and procfile in order to host on Heroku  platform
- Deployed to Heroku server for final project viewing 

## Credits
I would like to credit numerous cites for inspiration in ux design as I could 
not have done this without inspiration and at times a little persperation. Cite 
used for application inspiration <a href="https://www.canva.com/">here.</a> 
I would also like to credit the stackoverflow community for any methods and 
code snippets used, it was a really awesome resource to roll up my sleeves and 
learn on the website.
### Content
- The text for all the paragraphs was inspired by:
- https://www.chapters.indigo.ca/en-ca/

### Media
- boutique ado
- indigo books list
- canva


### Acknowledgements

I would like to acknowledge w3schools.com for when I got stuck. Also the use of 
several bootstrap components used to build the framework of my project.
I also searched stackoverflow.com countless
times for more information to solve problems with my application when I was puzzled and challenged
on the harder portions. I am thankful that my project is finally closer to what I 
envisioned. Thank you for viewing this presentation of my 
Full-Stack Frameworks with Django project. 
                                                <a href="#top">Back to top</a>
### This is for educational use.
