# NICE CXone Voice SDK

# Official SDK Documentation
NPM package
Sample Web App

# Requirements
TypeScript 4.9
Runtime: ES2022 (WebSocket, Intl, Promise, EventTarget, CustomEvent, JSON, Date, etc.)
Custom application bundler (webpack, create-react-app, etc.)

@nice-ccf/voice-sdk

This is the official README file for the `@nice-ccf/voice-sdk` library. This voice SDK empowers developers to integrate CXone Voice functionalities within their custom applications.

# Features

Client Interaction: To initialize voice extension, send message to web RTC Extension and to connect with server and enabling the chrome extension for voice call.
Connection Options: Initiate, answer, hold, transfer, Mute and perform other call actions.
Connection Status: To know about the status of voice connection of the current call.
Call/Messages: To get inbound and for outbound voice calls, To send and receive messages in the agent application.

Installation

bash
npm install @nice-ccf/voice-sdk

# Peer Dependencies
This library relies on several peer dependencies, including:

@nice-ccf/core-sdk
@nice-ccf/common-sdk
@nice-ccf/i18n
@nice-ccf/shared-apps-lib

Usage

1. Import necessary modules:

JavaScript
import { CXoneVoiceClient } from '@nice-ccf/Voice-sdk';
Import other relevant functionalities as needed (e.g., VoiceConnectionStatus, VoiceMessageType, VoiceConnection etc.,)

2. Initialize CXone Client:

JavaScript
const cxoneVoiceClient = CXoneVoiceClient.instance;
await cxoneVoiceClient.connectServer('acdAgentId', 'options', 'audioElement', 'appName'); // Replace with actual value for this params

3. Leverage SDK functionalities:

Refer to the official documentation (link to be provided) for detailed usage examples on specific features like CXoneVoiceClient, CXoneVoiceMessageType etc.
Explore the available classes and methods within the library to interact with CXone voice-sdk functionalities.
Documentation

# Compatibility

This SDK is likely compatible with specific CXone ACD versions. Refer to the documentation for supported versions.

# License

This library is licensed under the (mention license here).

# Support
For any issues or questions, please refer to the (mention support channel/link here).