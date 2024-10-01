---
description: >-
  Provides tools for administrators to control and configure system-wide
  settings and operations.
---

# Lidia Commander

## **Overview**

[Lidia Commander](https://dev.lidiacommerce.com/#c2bd95b5-26fe-4a7e-930f-6af81dd306cc) is a critical microservice within the Lidia Commerce Engine, designed to orchestrate and automate business processes across the platform. It acts as a central controller for workflows, tasks, and system events, enabling businesses to streamline their operations and ensure that various components of the platform work together seamlessly. Lidia Commander is essential for handling complex workflows, integrating different services, and ensuring that tasks are executed in the right sequence and on time.

{% hint style="info" %}
To learn more about how to register and create your applications, please follow the[ link](https://dev.lidiacommerce.com/#c2bd95b5-26fe-4a7e-930f-6af81dd306cc).
{% endhint %}

## Example

An online retailer using Lidia Commander might have a complex order fulfillment workflow that includes multiple steps:

* After a customer places an order, Lidia Commander triggers the following tasks:
  1. Verifies product availability with the [**Lidia Inventory**](https://dev.lidiacommerce.com/#a4531581-d17e-40db-b2a6-063b7d154202) service.
  2. Processes the payment through the **Lidia Payment** service.
  3. If payment is successful, triggers [**Lidia Delivery**](https://dev.lidiacommerce.com/#44584ab4-5c93-4d03-aa44-6ab7382e6965) to handle shipping and logistics.
  4. Sends an order confirmation email to the customer via [**Lidia Notification**](https://dev.lidiacommerce.com/#3487a081-296c-4620-86df-2de3e030994a).
* If the payment fails, Lidia Commander will retry the payment process or notify the customer to update their payment details.
* Throughout the process, Lidia Commander monitors each step, ensuring that the tasks are executed in the correct sequence and within the expected time frame.

If an error occurs at any point (e.g., the product is out of stock), Lidia Commander can trigger a fallback workflow that notifies the customer and suggests alternatives or backorders.

## Summary

Lidia Commander is the backbone of workflow automation and task orchestration within the Lidia Commerce Engine. It ensures that complex processes are executed smoothly, integrates with other systems, and provides real-time monitoring, making it indispensable for businesses looking to automate and optimize their digital commerce operations.
