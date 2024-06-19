Demo project to demonstrate how microservices interact with each other in event driven architecture.

Here, we created three microservices: order-service, stock-service, email-service.

order-service = producer
stock-service = consumer
email-service = consumer

base-domains module contains DTOs used across the microservices.