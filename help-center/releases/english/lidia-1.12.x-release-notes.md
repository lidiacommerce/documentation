---
description: >-
  Discover the latest updates and improvements introduced this month, enhancing
  the functionality and user experience across the Lidia platform.
cover: ../../../.gitbook/assets/September (2).png
coverY: 0
---

# December

## 💡 **December Release Notes**

This month's release covers significant updates to various components of the Lidia platform, including the Console, Merchant Console, and Product Information Management (PIM) systems. These improvements aim to optimize workflows and provide a smoother user experience for all platform users.

{% hint style="info" %}
🔎 **About Release Codes**\
In this document, you'll find release codes for different components of the Lidia platform:

* **LC**: Lidia Console - Enhancements and fixes related to the core management console.
* **LMC**: Lidia Merchant Console - Updates specific to the merchant's tools and workflows.
* **LP**: Lidia PIM (Product Information Management) - Improvements and new features related to product data management.

These codes help you track the specific areas of improvement across the platform.
{% endhint %}

***

### 🚀 Bug Fixes and Functional Improvements

* <mark style="color:blue;">**LC-122401-06-**</mark>Fixed an issue with viewing proof-of-residence documents for vendor applications.
* <mark style="color:blue;">**LC-122401-07-**</mark>Resolved date-based filtering and export issues in operations reports.
* <mark style="color:blue;">**LC-122401-08-**</mark>Fixed the sample Excel download error for bulk item addition in custom lists.
* <mark style="color:blue;">**LC-122401-09-**</mark>Addressed missing data in the user list view.
* <mark style="color:blue;">**LC-122401-10-**</mark>Resolved data-saving errors in the Page M anagement details.
* <mark style="color:blue;">**LC-122401-11-**</mark>Fixed display issues in the Coupons tab on the Customer Details page.
* <mark style="color:blue;">**LMC-122401-01-**</mark>Addressed errors in the Request Management page when filtering by process type (Cancel/Return).
* <mark style="color:blue;">**LMC-122401-02-**</mark>Fixed an issue where authorized store users were not visible.
* <mark style="color:blue;">**LC-122402-05-**</mark>Resolved request date inconsistencies in the Request Details page.
* <mark style="color:blue;">**LC-122402-06-**</mark>Fixed navigation issues on Customer Management detail pages.
* <mark style="color:blue;">**LC-122402-07-**</mark>Addressed errors in optional content validation for bulk document uploads.
* <mark style="color:blue;">**LC-122402-08-**</mark>Fixed broken search functionality in the Features and Options listing pages.



***

### 🚚 Delivery Management Enhancements

* <mark style="color:blue;">**LC-122401-01-**</mark>**Delivery Page Search Experience Enhancements**\
  Issues with inconsistent search results when using the "All Fields" filter on the Delivery page have been resolved. This update improves the search functionality within the "All Fields" filter, enabling faster and more accurate access to the desired information.
* <mark style="color:blue;">**LMC-122401-01-**</mark>**Delivery Splitting for Multi-Product Orders**\
  Improvements have been made to address issues in the delivery creation process for multi-product orders in the Merchant Console:
  * Fixed an issue where products with updated volumetric weight or kilograms would disappear from the delivery modal. Now, updated deliveries can be assigned to multiple shipping companies simultaneously.
  * Products are automatically split into suitable deliveries based on the updated volumetric weight and are fully visible in the modal.
  * Note: Merged deliveries cannot be supported after splitting based on updated weights. Users are advised to contact administrators for assistance in case of errors.

***

### **🖊️ User Experience Enhancements**

* <mark style="color:blue;">**LC-122402-02-**</mark>**Text and Button Redesigns for Better User Experience**\
  Guidance texts, action buttons, and headers on various screens have been updated for clarity and consistency. Temporary or unclear messages have been replaced with permanent and user-friendly content, ensuring that users can follow the steps easily and intuitively.

***

### 🛒 Vendor Management Improvements

* <mark style="color:blue;">**LC-122402-04-**</mark>**Merchant Tagging Feature**\
  A tagging feature has been added to the merchant detail page, allowing merchants to define custom tags for catalogs, brands, and variants. This improvement enables better categorization and management. The tagging field supports free-text input as organization-level tags are not yet implemented.
* <mark style="color:blue;">**LC-122402-01-**</mark>**Merchant City and District Search Enhancements**\
  Previously, the "City" and "District" fields in the merchant details page only allowed district-based searches. This update introduces city-based search functionality, enabling users to search by both city and district for improved usability.
*

    ***

### 💳 Payment Management Enhancements

* <mark style="color:blue;">**LC-122401-02-**</mark>**Payment Options Import Error Notification**\
  Previously, when attempting to upload an Excel file with incorrect formatting to the payment options section, no error messages were displayed. With this enhancement, clear and detailed error notifications are now provided when invalid files are uploaded, making it easier to understand the issue, select the correct file format, and complete the process without interruptions.
* <mark style="color:blue;">**LC-122401-04-**</mark>**Payment Options Status Consistency Enhancements**\
  Exported Excel files for payment options now have their "Status" values aligned with the system's (console's) status options. This update ensures consistency between the exported data and the system's settings.

***

### 📑 Invoice Management

* <mark style="color:blue;">**LC-122402-03-**</mark>**Invoice Visibility Across All Statuses**\
  Invoices uploaded via the vendor panel would previously disappear from the admin panel when the order status changed to "Completed." With this improvement, invoices are now always visible in the admin panel's invoice section, regardless of the order status (e.g., Delivered, Completed, etc.).

***

### 📁 Catalog Mangement Enchancements

* <mark style="color:blue;">**LC-122401-03-**</mark>**Category List and Search Consistency Fixes**\
  Discrepancies in the category tree structure when searching versus not searching have been addressed. Issues, particularly those related to dimension filters, have been fixed, ensuring a consistent category structure in both scenarios.

## PIM

### **🌍 Multilingual and Multi-Currency Management**

* <mark style="color:blue;">**LP-122401-01-**</mark>**Multilingual and Multi-Currency Enhancements**
  * **Language Support**: The system now supports 53 languages, enabling content management and use across diverse linguistic regions.
  * **Currency Support**: With the addition of 50 currencies, pricing and other financial operations now cater to a broader range of users, providing enhanced compatibility for global markets.

***

### **📊 Dashboard and Interface Enhancements**

* <mark style="color:blue;">**LP-122401-02-**</mark>**New Dashboard and Homepage View**\
  The dashboard has been redesigned to better reflect the capabilities of the PIM system. Key updates include:
  * Enhanced insights into data quality, product status, categories, product families, workflows, and channels.
  * A modernized layout for improved usability and functionality.
* <mark style="color:blue;">**LP-122401-03-**</mark>**Action Button Consistency**\
  Previously, action buttons suffered from color inconsistencies and lack of standardization. Updates have been made to:
  * Standardize button appearances for a cohesive visual and functional experience.
  * Improve interaction clarity, making screens more intuitive and user-friendly.
* <mark style="color:blue;">**LP-122401-04-**</mark>**Services and Flows Page Enhancements**\
  The Services and Flows page, which had an outdated design, has been revamped for a more modern, clear, and functional user experience.

***

These updates are designed to enhance both the functionality and usability of Lidia Platform, ensuring a smoother and more efficient experience for all users. Stay tuned for further improvements next month!

\
\
