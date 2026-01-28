---
description: >-
  Discover the latest updates and improvements introduced this month, enhancing
  the functionality and user experience across the Lidia platform.
cover: ../../../../.gitbook/assets/1 (2).png
coverY: 0
---

# Lidia 2.10.x release notes

This month's release covers significant updates to various components of the Lidia platform, including the Console, Merchant Console, and Product Information Management (PIM) systems. These improvements aim to optimize workflows and provide a smoother user experience for all platform users.

{% hint style="info" %}
🔎 **About Release Codes**\
In this document, you'll find release codes for different components of the Lidia platform:

* **LC**: Lidia Console - Enhancements and fixes related to the core management console.
* **LMC**: Lidia Merchant Console - Updates specific to the merchant's tools and workflows.
* **LP**: Lidia PIM (Product Information Management) - Improvements and new features related to product data management.
* **LCE:** Lidia Commerce Engine – Microservice improvements added to Lidia Commerce Engine

These codes help you track the specific areas of improvement across the platform.
{% endhint %}

{% hint style="info" %}
The release originally planned for September was postponed due to the Lidia Core infrastructure transition. Following the completion of the Core migration, the 2.10.x release was deployed collectively in October.
{% endhint %}

***

## <mark style="color:purple;">Releases in 2.10</mark>

### New Features

### 🎯 Catalog Management Enhancements

#### Ability to add featured filters and filter management experience improvements **Release Date:** 23/10/2025 **Release Number:** <mark style="color:purple;">LC-2.10.1</mark>

Filters and options could previously be managed through the filter management module available on category, brand, custom list, and seller detail pages. With this enhancement, the structure of the filter management tab has been redesigned with a more compact interface, and the ability to define “featured filters” has been added. Users can now easily select which filters they want to highlight through the _Featured Filters_ section using the select component. This update makes filter management more organized and enables faster access to frequently used filters.



#### Adding barcode information to product and variant details **Release Date:** 23/10/2025 **Release Number:** <mark style="color:purple;">LC-2.10.1</mark>

In previous versions, group code and barcode information were not available on product and variant detail screens, which led to incomplete data integrity.\
With this enhancement, group code and barcode fields have been added to product details, while group code and variant code fields have been added to variant details, ensuring more consistent and complete data management.



### 🎯 Platform Infrastructure Enhancements

#### Core framework transformation **Release Date:** 23/10/2025 **Release Number:** <mark style="color:purple;">LC-2.10.1</mark>

A comprehensive Core transformation has been completed to enhance the scalability of the Lidia platform, standardize the modular structure, and optimize the performance of all components.\
With this transformation, the platform’s underlying architecture has been restructured, and inter-service communication and data processing operations have been migrated to the Lidia Core infrastructure.\
The new framework enables higher processing speed, independent module deployment in the development environment, and greater flexibility in release management—laying a stronger foundation for future enhancements.



### 🎯 Media Management Enhancements

#### **Replacement of the media manager with a new application** **Release Date:** 23/10/2025 **Release Number:** <mark style="color:purple;">LC-2.10.1</mark>

The previous media manager application occasionally caused stability and performance issues.\
As part of this enhancement, the media manager has been replaced with a more modern and stable plugin, offering improved reliability and smoother file management.



### 🎯 Campaign Management Enhancements

#### Matching customer information during bulk coupon creation **Release Date:** 23/10/2025 **Release Number:** <mark style="color:purple;">LC-2.10.1</mark>

When defining bulk coupon codes via Excel, there was previously no option to match them with customer IDs, so coupons could not be assigned directly to customers. With this enhancement, a “Customer ID” column has been added to the bulk coupon definition Excel file. Users can now enter the customer ID in the Excel file to directly match coupons with the relevant customers. When the file is uploaded, the entered IDs are automatically matched with existing customer records, and the matched coupon codes appear in the list.



#### Defining payment channel as a condition in cart campaigns **Release Date:** 23/10/2025 **Release Number:** <mark style="color:purple;">LC-2.10.1</mark>

Previously, it was not possible to define rewards in purchase or cart campaigns based on the payment channel. With this enhancement, administrators can now set specific payment channels as campaign conditions and define discounts for those channels. As a result, customers can make payments with the applicable discounted amount according to their selected payment method.



### 🎯 Seller Management Enhancements

#### Centralization of seller management and support for multiple seller types **Release Date:** 23/10/2025 **Release Number:** <mark style="color:purple;">LC-2.10.1</mark>

In earlier versions, the seller registration flow in Lidia Console was designed exclusively for physical sellers. With this enhancement, the seller creation experience has been restructured—now capturing the seller catalog type during setup to dynamically configure the required information from each seller.\
Digital, hybrid (digital & physical), and physical seller types can now be registered in the system.\
Additionally, the left menu has been reorganized, separating “Applications” and “Seller List” into distinct tabs. Since seller applications can now be submitted directly via the user interface, the manual seller application flow has been deprecated.



### 🎯 Delivery Management Enhancements

#### Enrichment of delivery listing **Release Date:** 23/10/2025 **Release Number:** <mark style="color:purple;">LC-2.10.1</mark>

Previously, delivery listing pages only displayed basic order information and delivery numbers, requiring users to navigate to the delivery detail page to view detailed data. With this enhancement, the delivery listing view has been expanded to display product information, tracking numbers, sender and recipient details, delivery dates, and shipment profile directly within the list. Additionally, the newly added “Quick View” button allows users to open detailed delivery information in a drawer view or navigate to the full detail page if needed.



### Improvements

### 💡 Security **Enhancements**

#### Removal of “Remember me” option and update of password policies **Release date :** 12/08/2025 **Version number :** <mark style="color:purple;">LC-2.8.1.6</mark>

As part of this enhancement, the “Remember me” button has been removed to strengthen account security, and new password policies have been introduced across the platform. Passwords must now be at least 11 characters long, include at least one uppercase letter, one lowercase letter, one number, and one special character. Passwords are required to be changed periodically by default every 60 days, a duration that can be configured by the system administrator. Reuse of the last five passwords is restricted, and after three unsuccessful login attempts, the account is locked for 15 minutes.



#### Migration of all pages to the new listing interface **Release date :** 12/08/2025 **Version number :** <mark style="color:purple;">LC-2.8.1.6</mark>

This enhancement migrates all pages across the platform to the new listing interface.



{% hint style="info" %}
### Bug Fixes

* Various bugs have been fixed for Console stabilization caused by Core conversion.
{% endhint %}



These updates are designed to enhance both the functionality and usability of Lidia Platform, ensuring a smoother and more efficient experience for all users. Stay tuned for further improvements next month!

\
<br>
