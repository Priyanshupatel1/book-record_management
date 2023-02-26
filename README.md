# book-record_management
This is an application called book record management/API

## Endpoints

## /users
POST: create a new user 
GET : Get all list of users

## /users/{id} 
GET: get a user by thier id
POST : Update a user by their ID
DELETE : delete a user by their ID( check if a user still has an issued book && is there any fine to be collected from the user)

## /users/subcription-details/{id}
GET : get user subscription details
1. Date of subscription
2. valid till ??
3. fine if any ?

## /books
GET : Get a book 
POST : update a book 

## /books/{id}
GET : Get a book by id
POST : update a book by id

## /books/issued
GET : Get all issued books here

## /books/issued/withfine
GET : Get all issued books with fine

## subcriptions types 
Basic (3 months)
Standard (6 months)
Premium (12 months)

if user has an issued book and the issued book is to be rejected at 09-12-22
if user missed the date to return ,  and then users subscription also get expired , then user need to pay a fine of 
150/- (100 + 50)


<!-- MVC Arch
>>Model/Modal view controller
>>Mode & controler are wrt to backend
>>view wrt to forntend
>>Controller : Brain or logic of your route

-->
<!--  model : it speaks abt the structure of MongoDb Collection -->