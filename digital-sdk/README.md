# NICE CXone Digital SDK

*  [NPM package](https://www.npmjs.com/package/@nice-ccf/acd-sdk)
*  [Sample Web App](https://github.com/nice-cxone/webapp-acd-cxagent-sdk-consumer)

# Requirements

TypeScript 4.9
Runtime: ES2022 (WebSocket, Intl, Promise, EventTarget, CustomEvent, JSON, Date, etc.)
Custom application bundler (webpack, create-react-app, etc.)

@nice-ccf/digital-sdk

This is the official README file for the `@nice-ccf/digital-sdk` library. This digital SDK empowers developers to integrate CXone digital related functionalities within their custom applications.

# Features

Digital Client: To Interact with the CXone platform using the CXoneDigitalClient.
<br/><br />
Contact Information: To get the contact details from  (e.g., call alerts, work item updates).
<br/><br />
Digital Service: To get the digital Service details like information about digital channels, invoke Out bound Channels, inbound channels etc.
<br/><br />
User Slot Provider: Utilize user slot events like digital status, restart worker, terminate polling and refresh token etc.
<br/><br />
Contact Manager: To initialize the digital web socket connection and manage the user slot details and handling messages using digital web socket.
<br/><br />
Browser Utils: For updating co-browser data using local storage and to use other utils. 


# Installation

npm install @nice-ccf/digital-sdk

# Peer Dependencies
This library relies on several peer dependencies, including:

@nice-ccf/core-sdk <br/>
@nice-ccf/common-sdk<br />
@nice-ccf/acd-sdk<br />
@nice-ccf/agent-sdk<br />
@nice-ccf/i18n<br />
@nice-ccf/shared-apps-lib<br />

# Usage

1. Import necessary modules:<br />
   import { CXoneDigitalClient } from '@nice-ccf/digital-sdk';<br />
   Import other relevant functionalities as needed (e.g., call control, notifications)

2. Initialize CXoneDigital Client:<br />

   const cxoneDigtialClient: CXoneDigitalClient = CXoneDigitalClient.instance;<br />
   cxoneDigtialClient.digitalService.getContactHistory('customerId); 

3. Leverage SDK functionalities:<br />

    Refer to the official documentation (link to be provided) for detailed usage examples on specific features like CXoneDigitalClient, CXoneDigitalContact,SortOrder etc.<br />
    Explore the available classes and methods within the library to interact with CXone digital-sdk functionalities.

## Compatibility

This SDK is likely compatible with specific CXone ACD versions. Refer to the documentation for supported versions.

# License

Check the license file for specific terms regarding the use of this SDK.