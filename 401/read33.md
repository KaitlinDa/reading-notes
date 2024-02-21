# Read 33 Authentication & Production Server

## Reading Questions
1. What is the primary purpose of JSON Web Tokens (JWTs) and how do they work in terms of encoding and decoding data?
* The purpose of JSON Web Tokens (JWTs) serve as a compact and self-contained way for securely transmitting information between parties as a JSON object. This information can be verified and trusted because it is digitally signed. JWTs encode data as a JSON object that is then base64Url encoded to form the JWT structure (header, payload, and signature). Decoding a JWT involves verifying the signature using the secret key or public/private key pair that was used to sign the token, thereby ensuring the data's integrity and authenticity.

2. How does JWT Authentication integrate with Django REST Framework to secure API endpoints, and what are the key components involved in this process?
* JWT Authentication integrates with the Django REST Framework (DRF) by providing a secure method to authenticate users and protect API endpoints. It uses JWTs to authenticate requests by exchanging tokens. The key components involved in this process include the JWT Authentication class that handles token verification, the authentication backend that integrates JWT with Django's authentication system, and middleware that processes HTTP headers to extract and validate tokens on API requests.

3. Why is Django’s built-in runserver not suitable for production environments, and what are some alternative server options that should be considered for deploying a Django application?
* Django’s built-in runserver is not suitable for production environments because it is designed for development purposes only; lacking the robustness, security, and scalability required for handling real-world traffic. It does not serve static files efficiently, lacks SSL support, and is not optimized for performance. For deploying a Django application in production, alternative server options like Gunicorn or uWSGI as the application server, paired with Nginx or Apache as the web server, are better.

## Things I want to know more about
I want to know more about making my Django application secure. 