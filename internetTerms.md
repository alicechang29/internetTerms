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

PART TWO:

icanhazdadjoke.com
{"current_page":1,"limit":20,"next_page":1,"previous_page":1,"results":[{"id":"QuscibaMClb","joke":"What does a pirate pay for his corn? A buccaneer!"},{"id":"2gii3LeN7Ed","joke":"Why couldn't the kid see the pirate movie? Because it was rated arrr!"},{"id":"SvzIBAQS0Dd","joke":"What did the pirate say on his 80th birthday? Aye Matey!"},{"id":"SnOf2gqjiqc","joke":"Why are pirates called pirates? Because they arrr!"},{"id":"exXSCtkOKe","joke":"Why do pirates not know the alphabet? They always get stuck at \"C\"."}],"search_term":"pirate","status":200,"total_jokes":5,"total_pages":1}

IP Address - 104.21.66.15

PART THREE:

- can find it in debugger > Network > select the page (localhost) tab > Headers, Preview, Response

