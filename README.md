# Application overview

We will build Rest Apis for creating, retrieving, updating, deleting and searching Tutorials.

First, we start with an Express web server. Next, we add configuration for MySQL database, create Tutorial model, write the controller. Then we define routes for handling all CRUD operations:

The following table shows overview of the Rest APIs that will be exported:

# Methods 	Urls 	Actions
GET 	api/tutorials 	get all Tutorials
GET 	api/tutorials/:id 	get Tutorial by id
POST 	api/tutorials 	add new Tutorial
PUT 	api/tutorials/:id 	update Tutorial by id
DELETE 	api/tutorials/:id 	remove Tutorial by id
DELETE 	api/tutorials 	remove all Tutorials
GET 	api/tutorials/published 	find all published Tutorials
GET 	api/tutorials?title=[kw] 	find all Tutorials which title contains 'kw'

Finally, we’re gonna test the Rest Apis using Postman.