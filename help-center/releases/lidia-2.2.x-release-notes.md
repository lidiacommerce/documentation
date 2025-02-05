---
description: >-
  Discover the latest updates and improvements introduced this month, enhancing
  the functionality and user experience across the Lidia platform.
cover: ../../.gitbook/assets/feb.png
coverY: 0
---

# Lidia 2.2.x release notes

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

## Releases in 2.2.1 - 4 Feb 2025

### 🚀 **Bug Fixes and Functional Improvements**

* <mark style="color:purple;">**LP-2.2.1.4**</mark> <mark style="color:purple;"></mark><mark style="color:purple;">–</mark> Resolved the issue where newly added values were not included in all options.
* <mark style="color:purple;">**LP-2.2.1.5**</mark> <mark style="color:purple;"></mark><mark style="color:purple;">–</mark> Fixed the issue where password reset and "Forgot Password" emails were not being delivered.
* <mark style="color:purple;">**LP-2.2.1.6**</mark> <mark style="color:purple;"></mark><mark style="color:purple;">–</mark> Addressed the login screen redirection issue on Solution Center pages.
* <mark style="color:purple;">**LP-2.2.1.8**</mark> <mark style="color:purple;"></mark><mark style="color:purple;">–</mark> Resolved the issue where "Forgot Password" redirects were missing on the login page.
* <mark style="color:purple;">**LP-2.2.1.9**</mark> <mark style="color:purple;"></mark><mark style="color:purple;">–</mark> Fixed the dropdown display issue in the Merchant Details section.
* <mark style="color:purple;">**LP-2.2.1.10**</mark> <mark style="color:purple;"></mark><mark style="color:purple;">–</mark> Addressed the incorrect display issue in the Product Inventory Details.
* <mark style="color:purple;">**LP-2.2.1.11**</mark> <mark style="color:purple;"></mark><mark style="color:purple;">–</mark> Fixed the issue where filters could not be added in the Seller Details section.
* <mark style="color:purple;">**LP-2.2.1.12**</mark> <mark style="color:purple;"></mark><mark style="color:purple;">–</mark> Resolved the issue where the return code was not being sent via email.
* <mark style="color:purple;">**LP-2.2.1.13**</mark> <mark style="color:purple;"></mark><mark style="color:purple;">–</mark> Fixed the issue where the search function did not work when adding images to the header menu.
* <mark style="color:purple;">**LP-2.2.1.13**</mark> <mark style="color:purple;"></mark><mark style="color:purple;">–</mark> Resolved the issue where categories were not appearing in filter management.
* <mark style="color:purple;">**LP-2.2.1.14**</mark> <mark style="color:purple;"></mark><mark style="color:purple;">–</mark> Fixed the issue where the copy buttons in the delivery details were not functioning.
* <mark style="color:purple;">**LP-2.2.1.15**</mark> <mark style="color:purple;"></mark><mark style="color:purple;">–</mark> Fixed an issue with exporting data based on filters.
* <mark style="color:purple;">**LP-2.2.1.16**</mark> <mark style="color:purple;"></mark><mark style="color:purple;">–</mark> Resolved the issue where users were redirected to the login screen after entering an incorrect password.
* <mark style="color:purple;">**LP-2.2.1.17**</mark> <mark style="color:purple;"></mark><mark style="color:purple;">–</mark> Fixed the issue where newly added values were not immediately displayed in options.
* <mark style="color:purple;">**LMC-2.2.1.5**</mark> <mark style="color:purple;"></mark><mark style="color:purple;">–</mark> Fixed the duplicate record display issue in Delivery Profiles.

### 📈 **Sales Management Enhancements**

#### **Stoppage Tax Implementation** **Release date :**  02/04/2025 **Version number :&#x20;**<mark style="color:purple;">**LP-2.2.1.1 - LMC-2.2.1.1**</mark>

As of 2025, a new regulation enforces a 1% stoppage tax on e-commerce transactions. This regulation applies to amounts deducted by intermediary service providers (e-commerce platforms) from payments made to sellers.

With this update, the stoppage tax information is now displayed clearly and transparently across the platform.

**Implemented Changes**

* **Order Details Page** – The stoppage tax deduction is clearly displayed in the order summary section.
* **Cost Table (Sales Management Screen)** – The stoppage tax is included in the cost calculations.
* **Sales Reports (Platform & Partner Panels)** – The stoppage tax is fully included in the exportable (Excel) report format.
* **Operations, Cost, and Campaign Reports** – The stoppage tax deduction amount, and net payment details are displayed comprehensively.

### 🌟 **User Experience Enhancements**

**Custom Error Pages Implementation**\
**Release date :**  02/04/2025\
**Version number :&#x20;**<mark style="color:purple;">**LP-2.2.1.2 - LMC-2.2.1.2**</mark>

In this release, custom error pages were designed and developed to improve user experience for common errors:

* **404 - Page Not Found**: Includes a clear message and navigation options to return to the homepage or the previous page.
* **500 - Internal Server Error**: Displays an informative message with options to navigate back to the homepage or the previous page.
* **"Something Went Wrong"**: A generic error page with redirection options to the homepage or the previous page.

<div><figure><img src="../../.gitbook/assets/Master (6).png" alt=""><figcaption><p>Somethings went wrong</p></figcaption></figure> <figure><img src="../../.gitbook/assets/Master (5).png" alt=""><figcaption><p>500 Error</p></figcaption></figure> <figure><img src="../../.gitbook/assets/Master (4).png" alt=""><figcaption><p>404 Error</p></figcaption></figure></div>

**Browser Tab Structure** \
**Release date :**  02/04/2025\
**Version number : &#x20;**<mark style="color:purple;">**LMC-2.2.1.3**</mark>

\
The structure of browser tabs has been improved to provide better navigation. For example, the tab now shows the current page followed by the platform name, e.g., **Home | Lidia Partner**, making it easier for users to track their location within the platform.

### 🚚 Delivery Management improvements

**Newly Added Shipment Details**\
**Release date :**  02/04/2025\
**Version number : &#x20;**<mark style="color:purple;">**LP-2.2.1.3 - LMC-2.2.1.4**</mark>

Additional shipment movement details have been incorporated into the system to provide users with more detailed tracking.

* **Detailed Shipment Status Information**: More descriptive status updates have been introduced.
* **Status Timestamp**: The exact time of each status update is now displayed.
* **Last Processed Location**: The last recorded location where the shipment was processed is now included.

***

## Releases in 2.2.2 - 18 Feb 2025

***

These updates are designed to enhance both the functionality and usability of Lidia Platform, ensuring a smoother and more efficient experience for all users. Stay tuned for further improvements next month!

\
\
