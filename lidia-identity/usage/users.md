---
description: The API functions to manage users
---

# Users

Below you will find all you need to manage users in your application.

{% hint style="warning" %}
Please note that in order to use these API functions you will need a valid **ClientId** and **AppKey** which you can get after you sign up on Lidia Commerce Platform website and subscribe for
{% endhint %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/create" %}
{% api-method-summary %}
Create User
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to create users.
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

{% api-method-parameter name="UserToken" type="string" required=true %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=true %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="Firstname" type="string" required=true %}
This is Firstname of user to be created.
{% endapi-method-parameter %}

{% api-method-parameter name="Lastname" type="string" required=true %}
This is Lastname of user to be created.
{% endapi-method-parameter %}

{% api-method-parameter name="MobileNumber" type="string" required=false %}
The mobile number of new user
{% endapi-method-parameter %}

{% api-method-parameter name="Email" type="string" required=true %}
Email of the new user.
{% endapi-method-parameter %}

{% api-method-parameter name="CitizenId" type="string" required=false %}
CitizenId
{% endapi-method-parameter %}

{% api-method-parameter name="Phone Number" type="string" required=false %}
PhoneNumber
{% endapi-method-parameter %}

{% api-method-parameter name="UserToken" type="string" required=false %}
Identifies the application user triggering this API call. If the user is **not** authenticated please provide a unique token which should be the same across different API calls triggered by the same user. If the user if authenticated please use UserId field.
{% endapi-method-parameter %}

{% api-method-parameter name="SourceUserCode" type="string" required=false %}
Source User Code
{% endapi-method-parameter %}

{% api-method-parameter name="Gender" type="string" required=false %}
Related user's gender
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
All Lidia Commerce API responses \(including the ones with errors/problems\) use HTTP 200 by default.
{% endapi-method-response-example-description %}

```text
{"name": "User1"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/update" %}
{% api-method-summary %}
Update User
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to create users.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="Email" type="string" required=true %}
The email of new user
{% endapi-method-parameter %}

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

{% api-method-parameter name="Firstname" type="string" required=true %}
This is Firstname of user to be created.
{% endapi-method-parameter %}

{% api-method-parameter name="Lastname" type="string" required=true %}
This is Lastname of user to be created.
{% endapi-method-parameter %}

{% api-method-parameter name="CitizenId" type="string" required=false %}
CitizenId
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserId" type="int" required=true %}
Related user's id
{% endapi-method-parameter %}

{% api-method-parameter name="Phone Number" type="string" required=false %}
PhoneNumber
{% endapi-method-parameter %}

{% api-method-parameter name="UserToken" type="string" required=false %}
Identifies the application user triggering this API call. If the user is **not** authenticated please provide a unique token which should be the same across different API calls triggered by the same user. If the user if authenticated please use UserId field.
{% endapi-method-parameter %}

{% api-method-parameter name="SourceUserCode" type="string" required=false %}
Source User Code
{% endapi-method-parameter %}

{% api-method-parameter name="Gender" type="string" required=false %}
Related user's gender
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
All Lidia Commerce API responses \(including the ones with errors/problems\) use HTTP 200 by default.
{% endapi-method-response-example-description %}

```text
{"name": "User1"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/remove" %}
{% api-method-summary %}
Remove User
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to remove users.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-form-data-parameters %}
{% api-method-parameter name="UserToken" type="string" required=true %}
The user token 
{% endapi-method-parameter %}

{% api-method-parameter name="ClientId" type="string" required=true %}
Identifies the client \(your application\). By using this parameter we know who is calling our API function.
{% endapi-method-parameter %}

{% api-method-parameter name="AppKey" type="string" required=true %}
This is your unique application key \(or application secret you might have seen on other API documents\) which we provide you once your are successful subscribed to Lidia Identity.
{% endapi-method-parameter %}

{% api-method-parameter name="UserId" type="int" required=true %}
This is your User Id to be deleted. \(or application secret you might have seen on other API documents\) which we provide you once your are successful subscribed to Lidia Identity.
{% endapi-method-parameter %}

{% api-method-parameter name="SourceRelatedUserCode" type="string" required=false %}
SourceRelatedUserCode
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
All Lidia Commerce API responses \(including the ones with errors/problems\) use HTTP 200 by default.
{% endapi-method-response-example-description %}

```text
The user deleted successfully
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/role/add" %}
{% api-method-summary %}
Add User Role
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to add user roles.
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

{% api-method-parameter name="UserToken" type="string" required=true %}
UserToken
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=true %}
Environment
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserId" type="int" required=true %}
This is your User Id to be matched.
{% endapi-method-parameter %}

{% api-method-parameter name="RoleId" type="int" required=true %}
This is your Role Id to be matched.
{% endapi-method-parameter %}

{% api-method-parameter name="SourceRelatedUserCode" type="string" required=false %}
SourceRelatedUserCode
{% endapi-method-parameter %}

{% api-method-parameter name="Extra" type="string" required=false %}
Extra
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=false %}
The status of the userrole to be created. Possible values are:  
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
The userrole added successfully!
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/role/delete" %}
{% api-method-summary %}
Delete User Role
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to delete user roles.
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

{% api-method-parameter name="UserToken" type="string" required=true %}
The user token
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserId" type="int" required=true %}
This is your User Id to be matched.
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedRoleId" type="int" required=true %}
This is your Role Id to be matched.
{% endapi-method-parameter %}

{% api-method-parameter name="SourceRelatedUserCode" type="string" required=false %}
SourceRelatedUserCode
{% endapi-method-parameter %}

{% api-method-parameter name="SourceRoleCode" type="string" required=false %}
SourceRoleCode
{% endapi-method-parameter %}

{% api-method-parameter name="RoleName" type="string" required=false %}
RoleName
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
All Lidia Commerce API responses \(including the ones with errors/problems\) use HTTP 200 by default.
{% endapi-method-response-example-description %}

```text
The userrole deleted successfully!
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/password/update" %}
{% api-method-summary %}
Update User Password
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to update user password.
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

{% api-method-parameter name="UserToken" type="string" required=true %}
The UserToken
{% endapi-method-parameter %}

{% api-method-parameter name="UserToken" type="string" required=false %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=false %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="UserIP" type="string" required=false %}
The IP of the user triggering this API call.
{% endapi-method-parameter %}

{% api-method-parameter name="UserId" type="int" required=true %}
User Id making the request
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserId" type="int" required=true %}
UserId to be updated.
{% endapi-method-parameter %}

{% api-method-parameter name="SessionId" type="string" required=false %}
The session Id of the user triggering this API call.
{% endapi-method-parameter %}

{% api-method-parameter name="ThreadId" type="string" required=false %}
The unique thread Id to observe sub function calls of the same process. If you do not provide this, the API will create a new one and use it.  
Details about why and how to use **ThreadId** you can find here.
{% endapi-method-parameter %}

{% api-method-parameter name="TimeStamp" type="datetime" required=false %}
TimeStamp
{% endapi-method-parameter %}

{% api-method-parameter name="PasswordHash" type="string" required=true %}
Encrypted user password to be updated
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
All Lidia Commerce API responses \(including the ones with errors/problems\) use HTTP 200 by default.
{% endapi-method-response-example-description %}

```text
{"The password updated successfully"}
{"Error try again"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/adress/add" %}
{% api-method-summary %}
Create User Adress
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to create user adress.
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

{% api-method-parameter name="UserToken" type="string" required=true %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=false %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="UserIP" type="string" required=false %}
The IP of the user triggering this API call.
{% endapi-method-parameter %}

{% api-method-parameter name="UserId" type="int" required=true %}
User Id making the request
{% endapi-method-parameter %}

{% api-method-parameter name="FirstName" type="string" required=true %}
The related user's first name.
{% endapi-method-parameter %}

{% api-method-parameter name="LastName" type="string" required=true %}
The related user's last name.
{% endapi-method-parameter %}

{% api-method-parameter name="SourceRelatedUserCode" type="string" required=true %}
SourceRelatedUserCode
{% endapi-method-parameter %}

{% api-method-parameter name="Title" type="string" required=true %}
The title of the new adress.
{% endapi-method-parameter %}

{% api-method-parameter name="Name" type="string" required=true %}
The name of the new adress.
{% endapi-method-parameter %}

{% api-method-parameter name="Neighborhood" type="string" required=true %}
The neighborhood of the new adress.
{% endapi-method-parameter %}

{% api-method-parameter name="City" type="string" required=true %}
The city of the new adress.
{% endapi-method-parameter %}

{% api-method-parameter name="StreetAddress" type="string" required=true %}
The streetaddress of the new adress.
{% endapi-method-parameter %}

{% api-method-parameter name="District" type="string" required=true %}
The district of the new adress.
{% endapi-method-parameter %}

{% api-method-parameter name="Region" type="string" required=true %}
The region of the new adress.
{% endapi-method-parameter %}

{% api-method-parameter name="Country" type="string" required=true %}
The country of the new adress.
{% endapi-method-parameter %}

{% api-method-parameter name="Phone" type="string" required=true %}
The phone of the related user.
{% endapi-method-parameter %}

{% api-method-parameter name="ZipCode" type="string" required=true %}
The country of the new adress.
{% endapi-method-parameter %}

{% api-method-parameter name="ThreadId" type="string" required=false %}
The unique thread Id to observe sub function calls of the same process. If you do not provide this, the API will create a new one and use it.  
Details about why and how to use **ThreadId** you can find here.
{% endapi-method-parameter %}

{% api-method-parameter name="TimeStamp" type="datetime" required=false %}
TimeStamp
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=false %}
The status of the user adress to be created. Possible values are:  
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
{"The user adress added successfully"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/adress/update" %}
{% api-method-summary %}
Update User Adress
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to update user adress.
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

{% api-method-parameter name="UserToken" type="string" required=true %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=false %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="UserIP" type="string" required=false %}
The IP of the user triggering this API call.
{% endapi-method-parameter %}

{% api-method-parameter name="UserId" type="int" required=true %}
User Id making the request
{% endapi-method-parameter %}

{% api-method-parameter name="AdressId" type="int" required=true %}
Adress Id to be deleted.
{% endapi-method-parameter %}

{% api-method-parameter name="FirstName" type="string" required=true %}
The related user's first name.
{% endapi-method-parameter %}

{% api-method-parameter name="LastName" type="string" required=true %}
The related user's last name.
{% endapi-method-parameter %}

{% api-method-parameter name="SourceRelatedUserCode" type="string" required=true %}
SourceRelatedUserCode
{% endapi-method-parameter %}

{% api-method-parameter name="Title" type="string" required=true %}
The title of the adress to be updated.
{% endapi-method-parameter %}

{% api-method-parameter name="Name" type="string" required=true %}
The name of the adress to be updated.
{% endapi-method-parameter %}

{% api-method-parameter name="Neighborhood" type="string" required=true %}
The neighborhood adress to be updated.
{% endapi-method-parameter %}

{% api-method-parameter name="City" type="string" required=true %}
The city of the adress to be updated.
{% endapi-method-parameter %}

{% api-method-parameter name="StreetAddress" type="string" required=true %}
The streetaddress of the adress to be updated.
{% endapi-method-parameter %}

{% api-method-parameter name="District" type="string" required=true %}
The district of the adress to be updated.
{% endapi-method-parameter %}

{% api-method-parameter name="Region" type="string" required=true %}
The region of the adress to be updated.
{% endapi-method-parameter %}

{% api-method-parameter name="Country" type="string" required=true %}
The country of the adress to be updated.
{% endapi-method-parameter %}

{% api-method-parameter name="Phone" type="string" required=true %}
The phone of the related user.
{% endapi-method-parameter %}

{% api-method-parameter name="ZipCode" type="string" required=true %}
The zipcode of the adress to be updated.
{% endapi-method-parameter %}

{% api-method-parameter name="ThreadId" type="string" required=false %}
The unique thread Id to observe sub function calls of the same process. If you do not provide this, the API will create a new one and use it.  
Details about why and how to use **ThreadId** you can find here.
{% endapi-method-parameter %}

{% api-method-parameter name="TimeStamp" type="datetime" required=false %}
TimeStamp
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=false %}
The status of the user adress to be created. Possible values are:  
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
{"The user adress updated successfully"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/adress/remove" %}
{% api-method-summary %}
Remove User Adress
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to remove user adress.
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


{% api-method-parameter name="UserToken" type="string" required=true %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}


{% api-method-parameter name="Environment" type="string" required=false %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="UserIP" type="string" required=false %}
The IP of the user triggering this API call.
{% endapi-method-parameter %}

{% api-method-parameter name="AdressId" type="int" required=true %}
Adress Id to be deleted.
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
All Lidia Commerce API responses \(including the ones with errors/problems\) use HTTP 200 by default.
{% endapi-method-response-example-description %}

```text
{"The user adress deleted successfully"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/logins/add" %}
{% api-method-summary %}
Create User Login
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to create users logins.
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

{% api-method-parameter name="UserToken" type="string" required=true %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=false %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserId" type="int" required=true %}
The related user id.
{% endapi-method-parameter %}

{% api-method-parameter name="SourceRelatedUserCode" type="string" required=true %}
SourceRelatedUserCode
{% endapi-method-parameter %}

{% api-method-parameter name="Provider" type="string" required=true %}
Provider
{% endapi-method-parameter %}

{% api-method-parameter name="ProviderKey" type="string" required=true %}
ProviderKey
{% endapi-method-parameter %}

{% api-method-parameter name="SessionId" type="string" required=false %}
The session Id of the user triggering this API call.
{% endapi-method-parameter %}

{% api-method-parameter name="ThreadId" type="string" required=false %}
The unique thread Id to observe sub function calls of the same process. If you do not provide this, the API will create a new one and use it.  
Details about why and how to use **ThreadId** you can find here.
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=false %}
The status of the userlogin to be created. Possible values are:  
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
{"name": "UserLogin1"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/logins/remove" %}
{% api-method-summary %}
Remove User Login
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to remove user logins.
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

{% api-method-parameter name="UserToken" type="string" required=true %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=false %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="LoginId" type="int" required=true %}
The related login id.
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserId" type="int" required=true %}
The related user id.
{% endapi-method-parameter %}

{% api-method-parameter name="SourceRelatedUserCode" type="string" required=true %}
SourceRelatedUserCode
{% endapi-method-parameter %}

{% api-method-parameter name="Provider" type="string" required=true %}
Provider
{% endapi-method-parameter %}

{% api-method-parameter name="ProviderKey" type="string" required=true %}
ProviderKey
{% endapi-method-parameter %}

{% api-method-parameter name="SessionId" type="string" required=false %}
The session Id of the user triggering this API call.
{% endapi-method-parameter %}

{% api-method-parameter name="ThreadId" type="string" required=false %}
The unique thread Id to observe sub function calls of the same process. If you do not provide this, the API will create a new one and use it.  
Details about why and how to use **ThreadId** you can find here.
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
All Lidia Commerce API responses \(including the ones with errors/problems\) use HTTP 200 by default.
{% endapi-method-response-example-description %}

```text
{"User login deleted successfully"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/billinginfo/add" %}
{% api-method-summary %}
Create User Billing Info
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to create users billing infos.
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

{% api-method-parameter name="UserToken" type="string" required=true %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=false %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="SourceRelatedUserCode" type="string" required=false %}
SourceRelatedUserCode
{% endapi-method-parameter %}

{% api-method-parameter name="SourceBillingInfoCode" type="string" required=false %}
SourceBillingInfoCode
{% endapi-method-parameter %}

{% api-method-parameter name="SourceBillingInfoCode" type="string" required=false %}
SourceBillingInfoCode
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserId" type="int" required=true %}
The User Id to be matched
{% endapi-method-parameter %}

{% api-method-parameter name="Name" type="string" required=true %}
The name of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="Title" type="string" required=true %}
The title of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="StreetAdress" type="string" required=true %}
The StreetAdress of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="District" type="string" required=true %}
The District of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="Neighborhood" type="string" required=true %}
The Neighborhood of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="City" type="string" required=true %}
The City of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="Region" type="string" required=true %}
The Region of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="Country" type="string" required=true %}
The Country of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="Phone" type="string" required=true %}
The Phone of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="ZipCode" type="string" required=true %}
The Phone of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="ThreadId" type="string" required=false %}
The unique thread Id to observe sub function calls of the same process. If you do not provide this, the API will create a new one and use it.  
Details about why and how to use **ThreadId** you can find here.
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=false %}
The status of the billinginfo to be created. Possible values are:  
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
{"name": "Bill1ngInfo1"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/billinginfo/update" %}
{% api-method-summary %}
Update User Billing Info
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to update users billing infos.
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

{% api-method-parameter name="UserToken" type="string" required=true %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=false %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="SourceRelatedUserCode" type="string" required=false %}
SourceRelatedUserCode
{% endapi-method-parameter %}

{% api-method-parameter name="SourceBillingInfoCode" type="string" required=false %}
SourceBillingInfoCode
{% endapi-method-parameter %}

{% api-method-parameter name="SourceBillingInfoCode" type="string" required=false %}
SourceBillingInfoCode
{% endapi-method-parameter %}

{% api-method-parameter name="BillingInfoId" type="int" required=true %}
Related billing info's Id.
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserId" type="int" required=true %}
The User Id to be matched
{% endapi-method-parameter %}

{% api-method-parameter name="Name" type="string" required=true %}
The name of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="Title" type="string" required=true %}
The title of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="StreetAdress" type="string" required=true %}
The StreetAdress of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="District" type="string" required=true %}
The District of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="Neighborhood" type="string" required=true %}
The Neighborhood of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="City" type="string" required=true %}
The City of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="Region" type="string" required=true %}
The Region of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="Country" type="string" required=true %}
The Country of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="Phone" type="string" required=true %}
The Phone of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="ZipCode" type="string" required=true %}
The Phone of the new billing info.
{% endapi-method-parameter %}

{% api-method-parameter name="ThreadId" type="string" required=false %}
The unique thread Id to observe sub function calls of the same process. If you do not provide this, the API will create a new one and use it.  
Details about why and how to use **ThreadId** you can find here.
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=false %}
The status of the billinginfo to be created. Possible values are:  
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
{"name": "Bill1ngInfo1"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/billinginfo/remove" %}
{% api-method-summary %}
Remove User Billing Info
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to remove users billing infos.
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

{% api-method-parameter name="SourceRelatedUserCode" type="string" required=false %}
SourceRelatedUserCode
{% endapi-method-parameter %}

{% api-method-parameter name="SourceBillingInfoCode" type="string" required=false %}
SourceBillingInfoCode
{% endapi-method-parameter %}

{% api-method-parameter name="BillingInfoId" type="int" required=true %}
Related billing info's Id.
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserId" type="int" required=true %}
The User Id to be matched
{% endapi-method-parameter %}

{% api-method-parameter name="SessionId" type="string" required=false %}
The session Id of the user triggering this API call.
{% endapi-method-parameter %}

{% api-method-parameter name="ThreadId" type="string" required=false %}
The unique thread Id to observe sub function calls of the same process. If you do not provide this, the API will create a new one and use it.  
Details about why and how to use **ThreadId** you can find here.
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
All Lidia Commerce API responses \(including the ones with errors/problems\) use HTTP 200 by default.
{% endapi-method-response-example-description %}

```text
{"Billing info deleted successfully."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/properties/add" %}
{% api-method-summary %}
Add User Property
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to create users properties.
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

{% api-method-parameter name="Key" type="string" required=true %}
The key of property
{% endapi-method-parameter %}

{% api-method-parameter name="Value" type="string" required=true %}
The value of property
{% endapi-method-parameter %}

{% api-method-parameter name="Extra" type="string" required=false %}
The extras of property
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserId" type="int" required=true %}
The User Id to be matched
{% endapi-method-parameter %}

{% api-method-parameter name="ThreadId" type="string" required=false %}
The unique thread Id to observe sub function calls of the same process. If you do not provide this, the API will create a new one and use it.  
Details about why and how to use **ThreadId** you can find here.
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=false %}
The status of the property to be created. Possible values are:  
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
{"name": "Property1"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/properties/remove" %}
{% api-method-summary %}
Remove User Property
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to remove users properties.
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

{% api-method-parameter name="RelatedUserId" type="int" required=true %}
The User Id to be matched
{% endapi-method-parameter %}

{% api-method-parameter name="SourceRelatedUserCode" type="string" required=false %}
The SourceRelatedUserCode
{% endapi-method-parameter %}

{% api-method-parameter name="SourcePropertCode" type="string" required=false %}
The SourcePropertCode
{% endapi-method-parameter %}

{% api-method-parameter name="PropertyId" type="int" required=true %}
The User Id to be matched
{% endapi-method-parameter %}

{% api-method-parameter name="ThreadId" type="string" required=false %}
The unique thread Id to observe sub function calls of the same process. If you do not provide this, the API will create a new one and use it.  
Details about why and how to use **ThreadId** you can find here.
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=false %}
The status of the property to be created. Possible values are:  
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
{"name": "Property1"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/tags/add" %}
{% api-method-summary %}
Add User Tag
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to create users tags.
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

{% api-method-parameter name="UserToken" type="string" required=true %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=true %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="Type" type="string" required=true %}
The type of tag
{% endapi-method-parameter %}

{% api-method-parameter name="Value" type="string" required=true %}
The value of tag
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserId" type="int" required=true %}
The User Id to be matched
{% endapi-method-parameter %}

{% api-method-parameter name="ThreadId" type="string" required=false %}
The unique thread Id to observe sub function calls of the same process. If you do not provide this, the API will create a new one and use it.  
Details about why and how to use **ThreadId** you can find here.
{% endapi-method-parameter %}

{% api-method-parameter name="Status" type="string" required=false %}
The status of the tag to be created. Possible values are:  
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
{"name": "Tag1"}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

{% api-method method="post" host="https://api-identity.lidiacommerce.com" path="/users/tags/add" %}
{% api-method-summary %}
Remove User Tag
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to create users tags.
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

{% api-method-parameter name="UserToken" type="string" required=true %}
The authentication token returned to you if you use the OAuth2 protocol \(currently not in use\)
{% endapi-method-parameter %}

{% api-method-parameter name="Environment" type="string" required=false %}
The name of the environment on your side \(mainly used to separate calls of your dev, staging or prod environments\).
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserId" type="int" required=true %}
The User Id to be matched
{% endapi-method-parameter %}

{% api-method-parameter name="TagId" type="int" required=true %}
The Related Tag Id.
{% endapi-method-parameter %}

{% api-method-parameter name="RelatedUserId" type="int" required=true %}
The User Id to be matched
{% endapi-method-parameter %}

{% api-method-parameter name="ThreadId" type="string" required=false %}
The unique thread Id to observe sub function calls of the same process. If you do not provide this, the API will create a new one and use it.  
Details about why and how to use **ThreadId** you can find here.
{% endapi-method-parameter %}
{% endapi-method-form-data-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
All Lidia Commerce API responses \(including the ones with errors/problems\) use HTTP 200 by default.
{% endapi-method-response-example-description %}

```text
{"The tag deleted successfully."}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

