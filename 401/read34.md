# Read 34 API Deployment

## Reading Questions
1. What are the key principles to follow when organizing and configuring Django settings for a project, according to the “Django Settings Best Practices” reading?
* To organize and configure Django settings for a project effectively,you want to separate configuration from code by storing sensitive information like API keys and database passwords in environment variables or separate configuration files. Employing a base settings file for common configurations, while extending or overriding these settings in environment-specific files, ensures clarity and promotes reuse. 

2. How does the White Noise library contribute to the efficient serving of static files in a Django application, and what are the steps to integrate it into a project?
* The White Noise library improves the serving of static files in a Django application by enabling web servers to handle static file serving directly, which reduces the load on the application server and boosts performance. Integration of White Noise involves installing the library, adding it to the Django project's MIDDLEWARE settings after the SecurityMiddleware, configuring STATICFILES_STORAGE to utilize White Noise's storage backend, and optionally adjusting settings for optimized performance like enabling compression and caching.

3. What is the purpose of Cross-Origin Resource Sharing (CORS) in web applications, and how can it be implemented and configured in a Django project to control access to resources?
* Cross-Origin Resource Sharing (CORS) is important in web applications by allowing or restricting web pages to request resources from different domains, thereby safeguarding the application while enabling necessary resource access. Implementing and configuring CORS in a Django project can be achieved with the django-cors-headers library. This involves installation, adding the library to INSTALLED_APPS and MIDDLEWARE, and configuring access control settings such as CORS_ORIGIN_WHITELIST or CORS_ORIGIN_ALLOW_ALL to manage which domains can access your resources, ensuring a secure environment for managing cross-origin requests.

## Things I want to know more about
I would like to know about the practical implications of these configurations and libraries.