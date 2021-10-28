# microservices pattern

There are many patterns related to the microservices pattern. The other patterns address issues that you will encounter when applying the microservice architecture.

![image](https://user-images.githubusercontent.com/51394570/139198557-6873c9f7-4f5a-4116-8a12-f5c4c754d536.png)

## Decomposition
<details>
  <summary>Click here to expand</summary>

  
</details>

## Decomposition
<details>
  <summary>Click here to expand</summary>

  
</details>

## Decomposition
<details>
  <summary>Click here to expand</summary>

  
</details>

## Decomposition
<details>
  <summary>Click here to expand</summary>

  
</details>

## Decomposition
<details>
  <summary>Click here to expand</summary>

  ### Pattern: Decompose by business capability Context
  How to decompose an application into services?
  ### Forces
  The architecture must be stable
    * Services must be cohesive. A service should implement a small set of strongly related functions.
    * Services must conform to the Common Closure Principle - things that change together should be packaged together - to ensure that each change affect only one    service
    * Services must be loosely coupled - each service as an API that encapsulates its implementation. The implementation can be changed without affecting clients
    * A service should be testable
    * Each service be small enough to be developed by a “two pizza” team, i.e. a team of 6-10 people
    * Each team that owns one or more services must be autonomous. A team must be able to develop and deploy their services with minimal collaboration with other teams.

  ### Solution
    Define services corresponding to business capabilities. A business capability is a concept from business architecture modeling. It is something that a business     does in order to generate value. A business capability often corresponds to a business object, e.g.
      * Order Management is responsible for orders
      * Customer Management is responsible for customers
      * Business capabilities are often organized into a multi-level hierarchy. For example, an enterprise application might have top-level categories such as 
Product/Service development, Product/Service delivery, Demand generation, etc.

  ### Examples
    The business capabilities of an online store include:
      * Product catalog management
      * Inventory management
      * Order management
      * Delivery management

  The corresponding microservice architecture would have services corresponding to each of these capabilities.
 
  ![image](https://user-images.githubusercontent.com/51394570/139199844-c6419314-5eeb-4b51-8341-dd800dc5a6f6.png) 
</details>

## Decomposition
<details>
  <summary>Click here to expand</summary>

  
</details>

## Decomposition
<details>
  <summary>Click here to expand</summary>

  
</details>

## Decomposition
<details>
  <summary>Click here to expand</summary>

  
</details>
