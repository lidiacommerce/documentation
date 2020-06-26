---
description: 'The back-end logic to manage users, account or customers'
---

# Identity

Below you will find all you need to manage your users, accounts and customers in your mobile application.

{% hint style="warning" %}
Please note that in order to use these API functions you will need a valid **ClientId** and **AppKey** which you can get after you sign up on **Lidia Commerce Platform website** and subscribe for 
{% endhint %}

{% api-method method="post" host="https://api-mobile.lidiacommerce.com" path="/identity/register" %}
{% api-method-summary %}
Register
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to register \(sign up\) a user to your application.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="ClientId" type="string" required=true %}
Identifies the client \(your application\). By using this parameter we know who is calling our API function.
{% endapi-method-parameter %}

{% api-method-parameter name="AppKey" type="string" required=true %}
This is your unique application key \(or application secret you might have seen on other API documents\) which we provide you once you are successful subscribed to **Lidia Mobile** on **Lidia Commerce Platform website.**
{% endapi-method-parameter %}

{% api-method-parameter name="Token" type="string" required=true %}
This your unique token which you get as a response to your authentication request. 
{% endapi-method-parameter %}

{% api-method-parameter name="UserIP" type="string" required=true %}
This is the current IP address of the device calling the API function.
{% endapi-method-parameter %}

{% api-method-parameter name="Firstname" type="string" required=false %}
The first name of your new user.
{% endapi-method-parameter %}

{% api-method-parameter name="Lastname" type="string" required=false %}
The last name of your new user.
{% endapi-method-parameter %}

{% api-method-parameter name="Email" type="string" required=true %}
The e-mail of your new user.
{% endapi-method-parameter %}

{% api-method-parameter name="Password" type="string" required=true %}
The password of your new user.
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
After the registration attempt the API will **always return a HTTP 200 \(OK\) message.** In order to understand the details of the response you need to look at the **Type** parameter of the response object.  
The **responses** will look like this:
{% endapi-method-response-example-description %}

```
{
    "Result": [
        {
            "UserId": "1032",
            "Firstname": "Ad",
            "Lastname": "Soyad",
            "Email": "abc@getnada.com",
            "Mobile": null,
            "Created": "0001-01-01T00:00:00",
            "Status": 1
        }
    ],
    "PreProcessingTook": 1795,
    "ServiceTook": 3915,
    "TotalTook": 5710,
    "Type": 4,
    "Source": 0,
    "Code": null,
    "Message": "User successfuly regidtere. UserId:1032",
    "Details": null,
    "ResultCount": 1,
    "TotalCount": 0,
    "CurrentPageIndex": 0,
    "Errors": [],
    "InnerResponse": null
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-mobile.lidiacommerce.com" path="/identity/login" %}
{% api-method-summary %}

{% endapi-method-summary %}

{% api-method-description %}

{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="ClientId" type="string" required=true %}
\*\*\*\*
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



