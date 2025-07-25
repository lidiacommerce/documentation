---
description: >-
  Discover the latest updates and improvements introduced this month, enhancing
  the functionality and user experience across the Lidia platform.
cover: ../../../.gitbook/assets/2 (5).png
coverY: 0
---

# Lidia 2.7.x release notes

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

## <mark style="color:purple;">Releases in 2.6</mark>

### New Features

### 🎯 Finance Management Enhancements

#### **Ability to define commission rates by payment method** **Release Date:** 26/06/2025 **Release Number:** <mark style="color:purple;">LC-2.6.1.1</mark>

Commission rates could previously be configured by criteria such as category, brand, or seller, but could not be differentiated by payment method. With this enhancement, sellers can now define distinct commission rates based on the selected payment method.



#### **Standardizing the reference code format in payout breakdowns** **Release Date:** 26/06/2025 **Release Number:** <mark style="color:purple;">LC-2.6.1.2</mark>

The reference code displayed in the payout breakdowns was previously shown in an inconsistent and hard-to-read format. With this enhancement, the reference code has been standardized to improve clarity and consistency.



### 🎯 Reporting Enhancements

#### **Adding trade name information to operational reports** **Release Date:** 26/06/2025 **Release Number:** <mark style="color:purple;">LC-2.6.1.3</mark>

Operational reports previously did not include trade name information for sellers. With this enhancement, trade names have been added to report outputs, allowing users to distinguish and analyze seller data more easily.



#### **Logging login activity as part of audit logs** **Release Date:** 26/06/2025 **Release Number:** <mark style="color:purple;">LP-2.6.1.1</mark>

Login activity in the PIM module was previously tracked in a limited capacity. With this enhancement, login events are now comprehensively recorded as part of the system’s audit log structure.



### 🎯 Logistics Management Enhancements



**Extending DHL (MNG) package-level integration to the seller app**\
**Release Date: 26/06/2025**\
**Release Number:&#x20;**<mark style="color:purple;">**LMC-2.6.1.1**</mark>\
Package-level support for the DHL (MNG) shipping provider was previously available only at the integration level. With this enhancement, the same capability has been extended to the seller application, and the provider logo has been updated accordingly.



### Improvements

### 💡 Order Management Improvements

#### Enhancing delivery details and adding tracking redirection in order detail view **Release date :** 26/06/2025 **Version number :** <mark style="color:purple;">LC-2.6.1.4</mark>

In the order detail view, only the delivery number was previously shown, and users could not directly access the tracking link. With this improvement, the delivery section now includes the delivery ID, tracking link, and delivery type presented in a clear and structured layout.





{% hint style="info" %}
### Bug Fixes

* \-
{% endhint %}



These updates are designed to enhance both the functionality and usability of Lidia Platform, ensuring a smoother and more efficient experience for all users. Stay tuned for further improvements next month!

\
\
