# Read 27 Django Models

## Reading Questions
1. Explain the purpose and basic structure of Django models. How do they help in creating and managing database schema in a Django application?
* Django models are Python classes that define the structure of database tables in a Django application. They automate database schema creation and management by translating Python code into database tables, eliminating the need for manual SQL. This makes it easy to develop, maintain, and update the database as the application changes.

2. Describe the primary features and functionality of the Django Admin interface. How can it be customized to suit the specific needs of a project?
* The Django Admin interface is a built-in feature that provides a web-based interface for managing the content of a Django application. It allows administrators to create, read, update, and delete database records easily. The interface can be customized to suit specific project needs by modifying admin model options, creating custom admin classes, and using Django's template system to change its look and feel. 

3. Briefly outline the key components and workflow of a Django application, as discussed in the Beginner’s Guide to Django. How do these components interact with each other to create a functional web application?
* A Django application consists of key components such as models, views, templates, and URLs. Models define the data structure, views handle the business logic and interact with models to pass data to templates, which generate the HTML for the user interface. URLs route incoming web requests to the appropriate views. Together, these components interact to receive web requests, process them through business logic, access and modify data, and return responses, creating a functional web application.

## Things I want to know more about
I want to know more about how I can use the Admin feature to my advantage in making my app better using Django. 