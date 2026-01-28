---
description: >-
  Discover the latest updates and improvements introduced this month, enhancing
  the functionality and user experience across the Lidia platform.
cover: ../../../../.gitbook/assets/4 (3).png
coverY: 0
---

# Lidia 2.5.x release notes

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

***

## <mark style="color:purple;">Releases in 2.5</mark>

### New Features

### 🎯 Coupon Management Enhancements

#### **Defining coupons associated with multiple categories** **Release Date:** 05/05/2025 **Release Number:** <mark style="color:purple;">LC-2.5.1.1</mark>

Previously, coupons could only be linked to a single category. With this improvement, a coupon can now be defined for multiple categories simultaneously. This enhancement allows campaign setups to be more flexible and enables a single coupon to be valid for products across different categories.<br>



### 🎯 Finance Management Enhancements

#### Calculation and display of seller-based settlements **Release date :** 05/05/2025 **Version number :** <mark style="color:purple;">LC-2.5.1.2</mark>

Initially, templates were created to calculate settlements based on each seller’s selected due date and payment terms, and cross-team communication ensured that the breakdowns included in the settlement were calculated accurately. With this improvement, settlements calculated individually for each seller can now be viewed directly under the seller detail page in the console. Settlement documents include detailed breakdowns and amounts for both deductions and earnings.

<br>

### 🎯 Logistics Management Enhancements

#### **Hepsijet and HepsiXL – Service provider integration** **Release date :** 05/05/2025 **Version number :** <mark style="color:purple;">LC-2.5.1.3</mark>

Although Hepsijet and HepsiXL integrations were already available among Lidia’s logistics providers, they were not up to date. With this improvement, both integrations have been updated to their latest versions and orders can now be automatically transmitted. This allows e-commerce managers to add Hepsijet and HepsiXL to their delivery profiles and enable their sellers to use these integrated carriers as part of their marketplace shipping agreements.



**Adding package type information to MNG integration**\
**Release Date:** 05/05/2025\
**Release Number:** <mark style="color:purple;">LCE-2.5.1.1</mark>

In the MNG Cargo integration, package type information has been added to improve the accuracy of shipping and delivery processes. The development was carried out in line with the updated integration documents provided by MNG Cargo.



### 🎯 Reporting Management Enhancements

#### **Establishing audit log structure in microservices and improving audit reports** **Release date :** 05/05/2025 **Version number :** <mark style="color:purple;">LC-2.5.1.4 – LCE-2.5.1.2</mark>

To improve the traceability of operations performed within the microservice architecture, enhancements were made to the existing audit log structure. With this improvement, all actions carried out within the organization microservice are now logged, and these logs can be accessed via the audit reports section in Lidia Console by users with authorized roles.



### 🎯 Product Management Enhancements

#### **Development of product detail pages** **Release date :** 05/05/2025 **Version number :** <mark style="color:purple;">LMC-2.5.1.1</mark>

Although products could be viewed in a detailed list format within Lidia Merchant Console, individual product detail pages did not exist. With this improvement, each product now has a dedicated detail page where information such as sales, inventory, variants, and media can be accessed through a unified product view.





### 🎯 Case Management Enhancements

#### Ability to Renew Return Codes **Release date :** 05/05/2025 **Version number :** <mark style="color:purple;">LC-2.5.1.5</mark>

Previously, once a return barcode was generated, no new code could be obtained if the validity period expired. This situation made it difficult to manage the process in cases where customers could not deliver the return within the given timeframe. With this enhancement, administrators can now generate a new return code from the request detail screen once the validity period of the initial code has expired. In this way, if a customer fails to complete the return delivery on time, the administrator can create a new code upon request and resend it to the customer. This improvement both enhances the customer experience and provides greater flexibility in the return process.





{% hint style="info" %}
### Bug Fixes

* \-
{% endhint %}



These updates are designed to enhance both the functionality and usability of Lidia Platform, ensuring a smoother and more efficient experience for all users. Stay tuned for further improvements next month!

\
<br>
