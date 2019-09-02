### Homework Week 8, Day 1

1. What is responsible for defining the routes of the games resource?
The create_router file has reusable fetch requests that incorporate the restful routes.

2. What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?
The folder structure is divided by front end and back end. Client handles all the files which process the data and display it within the browser. The server folder handles all of the server side processes like storing the data.

3. What are the the responsibilities of server.js?
This handles the database and allows for the front end to access what it needs from the db.

4. What are the responsibilities of the gamesRouter?
The gamesRouter is responsible for allowing the front and backends to access the routes which move information back and forth.

5. What process does the the client (front-end) use to communicate with the server?
The client uses the routes set out by the create_router.js file to access the data as and when it needs too.

6. What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs.
The second optional argument can be 'init'. This appears to work much like a request function.

7. Which of the games API routes does the front-end application consume (i.e. make requests to)?
The front end makes requests to the base URL which is established using the INDEX route. And to a certain extent the SHOW route.

8. What are we using the MongoDB Driver for?
The driver allows all parts of the app to access the db based on callback and promise based interactions.

#### Extension:
Why do we need to use ObjectId from the MongoDB driver?
We use the ObjectID as the it's a unique hex code which is assigned to an object when added to the DB. The ensures the correct object is manipulated.
