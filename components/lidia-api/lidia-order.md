---
description: Manages cart, orders, deliveries and claims (cancellation, return).
---

# Lidia Order

## Overview

[**Lidia Order**](https://dev.lidiacommerce.com/#79ba0e4b-5257-47eb-9f06-24ee52efbdfd) manages orders across your commerce platform, handling everything from creation to fulfillment. It ensures that customer orders are processed efficiently and accurately, providing a smooth purchasing experience. Details about these concepts are provided below.

{% hint style="info" %}
You can find a sample implementation of the scenario below here.
{% endhint %}

## Quick Example

* You create an order structure within the **Lidia Commerce Platform Administration Interface**.
* You define order stages like "Pending," "Processing," and "Shipped."
* You use the [**Lidia Order**](https://dev.lidiacommerce.com/#79ba0e4b-5257-47eb-9f06-24ee52efbdfd) **API** to create and update orders based on customer actions and inventory availability.
* As customers place orders, the **Lidia Order Service** ensures that the order is processed and tracked through each stage until fulfillment.

## Concepts

### **Order Lifecycle**

The order lifecycle consists of various stages, such as creation, payment confirmation, fulfillment, and shipment. **Lidia Order** manages the entire process, ensuring each stage is handled smoothly and that customers are updated on the status of their orders.

### **Order Management**

**Lidia Order** provides tools to create, update, and track orders across multiple sales channels. It integrates seamlessly with other services like **Lidia Inventory** and **Lidia Delivery** to ensure orders are fulfilled based on real-time inventory and shipping data.

### **Payment and Fulfillment**

**Lidia Order** supports payment verification and connects with delivery services to ensure orders are shipped correctly. This integration allows your platform to offer a complete order management solution, from payment to the final delivery.
