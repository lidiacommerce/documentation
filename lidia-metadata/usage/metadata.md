# Metadata

{% api-method method="post" host="https://api-metadata.lidiacommerce.com/categories/create" path="" %}
{% api-method-summary %}
Create category
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to create new category.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="Environment" type="string" required=false %}
The Environment
{% endapi-method-parameter %}

{% api-method-parameter name="LongDescription" type="string" required=false %}
The long description of new product.
{% endapi-method-parameter %}

{% api-method-parameter name="Short Description" type="string" required=false %}
The short dscription of new product.
{% endapi-method-parameter %}

{% api-method-parameter name="CategoryType" type="string" required=false %}
The categorytype of new product.
{% endapi-method-parameter %}

{% api-method-parameter name="CRMCode" type="string" required=false %}
The crmcode of new product.
{% endapi-method-parameter %}

{% api-method-parameter name="ERPCode" type="string" required=false %}
The erpcode of new product.
{% endapi-method-parameter %}

{% api-method-parameter name="Name" type="string" required=true %}
The name of new product
{% endapi-method-parameter %}

{% api-method-parameter name="SessionId" type="string" required=true %}
The SessionId
{% endapi-method-parameter %}

{% api-method-parameter name="UserToken" type="string" required=true %}
The UserToken
{% endapi-method-parameter %}

{% api-method-parameter name="ClientId" type="string" required=true %}
The ClientId
{% endapi-method-parameter %}

{% api-method-parameter name="AppKey" type="string" required=true %}
The AppKey
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Cake successfully retrieved.
{% endapi-method-response-example-description %}

```text
{    "name": "Cake's name",    "recipe": "Cake's recipe name",    "cake": "Binary cake"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-metadata.lidiacommerce.com/categories/update" path="" %}
{% api-method-summary %}
Update Category
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to update categories.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="ERPCODE" type="string" required=false %}
The related product's erp code.
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=false %}
The Environment
{% endapi-method-parameter %}

{% api-method-parameter name="ShortDescription" type="string" required=false %}
The ShortDescription
{% endapi-method-parameter %}

{% api-method-parameter name="LongDescription" type="string" required=false %}
The LongDescription
{% endapi-method-parameter %}

{% api-method-parameter name="CategoryType" type="string" required=false %}
The Category type
{% endapi-method-parameter %}

{% api-method-parameter name="CategoryId" type="integer" required=false %}
Related product's Id
{% endapi-method-parameter %}

{% api-method-parameter name="CRMCode" type="string" required=false %}
The CrmCode
{% endapi-method-parameter %}

{% api-method-parameter name="ERP Code " type="string" required=false %}
The ErpCode
{% endapi-method-parameter %}

{% api-method-parameter name="ClientId" type="string" required=true %}
The ClientId
{% endapi-method-parameter %}

{% api-method-parameter name="UserToken" type="string" required=true %}
The UserToken
{% endapi-method-parameter %}

{% api-method-parameter name="AppKey" type="string" required=true %}
The UserToken
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```text

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-metadata.lidiacommerce.com/metadatas/categories/delete" path="" %}
{% api-method-summary %}
Delete Category
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="Environment" type="string" required=true %}
The Environment
{% endapi-method-parameter %}

{% api-method-parameter name="UserToken" type="string" required=true %}
The UserToken
{% endapi-method-parameter %}

{% api-method-parameter name="CategoryId" type="integer" required=false %}
The related Category Id
{% endapi-method-parameter %}

{% api-method-parameter name="ClientId" type="string" required=true %}
The ClientId
{% endapi-method-parameter %}

{% api-method-parameter name="AppKey" type="string" required=true %}
The AppKey
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```text

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-metadata.lidiacommerce.com/metadatas/metadatas/products/create" path="" %}
{% api-method-summary %}
Update Product
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows to yu create new products.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="ProductId" type="string" required=false %}
The related Product's Id
{% endapi-method-parameter %}

{% api-method-parameter name="LongDescription" type="string" required=false %}
The long description of new product.
{% endapi-method-parameter %}

{% api-method-parameter name="ShortDescription" type="string" required=false %}
The short description of new product.
{% endapi-method-parameter %}

{% api-method-parameter name="CRMCode" type="string" required=false %}
The CRMCode of new product.
{% endapi-method-parameter %}

{% api-method-parameter name="ERPCode" type="string" required=false %}
The ERPCode of new product.
{% endapi-method-parameter %}

{% api-method-parameter name="Code" type="string" required=false %}
The Code of new product
{% endapi-method-parameter %}

{% api-method-parameter name="Name" type="string" required=false %}
The name of new product
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=true %}
The Environment
{% endapi-method-parameter %}

{% api-method-parameter name="UserToken" type="string" required=true %}
The UserToken
{% endapi-method-parameter %}

{% api-method-parameter name="ClientId" type="string" required=true %}
The ClientId
{% endapi-method-parameter %}

{% api-method-parameter name="AppKey" type="string" required=true %}
The AppKey
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```text

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-metadata.lidiacommerce.com/metadatas/products/delete" path="" %}
{% api-method-summary %}
Delete Product
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="UserToken" type="string" required=true %}
The UserToken
{% endapi-method-parameter %}

{% api-method-parameter name="SessionId" type="string" required=true %}
The SessionId
{% endapi-method-parameter %}

{% api-method-parameter name="ClientId" type="string" required=true %}
The ClientId
{% endapi-method-parameter %}

{% api-method-parameter name="AppKey" type="string" required=true %}
The AppKey
{% endapi-method-parameter %}

{% api-method-parameter name="ProductId" type="integer" required=true %}
The related product's id.
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```text

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-metadata.lidiacommerce.com/metadatas/categories/product/create" path="" %}
{% api-method-summary %}
Create Categoy Product
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="Category Product Id" type="string" required=false %}

{% endapi-method-parameter %}

{% api-method-parameter name="ProductId" type="string" required=true %}
The Related ProductId
{% endapi-method-parameter %}

{% api-method-parameter name="UserToken" type="string" required=true %}
The UserToken
{% endapi-method-parameter %}

{% api-method-parameter name="SessionId" type="string" required=true %}
The SessionId
{% endapi-method-parameter %}

{% api-method-parameter name="ClientId" type="string" required=true %}
The ClientId
{% endapi-method-parameter %}

{% api-method-parameter name="AppKey" type="string" required=true %}
The AppKey
{% endapi-method-parameter %}

{% api-method-parameter name="CategoryId" type="integer" required=true %}
The related product's id.
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```text

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-metadata.lidiacommerce.com/metadatas/products/delete" path="" %}
{% api-method-summary %}
Update Category Product
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="CategoryProductId" type="string" required=true %}
The related category product id
{% endapi-method-parameter %}

{% api-method-parameter name="Category Id" type="string" required=true %}
The Related Category Id
{% endapi-method-parameter %}

{% api-method-parameter name="UserToken" type="string" required=true %}
The UserToken
{% endapi-method-parameter %}

{% api-method-parameter name="SessionId" type="string" required=true %}
The SessionId
{% endapi-method-parameter %}

{% api-method-parameter name="ClientId" type="string" required=true %}
The ClientId
{% endapi-method-parameter %}

{% api-method-parameter name="AppKey" type="string" required=true %}
The AppKey
{% endapi-method-parameter %}

{% api-method-parameter name="ProductId" type="integer" required=true %}
The related product's id.
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```text

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-metadata.lidiacommerce.com/categories/product/delete" path="" %}
{% api-method-summary %}
Delete Category Product
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="UserToken" type="string" required=true %}
The UserToken
{% endapi-method-parameter %}

{% api-method-parameter name="SessionId" type="string" required=true %}
The SessionId
{% endapi-method-parameter %}

{% api-method-parameter name="ClientId" type="string" required=true %}
The ClientId
{% endapi-method-parameter %}

{% api-method-parameter name="AppKey" type="string" required=true %}
The AppKey
{% endapi-method-parameter %}

{% api-method-parameter name="CategoryProductId" type="integer" required=true %}
The related categoryproduct id.
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```text

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}


{% api-method method="post" host="https://api-metadata.lidiacommerce.com/categories/product/delete" path="" %}
{% api-method-summary %}
Create Product Variant
{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="UserToken" type="string" required=true %}
The UserToken
{% endapi-method-parameter %}

{% api-method-parameter name="SessionId" type="string" required=true %}
The SessionId
{% endapi-method-parameter %}

{% api-method-parameter name="ClientId" type="string" required=true %}
The ClientId
{% endapi-method-parameter %}

{% api-method-parameter name="AppKey" type="string" required=true %}
The AppKey
{% endapi-method-parameter %}

{% api-method-parameter name="CategoryProductId" type="integer" required=true %}
The related categoryproduct id.
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```text

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

