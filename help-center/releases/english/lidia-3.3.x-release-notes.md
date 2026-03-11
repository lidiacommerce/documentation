---
description: >-
  Discover the latest updates and improvements introduced this month, enhancing
  the functionality and user experience across the Lidia platform.
cover: ../../../.gitbook/assets/2 (8).png
coverY: 0
---

# Lidia 3.3.x release notes

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

## <mark style="color:purple;">Releases in 3.3</mark>

### New Features



### 🎯 **Product Variant Management Enhancements**

#### **Variant Relationship Update Capability** Release Date: 11/03/2026 Version Numbe&#x72;**:** <mark style="color:purple;">LP-3.3.1</mark>

With this development, variant relationships of published products in Lidia PIM can now be managed more flexibly.

The Group Code / Product Code field, which previously could not be modified, is now editable through the variant detail page. This allows variants that were incorrectly associated with a product group to be repositioned under the correct product. With this capability, incorrect variant associations can now be managed directly by users within PIM.

### 🎯 **Data Synchronization Enhancements**

#### **Addition of the “Feed Pool with Data” Action** Release Date: 11/03/2026 Version Number: <mark style="color:purple;">LP-3.3.2</mark>

With this development, the “Feed Pool with Data” action has been introduced to ensure that updates made on the variant detail remain synchronized with the product pool.

Through this action, changes made on variant or product details can be reflected to the product pool under user control, ensuring consistent management between pool data and live product data.





### Improvements

### 💡 Pool Management Improvements

#### **Improvement of the Pool Publishing Validation Experience** **Release Date:** 11/03/2026 **Version Number:** <mark style="color:purple;">LP-3.3.2</mark>

With this development, the product publishing process on the Lidia PIM pool screen has been made more transparent and user-guided.

Before the publishing process starts, the system now runs an automatic validation and clearly displays the number of publishable and non-publishable products to the user. For products that cannot be published, reason-based explanations are provided, and users are given options to proceed with full publishing, partial publishing, or complete missing information and try again.

With this improvement, users can quickly identify publishing issues and manage the publishing process without interrupting operational workflows.



***

{% hint style="info" %}
### Bug Fixes

* Various bugs have been fixed for Lidia PIM and Lidia Merchant Console stabilization caused by Core conversion.
{% endhint %}

These updates are designed to enhance both the functionality and usability of Lidia Platform, ensuring a smoother and more efficient experience for all users. Stay tuned for further improvements next month!
