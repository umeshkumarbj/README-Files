## NICE CXone Core SDK

Official SDK Documentation
NPM package
Sample Web App

Requirements
TypeScript 4.9
Runtime: ES2022 (WebSocket, Intl, Promise, EventTarget, CustomEvent, JSON, Date, etc.)
Custom application bundler (webpack, create-react-app, etc.)

# @nice-ccf/core-sdk

This is the official README file for the `@nice-ccf/core-sdk` library. This core SDK empowers developers to integrate CXone Agent functionalities within their custom applications.

# Features

Logger: To manage log related activities using logger config, log appender, console log appender etc.,
Formatter: To perform format related functionalities using log formatter, utils formatter, basic formatter.
WebSocket Client: Interact with the CXone platform using websocket client.
Contact Events: To receive status about call contact events, voice mail contact events.
Helper functions: To reduce redundancy and for better practices helpers like Security Helper, Session Helper, LocalStorage Helper were used throughout the library.
Data Parsing and Manipulation: Utilities for parsing strings to booleans or integers, and calculating percentages.
Enums: Enumerations for various concepts like log level, Call Contact Events, Voice mail Contact events, Wem Notification Events.
Utility Functions: Helper functions for common tasks like data manipulation, formatting, and potentially logging.


# Installation

bash
npm install @nice-ccf/core-sdk


# Peer Dependencies
This library relies on several peer dependencies, including:

@nice-ccf/common-sdk
@nice-ccf/i18n
@nice-ccf/shared-apps-lib

# Usage

1. Import necessary modules:

JavaScript
import {
  AdminService,
  Logger,
  ACDSessionManager,
  LocalStorageHelper,
  StorageKeys,
  WebsocketStatusCode,
  BusinessUnit,
} from '@nice-ccf/core-sdk';

2. Initialize Logger:

JavaScript
const logger = new Logger('Browser Extension', 'DockingTab');

3. Leverage SDK functionalities:

Refer to the official documentation (link to be provided) for detailed usage examples on specific features like AdminService, WebsocketStatusCode, etc.
Explore the available classes and methods within the library to interact with CXone Core-sdk functionalities.

Documentation

# Compatibility

This SDK is likely compatible with specific CXone ACD versions. Refer to the documentation for supported versions.

# License

Check the license file for specific terms regarding the use of this SDK.
