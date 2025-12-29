---
description: >-
  The Settings section is where the necessary configurations are defined to
  allow users to manage system-wide pages and capabilities. The configurations
  made in this section are referenced by all other.
---

# Settings

## Authorization

The Authorization section includes the pages where user roles and permissions are defined and managed within the Lidia Console. In the Lidia Marketplace system, authorization is designed around a role-based approach rather than a user-based structure. This model enables centralized control and management of users’ access levels and permitted actions through assigned roles. The Authorization section consists of two main areas: Roles and Users.

*   ### **Roles**

    Under the Roles section, the predefined roles provided by Lidia are displayed under **Lidia Roles**. These roles are configured to cover the platform’s standard usage scenarios. In addition, new roles can be created based on organization-specific needs, the created roles can be deleted, and users assigned to a role can be viewed through the role detail screen. For each role, permissions can be configured across all modules and capabilities available in the system.

    Roles can be configured with the following permission levels:

    * View permission
    * Edit permission
    * Both view and edit permissions

    Roles created later represent customized permission sets tailored to the specific needs of the project and the organization. These roles are referenced across the system to enforce authorization consistently.
*   ### **Users**

    Under the Users section, a list of all registered users in the system is displayed. From this list, you can view each user’s first and last name, email address, assigned roles, system registration date, and user status (Active / Passive). By using the **Create New User** button located in the upper-right corner, a new member can be created by entering the following information:



    <figure><img src="../../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

    \
    By accessing an individual user’s detail page, you can view basic user information such as first and last name, email address, phone number, and date of birth, as well as role and permission details.

{% hint style="success" %}
Depending on the permissions assigned to the user, this information and the assigned roles can be edited.
{% endhint %}

## Legal

The Legal section is the area where the organization’s legal obligations, documentation, and responsible institution information are centrally managed within the Lidia Console. This section ensures that legal content published on the platform is managed in an up-to-date, traceable, and versioned manner.

*   ### **Consent Documents**

    When accessing the Legal Documents section, a document list is displayed containing the document ID, name, publisher, document code, version information, validity date, and active/passive status. In this area, legal documents such as KVKK texts, preliminary information forms, and similar documents can be uploaded, and uploaded documents can be versioned through this section.

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Through document versioning, it is possible to perform checks in later stages, such as identifying who approved or did not approve specific versions of a document. From the Basic Information area on the document detail screen, the document content can be accessed and edited. Additionally, the complete version history of the document can be viewed through the Version History section on the detail screen.

*   ### **Liables**

    Under the liables section, a list is displayed containing the name, address, and country information of the institution or institutions responsible for the management of the Lidia Console. By navigating to the details of a record, the institution’s basic information and the list of legal documents published by that institution can be accessed.

    Using the button located in the upper-right corner of the screen, a new data controller can be added.

## Payments

The Payments section is where the payment options, methods, and rules to be used on the platform are defined. Users’ preferred payment methods are configured through this section. During the payment collection process on the frontend, Lidia Collectors reference these definitions to verify whether the relevant payment method is defined in the system, as well as to check installment options and transaction conditions.

*   ### **Payment Channels**

    Through the Payment Channels tab, a new payment channel can be added and all payment channels defined in the system can be listed. Each payment channel is a core component that determines how the payment flow operates and under which conditions it can be used.

    When accessing the detail screen of a payment channel, four main sections are displayed. The channel name and channel code are shown in the **Basic Information** section. Installment options related to the payment channel, interest rates applied to installments, active or passive status information, editing actions, and adding new installment options are managed through the **Options** section.

    Integration details and integration processes related to the payment channel are available in the **Integration Info** section. Payment transactions related to completed orders, including transaction amounts, transaction dates, and transaction types, can be reviewed in the **Transactions** section.

{% hint style="info" %}
![](<../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png>)<br>

When adding a new payment channel, you may either select from the known providers available in the system or define a new provider from scratch.
{% endhint %}

*   ### **Payment Institutions**

    The Payment Institutions section is where the payment institutions to be used on the platform are defined and managed. Through this section, new payment institutions can be added, existing institutions can be listed, and removed when necessary.

    When accessing the detail screen of a payment institution, the institution’s basic information, related payment instruments, BIN codes, and payment channels are displayed. In the **Basic Information** section, the payment institution name, display name, and institution code are managed.

    In the **Payment Instruments** section, payment instruments associated with the relevant payment institution can be added, existing associations can be removed, or updated. In the **BIN Codes** section, BIN codes belonging to the institution can be listed and new BIN codes can be added.
*   ### **Payment Instruments and Instrument Groups**

    The Payment Instruments section is where payment instruments belonging to a specific bank or payment provider are listed and defined. A new payment instrument can be added through this section. During the payment instrument creation process, the payment instrument name, code, associated instrument group, institution information, and instrument type are entered to complete the definition. From the detail page of a listed payment instrument, basic information, the BIN code list, and payment options can be viewed and edited.

    The Instrument Groups section allows different variations or structures of the same payment instrument to be grouped under a single group. Through this section, new payment instrument groups can be defined, existing groups can be viewed, and filtering operations can be performed.
*   ### **Payment Options**

    The Payment Options section allows you to view and filter which payment institution offers which payment instrument and which installment options. Payment options can be listed based on payment institution, payment instrument, and installment details. When accessing the detail screen of any listed payment option, a description area containing basic information and a separate area containing technical parameters are displayed. \
    \
    Using the **Import Data** button located in the upper-right corner of the listing page, new payment option lists can be added to the system. During this process, the table should be prepared using the Excel template provided by the Lidia Console and uploaded accordingly. With the **Export Data** button in the same area, either selected fields from the list or the entire dataset can be exported in Excel format.

<figure><img src="../../../.gitbook/assets/image (3) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

*   ### **BIN Codes**

    The BIN Codes section is where BIN codes defined in the system are listed and their active or passive statuses are reviewed.
*   ### **Payment Rules**

    The Payment Rules screen is where rule-based configurations for product payment transactions are defined. Through this screen, payment type and installment count rules can be created based on criteria such as category, brand, seller, price, and down payment amount.

## Logistics

The Logistics section is where delivery processes on the platform are managed and configured. Through this section, contracted service providers are defined and managed, delivery profiles are created, and custom delivery rules can be configured based on specific requirements. Logistics settings form the core structure that supports accurate and seamless order fulfillment.

*   ### **Service Providers**

    The Service Providers section is the area where all contracted shipping companies and the shipping services they offer are managed. In this section, you can access the services provided by each shipping provider through labels such as standard shipping, bulky cargo, and next-day delivery. When accessing the detail screen of a service provider, the **Basic Information**, **Integration Information**, and **Service Information** sections are displayed.

    In the Basic Information section, the provider name and code can be edited. In the Integration Information section, the pricing interface URL, authorization interface URL, and API key information can be managed. In the Service Information section, a new service identity can be added by selecting a service type from the available options, and a price list can be uploaded for the defined service identity. During the price list upload process, the sample Excel template provided by the Lidia Console can be downloaded, edited as needed, and then uploaded to successfully complete the process.

    Thanks to these uploaded price lists, the system calculates estimated shipping costs at the moment products are prepared to be listed for sale on the platform and generates a shipping fee accordingly. This fee is later compared with the actual shipping cost, and this comparison is referenced in the calculation of settlement amounts.

<figure><img src="../../../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

*   ### **Profiles**

    The Profiles section is where marketplace-recommended delivery profiles are managed and custom delivery profiles can be created. In this area, prioritization for small cargo and bulky cargo can be easily configured using the drag-and-drop method.
*   ### **Rules**

    The Rules section is the area where delivery processes can be customized based on predefined rules. Under this section, service provider matching can be configured according to criteria such as category, weight, volumetric weight, city, district, and distance.

## Commercial

The Commercial section is where organizational commercial rules are defined and managed. In this section, existing rules are listed, viewed, and can be exported in Excel format when needed. When adding a new rule, the commission rule name, priority, and validity date are defined.

The created rule set can be configured based on criteria such as category, brand, product, seller, variant, and payment instrument. This allows commercial operations to be managed in a flexible and controlled manner according to organizational requirements.

<figure><img src="../../../.gitbook/assets/image (22).png" alt=""><figcaption></figcaption></figure>

## Catalog

The Catalog section is where the full scope of product data to be offered for sale or included in the product assortment is defined. In this section, the product data space, constraints, locks, and rules are configured, and the conditions under which products are included in the system are determined. Category-based fields and attributes are also managed to ensure product information is created in a consistent and controlled manner.

This area allows you to build the catalog architecture within the system and define an organization-specific product structure end to end. Through the Catalog, the product data space can be designed, data relationships can be established, and a solid foundation for product management can be created.

*   ### **Data Schemas**

    The Data Schemas section is where you define under which data schema the products to be uploaded to the system will be structured. From this page, you can view all your data schemas and create new ones. By navigating to the details of any data schema, new fields can be added through the **Data Schema Fields** section.

    During the field creation process, field names can be customized as needed. Field names such as short description, brand, category, color, weight, volumetric weight, and tax rate can be defined. The field types for these fields are selected from options such as attribute, option, category reference, brand reference, image source, and document source.

    In addition, validation and mapping information can be defined for each field to configure which information is mandatory during product entry and which rules must be met for products under the related schema to be accepted into the system. This allows product data entry standards to be controlled in an organization-specific manner. These configurations can also be managed by uploading custom documents under the **Documents** section.
*   ### **Product Relationships**

    The Product Relationships section is where logical and functional relationships between products are defined within the system. In this section, the name and description of product relationships are created to ensure that relationship types are defined with a standardized structure across the platform. At this stage, only the basic definition of the relationship is configured; the products or product variants to which the relationship applies are defined later through the product and variant detail screens. This structure allows different relationship scenarios, such as cross-sell, alternative products, or complementary products, to be managed flexibly.
*   ### **Data Locks**

    The Data Locks section is used to ensure that certain information cannot be modified in a marketplace environment. These locks are not limited to the product creation process; they can also be applied during product data transfers from different platforms into the system. The source and target of where the lock is applied can be configured as needed.

    Through this section, data locks can be defined while importing product data from external sources, while editing product data within the Lidia Console, or while sending product data through flows, channels, services, or feeds. This ensures that critical product information remains protected from unauthorized or unintended changes.

    When adding a new data lock, the process requires defining the lock title, lock type, the source to which the lock will be applied, the lock scope, the related object type, the locked field, and a description.

{% hint style="success" %}
This is an advanced feature that covers data locking not only during product flows but also at the product data level.
{% endhint %}

*   ### **Properties**

    The Properties section is where product characteristics are centrally defined and managed. When creating a new property in this section, basic information such as the property name, the property group it belongs to, and the data type it supports are defined. The selected data type determines which values the property can take and how it can be used across products.

    All product properties defined in the system can be viewed on the listing page. From this page, existing properties can be edited, updated, or deleted when necessary. Centralized property management ensures that product data is created in a consistent structure and contributes to more effective filtering, search, and product comparison functionalities.

    Properties are associated with **Property Groups** to create a more structured and meaningful organization. Under the Property Groups section, new property groups can be defined and existing groups can be listed. When navigating to the detail page of a property group, the list of property values associated with that group can be accessed. This relationship allows properties to be categorized and managed more efficiently, making the overall product data structure easier to control.
*   ### **Options**

    The Options section is where options, option groups, and the values associated with these options are centrally managed within the scope of product properties. This section is one of the core building blocks for creating product variants and standardizing product data.

    **The Options page** is where all options defined in the system are listed. Through this page, new options can be created, existing options can be viewed, and edits can be made. Options form the basis of variant structures used on products and are managed by being associated with relevant option groups.

    Under the **Option Groups** section, multiple options are grouped under meaningful structures. This allows options to be categorized, creating a more organized and manageable structure. In this section, new option groups can be defined, existing groups can be listed, and options associated with a group can be viewed through the group detail page.

    **The Option Values page** is where each option value defined in the system is listed individually and can be edited. This section helps maintain the consistency of values used across products and prevents duplicate data entry.

    In the **Option Value Groups** section, option values are organized under logical groups. Through these groups, related option values can be viewed and managed together. New value groups can be created from this section, and associated values can be accessed through the group detail page.

    The Options section enables options and values to be managed in a reusable, controlled, and scalable structure, contributing to a more organized and sustainable product data architecture.

{% hint style="info" %}
**Properties** are fields where descriptive information about a product is entered, such as Processor Type, Screen Size, or Color. These fields describe the product and typically do not affect the price.

**Options** represent product variants and usually affect the price. They are user-selectable fields that create variations, such as Memory Capacity or Color Options.
{% endhint %}

## Tags

The Tags section is where tags to be used across the system are defined and managed. Tags are used to provide classification, differentiation, and ease of management across products, categories, brands, documents, or system-related processes.

When adding a new tag, the first step is to select the **tag type**. The tag type determines how the tag will be used within the system and how it will behave in the user interface. During tag type selection, descriptions for each tag type are displayed on the screen, and the appropriate tag type is selected accordingly.

The tag types available in the system are as follows:

<figure><img src="../../../.gitbook/assets/image (23).png" alt=""><figcaption></figcaption></figure>

After selecting the tag type, the tag creation process is completed by entering the tag name, tag text, and tag code. The created tags can be used across relevant areas of the system and managed according to requirements.

## Extensions

