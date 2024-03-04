# Read 41 React 4

## Reading Questions
1. Explain the concept of dynamic routes in Next.js and how they differ from static routes.
* Dynamic routes in Next.js allow for the creation of paths that can change based on the data provided. By using file and folder naming conventions within the pages directory, dynamic segments are defined using square brackets (e.g., [id].js). This enables the creation of more flexible and scalable applications where the content or path can change based on user actions or data.

2. Describe the process of deploying a Next.js application. What are the key steps involved, and what are some deployment platforms you can use?
* Deploying a Next.js application involves: building the application for production (next build), starting the application (next start) for Node.js environments, or exporting the application for static hosting (next export) when applicable. Deployment platforms for Next.js applications include Vercel and Netlify as well as others These platforms often provide additional features like serverless functions and edge computing capabilities to enhance Next.js applications.

3. How does Next.js handle static file serving? Discuss the default folder structure for storing static assets and explain how to reference them in a Next.js application.
* Next.js handles static file serving through the public directory at the root of the project. Files placed in this directory can be accessed directly under the root URL path. For example, an image located at /public/images/photo.png can be referenced in the Next.js application with the path /images/photo.png. This setup simplifies the organization and referencing of static assets such as images, stylesheets, and scripts in a Next.js application.

## Things I want to know more about
I am interesting in learning about the dynamic routing in Next.js, like how to create routes using data fetching methods. 