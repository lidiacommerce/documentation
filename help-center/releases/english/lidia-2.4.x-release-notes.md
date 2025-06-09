---
description: >-
  Discover the latest updates and improvements introduced this month, enhancing
  the functionality and user experience across the Lidia platform.
cover: ../../../.gitbook/assets/3 (3).png
coverY: 0
---

# Lidia 2.4.x release notes

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

## <mark style="color:purple;">Releases in 2.4</mark>

### New Features

### 🎯 Logistics Management Enhancements

#### **Improved Ability to Create and Cancel Deliveries Based on Quantity** **Release date :**  08/04/2025 **Version number :** <mark style="color:purple;">LMC-2.4.1.1</mark>

Although quantity-based breakdown was functionally possible while creating deliveries, there were experience-related shortcomings on Lidia Merchant Console. With this improvement, the experience of managing delivery creation and cancellation processes based on quantity has been enhanced to allow more flexible control. Within this scope:

* It has become possible to create partial deliveries for products within an order.
* Products can also be cancelled based on quantity. The cancellation reason and explanation fields are mandatory and recorded.\
  This improvement aims to enable more effective shipment planning, especially in high-volume and multi-product orders.,

With this improvement, scenarios requiring manual intervention have been reduced and flexibility in delivery process control has been increased.



### 🎯 Order Management Enhancements

#### **Removal of installment interest information** **Release date :** 08/04/2025 **Version number :** <mark style="color:purple;">LMC-2.4.1.2</mark>

The installment interest information, which appeared in the order details but was not used in operational processes, has been removed from the order account summary section due to causing confusion for users and not contributing to workflow.

\


### 🎯 Goal Management Enhancements

#### **Ability to select target time and date range** **Release date :** 15/04/2025 **Version number :** <mark style="color:purple;">LC-2.4.1.5</mark>

In the goal definition process, it was previously only possible to select by day, without the ability to define precise time ranges. With this improvement, users can now set goals based on both time and date ranges, enabling more precise and time-sensitive performance tracking.





### Improvements

### 💡 Order Management Improvements

#### Making it easier to track different deliveries within the same order **Release date :** 08/04/2025 **Version number :** <mark style="color:purple;">LMC-2.4.1.3 - LC-2.4.1.6</mark>

In scenarios where multiple deliveries can be created for a single order, tracking these deliveries could become complex for users. With this improvement, interface and experience updates have been made to enable easier tracking of different deliveries within the same order. With this improvement, users who access the order detail screen can view other deliveries belonging to the same order in grouped format, easily see each delivery’s summary (such as date, status, quantity), and be quickly redirected to the relevant delivery detail to manage the process more efficiently.



### 💡 User Management Improvements

#### **Adding breadcrumbs navigation to all pages** **Release date :** 08/04/2025 **Version number :** <mark style="color:purple;">LC-2.4.1.1</mark>

To allow users to see the hierarchical location of the page they are on more clearly and to navigate the platform more easily, a breadcrumbs navigation structure has been added to all pages.



### 💡 Catalog Management Improvements

#### **Adjusting validation screens for errors when adding products to private list** **Release date :** 08/04/2025 **Version number :** <mark style="color:purple;">LC-2.4.1.2</mark>

During the process of adding products to a private list, the error messages and validation screens encountered by users were negatively affecting the user experience due to lacking sufficient information. With this improvement, errors that occur during private list operations can now be displayed more clearly with titles and descriptions.



### 💡 Catalog Management Improvements

#### **Adjusting validation screens for errors when adding products to private list** **Release date :** 08/04/2025 **Version number :** <mark style="color:purple;">LC-2.4.1.2</mark>

During the process of adding products to a private list, the error messages and validation screens encountered by users were negatively affecting the user experience due to lacking sufficient information. With this improvement, errors that occur during private list operations can now be displayed more clearly with titles and descriptions.



### 💡 Case Management Improvements

#### **Controlling the experience of creating returns based on quantity for multiple delivered products** **Release date :** 15/04/2025 **Version number :** <mark style="color:purple;">LC-2.4.1.3</mark>

In orders containing multiple delivered products, users were encountering errors in quantity selection during the return creation process. With this improvement, users can more clearly see how many units of which product they are returning and create the return through an error-free process guided by the system.



**Improving the experience of return approval and rejection**\
**Release Date:** 15/04/2025\
**Release Number:** <mark style="color:purple;">LC-2.4.1.4</mark>

Lack of guidance encountered by users during the approval or rejection of return requests was making it difficult to understand the process steps. With this improvement, interface and experience updates have been made for the approval and rejection steps of the return process.







{% hint style="info" %}
### Bug Fixes

* Missing cargo tracking codes in deliveries
* Display errors for cancelled orders in the Merchant Console
{% endhint %}



These updates are designed to enhance both the functionality and usability of Lidia Platform, ensuring a smoother and more efficient experience for all users. Stay tuned for further improvements next month!

\
\
