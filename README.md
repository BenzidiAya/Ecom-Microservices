<h1>MicroService Architecture</h1>
<img src="images/arc.png">
<p>Microservice architecture is a design approach where a complex application is decomposed into smaller, independent services that can be developed, deployed, and scaled independently. Each microservice focuses on a specific business capability and communicates with other services through well-defined APIs. This architectural style offers several advantages, including scalability, flexibility, and ease of maintenance. </p>
<h1>Ecom-App Project</h1>
<img src="images/prjEcom.png">
<p>The project aims to create a scalable, modular, and efficient system for comprehensive business management. Each microservice focuses on specific functionalities, and the use of advanced tools such as Spring Cloud Gateway, Eureka Discovery Service, and OpenFeign ensures a robust and streamlined implementation.</p>
<h5> Here's a breakdown of the project:</h5>

<h4>Customer Microservice (customer-service):<h4>

<p>The creation of a dedicated microservice to manage customer information. This includes functionalities for adding new customers, updating details, and retrieving customer data.</p>
<h4>Inventory Microservice (inventory-service):</h4>

<p>The development of a specialized microservice responsible for handling product inventory. This service allows for effective cataloging, updating, and retrieval of product information.</p>
<h4>Spring Cloud Gateway:</h4>

<p>Implementation of a Spring Cloud Gateway, serving as the central API Gateway. This gateway efficiently manages the routing of requests, directing them to the appropriate microservices based on predefined rules.</p>
<h4>Static Configuration of Routing System:</h4>

<p>Static configuration of the routing system within the Spring Cloud Gateway. This involves defining how requests are directed between the microservices, ensuring optimal flow and performance.<p>
<h4>Eureka Discovery Service:</h4>

<p>Creation of an Eureka Discovery Service to act as a service registry. Eureka enables dynamic registration and discovery of microservices within the system, facilitating seamless communication.</p>
<h4>Dynamic Configuration of Gateway Routes:</h4>

<p>Enhancement of the Spring Cloud Gateway to support dynamic route configuration. This enables adaptability to changes in the system and allows for efficient routing adjustments without the need for manual intervention.</p>
<h4>Billing Management Microservice (billing-service) using OpenFeign:</h4>

<p>Development of a specialized billing management microservice integrated with OpenFeign. OpenFeign simplifies communication between microservices, providing a declarative approach for defining HTTP clients.</p>
<h4>Discovery Service : Spring Cloud Eureka Server </h4>
<img src="images/eureka-register.png">
<h4>Customer Service </h4>
<img src="images/CUSTOMERS.png">
<h4>Inventory Service </h4>
<img src="images/INVENTORY-SERVICE.png">
<h4>Billing Service </h4>
<img src="images/Billing-service.png">