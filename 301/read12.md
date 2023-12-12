# Read 12 CRUD

## Status Codes Based On REST Methods

1. In your own words, describe what each group of status code represents:

    •100’s = Informational statuses that tell the client the header part of the request has been received. The server will then try to comply with the request of the client.

    •200’s = Success codes. They tell the client the request has been accepted.

    •300’s = Redirection codes. Tells the clients that the resources they are requesting are not expected at that location anymore.

    •400’s = Client error codes. These are invalid requests a client sent to a server.

    •500’s = Server error codes. They indicate problems with overwhelmed or unreachable servers.

2. What is a status code 202?

    •Accepted. Tells the client that the request was valid, but the processing will finish sometime in the future.

3. What is a status code 308?

    •Permanent redirect. Tells the client to use another URL to access the resource.

4. What code would you use if an update didn’t return data to a client?

    •204 No Content is the code you would use.

5. What code would you use if a resource used to exist but no longer does?

    •404 Not Found is the code you would use.

6. What is the ‘Forbidden’ status code?

    •The client has authorized itself, but still has no permission to access the resources.

## Build A REST API With Node.js, Express, & MongoDB - Quick

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

    •For security reasons. This will keep that information safe and secure.

2. What is middleware?

    •Software components or a piece of code that is between different layers of an application. It allows for communication and data processing.

3. What does <code>app.use(express.json())</code> do?

    •It is used to parse incoming json data from the request body in express.

4. What does the<code> /:id</code> mean in a route?

    •It means it is used to capture a variable value from the URL making it available to handle your parameters.

5. What is the difference between <code>PUT</code> and <code>PATCH</code>?

    •<code>PUT</code> is used to replace the entire resource with ne data while <code>PATCH</code> is used for partial updates by sending changed fields.

6. How do you make a default value in a schema?

    •You have to set a default value and then define it.

7. What does a <code>500</code> error status code mean?

    •Internal service error. There was an unexpected problem on the server’s side.

8. What is the difference between a status <code>200</code> and a status <code>201</code>?

    •<code>200</code> means a process was successfully processed and is being returned while  <code>201</code> indicates that the request has created a new resource on the server.

## Things I want to know more about

I want to know more about all the status codes available. They are very useful to know when programming and trying to troubleshoot a server. 

## Resources

I used all the reading material and ChatGPT for this assignment.
