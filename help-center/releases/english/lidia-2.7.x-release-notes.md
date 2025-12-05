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

## <mark style="color:purple;">Releases in 2.7</mark>

### New Features

### 🎯 Invoice Management Enhancements

#### **Ability for Admins to Approve or Reject Seller Invoices** **Release Date:** 22/07/2025 **Release Number:** <mark style="color:purple;">LC-2.7.1.1 - LMC-2.7.1.1</mark>

To ensure invoice validation and prevent off-system document entries, the invoice upload and approval workflows have been centralized under the "Invoice Center". With this enhancement, sellers can now upload order or return invoices through this module for platform admins to review. Admins can either approve or reject these invoices with comments. Rejected invoices can be revised and re-uploaded by sellers. This ensures end-to-end control and traceability of the invoice sharing process within the platform.



#### **Centralized Invoice Upload and Visibility for Sellers** **Release Date:** 22/07/2025 **Release Number:** <mark style="color:purple;">LMC-2.7.1.2</mark>

Previously, sellers could only upload invoices through individual order detail pages, which limited overall visibility. With this update, sellers can now upload both order and return invoices via a centralized invoice page. A dedicated upload field has also been added under the return invoice detail view. Regardless of the entry point, all invoices can now be viewed, edited, or deleted from a single screen.



#### **Unified Invoice View Across All Users** **Release Date:** 22/07/2025 **Release Number:** <mark style="color:purple;">LC-2.7.1.2 - LMC-2.7.1.3</mark>

Invoices were previously listed on scattered screens, making it difficult for both sellers and admins to manage or search through them. This update introduces a centralized invoice screen accessible under the "Invoice Center" in the sidebar. Admins can now filter invoices by seller name or invoice type, view, and download them, while sellers can search, edit, or delete their own invoices from one place.





### 🎯 Reporting Enhancements

#### **Availability of Withholding Collection Report** **Release Date:** 22/07/2025 **Release Number:** <mark style="color:purple;">LMC-2.7.1.4</mark>

In Turkey, marketplace commissions are subject to withholding, and while sellers are legally responsible for reporting them to the Revenue Administration (GİB), the preparation of this report is supported by the marketplace infrastructure provider. With this development, sellers can now generate GİB-compliant Excel reports from the Merchant Console. These can be accessed and exported via the "Withholding Collection Report" screen under the Reports section.







### 🎯 **Platform Health** Enhancements



#### **Manual Cache Clearing from Console** **Release Date: 22/07/2025** **Release Number:&#x20;**<mark style="color:purple;">**LC-2.7.1.3**</mark>

Previously, only technical teams could manage cache mechanisms, and admins lacked the ability to manually clear caches. With this update, a "Cache Management" module has been introduced under Operational Tools. This screen lists all cache-enabled data entities and allows admins with the appropriate roles to manually trigger cache clearing actions via the console—improving agility and reducing dependency on technical teams.





### 🎯 **Finance Management** Enhancements

#### **Displaying Payment Method in Payout Breakdown** **Release Date: 22/07/2025** **Release Number:** <mark style="color:purple;">LMC-2.7.1.5 - LC-2.7.1.4</mark>

The payment method (e.g., credit card, cash on delivery, bank transfer) for each order was previously not visible in payout breakdowns. With this update, the payment method is now shown for each payout item, allowing both sellers and admins to better analyze collection data and streamline financial and accounting workflows.



#### **Seller Payouts Positioned by Period in Finance Module** **Release Date:** 22/07/2025 **Release Number:** <mark style="color:purple;">LMC-2.7.1.6</mark>

Sellers previously lacked access to view their payouts based on periods or maturity dates. With this development, seller payouts are now recorded according to defined cycles and periods, and displayed under the "Finance Management > Payouts" section in the seller panel. Additionally, dashboards on this page offer clear insights into cost breakdowns across sales, campaigns, shipping, and more.



#### **Exporting Payouts Based on Periods** **Release Date:** 22/07/2025 **Release Number:** <mark style="color:purple;">LMC-2.7.1.7 - LC-2.7.1.5</mark>

While payout data could be viewed in the system, it wasn’t possible to export this data by period. With this enhancement, users can now export detailed Excel reports for each payout period, allowing admins and sellers to download and use the data for external reporting.



#### **Date & Time-Based Commission Rate Definitions** **Release Date:** 22/07/2025 **Release Number:** <mark style="color:purple;">LC-2.7.1.6</mark>

Previously, commission rates couldn’t be assigned to specific date or time ranges, limiting flexibility for dynamic campaign setups. With this improvement, users can define commission rates with both start and end dates and time intervals. Once the defined window expires, the system will automatically revert to the previously active rate to ensure seamless continuation of commission calculations.





### 🎯 **Merchant Management** Enhancements

#### **Defining Warehouse Address During Seller Registration** **Release Date: 22/07/2025** **Release Number:** <mark style="color:purple;">LC-2.7.1.7</mark>

Admins previously couldn't define warehouse addresses while manually registering sellers, often resulting in incomplete logistics data. With this update, admins can now add a required warehouse address field during manual seller creation (excluding seller self-applications). This field is mandatory and must be filled before saving. The warehouse address can also be updated after registration if needed.



### Improvements

### 💡 **User Experience Enhancements**

#### **Migration of Settings Pages to New Listing Interface** **Release date :** 22/07/2025 **Version number :** <mark style="color:purple;">LC-2.7.1.8</mark>

Some pages under the "Settings" menu were still using outdated listing and search components, creating inconsistencies across the interface. This update migrated those pages to the new listing architecture, ensuring that all Settings pages follow the same design language and provide a consistent and streamlined user experience.





{% hint style="info" %}
### Bug Fixes

* \-
{% endhint %}



These updates are designed to enhance both the functionality and usability of Lidia Platform, ensuring a smoother and more efficient experience for all users. Stay tuned for further improvements next month!

\
<br>
