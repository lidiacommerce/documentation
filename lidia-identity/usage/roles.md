---
description: The API functions to manage roles
---

# Roles

Below you will find all you need to manage roles in your application.

{% hint style="warning" %}
Please note that in order to use these API functions you will need a valid **ClientId** and **AppKey** which you can get after you sign up on Lidia Commerce Platform website and subscribe for
{% endhint %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/roles/create" %}
{% api-method-summary %}
Create Role
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to create roles.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="ClientId" type="string" required=true %}
Identifies the client \(your application\). By using this parameter we know who is calling our API function.
{% endapi-method-parameter %}

{% api-method-parameter name="AppKey" type="string" required=true %}
This is your unique application key \(or application secret you might have seen on other API documents\) which we provide you once your are successful subscribed to Lidia Identity.
{% endapi-method-parameter %}

{% api-method-parameter name="UserToken" type="string" required=false %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=false %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="SourceRoleCode" type="string" required=false %}
If you have an Id for this role on your side please provide it here.
{% endapi-method-parameter %}

{% api-method-parameter name="Name" type="string" required=true %}
The name of the role
{% endapi-method-parameter %}

{% api-method-parameter name="Description" type="string" required=true %}
The description of the role
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=false %}
The status of the role. Possible values are:  
-1 - Passive  
0 - Draft  
1 - Active
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
All Lidia Commerce API responses \(including the ones with errors/problems\) use HTTP 200 by default.
{% endapi-method-response-example-description %}

```text
{"name": "Role1"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/roles/update" %}
{% api-method-summary %}
Update Role
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to update roles.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="SessionId" type="string" required=true %}
The session Id
{% endapi-method-parameter %}

{% api-method-parameter name="ClientId" type="string" required=true %}
Identifies the client \(your application\). By using this parameter we know who is calling our API function.
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedRoleId" type="int" required=true %}
Identifies the related role id.
{% endapi-method-parameter %}

{% api-method-parameter name="AppKey" type="string" required=true %}
This is your unique application key \(or application secret you might have seen on other API documents\) which we provide you once your are successful subscribed to Lidia Identity.
{% endapi-method-parameter %}

{% api-method-parameter name="UserToken" type="string" required=false %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=false %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="SourceRoleCode" type="string" required=false %}
If you have an Id for this role on your side please provide it here.
{% endapi-method-parameter %}

{% api-method-parameter name="Name" type="string" required=true %}
The name of the role
{% endapi-method-parameter %}

{% api-method-parameter name="Description" type="string" required=true %}
The description of the role
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=true %}
The status of the role. Possible values are:  
-1 - Passive  
0 - Draft  
1 - Active
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
All Lidia Commerce API responses \(including the ones with errors/problems\) use HTTP 200 by default.
{% endapi-method-response-example-description %}

```text
{    "message": "Role updated succesfully."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/roles/remove" %}
{% api-method-summary %}
Remove Role
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to remove roles.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="UserId" type="string" required=false %}
The auth user id
{% endapi-method-parameter %}

{% api-method-parameter name="UserToken" type="string" required=true %}
The authentication token
{% endapi-method-parameter %}

{% api-method-parameter name="ClientId" type="string" required=true %}
Identifies the client \(your application\). By using this parameter we know who is calling our API function.
{% endapi-method-parameter %}

{% api-method-parameter name="AppKey" type="string" required=true %}
This is your unique application key \(or application secret you might have seen on other API documents\) which we provide you once your are successful subscribed to Lidia Identity.
{% endapi-method-parameter %}

{% api-method-parameter name="RoleId" type="int" required=true %}
This is your Role Id to be deleted. \(or application secret you might have seen on other API documents\) which we provide you once your are successful subscribed to Lidia Identity.
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
All Lidia Commerce API responses \(including the ones with errors/problems\) use HTTP 200 by default.
{% endapi-method-response-example-description %}

```text
{    "message": "Role deleted succesfully."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

