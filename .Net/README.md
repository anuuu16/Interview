# .NET

## .NET CORE

[1. Dependency injection ](1-QUESTION)

[2. Inversion of control ](2-QUESTION) 

[3.Design Pattern ](3-QUESTION) 

#### 1. QUESTION
#### Dependency injection
In software engineering, dependency injection is a technique in which an object receives other objects that it depends on, called dependencies. Typically, the receiving object is called a client and the passed-in ('injected') object is called a service. The code that passes the service to the client is called the injector. Instead of the client specifying which service it will use, the injector tells the client what service to use. The 'injection' refers to the passing of a dependency (a service) into the client that uses it.

The intent behind dependency injection is to achieve separation of concerns of construction and use of objects. This can increase readability and code reuse.

Dependency injection is one form of the broader technique of inversion of control. A client who wants to call some services should not have to know how to construct those services. Instead, the client delegates to external code (the injector). The client is not aware of the injector. The injector passes the services, which might exist or be constructed by the injector itself, to the client. The client then uses the services.

This means the client does not need to know about the injector, how to construct the services, or even which services it is actually using. The client only needs to know the interfaces of the services, because these define how the client may use the services. This separates the responsibility of 'use' from the responsibility of 'construction'.


#### 2. QUESTION
##### Inversion of control
In software engineering, inversion of control (IoC) is a programming principle. IoC inverts the flow of control as compared to traditional control flow. In IoC, custom-written portions of a computer program receive the flow of control from a generic framework. A software architecture with this design inverts control as compared to traditional procedural programming: in traditional programming, the custom code that expresses the purpose of the program calls into reusable libraries to take care of generic tasks, but with inversion of control, it is the framework that calls into the custom, or task-specific, code.

Inversion of control is used to increase modularity of the program and make it extensible,[1] and has applications in object-oriented programming and other programming paradigms

The term is related to, but different from, the dependency inversion principle, which concerns itself with decoupling dependencies between high-level and low-level layers through shared abstractions. The general concept is also related to event-driven programming in that it is often implemented using IoC so that the custom code is commonly only concerned with the handling of events, whereas the event loop and dispatch of events/messages is handled by the framework or the runtime environment.

#### 3. QUESTION
##### Design Pattern

Creational Design Pattern
  * Factory Method
  * Abstract Factory
  * Builder
  * Prototype
  * Singleton
