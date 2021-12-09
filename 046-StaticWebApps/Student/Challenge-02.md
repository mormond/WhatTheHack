# Challenge 2 - Staging Changes

[< Previous Challenge](./Challenge-01.md) - **[Home](../readme.md)** - [Next Challenge>](./Challenge-03.md)

## Pre-requisites
Make sure you have completed [Challenge 1](./Challenge-01.md) and successfully deployed a web app.

## Introduction
A common requirement when deploying a new site or updates to an existing site is to be able to stage changes to review before releasing to production. A pre-production (staging) environment is a fully-functional staged version of your application that includes changes not available in production.

Azure Static Web Apps natively supports deployment of pull requests to a staging environment to allow testing and sign-off before release to production. The GitHub action created in [Challenge 1](./Challenge-01.md) will be triggered when a pull request is created. It will create a new staging environment and deploy the new version of the web app.

## Description
Make a change to your app and validate it in a staging environment. 

eg modify the header text in the body of the main page.

## Success Criteria
1. Confirm in the Azure portal that a new staging environment is created by the workflow
2. View the changes in the staging site at the public URL
3. Confirm the production site has not changed

## Learning Resources
* [About Pull Requests](https://docs.github.com/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
* [Azure Static Web Apps - Review Pull Requests in a Staging Environment](https://docs.microsoft.com/azure/static-web-apps/review-publish-pull-requests)

