# NICE CXone shared-apps-lib SDK

# Official SDK Documentation
NPM package
Sample Web App

# Requirements
TypeScript 4.9
Runtime: ES2022 (WebSocket, Intl, Promise, EventTarget, CustomEvent, JSON, Date, etc.)
Custom application bundler (webpack, create-react-app, etc.)

@nice-ccf/shared-apps-lib

This is the official README file for the `@nice-ccf/shared-apps-lib` library. This shared-apps-lib SDK empowers developers to integrate Component Loaders, enums, Helpers, Interfaces within their custom applications.

# Features
Digital Contact Data: To get info about the digital contact details.
Integrating Agents: To embed the Agent Integration Process.
Switching Events: For Handling Agent Screen Pop data when the pop is trigger between switch events.
Contact Events: Models for managing voice contact events.
Interfaces: Models for managing Digital Contact data, Voice data, authentication request, Auth Response data, integrating i18n data, Integration entities etc., 
Enums: Enumerations for various concepts used throughout the library.
Utility Functions: Helper functions for common tasks like data manipulation, formatting, and potentially logging.


# Installation

bash
npm install @nice-ccf/shared-apps-lib

Usage

1. Import necessary modules:

JavaScript
import {
  ICXoneAgentIntegration,
  ClickToActCallback,
  CXoneAgentStateData,
  CXoneScreenPopData,
  CXoneVoiceContactData,
  CXoneDigitalContactData,
  LocaleChangeCallback,
  CXoneDigitalEventType,
  CXoneDigitalContactStatus,
  CXonePartnerPresenceSyncRule,
  CXonePartnerDetailsCallback,
} from '@nice-ccf/shared-apps-lib';

Import other relevant functionalities as needed (e.g., CXoneDigitalContactData, PartnerDetailsCallback, CXoneAgentStateData, CXoneDigitalEventType etc.,)

2. Initialize CXone Client:

JavaScript
const cxoneClient = CXoneClient.instance;
await cxoneClient.init('your_authorization_token'); // Replace with your actual token

3. Leverage SDK functionalities:

Refer to the official documentation (link to be provided) for detailed usage examples on specific features like CXoneDigitalContactData, PartnerDeailsCallback, CXoneAgentStateDate, CXoneDigitalEvnetType etc.,
Explore the available classes and methods within the library to interact with CXone shared-apps-libs functionalities.

# Documentation

Compatibility and Usage

This SDK is likely compatible with specific CXone ACD versions. Refer to the documentation for supported versions.

# License

Check the license file for specific terms regarding the use of this SDK.

Support
For any issues or questions, please refer to the (mention support channel/link here).