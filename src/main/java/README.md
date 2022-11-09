An intro to API's

-API stands for application programming interfaces
-An api is a tool that makes a websites data readable for a computer
-A computer can view and edit data through an API
-A server is the side that provides the API, and the other side is the client 
and the client knows what data is available through the API and can the alter it
-Technically, an API is just a set of rules (interface) that the two sides agree
to follow
-A computer protocol is an accepted set of rules that govern
how two computers can speak to each other
-For two computers to communicate effectively, the server has to know
exactly how the client will arrange its messages
-To make a valid request, the client needs to include four things:
1 URL (Uniform Resource Locator) 1
2 Method
3 List of Headers
4 Body
-The request method tells the server what kind of action the client wants
the server to take
-the 4 common methods seen in API's are GET, POST, PUT, and DELETE
-The request body contains the data the client wants to send the server
-URL,method,headers, and body make up a HTTP request
-After the server receives a request from the client, it attempts to fulfill
the request and send the client back a response
-JSON format has 2 pieces, keys and values
-Keys represent an attribute about the object being described
-If you read a line from left to right, you get a fairly natural English
sentence
-When the client sends the Content-Type header in a request, it is telling
the server that the data in the body of the request is formatted a
particular way
-There are several techniques APIs use to authenticate a client. These
are called authentication schemes
-Basic Auth only requires a username and password
-When the server receives the request, it looks at the Authorization
header and compares it to the credentials it has stored
-Authentication: process of the client proving its identity to the
server 
-Credentials: secret pieces of info used to prove the client's
identity (username, password...)
-Basic Auth: scheme that uses an encoded username and
password for credentials 
-API Key Auth: scheme that uses a unique key for credentials
-Authorization Header: the HTTP header used to hold credentials
-Enter OAuth. Automating the key exchange is one of the main problems
OAuth solves. It provides a standard way for the client to get a key from
the server by walking the user through a simple set of steps. From the
user's perspective, all OAuth requires is entering credentials. Behind
the scenes, the client and server are chattering back and forth to get
the client a valid key
-There are currently two versions of OAuth, aptly named OAuth 1 and
OAuth 2.
-OAuth: an authentication scheme that automates the key
exchange between client and server
-Access Token: a secret that the client obtains upon successfully
completing the OAuth process
-Scope: permissions that determine what access the client has to
user's data