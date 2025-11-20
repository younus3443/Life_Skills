# Service-Oriented Architecture(SOA)
SOA is a software design style where applications are built as a collection of small, independent services that communicate with each other over a network.

Think of SOA like a restaurant:

* The kitchen, billing counter, waiter, and menu management are separate services.

* Each does its job independently.

* They communicate to complete your order.

## Characteristics of SOA

#### Services are independent
Each service works on its own and can be replaced without affecting the others.
#### Loose coupling

Services are not tightly connected — they only need an agreed communication method
#### Reusability
A service can be used by multiple applications.
Example: A payment service can be used by website, mobile app, admin panel.
#### Interoperability
Services can be written in different programming languages and run on different systems but still communicate.

### Real worlds example

An e-commerce site using SOA may have:

* User Service – manages login, signup

* Product Service – handles product data

* Order Service – processes orders

* Payment Service – processes payments

* Email Service – sends order notifications

Each one is a separate service.

### Benefits of SOA

* Easier to scale
* Easy to maintain
* Reusable services
* Better for large enterprise systems
* Allows parallel development by different teams

### Drawbacks of SOA

* More complex than monolithic systems
* Network latency (because services communicate over network)
* Requires good governance and documentation
* security becomes harder (many access points)

### References
https://www.geeksforgeeks.org/software-engineering/service-oriented-architecture/
https://www.tutorialspoint.com/soa/soa_overview.htm
