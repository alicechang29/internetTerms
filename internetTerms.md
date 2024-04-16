Part One: Solidify Terminology»
In your own terms, define the following terms:

What is HTTP?
- hypertext transfer protocol
- set of rules of how we communicate with the web server

What is a URL?
- uniform resource locator
- composed of: protocol, hostname, port, resource, query

What is DNS?
- domain name service
- DNS servers - store all the IP addresses
- DNS is the protocol how computer changes URL to ip address


What is a query string?
- the extra info that is provided to the server for narrowing down a search
- may be used to change the page


What are two HTTP verbs and how are they different?
- GET: gets the information, without making any changes to the data on the server
- POST: requests with side effect. Data on the server is changing.

What is an HTTP request?
- asking the server for information
- composed of: method (GET/POST), HTTP protocol version, resource URL, headers

What is an HTTP response?
- the server responding with information
- composed of: HTTP protocol version, response status code, headers

What is an HTTP header? Give a couple examples of request and response headers you have seen.
- HTTP Request: (hostname, date, language, cookies)
- HTTP Response: (content type, date/time, cookies, caching info)

What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
- turns into:
- URL to IP address
- Connects IP Address using the port
- Using the HTTP protocol
- Asks for the resource
- Includes any query strings
