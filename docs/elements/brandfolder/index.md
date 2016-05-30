---
heading: Brandfolder
seo: Overview | Brandfolder | Cloud Elements API Docs
title: Overview
description: Integrate Brandfolder into your application via the Cloud Elements APIs.
layout: docs
breadcrumbs: /docs/elements.html
elementId: 492
parent: Back to Element Guides
order: 1
---

## Welcome to the Brandfolder Element


#### At a Glance

In order to create a connection to Brandfolder the following steps are required:

1. Get your [User Token](brandfolder-endpoint-setup.html)
2. Call the `POST /instances` API to instantiate your Brandfolder connected app

#### In Depth

The Brandfolder Element is a collection of resources providing a pre-built integration into a service endpoint. RESTful methods (POST, GET, PUT, PATCH, DELETE) are used to interact with these resources (accounts, contacts, files) regardless of the type of APIs (SOAP or REST) provided by the endpoint. Elements leverage Cloud Elements API Manager platform services including authentication, data transformation, and event management.  The API is built to allow you to create a functional application or integration quickly and easily.

All API calls to Cloud Elements should be made to the `https://api.cloud-elements.com/elements/api-v2` base domain. Requests are authorized with an Organization and User secret, as well as, an Element token.  We use many standard HTTP features, like HTTP verbs, which can be understood by many HTTP clients. JSON will be returned in all responses from the API, including errors. The APIs are designed to have predictable, straightforward URLs and to use HTTP response codes to indicate API errors.

Get started by [retrieving your user token](brandfolder-endpoint-setup.html).