# Read 17 Web Scraping

## Reading Questions
1. What are the key differences between scraping static and dynamic websites?
* In static websites, the content is fixed and the same HTML is returned to all users, data can be retrieved by downloading the HTML page and parsing the content, and typically simple HTTP requests are sufficient. For dynamic websites, the content will change depending on the user interaction, they require interaction with a webpage's Javascript, and they also require more sophisticated tools to handle dynamic content. 

2. Explain at least three techniques or best practices that can be employed to avoid getting blocked while scraping websites.
* Three techniques used to avoid getting blocked while scraping are by respecting the robots.txt file ensuring ethical scraping in line with the site's guidelines, while using CAPTCHA solving services can help navigate anti-bot measures. Additionally, being cautious of honeypot traps, which are set up to detect and block scrapers, is crucial.

3. What is Playwright, and how does it assist in web scraping tasks? Provide an example of a use case where Playwright would be particularly beneficial.
*  Playwright is a tool that helps you automate web browsers, like Chrome and Firefox. It's handy for web scraping, where you want to extract information from websites. For instance, if you want to scrape data from a fancy online store that uses a lot of interactive features, Playwright can make it easier to get the data you need, even if the website is complex.

4. Describe the purpose of using Xpath in web scraping, and provide an example of an Xpath expression to select a specific HTML element from a webpage.
* XPath is a way to navigate and select specific elements in an HTML document when web scraping. It's like a map that helps you find the data you want. For example, if you want to select a paragraph with the class "description" on a webpage, you can use an XPath expression like this:

`//p[@class='description']`


## Things I want to know more about
I am interested in learning about the ethics and legcality of web scraping. 