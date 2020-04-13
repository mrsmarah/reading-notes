# Data:

- sending form data is easy, but securing an application can be tricky. 
- Once the form data has been validated on the client-side, it is okay to submit the form. 
- And, since we covered validation in the previous article, we're ready to submit! This article looks at what happens when a user submits a form — where does the data go, and how do we handle it when it gets there? 

- We also look at some of the security concerns associated with sending form data.

**Prerequisites**

- Basic computer literacy, an understanding of HTML, and basic knowledge of HTTP and server-side programming.

**Objective:**

- To understand what happens when form data is submitted, including getting a basic idea of how data is processed on the server

**Client/server architecture**

- At it's most basic, the web uses a client/server architecture that can be summarized as follows. 
- A client (usually a web browser) sends a request to a server (most of the time a web server like Apache, Nginx, IIS, Tomcat, etc.), using the HTTP protocol. 

- The server answers the request using the same protocol.

**The action attribute**

- The action attribute defines where the data gets sent. Its value must be a valid relative or absolute URL. 
- If this attribute isn't provided, the data will be sent to the URL of the page containing the form — the current page.

**The method attribute**

- The method attribute defines how data is sent. The HTTP protocol provides several ways to perform a request; HTML form data can be transmitted via a number of different methods, the most common being the GET method and the POST method

- Just remember that a front-end developer is not the one who should define the security model of the data.It's possible to perform client-side form validation, but the server can't trust this validation because it has no way to truly know what has really happened on the client-side.

**Security issues**

- Each time you send data to a server, you need to consider security. 

- HTML forms are by far the most common server attack vectors (places where attacks can occur). The problems never come from the HTML forms themselves — they come from how the server handles data.

- The Website security article of our server-side learning topic discusses a number of common attacks and potential defences against them in detail. 
- You should go and check that article out, to get an idea of what's possible.