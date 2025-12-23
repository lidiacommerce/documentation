# Product Management

The Product Management section is the main management area that enables all products uploaded by sellers on the marketplace to be created and managed under a single catalog structure, within the rules defined by the platform. Since the system operates with a single catalog logic, sellers can upload products only through the category structures and data schemas determined by the platform. Thanks to this approach, all product data is collected within a standardized, consistent, and centralized data tree; category confusion, field incompatibilities, and data inconsistencies are prevented.

Within this section, operations such as defining the fields and criteria that sellers will use during product uploads, creating categories and category sets, managing product pools, defining brands, and structuring product–variant relationships are carried out. The Product Management area functions as the central structure that determines which category a product belongs to, which mandatory fields it must be uploaded with, how the variant structure is established, and how the product is represented across the marketplace. In this way, product entry processes on the seller side are kept under control, while listing, operational, and reporting processes proceed on a consistent data structure.

## **Pools**

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

## **Categories**

As mentioned earlier, each pool is based on a specific category and a data schema associated with that category. A category is a hierarchical structure in which products are logically grouped within the marketplace. A properly designed category structure ensures that products are listed in the correct place, filtering and search results function accurately, sellers fill in the correct fields when adding products, and business rules such as campaigns and commissions can be managed on a product group basis.

On the Categories page, a new category can be defined using the Add Category button located in the top-right corner. During this process, the category name is entered, the category is mandatorily matched with a data schema, and optionally a parent category can be selected to create a hierarchical structure. Associating a category with a data schema is mandatory. Within the data schema, attributes and options defined in the system are grouped.

* **Attribute**: Represents the defining characteristic of a product.
* **Option**: Represents the values that affect a product’s variants and pricing.

Attributes are defined under [**Settings**](settings.md) **> Catalog > Attributes**, and options are defined under [**Settings**](settings.md) **> Catalog > Options**.

Added categories are listed hierarchically under the Manage Categories section. In this list, the category name, the number of products in the category, the total number of products under parent categories, and the category status are displayed. When navigating to the details of any category, users are presented with a total of eight different sections related to category management.

* #### **Basic Information**

This section contains the core descriptive information of the category. The category name, category code, integration code, associated data schema, parent category, uploaded visuals (such as a cover image), short and long descriptions, and tag fields are displayed here. All fields can be filled in and existing information can be edited.

* #### **Attributes**

Under the Attributes section, predefined attributes and their associated options can be added to the category using the Add New Attribute button. This area is critical for defining how products under the category will be listed and filtered.

* #### **Product Management**

This page lists all products offered for sale under the selected category, including their images, product names, and product codes. When clicking on the details of any listed product, the user is redirected to the relevant product detail page under Product Management > Products in the Console’s left-hand menu.

* #### **Custom Sorting**

On the Custom Sorting page, products under the category are displayed based on the selected layout type (expanded view, 2-column, 3-column, 4-column, or 5-column view). The order in which products appear on the marketplace can be manually adjusted using drag-and-drop. To change the order of multiple products at once, the **CTRL** key can be used to make multiple selections.

* #### **Filter Management**

The Filter Management page is used to configure category-based filters to improve user experience. Filters can be created based on categories, brands, price ranges, attributes, options, and tags. The order of selected filters can be adjusted to determine which filters appear at the top in the marketplace interface.

* #### **Page Management**

The Page Management section includes the page name, template, page code, and tag information for the category. Using the Add Section button at the bottom of the page, sections, blocks, and core elements can be added to customize the category page. This structure allows category pages to be managed flexibly in terms of visuals and content.

* #### **SEO**

On the SEO page, the category’s meta title, meta description, and URL information can be configured. This area contributes to improved search engine indexing of category pages and helps increase organic traffic.

* #### **Slugs**

Under the Slugs section, the slug information for the category is displayed. This area is used to track and manage category URL structures when needed.
