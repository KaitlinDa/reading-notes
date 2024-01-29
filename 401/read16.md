# Read 16 Serverless Functions

## Reading Questions
1. What are the key characteristics of serverless computing, and how does it differ from traditional server-based architectures?
* Some key characteristics of serverless computing are no server management, stateless functions, and faster deployment / time to market development. It differs from traditional server-based architectures in that it allows for a faster deployment, can be more cost effective depending on the workload, and less control. 

2. How can one get started with Vercel, and what are the main steps involved in deploying a serverless function using Vercel?
* You first want to create an account and select the plan you want. You then choose to authenticate your Git or email. Once your account is made, you can create your new project. Either import an existing one or create a new one. Find and deploy the template you want. Once your project is cloned to your git provider, Vercel will start to deploy the project. The project is first build, assigned a domain, and then deployed. 

3. What are APIs, and how can they be utilized in Python applications to access and manipulate data from external sources?
* APIs (Application Programming Interfaces) are a set of rules for building and interacting with software applications. They allow different pieces of software to communicate with eachother allowing the user to access and manipulate data. Python first makes an HTTP request to an API's library. After the request is made, it is sent in a JSON like format. Authentication between the software and API takes place. Once it passes authentication and no errors are displayed along the way, you will get the data you were wanting. 

4. What is the Requests library in Python, and how can it be used to interact with APIs by sending HTTP requests? Can you provide an example of a basic GET request using the Requests library?
* The Requests library in Python is a HTTP library used for sending all types of HTTP requests. It is easy to make all kinds of HTTP requests, such as GET, POST, PUT, DELETE, etc. You must first install the Request library by using `pip install requests`. Below is a simple example of using a basic GET request using the Requests library:

            import requests

                url = 'https://api.example.com/data'

                response = requests.get(url)

                if response.status_code == 200:
                     data = response.json()  
                         print(data)
                    else:
                        print(f"Failed to retrieve data: Status code {response.status_code}")


## Things I want to know more about
I would like to know more about to how properly use different API's in Python. 