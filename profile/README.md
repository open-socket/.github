<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/open-socket/community/refs/heads/main/assets/logo/horizontal/black/openfeature-horizontal-black.png">
    <img align="center" alt="OpenFeature Logo" src="https://raw.githubusercontent.com/open-socket/community/refs/heads/main/assets/logo/horizontal/black/openfeature-horizontal-black.png" />
  </picture>
</p>

<h2 align="center">Welcome to the OpenSocket project 👋</h2>

**OpenSocket** is an open-source initiative aimed at creating a vendor-agnostic, multi-platform API for socket-based real-time communication. Our goal is to empower developers to integrate real-time features with flexibility and simplicity, allowing them to easily switch between socket providers (such as Ably, Socket.IO, and Pusher) without being locked into a single solution.

## Mission
Our mission is to simplify socket communication for developers by offering a unified API and SDKs across multiple platforms and languages. OpenSocket aims to make real-time features easier to integrate, maintain, and extend, allowing for seamless adoption in applications of any scale.

## Repositories
The OpenSocket project is organized as a Lerna monorepo, providing SDKs for various platforms:

- [ ] **js-sdk**: A monorepo containing JavaScript-based SDKs, including the foundational `@opensocket/core-js` and platform-specific SDKs for React, Next.js, Vanilla JS, and Angular.
  - [x] **core**: The core package (`@opensocket/core-js`) that provides a standardized API and Provider Interface, ensuring compatibility across multiple providers.
  - [ ] **react-sdk**: SDK for integrating OpenSocket into React applications.
  - [ ] **next-sdk**: SDK for integrating with Next.js applications.
  - [ ] **vanilla-sdk**: SDK for general JavaScript usage.
  - [ ] **angular-sdk**: SDK designed for Angular applications.

- [ ] **php-sdk**: PHP-based SDK for integrating OpenSocket in PHP applications.

- [ ] **python-sdk**: Python-based SDK for integrating OpenSocket into Python frameworks.

## Features
- [x] **Provider Agnostic**: Easily switch between providers like Ably, Socket.IO, and Pusher with minimal configuration changes.
- [x] **Comprehensive Interface**: Access advanced real-time features, including message history, presence management, and rewind support.
- [x] **Extensibility**: Easily add support for new providers by implementing the Provider Interface.
- [ ] **Multi-platform Support**: SDKs available for multiple platforms and languages to meet diverse application needs.

## Getting Started
To get started with OpenSocket, install the desired SDK package and configure your provider. Each SDK repository contains detailed setup and usage guides in its respective README.

```bash
# Example: Installing core-js SDK
npm install @opensocket/core-js
