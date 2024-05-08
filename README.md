# Ecommerce Application - Kubernetes Deployment

### Features
This repo contains all the config files to deploy the ecomm app into a kubernetes cluster. Ensure to apply the configs in following order. Also config, eureka and gateway server should be fully started before starting the other microservices.
* ecomm-config-server.yml
* ecomm-eureka-server.yml
* ecomm-gateway-server.yml
* ecomm-customer.yml
* ecomm-product-catalogue.yml
* ecomm-inventory.yml
* ecomm-order-processing.yml
* ecomm-payment.yml
