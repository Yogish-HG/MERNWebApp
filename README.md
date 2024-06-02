# CSCI 5709 Grp-13

Group project for 5709 Advanced Web services of Master's course.

# Book Stack - v3

This version of our application have 85% of features completed. 

## Authors

1. Member 1

   - Name:- [Yogish Honnadevipura Gopalakrishna](yg926299@dal.ca)

2. Member 2

   - Name:- [Ashish Nagpal](ashish.nagpal@dal.ca)

3. Member 3

   - Name:- [Jinal Dave](jinal.dave@dal.ca)

4. Member 4

   - [Abhinav Acharya Tirumala Vinjamuri](ab806657@dal.ca)

5. Member 5

   - Name:- [Arihant Dugar](arihant.dugar@dal.ca)

6. Member 6
   
   - Name:- [Aiwin Charalil Manuel](aiwin.manuel@dal.ca)


## Links

1. Frontend Deployment Link - Netlify: https://bookstack-csci-group-13.netlify.app/
2. Backend Deployment Link - Render: https://bookstack-grp13.onrender.com

## Login Details for testing

### Admin login credentials
- Username: abhinava465@gmail.com
- Password: securepassword

### Reader login credentials
- Username: ab806657@dal.ca
- Password: pass@1234

# Deployment

This directory contains a stable deployement version of the application. The ```front-end``` is deployed on Netlify which we configured by adding a remote that pushes the code to GitHub. The ```backend``` is deployed on Render using the same process. We have employed ```MongoDB``` for the database.

Deployment for Frontend is made through **Netlify**. 
[![Netlify Status](https://api.netlify.com/api/v1/badges/c9aa70e1-579d-4e9f-9e3a-f00b2c17b318/deploy-status)](https://app.netlify.com/sites/bookstack-csci-group-13/deploys)

Deployment for backend server is done on **Render**. ![](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)

# Project Overview

The project, Book Stack: Bridging the gap between libraries and loyal readers in this digital age, is a web application designed to revolutionize the way we interact with books and libraries. The project is primarily aimed at digitalizing libraries, transforming the way librarians and readers interact with the library’s resources. 
This project aims to bring libraries into the digital age, making books more accessible and promoting a culture of reading and sharing within a vibrant community. It’s not just about borrowing books; it’s about fostering a love for reading and creating a space where book lovers can share their experiences.

## 1. Details

### Landing Page

This is where the users reach `/` land on when they access our site for the first time. This helps users familiarize with the website and makes it intuitive for them to navigate around the website; with that in mind, we developed the landing page with utmost care as it is the first page that the users see. As the saying goes, **First impression should be the best impression**, it is really crucial that we showcase everything in a visually attractive manner as this is the page where we want to introduce ourselves, and the application. The only way to do that is to make it visually appealing by using a cozy color scheme, well adjusted components, and a clean layout.

### Contact Us

This is where the users can reach out to us if they have any questions, feedback, or issues regarding our application. Contact us pages are essential for building trust and credibility with the users, as well as providing them with the best customer service possible. We want to make it easy and convenient for the users to contact us, so we offer multiple channels and options for them to choose from. We also want to show our personality and values, so we use friendly and engaging language that reflects our brand identity. The contact us page is the last impression that we leave on the users, so we want to make it a positive and memorable one.

### FAQ

This is where the users can find answers to the most common questions that they may have about our application. FAQ pages are useful for providing quick and clear information, reducing the need for customer support, and improving the user experience. We want to make our FAQ page as helpful and comprehensive as possible. We also want to make our FAQ page easy to navigate, so we organize the questions into categories and use an accordian for a question-and-answer format. The FAQ page is an opportunity for us to address any concerns or objections that the users may have, as well as to highlight the benefits and features of our application.

## 2. Late Fee System

Late Fee System is essentially supposed to penalize users who borrowed books from the library, but failed to return them before the due date. We have defined 2 tasks in this feature which will be talked about in the section below: Late fees can deny users from borrowing/ reserving books until they are cleared. The tasks for this feature involve functionalities for both readers and administrators. Readers are required to view the costs associated with each book that has not been returned, and raise a dispute if they find a charge unnacceptable. On the other hand, administrators have the responsibility to identify users who have incurred late fees. Once it has been confirmed that the readers have cleared these fees, the administrators should be able to clear them from the system, or notify them if they haven't cleared the fee yet. These tasks ensure a smooth operation of the book rental service and maintain a fair system for all users.

## 3. Notifications

Notifications are essential for reminding users or admins about various purposes. Admins can use the service to remind users regarding their uncleared late fees, update in availability of a book, etc., whereas the users can use the service to notify the admin if they have a dispute in their late fee, send an invoice/ confirmation of a successful book reservation. 

## 4. User Registration and Authentication

### Registration
- Users can register for a new account by providing their first name, last name, email, phone number, password, and confirm password.
- Form validation checks if the entered information meets the required criteria (e.g., valid email format, password complexity).
- Upon successful registration, users are redirected to the login page.
- Users will assume a role of 'user' by default.

### Login
- Users can log in to their account using their email and password.
- Form validation ensures that the entered email is in a valid format and that the password meets specific criteria (minimum length, alphanumeric characters, etc.).
- Upon successful login, users are redirected to their profile page.

### Profile
- Users can view and edit their profile information, including their first name, last name, email, and phone number.
- The profile page includes an option to upload a new profile picture.
- Users can delete their account, which requires confirmation.

### Password Reset
- Users who forget their password can request a password reset link by entering their registered email address.
- Form validation checks if the entered email is in a valid format.
- Upon successful submission, users receive a reset email with instructions on how to reset their password.

## 5. Book Library
``Book Library feature`` includes following tasks :-View All, Search Books, Filter Books, Sort by Name, Price.  

1. The user can view all the books available in the library and explore books.

2. Using filters, the user can narrow down the results.

3. User can also search the book by entering a keyword related to it.

4. Lastly, uer can sort the books based on names.

## 6. Book Management:

This Feature involves the management of all books within the Book Stack application. It includes functionalities such as viewing, editing, and deleting books from the system. Admin can search book from the list of books as well.

### Add Book:

- Admin can add new books using this functionality. They need to input essential details such as book title, author, genre, description, etc., to successfully add a book.

### Delete Book:

- With this feature, admin can delete books. Deleting a book removes it permanently from the system.

### Update Book:

- This task enables admin to update the details of existing books. Admin can modify information such as the book title, author, genre, description, etc., as needed.

### Update Reservation on Book Return:

- When a user returns a reserved book, this functionality helps admin update the reservation status of the book accordingly. It ensures that the book becomes available for reservation by other users.

### Apply Late Fees for Book:

- This task involves the application of late fees for books that are returned past their due date. Users are notified of the late fee and required to settle the amount before further borrowing privileges are granted.

## 7. Book Detail: 
This feature shows the detailed view of the book that is clicked by the reader from the listing screen under 'Books' option of nav bar. A user can see the full book details by clicking on the option under "About" section. This page also shows a section of recommendations that will list similar books. The reader can navigate back and forth from the book detail screen to the book recommendation screen. For easy usability, the pagination option is included. Below are the tasks included within this feature: 

### View Book detail 
To show all related details of the book; such as book name, description, author, etc. When the user is logged in and they have a late-fees associated, they won't be able to see the reserve button below the book image.

### Similar recommendations 

This section is enclosed within the bottom part of the page where the similar book to the current one is shown.

### View Rating & review

A reader can get better insights about the book content by checking the associated ratings and reviews for the currently viewing book using this option lablled as "View Rating and Review". The relevant sorting options are included for checking the most recent and the most relevant reviews.  

## 8. Book Feedback: 
This is another feature linked within the  book details page where users can share their reading experience with the rest of the community by adding reviews or rating to it. Following are the tasks included within this: 

- Reviews: A reader can submit their comment regarding the currently opened book using the input option available under "Do you want to rate and review this book?".
- Rating: A reader can also rate a book using the same section and submit the details.

## 9. Add to Cart
The "Add to Cart" feature facilitates the process of purchasing books. Initially, the system checks whether the user has logged in. If not, the user is redirected to the login page. Once logged in, the user can navigate from the dashboard to the book details page. Here, they can review the desired book and, if they choose to purchase it, they can click on the "add to cart" button. Upon clicking this button, the system adds the book to the shopping cart and confirms the action with a prompt stating "Book added to Cart successfully." This feature provides a user-friendly approach to selecting and securing books for purchase.

## 10. Reserve Book 
The Reserve Book feature in Bookstack empowers users to reserve books with ease by placing holds and checking availability. Users can effortlessly reserve a book by placing it on hold and inquire about its availability through intuitive interactions. The process flow begins as users navigate to the Bookstack application and access the Reserve Book feature. From there, they can seamlessly place holds on desired books and check their availability status, ensuring a streamlined experience for managing their reading materials

## 11. Favorites
The favourite feature allows user to add their favourite book to a single list . The user visit the page of his favourite book. On that page there will be a button on shape of a heart , which the user can click to add the button to favourites. After adding a book to favourites the colour of the button changes to red to indicate that the book has been added to favourite successfully.

## Built With

1. [React](https://legacy.reactjs.org/docs/getting-started.html/) - The web framework used
2. [npm](https://docs.npmjs.com//) - Dependency Management
3. [Tailwind CSS](https://tailwindcss.com/) - Styling Framework
4. [NodeJS](https://nodejs.org/en) - Javascript runtime environment for building fast and scalable web applications
5. [ExpressJS](https://expressjs.com/) - Node framework for building REST apis
6. [React Bootstrap](https://react-bootstrap.netlify.app/) - Styling Framework
7. [ExpressJS](https://expressjs.com/) 


# Sources Used

## Frontend 

### Learning Materials

To have understanding of HTML and CSS concepts and refresh the knowledge on the topics we checked following videos :-
1. [Advanced HTML/CSS Concepts Crash Course](https://www.youtube.com/watch?v=XhqEuyWjbdo) - *codedamn*

2. [Flexbox CSS In 20 Minutes](https://www.youtube.com/watch?v=JJSoEo8JSnc) - *Traversy Media*

Using the above materials, we learnt about HTML5 semantics, CSS selectors, pseudo selectors and flex boxes.
