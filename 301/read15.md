# Read 15 Authentication

## What is OAuth

1. What is OAuth?

    * OAuth is a protocol that allows websites and other services to share assets with the users. It describes how unrelated servers can safely allow authenticated access to assets without sharing any credentials.

2. Give an example of what using OAuth would look like.

    * A user granting any third-party app;ocatiom access to their Google email without sharing any of their credentials. The user logs in by Google's authentication server and approves the request giving the applicatiom an access token for access. 

3. How does OAuth work? What are the steps that it takes to authenticate the user?

    * OAuth enables a user's authenticated access to one website (the second site) through another (the first site) by following these steps: The first site initiates the connection, generates unique one-time tokens, and provides them to the user's client software. After user authentication and approval, an access token is issued and passed to the first site, which uses it to access the second site on the user's behalf, resulting in a successfully completed transaction. OAuth is unique for its ability to work securely across the web and its widespread adoption.

4. What is OpenID?

    * OpenID is an open standard authentication protocol that enables users to log in to various websites and services using a single set of credentials, eliminating the need for multiple usernames and passwords.

## Authorization and Authentication flows

1. What is the difference between authorization and authentication?

    * Authorization is the process that determines what actions a user is allowed to perform or access within a system. Authentication is the process of verifying the ID of a user, system, or entity trying to access a resource or wanting to perform an action.

2. What is Authorization Code Flow?

    * Authorization Code Flow exchanges an authorization code for a token. It is used for securing web applications and APIs.

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

    * It allows the enhancement of security flow in which mobile or single page applications are involved. 

4. What is Implicit Flow with Form Post?

    * It secures single-page applications and other web applicationswhen the client secret is not recommended.

5. What is Client Credentials Flow?

    * It is used for machine to machine communication and server to server authorization. It is specifically designed for when a client application needs access to resources or APIs directly. 

6. What is Device Authorization Flow?

    * It is used for devices that have limited input capabilities that can not directly interact with a full web browser.

7. What is Resource Owner Password Flow?

    * This allows a client's application to exchange a user's username and password granting an access token directly to the authorization server.

## Things I want to know more about

How easy is it to bypass these security measures? Which one is the most secure?

## Resources

I used all the reading material and ChatGPT for this assignment. 
