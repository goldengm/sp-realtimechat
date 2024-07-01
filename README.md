# Official Angular SDK

> The official Angular components for real-time chat, a service for building chat applications.

![tests and release workflow](https://github.com/GetStream/stream-chat-angular/actions/workflows/workflow.yml/badge.svg)

<img align="right" src="https://getstream.imgix.net/images/chat/chattutorialart@3x.png?auto=format,enhance" width="50%" />

With my component library, you can build a variety of chat use cases, including:

- In-game chat like Overwatch or Fortnite
- Team-style chat like Slack
- Messaging-style chat like WhatsApp or Facebook's Messenger
- Customer support chat like Drift or Intercom

## Installation

### Install with NPM

Run the following command if you are using **Angular 17**

```shell
npm install stream-chat-angular stream-chat @ngx-translate/core
```

Run the following command if you are using **Angular 16**:

```shell
npm install stream-chat-angular stream-chat @ngx-translate/core
```

Run the following command if you are using **Angular 15**:

```shell
npm install stream-chat-angular stream-chat @ngx-translate/core@14 ngx-popperjs@15
```

Run the following command if you are using **Angular 14**:

```shell
npm install stream-chat-angular stream-chat @ngx-translate/core@14 ngx-popperjs@14
```

Run the following command if you are using **Angular 13**:

```shell
npm install stream-chat-angular stream-chat @ngx-translate/core@14 angular-mentions@1.4.0 ngx-popperjs@13 --legacy-peer-deps
```

Run this command if you are using **Angular 12**:

```shell
npm install stream-chat-angular stream-chat @ngx-translate/core@14 angular-mentions@1.4.0 ngx-popperjs@12 --legacy-peer-deps
```

## Sample App

This repository includes a sample app to test our library.

To test the app:

Create a file named `.env` in the root directory with the following content:

```
STREAM_API_KEY=<Your API key>
STREAM_USER_ID=<Your user ID>
STREAM_USER_TOKEN=<Your user token>
```

Run `npm install` to install dependencies.

Run `npm start` and navigate to `http://localhost:4200/`.

Preferred Node version: v16.

## Customization examples

This repository includes a sample app that showcases how you can provide your own template for different components within the SDK:

To run the app:

Create a file named `.env` in the root directory with the following content:

```
STREAM_API_KEY=<Your API key>
STREAM_USER_ID=<Your user ID>
STREAM_USER_TOKEN=<Your user token>
```

Run `npm install` to install dependencies.

Run `npm run start:customizations-example` and navigate to `http://localhost:4200/`.

Preferred Node version: v16.

## Local development

This repository includes a sample app to test our library.

To test the app:

Create a file named `.env` in the root directory with the following content:

```
STREAM_API_KEY=<Your API key>
STREAM_USER_ID=<Your user ID>
STREAM_USER_TOKEN=<Your user token>
```

Run `npm install` in the root of the project. You can use the `npm run start:dev` command to start the SampleApp with automatic reloading.

A note about the documentation:

- Documentations for Angular services are generated from doc comments in the source files (not under source control)
- Documentations for inputs and outputs of Angular components are generated from doc comments in the source files (not under source control)
- Everything else in the documentation is written in `mdx` files located in the `docusaurus` folder

Preferred Node version: v16.