# Assigning Kubernetes Access to a User in IBM Cloud

This article explains about how to invite an user into IBM Cloud account and give access to one of the Kubernetes  service in that account.

#### Invite user along with Kubernetes Access

1. Open the User management page by click on `Manage > IAM > Users`
2. Click on `Invite Users`
<img src="images/img-11.png">

Invite users page is opened.

3. Select the `Access Policy` option

<img src="images/img-12.png">

4. Type `Kub` in the search button
5. Select the `Kubernetes Service` option
6. Click on `Next`

<img src="images/img-13.png">

7. Select values according to the below image.
8. In the `value` box choose the cluster name that you want to give access to.
9. Click on `Next`
<img src="images/img-14.png">

10. Select the roles as per your need.
11. Click on `Review`
<img src="images/img-15.png">

12. Click on `Add`
<img src="images/img-16.png">

13. Click on `Invite`
<img src="images/img-17.png">

User will be in  `Pending` state
<img src="images/img-18.png">

#### Accept Invitation

User might have received mail from IBM cloud to join the account.

14. The user might click on `Join Now` link in the mail and join.
<img src="images/img-19.png">

User will goto `Active` state
<img src="images/img-20.png">

15. Go to `Users > access` screen

You can able to see the Kubernetes service access  is available.

So we have invited an user along with an access  to one of the Kubernetes  service.

If required we can give access to one more cluster for the same user again.

#### Give Another Kubernetes access

16. Click on `Assign Access`

<img src="images/img-21.png">

17. Fill the values as per your need.

<img src="images/img-22.png">

18. Fill the values as per your need.
19. Click on `Assign` to give an access.

<img src="images/img-23.png">

Now you can able to see the another Kubernetes service access is available.

<img src="images/img-24.png">