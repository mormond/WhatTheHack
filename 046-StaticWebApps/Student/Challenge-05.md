# Challenge 5 - Name It

[< Previous Challenge](./Challenge-04.md) - **[Home](../readme.md)** - [Next Challenge>](./Challenge-06.md)

## Pre-requisites

Make sure you have completed [Challenge 1](./Challenge-01.md) and successfully deployed a web app.

- A purchased domain name
- Access to the DNS configuration properties for your domain

If you do not meet these pre-requisites then skip this challenge and move to the next. Skipping will not prevent you from completing other challenges

## Introduction

A custom domain name allows your users to find your application more easily because of higher search engine rankings and consistent branding.

In this challenge we are going to introduce a custom domain name to reach your application, for example **https://www.example.com** rather than **https://auto-generated.region.azurestaticapps.net**

Azure Static Web Apps supports using your own custom domain and provides a free SSL/TLS certificate for any added custom domains as well as for the original, auto-generated URL.

## Description

Set up a custom domain name with certificate so that requests to your web application can be made securely.

## Success Criteria

- Visiting your custom domain in a web browser should navigate to your web application
- Insecure requests (http) should be redirected to a secure endpoint (https)
- A valid certificate should be present for your custom domain

## Learning Resources

* [DNS Configuration](https://docs.microsoft.com/azure/static-web-apps/custom-domain?tabs=azure-dns#dns-configuration-options)
* [What is Azure DNS?](https://docs.microsoft.com/azure/dns/dns-overview)
* [Azure Static Web Apps - Custom Domain](https://docs.microsoft.com/azure/static-web-apps/custom-domain)
