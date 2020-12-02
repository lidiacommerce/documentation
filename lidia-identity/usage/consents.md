
---
description: The API functions to manage consents
---

# Consents

Below you will find all you need to manage user consents in your application.

{% hint style="warning" %}
Please note that in order to use these API functions you will need a valid **ClientId** and **AppKey** which you can get after you sign up on Lidia Commerce Platform website and subscribe for
{% endhint %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/consents/create" %}
{% api-method-summary %}
Create User Consents
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to create user consents.
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

{% api-method-parameter name="Token" type="string" required=true %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=true %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="UserId" type="int" required=true %}
Identifies the application user triggering this API call. For For audit purposes please provide the ID of the user currently logged in to your application.
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserToken" type="string" required=true %}
Identifies the application user triggering this API call. If the user is **not** authenticated please provide a unique token which should be the same across different API calls triggered by the same user. If the user if authenticated please use UserId field.
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserIp" type="string" required=true %}
Identifies the application user triggering this API call. If the user is **not** authenticated please provide a unique token which should be the same across different API calls triggered by the same user. If the user if authenticated please use UserId field.
{% endapi-method-parameter %}

{% api-method-parameter name="Scope" type="string" required=false %}
Identifies the application user triggering this API call. If the user is **not** authenticated please provide a unique token which should be the same across different API calls triggered by the same user. If the user if authenticated please use UserId field.
{% endapi-method-parameter %}

{% api-method-parameter name="ValidForm" type="string" required=false %}
Identifies the application user triggering this API call. If the user is **not** authenticated please provide a unique token which should be the same across different API calls triggered by the same user. If the user if authenticated please use UserId field.
{% endapi-method-parameter %}

{% api-method-parameter name="UserIP" type="string" required=false %}
The IP of the user triggering this API call.
{% endapi-method-parameter %}

{% api-method-parameter name="SessionId" type="string" required=false %}
The session Id of the user triggering this API call.
{% endapi-method-parameter %}

{% api-method-parameter name="DocumentId" type="int" required=false %}
The Consent Document Id.
{% endapi-method-parameter %}

{% api-method-parameter name="ThreadId" type="string" required=false %}
The unique thread Id to observe sub function calls of the same process. If you do not provide this, the API will create a new one and use it.   
Details about why and how to use **ThreadId** you can find here.
{% endapi-method-parameter %}


{% api-method-parameter name="Password" type="string" required=false %}
The Password of the user.
{% endapi-method-parameter %}

{% api-method-parameter name="TimeStamp" type="datetime" required=true %}
The TimeStamp 
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=true %}
The status of the consent. Possible values are:  
-1 - Passive   
 0 - Draft  
 1 - Active
{% endapi-method-parameter %}

{% api-method-parameter name="Activity" type="string" required=true %}
The status of the consent. Possible values are:  
 100 - Given   
 -100 - Revoked
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
All Lidia Commerce API responses (including the ones with errors/problems) use HTTP 200 by default. 
{% endapi-method-response-example-description %}
```
{"name": "Consent1"}
```
{% endapi-method-response-example %}


```
{    "message": "Consent could not received. Try again."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/consent/update" %}
{% api-method-summary %}
Update Consent
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to update consents.
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

{% api-method-parameter name="Token" type="string" required=true %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=true %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="ConsentId" type="int" required=true %}
Related Consent Id
{% endapi-method-parameter %}

{% api-method-parameter name="UserId" type="int" required=true %}
Identifies the application user triggering this API call. For For audit purposes please provide the ID of the user currently logged in to your application.
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserToken" type="string" required=true %}
Identifies the application user triggering this API call. If the user is **not** authenticated please provide a unique token which should be the same across different API calls triggered by the same user. If the user if authenticated please use UserId field.
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserIp" type="string" required=true %}
Identifies the application user triggering this API call. If the user is **not** authenticated please provide a unique token which should be the same across different API calls triggered by the same user. If the user if authenticated please use UserId field.
{% endapi-method-parameter %}

{% api-method-parameter name="Scope" type="string" required=false %}
Identifies the application user triggering this API call. If the user is **not** authenticated please provide a unique token which should be the same across different API calls triggered by the same user. If the user if authenticated please use UserId field.
{% endapi-method-parameter %}

{% api-method-parameter name="ValidForm" type="string" required=false %}
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


{% api-method-parameter name="FirstName" type="string" required=true %}
FirstName of the user.
{% endapi-method-parameter %}

{% api-method-parameter name="Password" type="string" required=false %}
The Password of the user.
{% endapi-method-parameter %}

{% api-method-parameter name="TimeStamp" type="datetime" required=true %}
The TimeStamp 
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=true %}
The status of the consent. Possible values are:  
-1 - Passive   
 0 - Draft  
 1 - Active
{% endapi-method-parameter %}

{% api-method-parameter name="Activity" type="string" required=true %}
The status of the consent. Possible values are:  
 100 - Given   
 -100 - Revoked
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
{% endapi-method-response-example-description %}

{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
All Lidia Commerce API responses (including the ones with errors/problems) use HTTP 200 by default. 
{% endapi-method-response-example-description %}
```
The consent updated successfully
```
{% endapi-method-response-example %}


```
{    "message": "Consent could not updated. Try again."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/consents/remove" %}
{% api-method-summary %}
Remove Consent
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to remove consents.
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

{% api-method-parameter name="ConsentId" type="int" required=true %}
This is related consent Id.
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserId" type="int" required=true %}
This is related user id.
{% endapi-method-parameter %}

{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
All Lidia Commerce API responses (including the ones with errors/problems) use HTTP 200 by default. 
{% endapi-method-response-example-description %}
```
The consent deleted successfully
```
{% endapi-method-response-example %}


```
{    "message": "Consent could not deleted. Try again."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/consents/document/create" %}
{% api-method-summary %}
Create Consent Document
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to create consent documents.
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

{% api-method-parameter name="PublisherId" type="int" required=false %}
PublisherId
{% endapi-method-parameter %}

{% api-method-parameter name="Title" type="string" required=true %}
The document's title.
{% endapi-method-parameter %}

{% api-method-parameter name="Body" type="string" required=true %}
The document's body.
{% endapi-method-parameter %}

{% api-method-parameter name="Body" type="string" required=true %}
The document's body.
{% endapi-method-parameter %}

{% api-method-parameter name="Code" type="string" required=true %}
Code
{% endapi-method-parameter %}

{% api-method-parameter name="Version" type="decimal" required=true %}
Version of document
{% endapi-method-parameter %}

{% api-method-parameter name="ValidFrom" type="datetime" required=true %}
Validity start date of the document
{% endapi-method-parameter %}

{% api-method-parameter name="ValidTo" type="datetime" required=false %}
Validity end date of the document
{% endapi-method-parameter %}

{% api-method-parameter name="Changes" type="string" required=false %}
Changes
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=true %}
The status of the document. Possible values are:  
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
The document added successfully
```
{% endapi-method-response-example %}


```
{    "message": "Document could not created. Try again."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/consents/document/update" %}
{% api-method-summary %}
Update Consent Document
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to update consent documents.
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

{% api-method-parameter name="PublisherId" type="int" required=false %}
PublisherId
{% endapi-method-parameter %}

{% api-method-parameter name="DocumentId" type="int" required=true %}
DocumentId
{% endapi-method-parameter %}

{% api-method-parameter name="Title" type="string" required=true %}
The document's title.
{% endapi-method-parameter %}

{% api-method-parameter name="Body" type="string" required=true %}
The document's body.
{% endapi-method-parameter %}

{% api-method-parameter name="Body" type="string" required=true %}
The document's body.
{% endapi-method-parameter %}

{% api-method-parameter name="Code" type="string" required=true %}
Code
{% endapi-method-parameter %}

{% api-method-parameter name="Version" type="decimal" required=true %}
Version of document
{% endapi-method-parameter %}

{% api-method-parameter name="ValidFrom" type="datetime" required=true %}
Validity start date of the document
{% endapi-method-parameter %}

{% api-method-parameter name="ValidTo" type="datetime" required=false %}
Validity end date of the document
{% endapi-method-parameter %}

{% api-method-parameter name="Changes" type="string" required=false %}
Changes
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=true %}
The status of the document. Possible values are:  
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
The document updated successfully
```
{% endapi-method-response-example %}


```
{    "message": "Document could not updated. Try again."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/consents/document/delete" %}
{% api-method-summary %}
Delete Consent Document
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to update consent documents.
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

{% api-method-parameter name="DocumentId" type="int" required=true %}
DocumentId
{% endapi-method-parameter %}

{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
All Lidia Commerce API responses (including the ones with errors/problems) use HTTP 200 by default. 
{% endapi-method-response-example-description %}
```
The document deleted successfully
```
{% endapi-method-response-example %}


```
{    "message": "Document could not deleted. Try again."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/consents/document/publisher/create" %}
{% api-method-summary %}
Create Consent Document Publisher
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to create consent document publishers.
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

{% api-method-parameter name="Token" type="string" required=true %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=true %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="OrganizationId" type="int" required=true %}
OrganizationId
{% endapi-method-parameter %}

{% api-method-parameter name="OrganizationId" type="int" required=true %}
OrganizationId
{% endapi-method-parameter %}

{% api-method-parameter name="Name" type="string" required=true %}
The related publisher's name
{% endapi-method-parameter %}

{% api-method-parameter name="Adress" type="string" required=true %}
The related publisher's adress
{% endapi-method-parameter %}

{% api-method-parameter name="Country" type="string" required=true %}
The related publisher's country
{% endapi-method-parameter %}

{% api-method-parameter name="City" type="string" required=true %}
The related publisher's city.
{% endapi-method-parameter %}

{% api-method-parameter name="SessionId" type="string" required=false %}
The session Id of the user triggering this API call.
{% endapi-method-parameter %}

{% api-method-parameter name="ThreadId" type="string" required=false %}
The unique thread Id to observe sub function calls of the same process. If you do not provide this, the API will create a new one and use it.   
Details about why and how to use **ThreadId** you can find here.
{% endapi-method-parameter %}

{% api-method-parameter name="TimeStamp" type="datetime" required=true %}
The TimeStamp 
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=true %}
The status of the consent document publisher Possible values are:  
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
{"name": "Consent document publisher1"}
```
{% endapi-method-response-example %}


```
{    "message": "Consent could not received. Try again."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}