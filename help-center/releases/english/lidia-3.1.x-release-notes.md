---
description: >-
  Discover the latest updates and improvements introduced this month, enhancing
  the functionality and user experience across the Lidia platform.
cover: ../../../.gitbook/assets/SUDE.png
coverY: 0
---

# Lidia 3.1.x release notes

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

## <mark style="color:purple;">Releases in 3.1</mark>

### New Features



### 🎯 Platform Infrastructure Enhancements

#### Core framework transformation **Release Date:** 27/01/2026 **Release Number:** <mark style="color:purple;">LMC-3.1.1</mark>

A comprehensive Core transformation has been completed to enhance the scalability of the Lidia platform, standardize the modular structure, and optimize the performance of all components.\
With this transformation, the platform’s underlying architecture has been restructured, and inter-service communication and data processing operations have been migrated to the Lidia Core infrastructure.\
Under the new architecture, Lidia Merchant Console delivers higher processing performance, independent module deployment in development environments, and greater flexibility in version management, providing a more stable foundation for future developments.



### 🎯 Catalog Management Enhancements

#### Variant transfer capability **Release Date:** 27/01/2026 **Release Number:** <mark style="color:purple;">LC-3.1.1</mark>

With this enhancement, variants belonging to products can be transferred between different catalog structures or data pools. Lidia Console administrators can securely and reliably move their variants to a target catalog without the need to recreate existing variant structures.\
The transfer process is performed step by step via the product code change screens available in product and variant detail pages within Lidia Console, allowing selected variants to be repositioned under a different product code while preserving catalog integrity.



#### Product / Variant updates pool feedback capability **Release Date:** 27/01/2026 **Release Number:** <mark style="color:purple;">LC-3.1.2</mark>

With this enhancement, variant-level updates can be fed back into the relevant data pool. The process can be triggered via the feed back to pool button located on variant detail pages in Lidia Console, and the applied changes are reflected in the corresponding pool within a short period of time. This ensures that updates made across different sources or screens remain synchronized with pool data, preventing data inconsistencies. Users can access up-to-date variant information through a single, reliable source across all processes.



### 🎯 Media Management Enhancements

#### **Replacement of the media manager with a new application** **Release Date:** 05/01/2026 – 27/01/2026 **Release Number:** <mark style="color:purple;">LP-3.1.1 – LMC-3.1.2</mark>

The previous media manager application occasionally caused stability and performance issues.\
As part of this enhancement, the media manager has been replaced with a more modern and stable plugin, offering improved reliability and smoother file management.



### 🎯 Seller Management Enhancements

#### Seller approval and rejection capabilities **Release Date:** 27/01/2026 **Release Number:** <mark style="color:purple;">LC-3.1.3</mark>

With this enhancement, approval and rejection steps have been added to seller management processes. Lidia Console administrators can review seller applications and either approve them or reject them with a defined reason. This improvement standardizes seller onboarding workflows and enables more controlled and traceable seller management.



### 🎯 Delivery Management Enhancements

#### Printing delivery transport documents as stickers **Release Date:** 27/01/2026 **Release Number:** <mark style="color:purple;">LMC-3.1.3</mark>

With this enhancement, delivery transport documents can now be printed in sticker format.\
This improves packaging workflows in warehouse and logistics operations by enabling transport documents to be physically attached to shipments more easily. Operational efficiency is significantly increased, especially in high-volume delivery scenarios.



### Improvements

### 💡 Seller Management Improvements

#### Seller management listing improvements **Release date :** 27/01/2026 **Version number :** <mark style="color:purple;">LC-3.1.4</mark>

With this improvement, status information indicating the current step of the seller onboarding process has been added to the seller management listing screen. Previously, onboarding progress could not be viewed directly from the listing, requiring additional actions to track seller status. With this enhancement, platform administrators can directly monitor which stage sellers are in during creation and approval processes, enabling more transparent and controlled seller management operations.



### 💡 User Experince Improvements

#### Migration of all pages to the new listing interface **Release date :** 05/01/2026 – 27/01/2026 **Version number :** <mark style="color:purple;">LP-3.1.2 – LMC-3.1.4</mark>

This enhancement migrates all pages across the platform to the new listing interface.



#### Price range filtering in inventory listing **Release date :** 27/01/2026 **Version number :** <mark style="color:purple;">LC-3.1.5</mark>

With this improvement, price range filtering has been added to the inventory listing screen in Lidia Console. Users can filter products by defining minimum and maximum price values, allowing faster access to relevant inventory. This significantly improves search and management efficiency, particularly for large product catalogs.



#### Addition of new condition options in payment rules **Release date :** 27/01/2026 **Version number :** <mark style="color:purple;">LC-3.1.6</mark>

With this enhancement, the condition options available while defining payment rules have been expanded. Product-level and variant-level conditions can now be configured during payment rule setup. In addition, the previously mandatory category selection has been removed, and the condition field has been updated to support multi-select. This enables platform administrators to configure payment rules in a more flexible and targeted manner based on products, variants, and multiple categories.



{% hint style="info" %}
### Bug Fixes

* Various bugs have been fixed for Lidia PIIM and Lidia Merchant Console stabilization caused by Core conversion.
{% endhint %}



These updates are designed to enhance both the functionality and usability of Lidia Platform, ensuring a smoother and more efficient experience for all users. Stay tuned for further improvements next month!

\
<br>
