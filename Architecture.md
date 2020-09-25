# Discussing About the Software Architecture


## Table of contents
* [Software Architecture Patterns](#Software-Architecute-/-Software-Architecture-Patterns)
* [Client/Server](#Client/Server)
* [Peer-to-Peer](#Peer-to-Peer)
* [Monolithic](#Monolithic)
* [Microservices](#Microservices)
* [REST](#REST)

## Software Architecture / Software Architecture Patterns

An architectural pattern is a general, reusable solution to a commonly occurring problem in software architecture within a given context. Architectural patterns are similar to software design pattern but have a broader scope.

There are different software architecural patterns and choosing the right pattern is important when it comes to software development.

[Back To Top](#Table-of-Contents)


## Client/Server

This pattern consists of two parties; 
a server and multiple clients. 

The server component will provide services to multiple client components. Clients request services from the server and the server provides relevant services to those clients. Furthermore, the server continues to listen to client requests.
clients and servers communicate over a computer network on separate hardware, but both client and server may reside in the same system.

A client does not share any of its resources, but it requests content or service from a server. Clients, therefore, initiate communication sessions with servers, which await incoming requests. Examples of computer applications that use the client-server model are email, network printing, and the World Wide Web.

Usage
Online applications such as email, document sharing and banking.

[Back To Top](#Table-of-Contents)


## Peer-to-Peer 

In this pattern, individual components are known as peers. Peers may function both as a client, requesting services from other peers, and as a server, providing services to other peers. A peer may act as a client or as a server or as both, and it can change its role dynamically with time.

Usage
File-sharing networks such as Gnutella and G2)
Multimedia protocols such as P2PTV and PDTP.
Cryptocurrency-based products such as Bitcoin and Blockchain

[Back To Top](#Table-of-Contents)


## Monolithic

A monolithic application has most of its functionality within a single process/container. Monolithic application describes a single-tiered software application in which the user interface and data access code are combined into a single program from a single platform.

Monolithic software is designed to be self-contained; components of the program are interconnected and interdependent rather than loosely coupled as is the case with modular software programs. In a tightly-coupled architecture, each component and its associated components must be present in order for code to be executed or compiled.

The problem with monolithic software is that if there is a problem the entire software has to be rewritten.

[Back To Top](#Table-of-Contents)


## Microservices

Microservices are component parts of an application that are designed to run independently. A microservices-based application is a collection of loosely coupled services that are lightweight and independently deployable and scalable. Because each microservice is modular and runs its own processes, it can be modified without affecting the entire application.

This architecture allows for each service to scale or update without disrupting other services in the application. A microservices framework creates a massively scalable and distributed system, which avoids the bottlenecks of a central database and improves business capabilities, such as enabling continuous delivery/deployment applications and modernizing the technology stack.

Benefits:

* Agility
* Flexible Scaling
* Easy Deployment
* Technological Freedom


### More Info
[AWS-Microservice](https://aws.amazon.com/microservices/)

[Microservice](https://www.citrix.com/glossary/what-are-microservices.html)


## Monolithic vs. Microservices Architecture

With monolithic architectures, all processes are tightly coupled and run as a single service. This means that if one process of the application experiences a spike in demand, the entire architecture must be scaled. Adding or improving a monolithic application’s features becomes more complex as the code base grows. This complexity limits experimentation and makes it difficult to implement new ideas. Monolithic architectures add risk for application availability because many dependent and tightly coupled processes increase the impact of a single process failure.

With a microservices architecture, an application is built as independent components that run each application process as a service. These services communicate via a well-defined interface using lightweight APIs. Services are built for business capabilities and each service performs a single function. Because they are independently run, each service can be updated, deployed, and scaled to meet demand for specific functions of an application.

### More Info

[AWS-Monolithic-VS-Microservices](https://aws.amazon.com/microservices/)

[Back To Top](#Table-of-Contents)


## REST

Representational State Transfer (REST) is a style of architecture based on a set of principles that describe how networked resources are defined and addressed. 

REST, or REpresentational State Transfer, is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other. REST-compliant systems, often called RESTful systems, are characterized by how they are stateless and separate the concerns of client and server. We will go into what these terms mean and why they are beneficial characteristics for services on the Web.

### More Info

 [REST](https://www.codecademy.com/articles/what-is-rest)

 [Back To Top](#Table-of-Contents)