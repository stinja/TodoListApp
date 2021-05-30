# TodoListApp



## Requirements


## Abstract

* Allow a user to make a list of their tasks to accomplish today
* User needs the ability to mark tasks as complete so they can remove them from the list when they’re done
* User needs the ability to edit tasks in case they make a typo
* User needs the ability to delete tasks in case they over-estimate their capacity to get stuff done and need to save face

## Concrete
* Same as the echo server, bind to a port and listen for HTTP requests
* Support must be provided for GET, POST, PUT and DELETE methods to read, create, update and delete tasks respectively. These must all be triggered by the same URL (barring parameters but.. Yeah you get what i mean);
  * GET /tasks - Get a list of tasks
  * GET /tasks/:id - Get a specific task
  * POST /tasks - Create a new task
  * PUT /tasks/:id - Update an existing task
  * DELETE /tasks/:id - Delete an existing task

Bonus points if tasks get saved to a database, but not required

## Resources
https://scotch.io/tutorials/build-a-restful-api-using-node-and-express-4  
https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods  
https://httpstatuses.com/  
https://express-validator.github.io/docs/  


### stinja's additional resource grabs
https://zellwk.com/blog/crud-express-mongodb/  
https://codeburst.io/writing-a-crud-app-with-node-js-and-mongodb-e0827cbbdafb  

### useful repos (maybe)
https://github.com/smallpaes/todo-list  
https://github.com/cedricVu/express-todo-boilerplate
