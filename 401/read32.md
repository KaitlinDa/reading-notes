# Read 32 Permissions and Postgresql

## Reading Questions
1. What are the key components and purpose of Django Rest Framework (DRF) permissions, and how do they help in securing an API?
* Django Rest Framework (DRF) permissions are rules that determine whether a request should be granted or denied access to a particular API endpoint. Key components include permission classes such as IsAuthenticated, IsAdminUser, and IsOwnerOrReadOnly. These permissions help secure an API by ensuring that only authorized users can perform certain actions, like creating, updating, or deleting resources.

2. In SQL, what is the purpose of the SELECT statement, and how would you use it to retrieve all columns from a table called ‘employees’?
* The purpose of the SQL SELECT statement is to query data from one or more tables in a database. It allows you to specify exactly which data you want to retrieve. To retrieve all columns from a table called ‘employees’, you would use the statement: SELECT * FROM employees;. This command fetches all rows and columns from the ‘employees’ table.

3. Can you explain the role of DRF Generic Views and provide examples of their usage in building a RESTful API?
* DRF Generic Views simplify the process of creating API endpoints by providing mixins and classes that handle common tasks such as querying a database and serializing data. Examples include ListAPIView for retrieving a list of objects, RetrieveAPIView for fetching a single instance, CreateAPIView for creating new instances, and DestroyAPIView for deleting instances. These views reduce the amount of code you need to write for a RESTful API by abstracting common functionality into reusable components.

## Things I want to know more about
I would like to know more about building and securing websites when using different types of frameworks.