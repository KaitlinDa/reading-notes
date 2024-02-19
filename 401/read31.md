# Read 31 Django REST Framework & Docker

## Reading Questions
1. What are the key components of a Docker container, and how do they help streamline the development and deployment of applications?
* The key components of a Docker container include the Dockerfile, images, and containers. A Dockerfile is a script containing commands for building a Docker image, which is a portable and lightweight snapshot of an application and its environment. Containers are instances of Docker images that run the application. These components help streamline development and deployment by ensuring consistency across environments, reducing conflicts between differing system configurations, and facilitating easy version control and sharing.

2. Describe the primary steps involved in building a library website using Django, including essential components like models, views, and templates.
* First, set up a Django project and app where the website's configurations and components will reside. Second, define models in your app to represent the database structure for things like books, authors, and borrowers. Third, create views to handle the logic of processing user requests and returning responses. Fourth, design templates to define the HTML structure of the web pages for user interaction. Lastly, configureURLs to map requests to the appropriate views. These components work together to facilitate the development of a dynamic, database-driven website. 

3. Can you explain the primary differences between Django and Django REST framework?
* The primary differences between Django and Django REST framework (DRF) are their intended use cases and capabilities. Django is a high-level Python web framework that encourages rapid development and clean, pragmatic design, ideal for building web applications with a built-in template system. Django REST framework, on the other hand, is an extension of Django specifically designed to build web APIs, making it easier to create RESTful services with JSON or XML responses. DRF provides additional tools for authentication, serialization, and request parsing, which are essential for API development but are not as directly addressed by Django itself.

## Things I want to know more about
I would like to know more about how to use Django applications for specific purposes. I would also liek to know about if there are any easier ways to create these applications. There are a lot of steps that need to be followed and it's easy to make mistakes. 