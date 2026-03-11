---
description: >-
  Discover the latest updates and improvements introduced this month, enhancing
  the functionality and user experience across the Lidia platform.
cover: ../../../.gitbook/assets/2.png
coverY: 0
---

# Lidia 3.2.x release notes

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

## <mark style="color:purple;">Releases in 3.2</mark>

### New Features



### 🎯 Platform Infrastructure Enhancements

#### Core framework transformation **Release Date:** 17/02/2026 **Release Number:** <mark style="color:purple;">LP-3.2.1</mark>

A comprehensive Core transformation has been completed to enhance the scalability of the Lidia platform, standardize the modular structure, and optimize the performance of all components.\
With this transformation, the platform’s underlying architecture has been restructured, and inter-service communication and data processing operations have been migrated to the Lidia Core infrastructure.\
Under the new architecture, Lidia PIM delivers higher processing performance, independent module deployment in development environments, and greater flexibility in version management, providing a more stable foundation for future developments.



### 🎯 Localization Enhancements

#### Addition of German language support **Release Date:** 17/02/2026 **Release Number:** <mark style="color:purple;">LP-3.2.2</mark>

With this enhancement, German (DE) language support has been added to Lidia PIM.\
The application is now available in three languages: English (EN), Turkish (TR), and German (DE).



### 🎯Product Variant Management Enhancements

#### **Variant Relationship Update Capability and Pool Synchronization** **Release Date:** 11/03/2026 **Version Number:** <mark style="color:purple;">LP-3.2.3</mark>

With this development, variant relationships of published products in Lidia PIM can now be managed more flexibly. The Group Code / Product Code field, which previously could not be modified, is now editable through the variant detail page. This enables variants that were incorrectly associated with a product group to be repositioned under the correct product.

Additionally, a “Feed Pool with Data” action has been introduced to ensure that updates made on the variant detail remain synchronized with pool data. Through this action, the changes can be reflected to the product pool in a controlled manner.



### Improvements

### 💡 Security Enhancements

#### Removal of “Remember me” option and update of password policies **Release date :** 17/02/2026 **Version number :** <mark style="color:purple;">LMC-3.2.1</mark>

As part of this enhancement, the “Remember me” button has been removed to strengthen account security, and new password policies have been introduced across the platform. Passwords must now be at least 11 characters long, include at least one uppercase letter, one lowercase letter, one number, and one special character. Passwords are required to be changed periodically by default every 60 days, a duration that can be configured by the system administrator. Reuse of the last five passwords is restricted, and after three unsuccessful login attempts, the account is locked for 15 minutes.



### 💡 Search Enhancements

#### **Addition of New Options to Invoice List Search Behavior** **Release Date:** 23/02/2026 **Release Number:** <mark style="color:purple;">LC-3.2.1</mark>

As part of this enhancement, the Invoice Center search experience has been expanded. Users can now search invoices by selecting Order ID, Delivery ID, or Return Code/ID from the field dropdown.

Search is triggered only when a valid field is selected and at least 3 characters are entered. Existing loading and empty-state behaviors continue to operate without any change within the current search flow.



### 💡 Pool Management Improvements

#### **Improvement of the Pool Publishing Validation Experience** **Release Date:** 11/03/2026 **Version Number:** <mark style="color:purple;">LP-3.2.4</mark>

With this development, the product publishing process on the Lidia PIM pool screen has been made more transparent and user-guided.

Before the publishing process starts, the system now runs an automatic validation and clearly displays the number of publishable and non-publishable products to the user. For products that cannot be published, reason-based explanations are provided, and users are given options to proceed with full publishing, partial publishing, or complete missing information and try again.

With this improvement, users can quickly identify publishing issues and manage the publishing process without interrupting operational workflows.

***

{% hint style="info" %}
### Bug Fixes

* Various bugs have been fixed for Lidia PIM and Lidia Merchant Console stabilization caused by Core conversion.
{% endhint %}



These updates are designed to enhance both the functionality and usability of Lidia Platform, ensuring a smoother and more efficient experience for all users. Stay tuned for further improvements next month!

\
<br>
