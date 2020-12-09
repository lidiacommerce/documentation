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

```
{    "name": "Cake's name",    "recipe": "Cake's recipe name",    "cake": "Binary cake"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



