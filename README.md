# Bookshelf-API-Submission
Bookshelf API Submission Criteria
There are 5 main criteria that you must fulfill in creating the Bookshelf API project.

Criterion 1: API can store books
The API you create must be able to store books via the route:

Method: POST
URL: /books
Body Request:

Criterion 2: API can display all books
The API you create must be able to display all stored books via the route:

Method: GET
URL: /books

The server must return a response with:

Status Code: 200
Response Body

Criterion 3: API can display book details
The API you create must be able to display details of a book via the route:

Method: GET
URL: /books/{bookId}

If the book with the provided id is not found, the server must return a response with:

Status Code: 404
Response Body

Criterion 4: API can update book data
The API you create must be able to update book data based on id via the route:

Method: PUT
URL: /books/{bookId}
Body Request

Criterion 5: API can delete books
The API you create must be able to delete books based on id via the following route:

Method: DELETE
URL: /books/{bookId}

If the provided id does not belong to any book, the server must return the following response:

Status Code: 404
Response Body

API Testing
When building the Bookshelf API, you need to test to ensure that the API functions according to the specified criteria. We have provided a Postman Collection and Environment files that you can use for testing. Please download the files from the following link:

Postman Bookshelf API Test Collection and Environment
