# Web Architecture

## Learning Goals

- Give an overview of client-server architecture.
- Describe clients and servers.

## Introduction

A modern web architecture can involve multiple components like user interface,
database, caches, message queues, load balancers, etc. We will only be looking
at the client-server architecture in this course.

## Client-Server Architecture

The client-server architecture is the fundamental building block of the web.
This architecture works on a request-response model. In this model, the client
sends a request (eg. do I have any new emails) to a server and the server
returns a response (eg. yes you do and here are the new emails).

![Untitled](https://curriculum-content.s3.amazonaws.com/modern-app-dev-managers-leadership/tiers-of-applications/01.png)

Let’s look at the client and server in a bit more detail.

### Client

The client contains the user interface. The user interface is written in HTML,
CSS, and JavaScript. A client is a gateway to the server. It can be an app or a
console in which commands are run.

### Server

A server is mainly used for receiving requests from clients and sending back the
correct response after running business logic based on the request parameters.
All online services require servers to run. Servers that run web applications
are called application servers.

A server can be configured to perform other tasks. These can be:

- Mail server
- File server
- Data storage server
- Proxy server (routes requests to other servers)

## Conclusion

We have learned about the core web architecture that is used in most web
applications. In complex applications, different types of servers are set up and
communicate with each other to perform tasks.
