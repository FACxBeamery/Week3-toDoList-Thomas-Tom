# Week3-toDoList-Thomas-Tom
### Authors: Thomas Kostrzewski & Tom Galligan
This is the backend of a To-Do web-app. We use node.js to construct an http server, which holds a to-do list. 

The server accepts a variety of requests for managing the to-do list. A full collection of these, with examples, can be found in the Postman collection at the bottom of this README. You will need Postman (https://www.getpostman.com/) to run them. 

Current features include:
- Adding a new item
- Changing an item's status
- Deleting an item
- Sorting items by date created
- Sorting items by date edited

### Known issues:
- Currently the to-do list is an array of objects, with each item being referenced by its index in the array. While this is a clean formulation on the back-end, it will pose problems during front-end integration as the item ids are not fixed. This issue will be fixed in version 1.1

![A screenshot of a post request in postman](https://ibb.co/WxvrJc3 "Example POST request in postman")

## Postman collection: 
https://www.getpostman.com/collections/c427528af19a4ebc122f
