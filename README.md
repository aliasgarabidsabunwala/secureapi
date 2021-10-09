# Backend API in Golang (Go)

Here, I'm building a HTTP JSON API capable of the following operations,

Create an User
Should be a POST request
Use JSON request body
URL should be ‘/users'

Get a user using id
Should be a GET request
Id should be in the url parameter
URL should be ‘/users/<id here>’

Create a Post
Should be a POST request
Use JSON request body
URL should be ‘/posts'

Get a post using id
Should be a GET request
Id should be in the url parameter
URL should be ‘/posts/<id here>’

List all posts of a user
Should be a GET request
URL should be ‘/posts/users/<Id here>'

and here Passwords are securely stored such they can't be reverse engineered
and the server is thread safe
And has pagination to the list endpoint
And has unit tests

also it makes subsequent calls to a MongoDB database.
