# NICE CXone Voice SDK

*  [NPM package](https://www.npmjs.com/package/@nice-ccf/acd-sdk)
*  [Sample Web App](https://github.com/nice-cxone/webapp-acd-cxagent-sdk-consumer)

# Requirements
TypeScript 4.9
Runtime: ES2022 (WebSocket, Intl, Promise, EventTarget, CustomEvent, JSON, Date, etc.)
Custom application bundler (webpack, create-react-app, etc.)

@nice-ccf/voice-sdk

This is the official README file for the `@nice-ccf/voice-sdk` library. This voice SDK empowers developers to integrate CXone Voice functionalities within their custom applications.

# Features

<b>Client Interaction:</b> To initialize voice extension, send message to web RTC Extension and to connect with server and enabling the chrome extension for voice call.
<br/>
<b>Connection Options:</b> Initiate, answer, hold, transfer, Mute and perform other call actions.
<br/>
<b>Connection Status:</b> To know about the status of voice connection of the current call.
<br/>
<b>Call/Messages:</b> To get inbound and for outbound voice calls, To send and receive messages in the agent application.

# Installation

`npm install @nice-ccf/voice-sdk`

# Peer Dependencies
This library relies on several peer dependencies, including:

@nice-ccf/core-sdk
@nice-ccf/common-sdk
@nice-ccf/i18n
@nice-ccf/shared-apps-lib

# Usage

1. Import necessary modules:<br />

   import { CXoneVoiceClient } from '@nice-ccf/Voice-sdk';<br />
   Import other relevant functionalities as needed (e.g., VoiceConnectionStatus, VoiceMessageType, VoiceConnection etc.,)

2. Initialize CXone Client:<br />

   const cxoneVoiceClient = CXoneVoiceClient.instance;<br />
   await cxoneVoiceClient.connectServer('acdAgentId', 'options', 'audioElement', 'appName'); // Replace with actual value for this params

3. Leverage SDK functionalities:<br />

   Refer to the official documentation (link to be provided) for detailed usage examples on specific features like CXoneVoiceClient, CXoneVoiceMessageType etc. <br />
   Explore the available classes and methods within the library to interact with CXone voice-sdk functionalities.

## Compatibility

This SDK is likely compatible with specific CXone ACD versions. Refer to the documentation for supported versions.

# License

This library is licensed under the (mention license here).

# Support

For any issues or questions, please refer to the (mention support channel/link here).