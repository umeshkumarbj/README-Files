# NICE CXone Digital SDK

*  [NPM package](https://www.npmjs.com/package/@nice-ccf/digital-sdk)
*  [Sample Web App](https://github.com/nice-cxone/webapp-acd-cxagent-sdk-consumer)

# Requirements

TypeScript 4.9
Runtime: ES2022 (WebSocket, Intl, Promise, EventTarget, CustomEvent, JSON, Date, etc.)
Custom application bundler (webpack, create-react-app, etc.)

@nice-ccf/digital-sdk

This is the official README file for the `@nice-ccf/digital-sdk` library. This digital SDK empowers developers to integrate CXone digital related functionalities within their custom applications.

# Features

<b>Digital Client:</b> To Interact with the CXone platform using the CXoneDigitalClient.

<b>Contact Information:</b> To get the contact details from  (e.g., call alerts, work item updates).

<b>Digital Service:</b> To get the digital Service details like information about digital channels, invoke Out bound Channels, inbound channels etc.

<b>User Slot Provider:</b> Utilize user slot events like digital status, restart worker, terminate polling and refresh token etc.

<b>Contact Manager:</b> To initialize the digital web socket connection and manage the user slot details and handling messages using digital web socket.

<b>Browser Utils:</b> For updating co-browser data using local storage and to use other utils. 


# Installation

`npm install @nice-ccf/digital-sdk`

# Peer Dependencies
This library relies on several peer dependencies, including:

@nice-ccf/core-sdk 

@nice-ccf/common-sdk

@nice-ccf/acd-sdk

@nice-ccf/agent-sdk

@nice-ccf/i18n

@nice-ccf/shared-apps-lib

# Usage

1. Import necessary modules:

      import { CXoneDigitalClient } from '@nice-ccf/digital-sdk';
      
      Import other relevant functionalities as needed (e.g., call control, notifications)

2. Initialize CXoneDigital Client:

      const cxoneDigtialClient: CXoneDigitalClient = CXoneDigitalClient.instance;
      
      cxoneDigtialClient.digitalService.getContactHistory('customerId); 

3. Leverage SDK functionalities:

      Refer to the official documentation (link to be provided) for detailed usage examples on specific features like CXoneDigitalClient, CXoneDigitalContact,SortOrder etc.
      
      Explore the available classes and methods within the library to interact with CXone digital-sdk functionalities.

## Compatibility

This SDK is likely compatible with specific CXone ACD versions. Refer to the documentation for supported versions.

# License

Check the license file for specific terms regarding the use of this SDK.