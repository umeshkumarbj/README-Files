# NICE CXone shared-apps-lib SDK

*  [NPM package](https://www.npmjs.com/package/@nice-ccf/acd-sdk)
*  [Sample Web App](https://github.com/nice-cxone/webapp-acd-cxagent-sdk-consumer)

# Requirements

TypeScript 4.9
Runtime: ES2022 (WebSocket, Intl, Promise, EventTarget, CustomEvent, JSON, Date, etc.)
Custom application bundler (webpack, create-react-app, etc.)

@nice-ccf/shared-apps-lib

This is the official README file for the `@nice-ccf/shared-apps-lib` library. This shared-apps-lib SDK empowers developers to integrate Component Loaders, enums, Helpers, Interfaces within their custom applications.

# Features
Digital Contact Data: To get info about the digital contact details.
<br/><br />
Integrating Agents: To embed the Agent Integration Process.
<br/><br />
Switching Events: For Handling Agent Screen Pop data when the pop is trigger between switch events.
<br/><br />
Contact Events: Models for managing voice contact events.
<br/><br />
Interfaces: Models for managing Digital Contact data, Voice data, authentication request, Auth Response data, integrating i18n data, Integration entities etc.
<br/> <br />
Enums: Enumerations for various concepts used throughout the library.
<br/><br />
Utility Functions: Helper functions for common tasks like data manipulation, formatting, and potentially logging.<br />


# Installation

npm install @nice-ccf/shared-apps-lib

# Usage

1. Import necessary modules: <br />

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
    } from '@nice-ccf/shared-apps-lib';<br />

    Import other relevant functionalities as needed (e.g., CXoneDigitalContactData, PartnerDetailsCallback, CXoneAgentStateData, CXoneDigitalEventType etc.,)

2. Initialize CXone Client:<br />

   const cxoneClient = CXoneClient.instance;<br />
   await cxoneClient.init('your_authorization_token'); // Replace with your actual token

3. Leverage SDK functionalities:

    Refer to the official documentation (link to be provided) for detailed usage examples on specific features like CXoneDigitalContactData, PartnerDeailsCallback, CXoneAgentStateDate, CXoneDigitalEvnetType etc., <br />
    Explore the available classes and methods within the library to interact with CXone shared-apps-libs functionalities.

## Compatibility

This SDK is likely compatible with specific CXone ACD versions. Refer to the documentation for supported versions.

# License

Check the license file for specific terms regarding the use of this SDK.

# Support

For any issues or questions, please refer to the (mention support channel/link here).