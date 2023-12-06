# Read 08 APIs

## API Design Best Practices

1. What does REST stand for?

    •REST stands for Representational State Transfer.

2. REST APIs are designed around a ____.

    •They are designed around resources which are any kind of data, object, or service that can be accessed by the client.

3. What is an identifier of a resource? Give an example.

    •It is a unique identifier of a name or string that distinguishes a resource on a network or system. An example of this is a URL. It is used to access web pages on the internet.

4. What are the most common HTTP verbs?

    •<code>GET </code> retrieves a representation of the resource as a specified URI.

    •<code>POST </code> creates a new resource at the specified URI.

    •<code>PUT </code> creates or replaces the resource at a specific URI.

    •<code>PATCH </code> performed a partial update to a resource.

    •<code>DELETE </code>removes the resource at a specific URI.

5. What should the URIs be based on?

    •They should be based on a structure than enables an unique identification resource across the network.

6. Give an example of a good URI.

    •An example of a good URI is one that follows a standard convention and is clear. A web side that starts with https:// is a good example, because it shows that the resource can be accessed by the HTTP protocol.

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

    •This is when an API requires a large number of small HTTP requests to retrieve data. Numerous requests are needed to perform simple operations. They should be avoided.

8. What status code does a successful GET request return?

    •This will return a HTTP status code 200 (OK).

9. What status code does an unsuccessful GET request return?

    •This will return a HTTP status code 204 (No Content).

10. What status code does a successful POST request return?

    •It will return a HTTP status code 201 (Created).

11. What status code does a successful DELETE request return?

    •The web server will respond with a HTTP status code 204 (No Content).

## Things I want to know more about

There are many status codes and they can be very useful to understand.

## Resources

I used all the reading material and ChatGPT for this assignment.
