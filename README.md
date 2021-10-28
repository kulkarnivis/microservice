# microservice

### Interduction
<details>
  <summary>Click to expand</summary>
  Some of the defining characteristics that are frequently cited include:

  Services in a microservice architecture are often processes that communicate over a network to fulfill a goal using technology-agnostic protocols such as HTTP.

  * Services are organized around business capabilities.
  * Services can be implemented using different programming languages, databases, hardware and software environments, depending on what fits best.
  * Services are small in size, messaging-enabled, bounded by contexts, autonomously developed, independently deployable, decentralized and built and released with     automated processes.

    A microservice is not a layer within a monolithic application (example, the web controller, or the backend-for-frontend). Rather, it is a self-contained piece of business functionality with clear interfaces, and may, through its own internal components, implement a layered architecture. From a strategy perspective, microservice architecture essentially follows the Unix philosophy of "Do one thing and do it well".Martin Fowler describes a microservices-based architecture as having the following properties

  * Lends itself to a continuous delivery software development process. A change to a small part of the application only requires rebuilding and redeploying only       one or a small number of services.
  * Adheres to principles such as fine-grained interfaces (to independently deployable services), business-driven development (e.g. domain-driven design).

    It is common for microservices architectures to be adopted for cloud-native applications, serverless computing, and applications using lightweight container deployment. According to Fowler, because of the large number (when compared to monolithic application implementations) of services, decentralized continuous delivery and DevOps with holistic service monitoring are necessary to effectively develop, maintain, and operate such applications.A consequence of (and rationale for) following this approach is that the individual microservices can be individually scaled. In the monolithic approach, an application supporting three functions would have to be scaled in its entirety even if only one of these functions had a resource constraint.With microservices, only the microservice supporting the function with resource constraints needs to be scaled out, thus providing resource and cost optimization benefits.
</details>

### Benifits
<details>
  <summary>Click to expand</summary>
  
  The benefit of decomposing an application into different smaller services are numerous:
  * **Modularity**: This makes the application easier to understand, develop, test, and become more resilient to architecture erosion.This benefit is often argued in comparison to the complexity of monolithic architectures.
  * **Scalability**: Since microservices are implemented and deployed independently of each other, i.e. they run within independent processes, they can be monitored and scaled independently.
  * **Distributed development**: it parallelizes development by enabling small autonomous teams to develop, deploy and scale their respective services independently. It also allows the architecture of an individual service to emerge through continuous refactoring.[40] Microservice-based architectures facilitate continuous integration, continuous delivery and deployment.
</details> 
