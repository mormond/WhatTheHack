# Challenge 3 - APIs

[< Previous Challenge](./Challenge-02.md) - **[Home](../readme.md)** - [Next Challenge>](./Challenge-04.md)

## Pre-requisites
Make sure you have completed [Challenge 2](./Challenge-02.md) and successfully deployed a web app with staging.

## Introduction
Deploying static content and staging changes is great but to make your site pop it's going to need some dynamic content. Serving dynamic content requires some compute resource in the form of APIs we can call.

Azure Static Web Apps provides integrated API support through Azure Functions. Azure Functions are a standard, event-driven serverless compute platform in Azure that can scale based on demand. In Azure Static Web Apps they offer integrated security and seamless routing of the API URLs - no configuration required!

By default, the API of a static web app is an Azure Functions application managed and deployed by Azure Static Web Apps. It is also possible to "Bring your own functions" by linking your Azure Static Web App with an exising Azure Functions application.

## Description
Add an API to your app that returns text that is used to update content in the main body of your page. Have the API return the current date / time and display that on the page.

## Success Criteria
1. Your web app displays content in the main body of the page that is returned from the API
2. Ensure that the date / time displays correctly and updates when the page is refreshed 

## Learning Resources
* [Introducing Azure Functions](https://azure.microsoft.com/blog/introducing-azure-functions/)
* [Azure Static Web Apps - Add an API](https://docs.microsoft.com/azure/static-web-apps/add-api?tabs=vanilla-javascript)

## Tips
* You can use the Azure Static Web Apps integrated API support for this challenge (ie there is no need to create a separate Azure Functions app)
* Make sure you follow the "No Framework" guide
* You may need to update your GitHub action to get things wired up correctly
* You don't have to follow the steps to run locally but it will simplify any debugging
* For running locally, [DevContainers in Visual Studio Code](https://code.visualstudio.com/docs/remote/containers) provides a convenient way of provisioning a dev environment for Azure Functions. You will need Docker installed.
