# Feeds

The **Feeds module** in Lidia PIM enables businesses to **distribute product data** to **third-party platforms** by creating **customizable data feeds**. Feeds act as a **bridge** between the PIM system and external systems such as **marketplaces, e-commerce platforms, ERP systems, and marketing tools**.

***

### **Feed Management Overview**

The **Feeds page** provides a centralized interface where users can:

* **Create, edit, and delete feeds** for external integrations.
* **View active and inactive feeds** along with their details.
* **Define feed URLs** for seamless data synchronization.
* **Monitor product counts associated with each feed.**

Each feed contains:\
**Feed Name** – The identifier for the feed.\
**URL** – The endpoint where the data is made available.\
**Format** – The data structure (e.g., JSON, XML).\
**Feed Code** – A unique code for the feed.\
**Product Count** – The number of products included in the feed.\
**Status** – Indicates whether the feed is active or inactive.

Users can add **new feeds** by clicking on the **"Add New Feed"** button

***

### **Feed Configuration & Customization**

When creating or editing a feed, users can define several key parameters:

#### **Basic Information**

* **Feed Status:** Set the feed as **Active or Inactive**.
* **Feed Code:** A unique identifier for the feed.
* **Feed Format:** The data format used for integration (e.g., JSON, XML).
* **Access Control:** Manage authorization and access settings for the feed.
* **Feed URL:** The endpoint for retrieving product data.

### **Filtering Data for Feeds**

Lidia PIM allows users to **customize the product data included in each feed** using **filtering options**. This ensures that **only relevant products** are exported to third-party systems.

#### **Available Filters:**

* **Categories:** Include only products from specific categories.
* **Brands:** Restrict the feed to selected brands.
* **Special Lists:** Add products from pre-defined custom lists.
* **Product Properties:** Include products with specific attributes (e.g., "Material: 100% Leather").
* **Variant Properties:** Define feeds based on product variations.
* **Option Values:** Filter products by options like **color, size, or configuration**.
* **Tags:** Select only products with specific labels or tags.

Negative filters can also be applied to **exclude** certain products from the feed.

***

### **Data Package & Collections**

The **Data Package** defines the **extent of product data** included in the feed. Users can:

* Choose **which collections** should be part of the feed.
* Include **category dimensions** to enhance product classification.

#### **How Feed Data is Generated:**

1. **The system applies the selected filters** to retrieve relevant product data.
2. **Products are enriched with their properties, options, and tags** unless they are excluded by filters.
3. **If collections are included, the system adds extra product attributes** based on the defined collections.

***

### **Authorization & Data Access**

Feeds in Lidia PIM can be protected using **access keys**, ensuring that **only authorized systems** can access the product data. Users can:

* **Generate new authorization keys** for secure data sharing.
* **Restrict access** to prevent unauthorized use.
