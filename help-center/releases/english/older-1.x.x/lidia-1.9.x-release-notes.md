---
description: >-
  Discover the latest updates and improvements introduced this month, enhancing
  the functionality and user experience across the Lidia platform.
cover: ../../../../.gitbook/assets/September (1).png
coverY: 0
---

# Lidia 1.9.x release notes

## 💡 **September Highlights: New Features and Improvements**

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

* <mark style="color:blue;">LC-092401-01-</mark>**Improved Validation for Custom Lists**: Validation screens for custom lists have been enhanced, ensuring more accurate data entry and management.
* <mark style="color:blue;">LC-092401-02-</mark>**Functional Issues in Merchant Onboarding Process Resolved**: Errors encountered during the onboarding process process have been addressed to ensure a smoother experience. &#x20;
* <mark style="color:blue;">LC-092401-03-</mark>**Duplicate Menu Titles and Page Redirections Fixed**: We have fixed the issues where duplicate menu titles and incorrect page redirects were causing confusion. &#x20;
* <mark style="color:blue;">LC-092401-04-</mark>**Category Tree Cleanup**: Deleted categories no longer appear in the upper category tree, improving clarity and organization. &#x20;
* <mark style="color:blue;">LMC-092401-01-</mark>**End-to-End Delivery Provider Tests Completed:** Minor bugs identified and resolved during the process.
* <mark style="color:blue;">LC-092403-01-</mark>**Payment Error Visibility**: If a payment error occurs during an order, it will now be displayed in the order’s payment records, helping administrators quickly identify issues.

***

### 🎫 **Campaign\&Coupon Enhancements**

* <mark style="color:blue;">LC-092402-01-</mark> **Partial Cart Discount Now Fully Functional**: Previously, the discount functionality for "a portion of the cart" was not active on campaign reward pages. With this update, discounts can now be applied based on values entered in the campaign reward settings, making partial cart discounts fully operational.
* <mark style="color:blue;">LC-092402-04</mark>-**Seller-Specific Coupon Conditions**: A "seller" option has been added to coupon creation, enabling coupons to be conditioned specifically for certain sellers.

***

### 👥 **Advanced Customer Management**

* <mark style="color:blue;">LC-092402-02</mark>-**Enhanced Customer Pages**: The customer page has been revamped, allowing detailed management of customer information, including addresses, orders, payments, campaign participation, and coupon details.
* <mark style="color:blue;">LC-092402-03</mark>-**Customer Type Management**: Managing different customer types (e.g., registered customers) is now possible with the ability to filter and manage based on customer type.
* <mark style="color:blue;">LC-092403-05-</mark>**Platform Information Added**: Platform details have been added to the customer card in the order details screen, providing more comprehensive customer insights.

***

### 🚚 **Delivery Management Enhancements**

* <mark style="color:blue;">LC-092403-03-</mark>**Address Update Feature**: Console administrators can now change the delivery address for orders that haven't been shipped. Both the new and old addresses can be tracked after the update. Additionally, users on the front end will also be able to update their delivery address with this new feature.
* <mark style="color:blue;">LMC-092403-01-</mark>**Delivery Address Change Notifications:** Both administrators and buyers can update delivery addresses. After changes, the new and old addresses will be communicated to the seller.
* <mark style="color:blue;">LMC-092403-03-</mark>**Unsuccessful Deliveries Management:** The marketplace now supports tracking unsuccessful deliveries and handling returns through the Merchant Console.
* <mark style="color:blue;">**LMC-092403-04**</mark><mark style="color:blue;">-</mark> **Delivery Management Improvements**: This update includes various bug fixes and improvements to enhance the appearance and user experience of the delivery management pages.

***

### 🖼 **Media Management Enhancements**

* <mark style="color:blue;">LC-092402-06</mark>-**Document Details Added**: Users can now view detailed information for documents, similar to how they can for images. This allows for easier review and access to document links from the product or variant detail pages.
* <mark style="color:blue;">LMC-092401-02-</mark>**Bulk Media Upload Screen Enhancements:** Issues regarding incomplete notifications and functional errors have been fixed.
* <mark style="color:blue;">LC-092402-07</mark>-**Improved Error Handling**: In cases where incorrect media is uploaded, the process will no longer continue. If errors are detected, users are now offered a back option to exit the process, and if all media is removed during verification, the process resets to the first step.
* <mark style="color:blue;">LMC-092402-01-</mark>**Error Handling Improvements in Media Uploads:** If errors are detected during media uploads, the process will not continue. Users can now exit the process or return to the first step if all media is removed.
* <mark style="color:blue;">LP-092403-03-</mark>**File Format Consistency:** Media uploads now include validation to ensure that file extensions match actual file formats. Files failing this check will no longer be uploaded.

***

### 📁 Catalog Mangement Enchancements

* <mark style="color:blue;">LC-092403-04-</mark>**New Rejection Reasons**: Administrators can now select multiple rejection reasons when declining products in the product pool. Additionally, three new rejection reasons have been added:
  * Missing/incorrect color information
  * Incorrect desi information
  * Incorrect pool entry
* <mark style="color:blue;">LMC-092403-02-</mark>**Product Pool Rejection Reasons:** Console administrators can now reject products with multiple rejection reasons. Merchants can view these reasons in the product details.

***

### 📑 **Invoice Management**

* <mark style="color:blue;">LC-092403-02-</mark>**New 'Invoice Information' Section**: Administrators can now request invoice uploads directly from the order details page, review uploaded invoices, and access the invoice via a dedicated section for easier tracking and management.

***

### 📊 **Improved Left Menu Experience** <a href="#improved-left-menu-experience" id="improved-left-menu-experience"></a>

* <mark style="color:blue;">LC-092402-05</mark>-**Streamlined Reports Section**: Passive report headers have been hidden, showing only active report features to provide clearer navigation for console administrators.
* <mark style="color:blue;">LP-092402-03-</mark>**Active Page Updates:** Pages displaying option values under certain menu items are now active, allowing users to view and manage all option values.

***

### **📧 Guest\&User Account Enhancements**

* <mark style="color:blue;">LP-092401-02-</mark>**Improved Search Results:** Missing redirects and notifications on guest account search results pages have been fixed to enhance the user experience.&#x20;
* <mark style="color:blue;">LP-092403-01-</mark>**Updated Email Content:** Guest account invitation emails no longer contain the login link and have been updated to include PIM definitions and contact options.
* <mark style="color:blue;">LP-092403-02-</mark>**Access Termination Notifications:** Deleted users are now notified via email that their access has been terminated, and attempts to log in are also met with an explanation of access denial.
* <mark style="color:blue;">LP-092401-01-</mark>**Subject Line Adjustments:** Password reset emails and guest account invitation emails now feature updated subject lines.&#x20;

***

### &#x20;🔍**Filtering\&Reporting Enhancements**

* <mark style="color:blue;">LP-092402-01-</mark>**Filter Improvement:** Categories without products will no longer appear in filters, improving clarity and user experience.&#x20;
* <mark style="color:blue;">LP-092402-02-</mark>**Improved Reporting:** Summary reports for users integrating with PIM have updated column names and more detailed error explanations, allowing for better issue resolution.

***

### **📤 Advanced Product Publishing/Uploading Experiences**&#x20;

* <mark style="color:blue;">LP-092402-04-</mark>**Excel Validation Fixes:** Validation screens for product uploads via Excel have been improved to display errors correctly, ensuring smooth product uploads.
* <mark style="color:blue;">LP-092402-05-</mark>**Step-by-Step Process Improvements:** The product publishing flow now shows clearer, step-by-step updates, making the process easier to manage.

***

These updates are designed to enhance both the functionality and usability of Lidia Platform, ensuring a smoother and more efficient experience for all users. Stay tuned for further improvements next month!
