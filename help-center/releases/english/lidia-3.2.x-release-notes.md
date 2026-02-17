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





### Improvements

### 💡 Security Enhancements

#### Removal of “Remember me” option and update of password policies **Release date :** 17/02/2026 **Version number :** <mark style="color:purple;">LMC-3.2.1</mark>

As part of this enhancement, the “Remember me” button has been removed to strengthen account security, and new password policies have been introduced across the platform. Passwords must now be at least 11 characters long, include at least one uppercase letter, one lowercase letter, one number, and one special character. Passwords are required to be changed periodically by default every 60 days, a duration that can be configured by the system administrator. Reuse of the last five passwords is restricted, and after three unsuccessful login attempts, the account is locked for 15 minutes.







{% hint style="info" %}
### Bug Fixes

* Various bugs have been fixed for Lidia PIM and Lidia Merchant Console stabilization caused by Core conversion.
{% endhint %}



These updates are designed to enhance both the functionality and usability of Lidia Platform, ensuring a smoother and more efficient experience for all users. Stay tuned for further improvements next month!

\
<br>
