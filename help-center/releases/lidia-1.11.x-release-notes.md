---
description: >-
  Discover the latest updates and improvements introduced this month, enhancing
  the functionality and user experience across the Lidia platform.
cover: ../../.gitbook/assets/September (1) (1).png
coverY: 0
---

# Lidia 1.11.x release notes

## 💡 **November Release Notes**

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

* <mark style="color:blue;">**LC-112401-02-**</mark>**Menu Item Update Issue:**\
  Previously, when category page URLs were updated, menu items marked as "category" were not updated. With this enhancement, menu items now automatically reflect the updated URL when changes are made.
* <mark style="color:blue;">**LC-112402-05-**</mark>**Category Search Result Feedback:**\
  When a category search returned no results, there was no clear feedback for users. With this enhancement, users now receive a "no results found" message, providing more precise information.

***

### 🚚 Delivery Management Enhancements

* <mark style="color:blue;">**LMC-112401-01-**</mark>**Product-Level Cancellation Restrictions:**\
  Previously, multiple items in a delivery could be selected and canceled at once. With this update, bulk cancellations are restricted, preventing misuse, such as partially canceling multi-item deliveries to avoid penalties for remaining items.

***

### 🎫 Campaign & Coupon Enhancements

* <mark style="color:blue;">**LC-112402-01-**</mark>**Campaign Restriction Management Improvements:**\
  Features for defining user-based restrictions in campaigns were already available. This enhancement activates the necessary capabilities to ensure smooth enforcement of these restrictions.

***

### 🔍 Reporting & Updating Improvements

* <mark style="color:blue;">**LC-112402-02-**</mark>**Order Export Feature Added:**\
  Previously, orders displayed on the orders page could not be exported. With this update, specific or all orders, along with visible columns, can now be exported in Excel format using the button on the left side of the page.
* <mark style="color:blue;">**LC-112401-01-**</mark>**Bulk Payment Option Update:**\
  Previously, options in the payment section could only be updated individually. With this enhancement, templates can be exported, updated, and re-imported to perform bulk option updates.
* <mark style="color:blue;">**LC-112402-03-**</mark>**Bulk Update Validation Capabilities:**\
  To prevent errors during bulk updates in the payment section, validation capabilities have been added. With this update, incomplete or erroneous data in imported templates is identified, and users receive feedback, ensuring more accurate and efficient updates.

***

### 🔍 Search Bar Improvements

* <mark style="color:blue;">LMC-112402-01-</mark>Activation of General Search Bar:\
  The search bar in the Merchant Console was inactive, and no searches could be performed. With this improvement, the search bar now allows searches for pools, products, and variants.

***

### 🛒 Vendor Management Improvements

* <mark style="color:blue;">**LC-112401-03-**</mark>**Default Settings for Newly Added Merchants:**\
  When new merchants were added in the "Organizations" section, only basic and entitlement information was mandatory, and inventory settings like "Can select category" and "Can add product" were not enabled by default. As a result, sellers couldn't access product upload steps in their panels. This update ensures these settings are enabled by default, while admins retain the ability to modify them.
* <mark style="color:blue;">**LC-112402-04-**</mark>**Display of Store Warehouse Information in Organization Details:**\
  Previously, store warehouse information was not visible in merchant details. With this improvement, warehouse information is now displayed in a read-only format in the relevant merchant details section.

***

### 📁 Catalog Management Enhancements

* <mark style="color:blue;">**LC-112402-06-**</mark>**Prevention of Timeout Issues in Product Pools:**\
  While publishing 250 products, a timeout error occurred due to delayed system responses, even though products were successfully published. With this enhancement, timeout errors have been prevented, ensuring smooth publication without errors appearing in the console.

***

### 🔐 Authorization Enhancements

* <mark style="color:blue;">**\[LC-112402-07, LMC-112402-02, LP-112402-02-]**</mark>**Lidia User Password and Session Security:**\
  Minimum requirements for passwords in Lidia Console, Lidia Merchant Console and Lidia PIM have been established, including a minimum length, uppercase and lowercase letters, numbers, and special characters. Additionally, account lockout and retry delay durations have been introduced to enhance security. Password policy settings can now only be configured by authorized users and support multi-tenant, multi-application environments, allowing centralized management across all Lidia products. Default settings enforce a password update every 90 days, with application-specific overrides available.
* <mark style="color:blue;">**LP-112401-01-**</mark>**User Invitation Process Improvements:**\
  Previously, PIM administrators manually set passwords for new users (excluding guest roles) and shared them for system login. With this enhancement, the password creation step is removed from user addition modals, and secure system-generated passwords and login directions are now sent directly to users' email addresses. This improves security and simplifies the login process.
* <mark style="color:blue;">**LP-112402-01-**</mark>**Resending Invitation Emails:**\
  Previously, invited users only received an initial invitation email. With this improvement, invitation emails can be resent via the button in user details, ensuring seamless follow-up in cases where the email was missed.
* <mark style="color:blue;">**LP-112402-03-**</mark>**Password Update Reminder and Email Notification:**\
  After logging in with the system-generated password, non-guest users are reminded via a pop-up to update their password within 7 days. Once successfully updated, users receive an email confirming the password change with a "Password successfully updated" message.

***

These updates are designed to enhance both the functionality and usability of Lidia Platform, ensuring a smoother and more efficient experience for all users. Stay tuned for further improvements next month!

\
\
