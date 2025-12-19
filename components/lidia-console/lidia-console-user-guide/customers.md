# Customers

Regardless of whether they have made a purchase or not, every individual who has created a registration on the platform is considered a customer. The Customers section is the area where all users registered on the platform are centrally managed. Through this section, customers can be listed, their basic information can be viewed, order and payment histories can be tracked, campaigns and coupons they have benefited from can be reviewed, the permissions they granted during registration can be viewed, and referral code definitions can be created.

The Customers module is designed to monitor customer behavior, enable customer segmentation, and support end-to-end analysis of the customer experience.

## **Customer Management**

When entering the Customer Management page, users are first presented with the Customer List screen. On this screen, all customers registered in the system are listed, and for each customer, name and email address, segment information, order count, total order amount, membership date, and active/passive status can be viewed in a single overview. A new customer can also be manually created in the system using the **Add New Customer** button located in the upper-right corner of the page.

### **Customer Details**

When navigating to the customer detail screen, a total of eight main sections are available where customer information and behaviors can be monitored. In the summary area located at the top of these sections, key indicators such as the customer’s name, membership date, last visit date, last order date, total number of orders, total amount spent, and current wallet balance are displayed in real time. This summary area provides a quick overview of customer behavior and facilitates navigation to detailed sections.

#### **1. Basic Information**

This screen displays the basic information entered by the customer during registration. Details such as first and last name, gender, email address, phone number, and account activity status can be viewed and edited depending on user authorization.

#### **2. Addresses**

The Addresses screen is where customer address information is managed. In this section, Delivery Addresses, Corporate Invoice Addresses, and Individual Invoice Addresses are displayed in separate areas. Existing addresses can be edited, or new addresses can be added.

#### **3. Orders**

On the Orders screen, the customer’s entire order history is listed. For each order, information such as order number, product quantity, order date, order amount, payment method used, and order status is displayed. The order list can be filtered by date, order status (Draft, Pending Delivery, New, In Progress, Prepared, Invoiced, In Delivery Process, Delivered, Completed, Not Delivered, Returned, Cancelled, Expired), and request type (cancellation, return). When clicking on the details of any listed order, the user is redirected to the relevant order detail screen under **Sales > Orders** in the left menu.

{% hint style="info" %}
**Note:** This section is explained in detail in the Orders section. To review: [_Orders_](customers.md#id-3.-orders).
{% endhint %}

#### **4. Payments**

On the Payments screen, all payment transactions related to the customer are listed. For each payment, information such as transaction code, transaction date, payment method used, instrument group, service provider, and institution is displayed. When clicking on the details of any payment, the user is redirected to the relevant payment detail page under **Finance > Payments** in the left menu.

{% hint style="info" %}
**Note:** This section is explained in detail in the Payments section. To review: [_Payments_](finance.md).
{% endhint %}

#### **5. Campaigns**

On the Campaigns screen, the campaigns that the customer has benefited from are listed. Each campaign is displayed with information such as campaign name, campaign type, and start–end dates. The campaign list can be filtered based on campaign status and discount type (Membership, Promotion, Purchase, After-Sales). When clicking on a campaign detail, the user is redirected to the **Campaign Management > Campaigns** page in the left menu.

{% hint style="info" %}
**Note:** This section is explained in detail in the Campaigns section. To review: [_Campaigns_](campaign-management.md).
{% endhint %}

#### **6. Coupons**

On the Coupons screen, the coupons used by the customer in their orders are listed. This list includes information such as coupon name, coupon type, discount type, discount amount, usage limit, and expiration date. When navigating to the details of any listed coupon, the user is redirected to the **Campaign Management > Coupons** page in the left menu.

{% hint style="info" %}
**Note:** This section is explained in detail in the Coupons section. To review: [_Coupons_](campaign-management.md).
{% endhint %}

***

#### **7. Permissions**

The Permissions screen is where all permissions approved by the customer during marketplace login and usage processes are displayed and managed. On this screen, the customer’s accepted legal permissions, notification permissions, and other mandatory or approval-based preferences can be monitored in detail. Permissions can be filtered and analyzed based on their current status. The permission contents displayed in this section are sourced from the documents uploaded under **Settings > Legal Documents** and referenced by the system. This structure ensures that customer permissions are managed centrally, traceably, and in compliance with legal requirements.

***

#### **8. Logs**

On the Logs screen, the customer’s order and payment logs are listed separately along with date and IP address information. This area is used for tracking customer activities and supporting auditing processes.

## **Permissions**

When the Permissions page is accessed, all customer permissions are displayed on a single screen, listed according to customer ID numbers. This screen allows centralized monitoring of the legal, notification, and other permission types approved by customers and enables quick review of permission statuses.

## **Reference Codes**

A reference code is an identifier used to track where users or transactions originate from and to apply source-specific rules or benefits.\
The Reference Codes screen is the area where reference codes to be used on the platform are defined and managed. Through this screen, new reference codes can be created and a list of all reference codes defined in the system can be viewed. Reference codes can be defined according to different usage types such as platform-based, seller-based, or user-based.

When navigating to the details of any reference code, the Dashboard screen opens first. In the summary panel displayed on this screen, the creation date of the reference code, the start date, and the planned end date are shown. Through the 'stop refferal code validity' and 'expire refferal code'  buttons located in the same area, the active status of the code can be managed. In the side summary panel, statistics such as the usage count of the reference code and access and usage percentages are presented. At the bottom of the Home page, there is a usage detail chart that can be customized based on the selected date range, allowing the performance of the reference code to be visually monitored.

Another section available on the reference code detail screen is the Conditions and Rewards page. Through this page, the conditions under which the reference code will be valid can be defined. By creating role-based, seller-based, or user-based rules, the scope of use and the benefits provided by the reference code can be configured.

On the final section of the detail screen, the General Settings page, the basic configurations of the reference code are managed. In this area, the reference code name, reference code type, usage limit, and validity dates can be viewed and updated when necessary. This structure ensures that the lifecycle of reference codes is fully controlled end to end.



