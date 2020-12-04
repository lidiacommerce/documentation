---
description: 'Lidia Identity manages roles, users, authentication and consents'
---

# About

Lidia Identity is an API-first product exposing functions to manage roles, users and consents. Details about these concepts you can find [here](concepts.md).

In order to use Lidia Identity you should create a new account on [Lidia Commerce Platform website](https://www.lidiacommerce.com) and start a subscription for this product. After a successful registration you will get an e-mail confirming your login credentials for the [Lidia Commerce Platform Administration Interface](https://app.lidiacommerce.com).

Before using Lidia Identity API, you have to log in to the Lidia Commerce Administration Interface with your credentials, **create your application** and get your **ClientId** and **AppKey**.

For more details about registration and creating your applications please click the link below:

{% page-ref page="../on-boarding.md" %}

If you have a valid Lidia Identity subscription, you will the following options when you log in to the administration interface of Lidia Commerce Platform:

* Create, update, delete your applications \(you have to create your 
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

You can find a sample implementation of the scenario above [here](usage/code-samples.md).

If you have questions or you need help, please use the link below to reach possible communication channels.

{% page-ref page="../support.md" %}

