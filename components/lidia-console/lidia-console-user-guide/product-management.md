# Product Management

The Product Management section is the main management area that enables all products uploaded by sellers on the marketplace to be created and managed under a single catalog structure, within the rules defined by the platform. Since the system operates with a single catalog logic, sellers can upload products only through the category structures and data schemas determined by the platform. Thanks to this approach, all product data is collected within a standardized, consistent, and centralized data tree; category confusion, field incompatibilities, and data inconsistencies are prevented.

Within this section, operations such as defining the fields and criteria that sellers will use during product uploads, creating categories and category sets, managing product pools, defining brands, and structuring product–variant relationships are carried out. The Product Management area functions as the central structure that determines which category a product belongs to, which mandatory fields it must be uploaded with, how the variant structure is established, and how the product is represented across the marketplace. In this way, product entry processes on the seller side are kept under control, while listing, operational, and reporting processes proceed on a consistent data structure.

### **Pools**

Pools are structures created by the Console administrator to ensure that sellers upload their products in accordance with defined standards and the correct data structure on the platform. Pools are the area where products are initially created and controlled within the system. Products can be uploaded to this area via SAP integration or through Excel files.

Each pool is created based on a specific category and a data schema linked to that category. On the Pools screen, a new pool (product family) is defined using the Add New Product Family button located in the top right corner. In order to create a new product family and add products to it, selecting a category or subcategory from the list is mandatory. The selected category must be associated with a data schema defined in the system.

If a data schema has not yet been created for the relevant category, a data schema must first be defined and then linked to that category. The data schema definition process is carried out via the [**Settings**](settings.md) **> Catalog > Product Families** page. On this page, under the Data Schema Fields heading, the required attributes, options, and other field definitions for the relevant product family are configured. These field definitions are created as combinations that differentiate and customize data schemas from one another. Data schemas play a critical role in category creation and in defining product standards.

After all prerequisites are completed and pools are created, the defined product families are listed under the Manage Your Pool List heading. Each product family is displayed together with the total number of products it contains, the categories it is associated with, and its active/passive status. For active product families, if there are products that have not yet passed approval, the label “_X Products Pending Approval_” is displayed. Additionally, each product family includes a Manage Products button. If the number of products contained in a product family is 0, the Delete Product Family button becomes active alongside the Manage Products button.

When the Manage Products button is clicked, four separate pages are displayed under the heading “_View Products in the XXX Pool._” These pages are Pending Approval, Approved, Rejected, and Published. The number of products on each page is shown next to the page title.

The products listed on these pages are displayed in a comprehensive table consisting of the following columns:

-Basic Information (product name, unique product code, Lidia code, seller item code, group code, image code),\
-Category Information,\
-Brand Information,\
-Options,\
-Attributes,\
-Other Information (short description, tax rate, product status, pool status, creation date).

On the Pending Approval page, Approve / Reject buttons are available for each product. Products can be approved or rejected individually or in bulk. During the rejection process, one of the system-provided rejection reasons must be selected. These rejection reasons include:

* [x] Missing description
* [x] Image not appropriate
* [x] Incorrect product name
* [x] Missing / incorrect category information
* [x] Incorrect volumetric weight information
* [x] Missing / incorrect color information
* [x] Incorrect pool
* [x] Uploaded category not defined under the brand
* [x] Product name and color information mismatch
* [x] Missing / incorrect VAT rate
* [x] Other

When a product is rejected, it is returned to the seller together with the selected rejection reason.

The tools located in the top right corner of the product management screen allow products within the pool to be filtered by seller, enable selected or all listed products to be exported to Excel format, and allow bulk row deletion via the Bulk Updates button. These features enable product management and approval processes to be carried out efficiently from a single center, while ensuring that data control is scalable and operationally sustainable.
