# Quick Start Guide

## Introduction

Lidia Product Information Management (PIM) software is used by companies to collect, organize, and process product information, including product descriptions, features, technical specifications, images, videos, pricing, and product documents.

Here is a summary of how the PIM software operates within an organization:

* Any modifications made to an existing product by the relevant team in the organization are added to the central PIM system.
* The central PIM system updates or overwrites unlocked product data and makes it accessible to all teams.
* The product management team reviews these changes, adjusts the product price based on the modifications, and the PIM system automatically updates the price across all distribution channels.
* The product team can access updated information without concerns about accuracy and update product descriptions. The PIM system then synchronizes these updates across all distribution channels.

The core features of Lidia PIM typically include:

* Centralized product information storage
* Integration with various systems such as e-commerce platforms, marketplaces, SAP, and ERPs
* Data enrichment and validation workflows
* Collaboration and approval workflows
* Data management and quality rules
* Product categorization management
* Product variant management
* Multi-language and multi-channel support
* Analytics and reporting capabilities

## Getting Started

To begin, visit [https://pim.lidiacommerce.com/](https://pim.lidiacommerce.com/). You will be greeted by the login screen, where you can log in using your assigned email and password.

Once logged in, you will be redirected to the homepage.

### Homepage

<figure><img src="../../.gitbook/assets/dev-pim.lidiacommerce.com_ (2).png" alt=""><figcaption><p>Dashboard</p></figcaption></figure>

## Bulk Product Addition

Before adding products, you must define options and option values. Navigate to **Configuration > Catalog > Option Management > Options** and add necessary options such as size and color.

When adding a product, first ensure that the product category and brand are assigned. You can view, edit, and add brands under **Catalog > Brands**.

To add a product brand: **Catalog > Brands > Add New Brand** or use a previously added brand.

Adding a category is another crucial step. You can either use an existing category or add a new one. To view categories: **Catalog > Categories** To add a new category: **Catalog > Categories > Add Category**

Each category must be linked to a data schema. For example, a computer or mobile phone should be linked to the "Electronics" category. To add a new data schema: **Configuration > Catalog > Data Schemas** Once the schema is created, add fields by clicking **New Field**, entering the field name, and filling in the required details.

After completing these steps, navigate to **Catalog > Products** to view and manage existing products. To add a new product: **Catalog > Products > Add New Product**

Another method to add products is through pools:

1. Go to **Services > Pools** and open the relevant pool.
2. Click **Edit**.
3. Click **Import Data** to upload an Excel file.
4. Download the template schema and fill in the product data.
5. Ensure required fields like size, color, category, and brand are pre-defined in the system.
6. Upload the completed Excel file and verify the data before approval.

## Media Management

Media management is accessible via **Media** in the left menu, where you can manage images, videos, and documents. In the **Images** section, you can add, rename, delete, and view image details. When uploading products, image names must match the image code. The **Media > Documents** section allows you to manage all documents.

## Publishing a Pool

To publish a pool:

1. Go to **Services > Pools > Edit**.
2. Select the products to be published using one of two methods:
   * Hold **Ctrl** and select the desired products.
   * Set the product status to **1** in the Excel file (all products marked as **1** will be published).
3. Click **Publish Pool** to complete the process.

## Verifying Published Pools

To verify published pools, navigate to **Catalog > Products** and check the status of the selected products.

## Exporting Product Data

Product data can be exported to external stakeholders without requiring technical assistance (**Product Publication**). Using Lidia PIM, channels can be created to supply product data, and data feeds can be established for these channels. Filters can be applied to determine which products are included in the feed, and the data format (included/excluded fields) can be customized before export.
