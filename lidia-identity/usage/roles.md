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

{% api-method-parameter name="Token" type="string" required=false %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=false %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="UserId" type="string" required=false %}
Identifies the application user triggering this API call. For For audit purposes please provide the ID of the user currently logged in to your application.
{% endapi-method-parameter %}

{% api-method-parameter name="UserToken" type="string" required=false %}
Identifies the application user triggering this API call. If the user is **not** authenticated please provide a unique token which should be the same across different API calls triggered by the same user. If the user if authenticated please use UserId field.
{% endapi-method-parameter %}

{% api-method-parameter name="UserIP" type="string" required=false %}
The IP of the user triggering this API call.
{% endapi-method-parameter %}

{% api-method-parameter name="SessionId" type="string" required=false %}
The session Id of the user triggering this API call.
{% endapi-method-parameter %}

{% api-method-parameter name="ThreadId" type="string" required=false %}
The unique thread Id to observe sub function calls of the same process. If you do not provide this, the API will create a new one and use it.   
Details about why and how to use **ThreadId** you can find here.
{% endapi-method-parameter %}

{% api-method-parameter name="SourceRoleCode" type="string" required=false %}
If you have an Id for this role on your side please provide it here.
{% endapi-method-parameter %}

{% api-method-parameter name="Name" type="string" required=false %}
The name of the role
{% endapi-method-parameter %}

{% api-method-parameter name="Description" type="string" required=false %}
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
All Lidia Commerce API responses (including the ones with errors/problems) use HTTP 200 by default. 
{% endapi-method-response-example-description %}
```
{"name": "Role1"}
```
{% endapi-method-response-example %}


```
{    "message": "Role could not received. Try again."}
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
{% api-method-parameter name="ClientId" type="string" required=true %}
Identifies the client \(your application\). By using this parameter we know who is calling our API function.
{% endapi-method-parameter %}

{% api-method-parameter name="AppKey" type="string" required=true %}
This is your unique application key \(or application secret you might have seen on other API documents\) which we provide you once your are successful subscribed to Lidia Identity.
{% endapi-method-parameter %}

{% api-method-parameter name="Token" type="string" required=false %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=false %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="UserId" type="string" required=false %}
Identifies the application user triggering this API call. For For audit purposes please provide the ID of the user currently logged in to your application.
{% endapi-method-parameter %}

{% api-method-parameter name="UserToken" type="string" required=false %}
Identifies the application user triggering this API call. If the user is **not** authenticated please provide a unique token which should be the same across different API calls triggered by the same user. If the user if authenticated please use UserId field.
{% endapi-method-parameter %}

{% api-method-parameter name="UserIP" type="string" required=false %}
The IP of the user triggering this API call.
{% endapi-method-parameter %}

{% api-method-parameter name="SessionId" type="string" required=false %}
The session Id of the user triggering this API call.
{% endapi-method-parameter %}

{% api-method-parameter name="ThreadId" type="string" required=false %}
The unique thread Id to observe sub function calls of the same process. If you do not provide this, the API will create a new one and use it.   
Details about why and how to use **ThreadId** you can find here.
{% endapi-method-parameter %}

{% api-method-parameter name="SourceRoleCode" type="string" required=false %}

{% endapi-method-parameter %}

{% api-method-parameter name="RoleId" type="integer" required=true %}

{% endapi-method-parameter %}

{% api-method-parameter name="Name" type="string" required=false %}
The name of the role to be updated.
{% endapi-method-parameter %}

{% api-method-parameter name="Description" type="string" required=false %}
The description of the role to be updated.
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=false %}
The status of the role to be updated. Possible values are:  
-1 - Passive  
 0 - Draft  
 1 - Active
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
{% endapi-method-response-example-description %}

{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Operation failed.
{% endapi-method-response-example-description %}

```
{    "message": "Role could not updated. Try again."}
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
All Lidia Commerce API responses (including the ones with errors/problems) use HTTP 200 by default. 
{% endapi-method-response-example-description %}
```
The role deleted successfully
```
{% endapi-method-response-example %}


```
{    "message": "Role could not deleted. Try again."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

