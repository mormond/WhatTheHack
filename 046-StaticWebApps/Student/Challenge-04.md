# Challenge 4 - Authentication

[< Previous Challenge](./Challenge-03.md) - **[Home](../readme.md)** - [Next Challenge>](./Challenge-05.md)

## Pre-requisites
Make sure you have completed [Challenge 3](./Challenge-03.md) and have a web app that calls an API and displays the results.

## Introduction
Authentication (who are you) and authorization (what are you allowed to do) are critical aspects of Identity and Access Management (IAM) which help to secure access to your application and ensure users can access they data they should have access to while preventing them accessing data they shouldn't (intentionally or otherwise).

Azure Static Web Apps provides a streamlined authentication experience making it very easy to integrate with a range of identity providers. Out of the box Azure Static Web Apps comes pre-configured with support for [Azure Active Directory](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-whatis), GitHub and Twitter. You can also [register your own custom provider](https://docs.microsoft.com/azure/static-web-apps/authentication-custom).

## Description
Create a new page in your app called `secure.html`. Restrict access to that page to authenticated users only. On `secure.html` display some information (claims) about the current user. You will need to provide a facility for login / logout. Make sure that users can login with a friendly URL such as `/mysite/login`.

## Success Criteria
1. Users can login / logout by following links from `index.html`
1. A user should also be able to login (logout) by browsing to `.../mysite/login` (`.../mysite/logout`) 
1. A user who is not logged should not be able to access `secure.html` 
1. An unauthenticated user who browses to `secure.html` should be redirected to a login page
1. `secure.html` should display a claim such as the users's email address or username

## Learning Resources
* [Azure Static Web Apps - Authentication and Authorization](https://docs.microsoft.com/azure/static-web-apps/authentication-authorization)
* [Azure Static Web Apps - Configuration](https://docs.microsoft.com/azure/static-web-apps/configuration)
* [Azure Static Web Apps - Configure Routes](https://docs.microsoft.com/azure/static-web-apps/configuration#routes)
* [Azure Static Web Apps - Securing Routes with Roles](https://docs.microsoft.com/azure/static-web-apps/configuration#securing-routes-with-roles)
* [Azure Static Web Apps - User Information](https://docs.microsoft.com/azure/static-web-apps/user-information?tabs=javascript)

## Tips
* You can copy `index.html` and rename to `secure.html` as a good starting point
* Use one of the pre-configured identity providers
* Make sure to redirect **unauthorised** users trying to access `secure.html` to a login page