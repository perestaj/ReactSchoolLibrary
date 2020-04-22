# ReactSchoolLibrary

ReactSchoolLibrary is a sample school library application that I wrote while learning React / Redux. 

For Angular version of the application please go to: [AngularSchoolLibrary](https://github.com/perestaj/Angular_SchoolLibrary).

Installed packages:
- redux
- react-redux
- redux-thunk
- redux-form
- redux-immutable-state-invariant
- react-router-dom
- react-datepicker

In order to run and test the app you need to download and run the .NET Core project: [SchoolLibraryAPI](https://github.com/perestaj/SchoolLibraryAPI)
    
In order to run ReactSchoolLibrary type: 
```sh
$ npm install
$ npm start
```
 If you want to run the application in the docker container navigate to the react-school-library subdirectory (where docker-compose.yml file is located) and run the following command in the terminal: docker-compose up. The application will be accessible under http://127.0.0.1:3000
 
If you want to login you can use the following accounts:
##### Administrator

**username**: admin

**password**: admin

Description: can display and manage the list of books, loans, authors, publishers and users.


##### Librarian

**username**: barbara

**password**: library

Description: can display and manage the list of books, loans, authors and publishers

##### Student

**username**: bil

**password**: bil

Description: can display the list of books and request a book if they want to borrow it



The application consists of four tabs:

##### Home
Home page

##### Books
Displays the list of all books in the library with their statuses (Available, Borrowed, Lost, Requested).

##### Loans
Displays the books that have been requested, borrowed or lost. It enables the librarian to change the book status to "Borrowed" (when the requested book is being lent), "Available" (when a student returns the book) or "Lost" (when a student has lost the book).  

##### Administration
###### Authors
Displays the list of all authors of the books in the library

###### Publishers
Displays the list of all publishers of the books in the library

###### Users
Displays the list of all users
