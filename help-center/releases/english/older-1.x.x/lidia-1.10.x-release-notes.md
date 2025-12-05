---
description: >-
  Discover the latest updates and improvements introduced this month, enhancing
  the functionality and user experience across the Lidia platform.
cover: ../../../../.gitbook/assets/October.png
coverY: 0
---

# Lidia 1.10.x release notes

## 💡 **October Release Notes**

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

### 🚀 **Bug Fixes and Functional Improvements**&#x20;

* <mark style="color:blue;">**LC-102402-01-**</mark>**Empty Record Improvements:** Previously, when there was no order record, the page would simply load without any indication. With this update, users are now notified when no record exists, making the page clearer.
* <mark style="color:blue;">**LC-102402-03-**</mark>**Commission Management Page Enhancements:** Previously, there were separate pages for commission rates and rules, causing confusion for users wanting to add commission rules. This update removes the old commission rate page and provides a clearer navigation.
* <mark style="color:blue;">**LMC-102401-01-**</mark>**Delivery Management Bug Fixes and Notifications:** Missing visuals and notification adjustments have been made on delivery and order pages, with corrections for listing and redirection errors.

***

### 🛍 Order Management Enhancements

* <mark style="color:blue;">**LC-102401-01-**</mark>**Order Listing View:** The order listing page has been updated to a new design, enhancing page performance and user experience.
* <mark style="color:blue;">**LC-102401-02-**</mark>**Undelivered and Returned Shipments:** In cases where a delivery cannot reach the recipient, the return process to the sender is now fully traceable in the console. When a package is returned to the sender after a failed delivery attempt, refunds to the buyer are now supported, ensuring clear tracking and updates throughout the delivery process.
* <mark style="color:blue;">**LC-102402-02-**</mark>**Cancellations with Integrated Service Providers:** Administrators were able to cancel unshipped deliveries, but the cancellation information was not communicated to marketplace-integrated service providers. Now, admins can cancel shipments that sellers are unable to fulfill directly from the order details, ensuring synchronization with service providers.
* <mark style="color:blue;">**LC-102402-06-**</mark>**Order Status Filtering Enhancements:** Draft orders were listed among regular orders, causing confusion. With this update, the "draft" status has been removed from the order status filters to improve clarity.

***

### 📑 Invoice Management

*   <mark style="color:blue;">**LC-102401-03-**</mark> **Uploaded Invoice Details:** The information for uploaded invoices in order details has been updated to include invoice type, invoice number, and order reference number, instead of relying on limited address and tax ID fields.<br>

    ***

### 📁 Catalog Mangement Enchancements

* <mark style="color:blue;">**LC-102402-04-**</mark>**New Rejection Reasons:** Console administrators can now reject products sent for approval by sellers using 11 different reasons (an addition of 4 new options). Additionally, the reason previously labeled as "incorrect category" has been updated to "category information missing/incorrect."
* <mark style="color:blue;">**LC-102402-05-**</mark>**Category Data Schema Modification Restriction Based on Pool Content:** Previously, there was no restriction on modifying the category data schema based on pool content status. Now, if no items have been added to a pool, the schema can be changed; if items are present, the schema cannot be altered.

***

### 🛒 Vendor Management Enhancements

* <mark style="color:blue;">**LMC-102402-01-**</mark>**Merchant Application Process Enhancements:** Information and navigation have been enhanced for users applying to become merchant. Required fields are now accurately marked, preventing incomplete submissions and ensuring a smooth merchant application process.

***

### PIM

### 🛠️ Bug Fixes and Functional Improvements&#x20;

* <mark style="color:blue;">**LP-102402-02-**</mark>**Product Upload Stage Review:** Product upload stages have been checked and optimized to ensure smoother processing.
* <mark style="color:blue;">**LP-102402-03-**</mark>**Visual Matching Corrections for Updated Products:** Issues with visual matching for updated products have been resolved, ensuring accurate display of images.
* <mark style="color:blue;">**LP-102402-04-**</mark>**Notification Settings Save Fix:** Problems with saving notification settings have been addressed, providing a more reliable experience.
* <mark style="color:blue;">**LP-102402-05-**</mark>**Category and Dimension Relationship Adjustments:** Listed category and dimension relationships have been adjusted for consistency and accuracy.

***

### 🔔Notification Center Improvements

* <mark style="color:blue;">**LP-102401-01-**</mark>**Notification Center v1.0 (PIM):** Notification Center pages are now active in the left menu on PIM, allowing administrators to view platform notifications. This version includes notifications for product variants, product families, attributes, options, tags, categories, brands, and custom lists, which can be managed through notification settings.

***

### 📝Listing Pages Enhancements

* <mark style="color:blue;">**LP-102402-01-**</mark>**Category Listing Enhancements:** ID search functionality has been added to category listing, enabling users to search by ID.

***

These updates are designed to enhance both the functionality and usability of Lidia Platform, ensuring a smoother and more efficient experience for all users. Stay tuned for further improvements next month!

<br>
