# NICE CXone i18n SDK

Official SDK Documentation
NPM package
Sample Web App

# Requirements
TypeScript 4.9
Runtime: ES2022 (WebSocket, Intl, Promise, EventTarget, CustomEvent, JSON, Date, etc.)
Custom application bundler (webpack, create-react-app, etc.)

@nice-ccf/i18n

This is the official README file for the `@nice-ccf/i18n` library. This i18n SDK helps the application to turn into desired languages like Chinese, Japanese, Korean, dutch, Russian, protuguese, Spanish, Italian, French, German etc.,

# Installation

bash
npm install @nice-ccf/i18n

1. Import necessary modules:

JavaScript
import { translations } from '@nice-ccf/i18n';
import { CcfTranslationKey } from '@nice-ccf/i18n';

2.Usage
Translated key, value pairs should be stored in json files for each language. With the usage of i18n sdk on Change of language it turns the application into desired language.

# Compatibility

This SDK is likely compatible with specific CXone ACD versions. Refer to the documentation for supported versions.

# License

Check the license file for specific terms regarding the use of this SDK.

# Support
For any issues or questions, please refer to the (mention support channel/link here).