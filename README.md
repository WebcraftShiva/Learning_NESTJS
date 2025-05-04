# Whenever we request something from server it look like this:

- Request-----> 
validate data contained in the request
Make sure the user is authenticated 
Route the request to a particular function
Run some business logic
Access a database
Response  <------

# NestJS has special tools to address thes particaulr steps above:

- Request---->
Validate data contained in the request (pipe)
Make sure the user is authenticated (Guard)
Route the request to a particular function (Controller)
Run some business logic (Service)
Access a database (Repository)
Response <----------

# Parts of Nest:

- Controllers: Handles incoming requests
- Service: Handles data access and business logic
- Modules: Group together code
- Pipes: validates incoming data
- Filter: Handles error that occur during request handling
- Guards: handles authentication
- Interceptors: Add extra lgic to incoming requests or outgoing responses
- Repositories: Handles data stored in a DB.






