SaaS Application with Spring Boot and REST API
This project is a Java-based SaaS (Software as a Service) application that leverages Spring Boot and a REST API to manage user subscriptions. The key features and functionality of this project include:
Features

Subscription Management:

Create, read, update, and delete subscriptions
Associate subscriptions with customer information (email, name)
Validate that subscriptions use valid subscription plans


Subscription Plan Management:

Define and manage different subscription plans (name, price, description)
Ensure users can only select from available subscription plans


Email Notifications:

Send notifications to customers when their subscription is created, updated, or canceled


Invoicing and Billing:

Generate invoices for each subscription
Maintain a history of invoices for each subscription
Provide APIs to retrieve invoices by subscription


Analytics and Reporting:

Track key metrics such as total revenue, active subscriptions, and churn rate
Generate reports and visualizations for subscription data


Security and Documentation:

Implement authentication and authorization for the API
Provide comprehensive documentation using Swagger



Technology Stack

Java 11
Spring Boot
Spring Data JPA
Spring Security
Swagger
JavaMail
Thymeleaf (for email templates)
