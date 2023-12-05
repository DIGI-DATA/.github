# Digieye Platform

Welcome to Digieye Platform, a comprehensive data and IoT platform designed to empower users with advanced data management and Internet of Things capabilities.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Architecture](#architecture)
- [Usage](#usage)
- [Namespaces and Repositories](#namespaces-and-repositories)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Digieye Platform is a powerful solution that combines robust data management with cutting-edge IoT capabilities. Whether you're dealing with large datasets, connecting devices, or orchestrating complex workflows, Digieye Platform provides the tools and infrastructure to make it happen.

## Features

- **Data Management:** Easily manage and analyze large volumes of data with Digieye's intuitive data management features.
  
- **IoT Integration:** Connect and control IoT devices seamlessly. Digieye Platform supports a wide range of IoT protocols and devices.

- **Scalability:** Scale your applications effortlessly as your data and IoT requirements grow.

- **Security:** Ensure the security of your data and devices with built-in security features.

- **Customization:** Tailor Digieye Platform to your specific needs with flexible configuration options.

## Architecture

Digieye Platform is built on a modular and scalable architecture that ensures flexibility and robustness. The architecture comprises the following key components:

1. **Data Ingestion Layer:** Responsible for collecting and ingesting data from various sources, ensuring seamless integration.

2. **Data Processing Layer:** Processes and analyzes the ingested data, providing insights and actionable information.

3. **IoT Integration Layer:** Connects and manages IoT devices, facilitating real-time communication and control.

4. **Storage Layer:** Stores processed data efficiently, supporting scalable and reliable data storage.

5. **API Layer:** Exposes APIs for easy integration with third-party applications and services.

6. **Integration layer:** Data forwarding and integration from Digieye platform to Thead platform || protocols

For a more detailed understanding of Digieye Platform's architecture, please refer to our [Architecture Documentation](docs/architecture.md).

## Namespaces and Repositories

1. **Data Ingestion Namespace**

   The **Data Ingestion Namespace** is a critical aspect of Digieye Platform, focusing specifically on handling data ingestion processes. Repositories within this namespace are dedicated to efficiently collecting and ingesting data from diverse sources.
   - [DPEP-HTTP-KAFKA](https://github.com/DIGI-DATA/DPEP-HTTP-KAFKA)
   - [DPEP-MQTT-KAFKA](https://github.com/DIGI-DATA/DPEP-MQTT-KAFKA)
   - [DPEP-WS-KAFKA](https://github.com/DIGI-DATA/DPEP-WS-KAFKA)
   - [DPEP-OPCUA-KAFKA](https://github.com/DIGI-DATA/DPEP-OPCUA-KAFKA)

2. **Queue Namespace**

   The **Queue Namespace** comprises repositories focused on queue-related functionalities. Explore the following repositories:

   - [Kafka & NATS](https://github.com/DIGI-DATA/DP-Infrastructure.git)

3. **Core Namespace**

   The **Core Namespace** houses fundamental modules and libraries that form the backbone of Digieye Platform. Explore the following repository:

   - [DPC-DM-CM](https://github.com/DIGI-DATA/DPC-DM-CM)

4. **Database Namespace**

   The **Database Namespace** encompasses repositories related to database operations and functionalities. Explore the following repositories:

   - [Mongodb & Postgres](https://github.com/DIGI-DATA/DP-Infrastructure.git)

5. **Entrypoint Namespace**

   The **Entrypoint Namespace** focuses on entry points and interfaces within Digieye Platform. Explore the following repositories:

   - [DPC-UI](https://github.com/DIGI-DATA/DPC-UI)
   - [DPC-DM-Api](https://github.com/DIGI-DATA/DPC-DM-Api)
   - [DPC-HISTORY](https://github.com/DIGI-DATA/DPC-HISTORY)

6. **Rule engine Namespace**

   The **Rule engine Namespace** houses repositories related to rule-based functionalities within Digieye Platform. Explore the following repositories:

   - [DPC-UI](https://github.com/DIGI-DATA/DPC-UI)
   - [DPC-DM-Api](https://github.com/DIGI-DATA/DPC-DM-Api)
   - [DPC-HISTORY](https://github.com/DIGI-DATA/DPC-HISTORY)

7. **Integration Namespace**

   The **Integration Namespace** comprises repositories dedicated to integrating Digieye Platform with external systems and services. Explore the following repositories:

   - [DPEX-PUB-SUB](https://github.com/DIGI-DATA/DPEX-KAFKA-PUB-SUB)
   - [DPEX-REST-API](https://github.com/DIGI-DATA/DPEX-KAFKA-REST-API)
   - [DPEX-IOT-CENTER](https://github.com/DIGI-DATA/DPEX-KAFKA-IOT-CENTER)
   - [DPEX-IOT-HUB](https://github.com/DIGI-DATA/DPEX-KAFKA-IOT-HUB)
   - [DPEX-SQS](https://github.com/DIGI-DATA/DPEX-KAFKA-SQS)
   - [DPEX-SNS](https://github.com/DIGI-DATA/DPEX-KAFKA-SNS)
   - [DPEX-KAFKA](https://github.com/DIGI-DATA/DPEX-KAFKA-KAFKA)
   - [DPEX-AMQP](https://github.com/DIGI-DATA/DPEX-KAFKA-AMQP)
   - [DPEX-MQTT](https://github.com/DIGI-DATA/DPEX-KAFKA-MQTT)

<!-- Add more namespaces and repositories as needed -->

## Getting Started

Follow these steps to get started with Digieye Platform:

1. Clone the repository: `git clone https://github.com/your-username/digieye-platform.git`
2. Install dependencies: `npm install` or `yarn install`
3. Configure your settings in `config.js`
4. Run the platform: `npm start` or `yarn start`


## Usage

Here are some common use cases and examples to help you make the most of Digieye Platform. Refer to our [documentation](docs/) for detailed instructions.

### Example:

```javascript
const digieye = require('digieye-platform');

const data = digieye.getData('example_dataset');
console.log('Data:', data);
