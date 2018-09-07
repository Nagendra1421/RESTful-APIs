# Restful API Development using Python and Flask

### Rest API Basic:
A Restful API also referred to as a Restful Web Service is based on representational state transfer technology, an architectural style and approach to Communications often used in web services development

Rest technology is generally preferred to the more robust Simple Object Access Protocol technology because Rest leverages less bandwidth, making it more suitable for internet usage. An API for a website is code that allows two software programs to communicate with each another. The API spells out the proper way for a developer to write a program requesting services from an operating System or other application.

### How Restful APIs work:
A RESTful API breaks down a transaction to create a series of small modules. Each module addresses a particular underlying part of the transaction. This modularity provides developers with a lot of flexibility, but it can be challenging for developers to design from scratch. Currently, the models provided by Amazon Simple Storage Service, Cloud Data Management Interface and OpenStack Swift are the most popular.

A RESTful API explicitly takes advantage of HTTP methodologies defined by the RFC 2616 protocol. They use GET to retrieve a resource; PUT to change the state of or update a resource, which can be an object, file or block; POST to create that resource; and DELETE to remove it.

There are seven layers available in the OSI(Open Systems Interconnection) model which are:

1). Physical Layer
2). Data Link Layer
3). Network Layer
4). Transport Layer
5). Session Layer
6). Presentation Layer
7). Application Layer

For APIs we mainly focuses on Application layers which contains a variety of protocols that are commonly needed by users. One widely used application protocol is HTTP, which is the basis for the world  wide web. When a browser wants a web page, it sends the name of the page it wants to the server using HTTP. The server then sends the page back.

Other Application Protocols are: File Transfer Protocol(FTP), Trivial File Transfer Protocol (TFTP), Simple Mail Transfer Protocol(SMTP), TELNET, Domain Name System(DNS).

### Rest Constraints:
1.) Client-Server
2). Stateless
3). Cacheable
4). Uniform Interface
5). Layered System
6). Code on Demand

### Status Code & Reason Phrases:

200 OK
404 Not Found
403 Forbidden
500 Internal Server Error