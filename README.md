# Book Search Engine

## Program Logic / Assignment Acceptance Criteria

* GIVEN a book search engine
* WHEN I load the search engine
* THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
* WHEN I click on the Search for Books menu option
* THEN I am presented with an input field to search for books and a submit button
* WHEN I am not logged in and enter a search term in the input field and click the submit button
* THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
* WHEN I click on the Login/Signup menu option
* THEN a modal appears on the screen with a toggle between the option to log in or sign up
* WHEN the toggle is set to Signup
* THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
* WHEN the toggle is set to Login
* THEN I am presented with two inputs for an email address and a password and login button
* WHEN I enter a valid email address and create a password and click on the signup button
* THEN my user account is created and I am logged in to the site
* WHEN I enter my account’s email address and password and click on the login button
* THEN I the modal closes and I am logged in to the site
* WHEN I am logged in to the site
* THEN the menu options change to Search for Books, an option to see my saved books, and Logout
* WHEN I am logged in and enter a search term in the input field and click the submit button
* THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
* WHEN I click on the Save button on a book
* THEN that book’s information is saved to my account
* WHEN I click on the option to see my saved books
* THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
* WHEN I click on the Remove button on a book
* THEN that book is deleted from my saved books list
* WHEN I click on the Logout button
* THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button

## Back-End Specifications

Complete the following tasks in each of these back-end files:

* `auth.js`: Update the auth middleware function to work with the GraphQL API.
    * `server.js`: Implement the Apollo Server and apply it to the Express server as middleware.
    * `/Schemas` directory:
        * `index.js`: Export your typeDefs and resolvers.
        * `resolvers.js`: Define the query and mutation functionality to work with the Mongoose models.

## Code Sources

* The HTML pages, CSS, and frontent were provided by the UCLA coding bootcamp as "starter code"; see [here](https://github.com/coding-boot-camp/solid-broccoli) for their repo, and the [first commit](https://github.com/giancarlow333/book-search-engine/commit/e7ab613320ef9ca28fb42c31a1a347cc28e30af2) for details.
* Code from class activity 21.23 was reused in: [App.jsx](./client/src/App.jsx), [LoginForm.jsx](./client/src/components/LoginForm.jsx), [SignupForm.jsx](./client/src/components/SignupForm.jsx), [mutations.js](./client/src/utils/mutations.js), and [queries.js](./client/src/utils/mutations.js).
* Code from class activity 21.24 was reused in: [server.js](./server/server.js), [schemas/](./server/schemas/), and [auth.js](./server/utils/auth.js).
* A special thank you to [Fabian De La Peña Montero](http://fdlpm.com/) for help with logging in via GraphQL and resolving an issue with vite.config.js!

---

(c) 2023 Giancarlo Whitaker
