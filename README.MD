Bertie's Books
A Node.js web application built using Express.js, EJS, and MySQL2.
The application allows users to browse books, add new books, register, search the catalogue, and interact with dynamically rendered pages backed by a MySQL database.
Technologies Used
Node.js – server runtime
Express.js – routing and HTTP handling
EJS – template engine for dynamic pages
MySQL2 – database connector
CSS – styling via the public/ folder
Main Routes
Route	Purpose
/	Home page displaying shop name
/about	About page for Bertie's Books
/list	Shows all books from the database
/addbook	Form to add a new book
/bookadded	Adds a new book to the database
/search	Search form for books
/search-result	Displays search results
/users/register	User registration form
/users/registered	Displays confirmation after registration
How to Install and Run Locally
1. Clone the repository
git clone https://github.com/YOUR_USERNAME/berties-books.git
cd berties-books
2. Install dependencies
npm install
3. Create a .env file
Inside the project folder, create a file named .env:
BB_USER=berties_books_app
BB_PASSWORD=BertiesApp@2024
BB_DATABASE=berties_books
4. Start the application
node index.js
5. Open in your browser
Go to:
http://localhost:8000
Running on the University Server (doc.gold.ac.uk)
1. Connect to the server
ssh YOUR_USERNAME@doc.gold.ac.uk
2. Navigate to your app directory
cd ~/public_html/berties-books
3. Start the app using Forever
forever start index.js
To view running apps
forever list
To stop a running app
forever stop <id>
Live Application URL
http://www.doc.gold.ac.uk/usr/YOUR_STUDENT_NUMBER/
Author
Student ID: YOUR_ID
Dynamic Web Applications – Goldsmiths, University of London