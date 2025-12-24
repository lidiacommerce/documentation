# Content Management

Content section is the central area where the page structures, visual areas, and user-facing content within the marketplace are managed. Under this heading, the platform’s interface, navigation structure, and showcase layouts can be customized, configured according to different scenarios, and managed through dynamic content controls. Thanks to content management, page layouts, redirects, and visual components can be controlled without the need for technical development, supporting both user experience and operational flexibility.

## **Templates**

In the marketplace system, **T**emplates are predefined structures that enable product and content information to be created with a standard visual and structural layout. Templates under the Content section are designed to ensure that, especially in PDP areas, headings, text fields, and content blocks are presented with the same visual hierarchy and layout logic. This structure provides consistency across the platform and prevents manual and unstructured content creation.

A new template can be created using the Add Template button located in the top-right corner of the Template Management page. During the template creation process, the template type and template name must first be defined. The template type is selected from the options provided by the system: Section, Showcase, Showcase Page, Special List, and Block. During the creation process, the system checks whether the template complies with the rule set of the selected type, and the creation is completed once compliance is confirmed.

All created templates are listed on the Template Management page. When navigating to the details of any template, the user is presented with the Template Type, Template Name, Description, Category, Cover Image, Preview Image, and the main Template Content area where configuration is performed. These fields allow the basic template information to be viewed and edited.

In the Lidia Console, the Template Content area is empty by default. This area is populated only within the structure provided by the selected template type before content is created. Templates do not offer a free-form structure; each template operates with a specific content and layout logic aligned with its intended use.

Within this scope, the Console administrator:

* Creates the template content in accordance with the template types provided by Lidia
* May request the preparation or modification of template content from the Lidia Admin when needed

Templates predefine:

* [x] Which fields the content will consist of
* [x] In which layout these fields will be displayed on the page
* [x] Within which template type the content will be used

Thanks to this structure, content is created with a standard layout, visual and structural consistency is maintained, and content management is handled centrally.

Lidia provides 5 different template types for use in content management. Each template type is designed for a different usage scenario:\
**Section**\
Used to create a separate content area within a page. It allows content to be grouped within a specific layout.\
**Showcase**\
Used to prominently display content, campaigns, or visuals that need to stand out.\
**Showcase Page**\
Used for independent, full-page content created with a showcase logic.\
**Special List**\
Allows multiple items with the same structure to be displayed as a list with a defined ordering logic.\
**Block**\
Used to create small, modular, and reusable content areas within a page.

## **Pages**

Pages is the area where all static and dynamic content presented to users on the marketplace is structured and managed. Through this section, controlled, consistent, and reusable page structures can be created for different content types such as categories, brands, campaigns, stores, or special lists. Page management standardizes both the user experience and content operations by ensuring that content is presented in the correct context, with the correct template and layout.

* **Creating a Page**

A new page can be added to the system using the Create New Page button located in the top-right corner of the Page Management screen. When creating a new page, the page characteristic must first be selected. The page characteristic defines the purpose of the page and the type of content it represents. This field can be one of the following options:\
Standard,Category,Brand,Store,Campaign,Special List,Topic.

After selecting the page characteristic, the page is created by entering the Page Name, Page Code, and Location information. The selected page characteristic directly affects the template and structure used by the page.

* #### **Page Detail**

When navigating to the details of any created page, the user is presented with 4 main sections where the page configuration is managed.

* **Basic Information**

The Basic Information section contains the main definitions of the page. This section includes:

Page name,Page template,Page code,Tags

Since the page characteristic is selected during page creation, the page template field is automatically populated according to the selected characteristic.

* Standard → `generic`
* Category → `category`
* Brand → `trademark`
* Store → `store`
* Campaign → `promotion`
* Special List → `customList`
* Topic → `topic`

This mapping ensures that each page type is created only with the template appropriate to its purpose and that structural consistency is maintained. On the right side of the Page Detail screen, a prototype preview of the created page is displayed. This area allows a quick visual preview of the page’s current structure.

* **Page Structure**

The Page Structure section is the main area where the content layout and components of the page are managed. This area is not a free-form design editor; content is created using predefined content building blocks provided by Lidia Console. This approach ensures that page designs remain consistent and sustainable.

Using the Add Section area, the following General Content Structures can be added to the page:

* -Paragraph  \
  -Basic List  \
  -Button  \
  -Divider  \
  -Video  \
  -Image  \
  -Two-Row Image  \
  -Spacer  \
  -Heading  \
  -Showcase  \
  -Advanced List

Each of these structures is designed to address a specific content need on the page. Content building blocks can be used individually or combined to create blocks. Through the use of blocks:

* Multiple content elements are grouped under a single structure
* Page layout becomes more readable and organized
* The same structure can be reused across different pages

This structure both accelerates content creation and ensures visual and structural consistency across pages.

* **SEO**

In the SEO section, meta title, meta description, and other search engine optimization settings related to the page are configured. This area supports proper indexing of the page by search engines and helps increase organic visibility.

* **Slug**&#x20;

The Slug section displays and manages the page’s URL structure. This field represents the page’s access address on the marketplace and is directly related to SEO.
