---
description: Lidia Identity manages roles, users, authentication and consents
---

# Lidia Identity

Lidia Identity is an API-first product exposing functions to manage roles, users and consents. Details about these concepts you can find below.

In order to use Lidia Identity related features you should create a new account on [Lidia Commerce Platform website](https://www.lidiacommerce.com) and start a subscription or trial for the platform. After a successful registration you will get an e-mail confirming your login credentials for [Lidia Console](https://console.lidiacommerce.com).

Before using Lidia Identity API, you have to log in to the Lidia Commerce Administration Interface with your credentials, **create your application** and get your **ClientId** and **AppKey**.

For more details about registration and creating your applications please click the link below:

{% content-ref url="../../onboarding.md" %}
[onboarding.md](../../onboarding.md)
{% endcontent-ref %}

If you have a valid Lidia Identity subscription, you will the following options when you log in to the administration interface of Lidia Commerce Platform:

* Create, update, delete your applications (you have to create your
* List roles
* See details of each role
* Create, update and delete roles
* List users
* See details of each user
* Create, update and delete users
* Add users to roles

So here is a quick example of using Lidia Identity.

1. You create two roles with the names "Administrator" and "User"
2. You create your admin users by using the Lidia Commerce Platform Administration Interface and assign the "Administrator" role to these users.
3. You use the Rest API to create your users with the standard "User" role
4. While logging in users in your application, you query the user role and assign rights to the user based on it's role

You can find a sample implementation of the scenario above [here](broken-reference).

### Concepts

#### Roles

We use multiple roles in today's applications to realize the requirement of different user groups with different set of rights. As an easy example you might think of normal users of your e-commerce application who does not have any kind of access to the administrative features of the application and the team handling the customer care with access to user's contact information, order history and so on.

Lidia Identity allows you to create multiple roles and add users to these roles. It is also possible that one user has more than one role.

#### Users

Modern applications use membership scenarios very often. Most of the time the requirement as easy as getting the username and/or email address, first name, last name and password during the registration process and saving into the database. The email address and password will be used to sign in users where other data (for some applications even more data like gender, date of birth etc) will be used to create user segments for marketing purposes.

Lidia Identity has a large set of out-of-the-box fields for the user data in addition to two extension options, tags and properties.

#### Consents

Legal restrictions lately forced us to record explicit consents of users for different types of engagements. To reach out to users by using communication channels such as e-mail and text messages requires marketing consents where processing personal data requires consent of the user especially asked for this purpose. We also have to consider to get separate consents for different legal regions such as Europe (EU) and United States even to use cookies. One consent for everything does not work anymore.

Lidia Identity helps you record user consents in a chronological way. We do not use one record for each user and do updates on it, we save every consent-related activity as a new record so we can say exactly at a specific point of time which consents do we have for a specific user.

### Versions

#### 0.0.1 - Alpha version

* Added create, update, delete and query functions for users
* Added create, update, delete and query functions for user addresses
* Added create, update, delete and query functions for user billing information
* Added create, update, delete and query functions for user properties and tags
* Added create, delete and query functions for user pictures
* Added create, delete and query functions for user roles
* Added create, update, delete and query functions for user consents
* Added simple stats functions for user data

If you have questions or you need help, please use the link below to reach possible communication channels.

{% content-ref url="../../../support.md" %}
[support.md](../../../support.md)
{% endcontent-ref %}
