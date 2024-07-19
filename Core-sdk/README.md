# NICE CXone Core SDK

*  [NPM package](https://www.npmjs.com/package/@nice-ccf/acd-sdk)
*  [Sample Web App](https://github.com/nice-cxone/webapp-acd-cxagent-sdk-consumer)

# Requirements

TypeScript 4.9
Runtime: ES2022 (WebSocket, Intl, Promise, EventTarget, CustomEvent, JSON, Date, etc.)
Custom application bundler (webpack, create-react-app, etc.)

@nice-ccf/core-sdk

This is the official README file for the `@nice-ccf/core-sdk` library. This core SDK empowers developers to integrate CXone Agent functionalities within their custom applications.

# Features

<b>Logger:</b> To manage log related activities using logger config, log appender, console log appender etc.
<br/>
<b>Formatter:</b> To perform format related functionalities using log formatter, utils formatter, basic formatter.
<br/>
<b>WebSocket Client:</b> Interact with the CXone platform using websocket client.
<br/>
<b>Contact Events:</b> To receive status about call contact events, voice mail contact events.
<br/>
<b>Helper functions:</b> To reduce redundancy and for better practices helpers like Security Helper, Session Helper, LocalStorage Helper were used throughout the library.
<br/>
<b>Data Parsing and Manipulation:</b> Utilities for parsing strings to booleans or integers, and calculating percentages.
<br/>
<b>Enums:</b> Enumerations for various concepts like log level, Call Contact Events, Voice mail Contact events, Wem Notification Events.
<br/>
<b>Utility Functions:</b> Helper functions for common tasks like data manipulation, formatting, and potentially logging.


# Installation

`npm install @nice-ccf/core-sdk`


# Peer Dependencies
This library relies on several peer dependencies, including:

@nice-ccf/common-sdk<br/>
@nice-ccf/i18n<br/>
@nice-ccf/shared-apps-lib<br/>

# Usage

1. Import necessary modules:
   <br />
    import {
    AdminService,
      Logger,
    ACDSessionManager,
    LocalStorageHelper,
    StorageKeys,
    WebsocketStatusCode,
    BusinessUnit,
  } from '@nice-ccf/core-sdk';

2. Initialize Logger:<br/>
   const logger = new Logger('Browser Extension', 'DockingTab');

3. Leverage SDK functionalities:<br />
   Refer to the official documentation (link to be provided) for detailed usage examples on specific features like AdminService, WebsocketStatusCode, etc.<br />
   Explore the available classes and methods within the library to interact with CXone Core-sdk functionalities.

## Compatibility

This SDK is likely compatible with specific CXone ACD versions. Refer to the documentation for supported versions.

# License

Check the license file for specific terms regarding the use of this SDK.