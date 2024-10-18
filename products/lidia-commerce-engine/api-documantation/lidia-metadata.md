---
description: >-
  Manages product, category, trademark and list data. This is the PIM (Product
  Information Management) of the Lidia Platform.
---

# Lidia Metadata

## **Overview**

[**Lidia Metadata**](https://dev.lidiacommerce.com/#68a8a237-fcdd-4c5e-b6fd-223265f49f77) is an API-first product that exposes functions to manage and structure metadata for your digital commerce platform. Metadata helps organize information related to products, categories, and other core elements of your business. Details about these concepts are provided below.

{% hint style="info" %}
For more details about registration and creating your applications, please click the [link](https://dev.lidiacommerce.com/#68a8a237-fcdd-4c5e-b6fd-223265f49f77).
{% endhint %}

Here is a quick example of using **Lidia Metadata**:

* You create a custom metadata schema for "Data Schemas" in the Lidia Commerce Platform Administration Interface.
* You define fields like "Material," "Weight," and "Color."
* You use the **Lidia Metadata API** to assign these specifications to each product in your catalog.
* When customers browse your products, the metadata you've created helps filter, categorize, and display the relevant details.

You can find a sample implementation of the scenario above here.

## Concepts

### **Metadata Schemas**

Metadata schemas are structured sets of information that help define the attributes of products, categories, and other core entities. By using metadata, you can add detailed specifications like size, material, or region to any element in your application. Lidia Metadata allows you to create custom schemas to tailor your commerce platform's information structure to your business needs.

### **Metadata Types**

Metadata types define the categories of information that can be assigned to your products or other entities. For example, you might create metadata for product specifications, content management, or customer preferences. This allows flexibility in how information is stored and accessed throughout your application.

### **Custom Fields**

Custom fields are user-defined fields that allow you to extend the basic structure of your metadata. These fields can represent any type of data your business needs, such as technical specifications for products or custom categorizations for different regions.
