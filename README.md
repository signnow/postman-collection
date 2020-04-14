# signNow API Postman Collection
[![License](https://img.shields.io/github/license/signnow/SignNow.NET?style=flat-square)](LICENSE)

## About signNow REST API Collection

Full Postman collection to get a trial run of the signNow REST API - the easiest way to embed document signing into your app.

To get your account, register at https://www.signnow.com/developers

## Contents

1. [Get started](#get-started)
2. [Installation](#installation)
3. [Documentation](#documentation)
4. [Features](#features) 
5. [API Contact Information](#api-contact-information)     
6. [License](#license)

## <a name="get-started"></a>Get started

Postman collection - a set of requests for making calls to REST API endpoints using the Postman app.

signNow REST API combines endpoints that cover various steps of e-signature workflows: document uploads, using templates, sending documents out to be signed, verifying and managing users, storing signed copies, automating bulk operations with document groups.

To start using the signNow API Postman collection you should get a Sandbox account at https://www.signnow.com/developers.

## <a name="get-started"></a>Installation

*Requirements*: 
Sandbox account, Basic Authorization token, Postman application

* Clone or download the collection to your computer
* Import the following files to Postman: `SignNow API.postman_collection.json`; `signNow Sandbox Env.postman_environment.json`
* Go to your Sandbox account and copy the Basic Authorization token from the [API Dashboard](https://docs.signnow.com/dashboard);
* Add your Sandbox login and password and your Basic Authorization token to the environment in Postman

The base URL is https://api-eval.signnow.com .

## <a name="documentation"></a>Documentation

Read about the available SignNow features in [SignNow API Docs](https://docs.signnow.com/).

## <a name="features"></a>Features
    **Folder 00**: Invite to sign the document with fields (role-based invite)

    **Folder 01**: Invite to sign the document without fields (freeform invite)

    **Folder 02**: Create a single-use link to the document for signature

    **Folder 03**: Bulk invite

    **Folder 04**: Document Group Invite

    **Folder 05**: Embedded Signing

    **Users**:  Create a user, Get user's info, Change user's details, Send a verification email, Verify email, Reset password, Get modified documents, Get user documents

    **OAuth**: Generate an access token, Verify an access token

    **Document**: Get document, Edit document, Delete document, Upload document, Upload document with tags, Download document, Move document, Send an invite to sign, Cancel invite to sign, Get document download link, Add custom event, Merge documents, Get document history

    **Template**: Create a template, Get document out of a template

    **Document Group**: Create document group, Get document group,  Delete document group, Get document groups, Invite to sign document group, Get document group invite, Cancel document group invite, Get pending group invites, Resend document group invite, Update document group invite

    **Signing link**: Create a signing link

    **Webhooks**: Create an event subscription, Get event subscriptions, Delete an event subscription, Update an event subscription

    **Folder**: Create a folder, Get all folders, Get a folder by ID, Delete a folder, Rename a folder

    **Smart fields**: Prefill Smart field


## <a name="api-contact-information"></a>API Contact Information
If you have questions about the SignNow API, please visit https://help.signnow.com/docs or email api@signnow.com.<br>
**Support**: To contact SignNow support, please email support@signnow.com or api@signnow.com.<br>
**Sales**: For pricing information, please call (800) 831-2050, email sales@signnow.com or visit https://www.signnow.com/contact.


## <a name="license"></a>License

This Postman collection is distributed under the MIT License, see [LICENSE](https://github.com/signnow/SignNow.NET/blob/develop/LICENSE) for more information.
