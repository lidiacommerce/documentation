# Bulk Upload

The Bulk Media Upload area is a management section that allows multiple images or documents to be uploaded in a single operation. The upload process consists of the following steps:

**Document Upload → Data Validation → Completed**

With this structure, category, brand, and product images as well as document files can be added to the system quickly and securely, in compliance with predefined standards.

There are four main template types available on the upload screen:

* Category Image (2000 × 2000 px)
* Brand Image (2000 × 2000 px)
* Product Image (2000 × 2000 px)
* Document

- [x] To upload documents, first select the relevant document type, then add the files you wish to upload to the opened area. After adding the files, you can proceed to the next step by clicking the Continue button.
-   [x] During the Data Validation step, all uploaded files are **automatically checked** according to system rules. If any media item within the uploaded bulk data does not meet the required conditions in terms of format, size, or content, the system displays a warning and requests correction of the relevant rows.

    **Supported image formats:**\
    `.jpg .jpeg .png .gif .bmp .jfif .webp .rar .zip`  \
    **Supported document formats:**\
    `.rar .zip .3dmax .3ds .step .stp .dwg .pdf`\
    \
    \
    &#x20;\
    \
    At this stage, the Show Invalid Rows Only button simplifies the editing process for sellers by listing only the erroneous files.

* If errors exist, the system displays the message:\
  &#xNAN;**“X media items in your uploaded bulk data do not meet the required conditions!”**\
  In this case, the necessary corrections must be made by the uploader.
* If no errors are detected, the message:\
  &#xNAN;**“Your bulk data has been successfully uploaded without errors!”**\
  is displayed, and the Continue option becomes active.

- [x] At the Final Approval step, the upload process is completed and all files are successfully added to the system. If necessary, additional files can be added during the data validation step.

***

### Image Codes and Product Association

The **file name** assigned to each image during bulk or individual upload is considered the **image code** in the system. This code is used to associate images with products.

The product–image matching process works as follows:

* To upload products, an Excel template is downloaded from the **Pool List** page.
* While entering product data, the **Image Code** column in the template is filled with the image code specified during media upload.
* The system automatically **matches the product with the corresponding image** based on the entered code.

This structure eliminates the need to manually select images one by one during product upload, speeds up the process, and prevents incorrect associations.
