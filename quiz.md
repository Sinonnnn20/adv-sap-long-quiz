## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).
- Microservices is like a cool way of doing software stuff for a whole big company. so, there's these reusable software thingies called services, and each one's got code and data stuff mashed together to do specific business things, like checking if a customer's credit is good or logging into a website or handling a mortgage application.
2. List and discuss the characteristics of SOA.
- Standardized Service Contracts are like rules that services must follow. These contracts serve to describe what services are meant to do.

- Loose Coupling in services is about avoiding tight dependencies.

- Abstraction in services is like keeping secrets. Services hide the technical details, dodge information overload, and keep things straightforward.

- Service Reusability is when they split up the complicated stuff into services, aiming to use it over and over again

- Autonomy in services refers to the ability of services to control their own logic independently.

- Statelessness in services is the idea that they ideally shouldn't carry any baggage.

- Discoverability in services involves the ability to be found, typically in a service registry.

- Composability in services is about breaking down complex issues into smaller ones, aligning with the Reusability principle.

- Interoperability in services involves using standards that enable diverse users to access and utilize the service.
3. Define Microservices.
- I think microservices are kind of like building things in a chill way with pieces that aren't super attached. It's not like the old-school deal of using Service-Oriented Architecture (SOA) for the whole company. Microservices are more about doing one application at a time, making it more nimble, scalable, and tough.
4. List and discuss the benefits of using Microservices.
- independently deployable microservices offer a relaxed approach to building things, using loosely connected components.

- right tool for the job traditional architecture pattern has limitations, especially in sharing a common stack and database for the entire application.

- microservices allow for precise scaling by enabling the individual deployment and scaling of specific services.
5. List and discuss the similarities and differences of SOA and Microservices.
- Difference is that SOA is less flexible due to common standards and shared infrastracture and microservices are more flexible because each service can use its own tech stack and the similarity is both approaches involve breaking down a system into smaller, more manageable components.
6. Define Web Services.
- A web service is like a way for different computer programs to talk to each other over the internet. It helps them share information, even if they're written in different languages or run on different types of computers. It's kind of like how programs on one computer can communicate with each other.
7. List and discuss the benefits of using Web Services.
- A web service is like a code that can be accessed from afar using HTTP. It's like making your program's features available to other apps over the internet once you put it out there.

- Web services enable diverse apps to communicate and share data. They support interoperability, allowing applications in different languages (like VB or .NET) to connect with Java web services, making them independent of specific platforms and technologies.

- Web services employ standardized protocols for communication across all layers: Service Transport, XML Messaging, Service Description, and Service Discovery. This protocol stack standardization provides businesses with numerous benefits.

- Web services use standardized protocols in all communication layers—Service Transport, XML Messaging, Service Description, and Service Discovery. This standardization brings numerous benefits to businesses.
8. List and discuss the characteristics of Web Services.
- Web services use XML for data representation and transportation, freeing them from network, operating system, and platform restrictions. This XML-based approach ensures strong interoperability at the core of these applications.

- In web services, consumers aren't directly bound to the service. The service interface can evolve without affecting the client's ability to interact. This contrasts with tightly coupled systems, where changes in one interface require updates in the other.

- Java and similar technologies typically expose services through individual methods. However, for corporate-level capabilities, it's better to use coarse-grained interfaces. Web services provide a natural way to define these interfaces, accessing the right amount of business logic.

- Web services can operate synchronously or asynchronously. Synchronicity involves the client being tied to the service execution. In synchronous invocations, the client blocks and waits for the service to complete its operation before proceeding.

- Web services enable clients to call procedures, functions, or methods on remote objects through an XML-based protocol. Remote procedures define input and output parameters that the web service must support.

- XML's versatility goes beyond data to represent complex documents in web services, enabling transparent exchange for seamless business integration.
9. List and discuss the distinct roles in Web Services Architecture.
- The provider develops and offers the web service to client applications seeking to use it.

- A requestor is simply the client application seeking to connect with a web service. It could be an application in .Net, Java, or any other language, looking for specific functionality through the web service.

- A broker is the application that grants access to the UDDI (Universal Description, Discovery, and Integration). UDDI, as mentioned earlier, is a registry for businesses and web services.

- Publishing involves the provider notifying the broker (service registry) about the web service's existence. The provider uses the broker's publish interface to make the service accessible to clients.

- To find a published web service, the requestor consults the broker, which acts as the intermediary connecting clients with available services.

- With details from the broker, the requestor can then bind or invoke the web service, accessing its functionalities.
10. List and discuss the Web Services Components.
- SOAP is an XML-based protocol for computer communication, allowing data exchange between different systems. It's platform-independent and supports communication by encoding HTTP headers and XML files, with the added benefit of firewall compatibility.

- WSDL, or Web Services Description Language, is an XML-based tool for describing and accessing web services. It plays a key role in UDDI, helping businesses list services online and facilitating easy access for individuals and other businesses.

- UDDI, or Universal Description, Discovery, and Integration, is an XML-based standard for describing, publishing, and finding web services. It's a key foundation for web services, working alongside SOAP and WSDL, and serves as a specification for a distributed registry of these services.
