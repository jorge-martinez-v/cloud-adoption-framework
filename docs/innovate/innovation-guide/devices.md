---
title: Ubiquitous computing and device management
description: Learn about ubiquitous computing and Azure's framework for building immersive and effective business solutions through connected devices and perceptive edge devices.
author: umarmohamedusman
ms.author: pnp
ms.date: 01/27/2021
ms.topic: conceptual
ms.custom: think-tank, fasttrack-new, AQC
keywords: Connected devices, ubiquitous computing, device management, edge devices
---

# Interact through connected devices

Innovate through intermittently connected devices and perceptive edge devices. Orchestrate millions of such devices, acquire and process limitless data, and take advantage of a growing number of multisensory, multidevice experiences. For devices at the edge of your network, Azure provides a framework for building immersive and effective business solutions. With ubiquitous computing, enabled by Azure combined with AI technology, you can build every type of intelligent application and system you can envision.

Ubiquitous computing is the processing of information that connects devices and processors to have constant availability, so that computing and processing are made to appear anytime and everywhere needed, using any connected device or perceptive edge device. Examples of ubiquitous computing include any system that sends information to another system to complete a task seamlessly, like a fitness watch that alerts that there is an incoming call from a cell phone and allows completion of the call through the watch, or systems that learn and adjust such as a thermostat or smart speakers.

Azure customers employ a continually expanding set of connected systems and devices that gather and analyze data (close to their users, the data, or both), with complete device management. Users get real-time insights and experiences, delivered by highly responsive and contextually aware applications. By moving parts of the workload to the edge, these connected devices can spend less time sending messages to the cloud and react more quickly to spatial events.

> [!div class="checklist"]
>
> - Industrial assets
> - [Azure Sphere](/azure-sphere/product-overview/what-is-azure-sphere)
> - Drones
> - [IoT plug and play](/azure/iot-develop/overview-iot-plug-and-play)

## [Global scale IoT service](#tab/IoTHub)

Architect solutions that exercise bidirectional communication with IoT devices at billions scale. Use out-of-box, device-to-cloud telemetry data to understand the state of your devices and define message routes to other Azure services just through configuration. By taking advantage of cloud-to-device messages, you can reliably send commands and notifications to your connected devices and track message delivery with acknowledgment receipts. And you'll automatically resend device messages as needed to accommodate intermittent connectivity.

Here are a few features you'll find:

- **Security-enhanced communication** channel for sending and receiving data from IoT devices.
- **Built-in device management** and provisioning to connect and manage IoT and edge devices at scale.
- **Full integration with Event Grid** and serverless compute, simplifying IoT application development.
- **Compatibility with Azure IoT Edge** for building hybrid IoT applications.

::: zone target="docs"

### Learn more

- [Azure IoT Hub](/azure/iot-hub/)
- [Azure IoT Hub Device Provisioning Service (DPS)](/azure/iot-dps/)
- [Use our modern IoT Azure DevOps project to help with your work item management](https://azuredevopsdemogenerator.azurewebsites.net/?name=modiot)

::: zone-end

::: zone target="chromeless"

### Action

To create an IoT Hub instance:

1. Go to **IoT Hub**.
2. Select **Create IoT hub**.

The Azure IoT Hub Device Provisioning Service is a helper service for Azure IoT Hub that enables zero-touch, just-in-time provisioning.

<!-- markdownlint-disable MD024 -->

### Action

To create an Azure IoT Hub Device Provisioning Service:

1. Go to **Device Provisioning Services**.
2. Select **Add**.

::: zone-end

## [Azure Digital Twins](#tab/DigitalTwins)

Build reusable, highly scalable, spatially aware experiences that link streaming data across the physical and digital world. Enhance your customer engagement using comprehensive models of physical environments. Generate spatial intelligence graphs to model the relationships and interactions between people, places, and devices. Query data from a physical space rather than disparate sensors.

**Azure Digital Twins object models:** An ontology that describes the regions, venues, floors, offices, zones, conference rooms, and focus rooms of a smart building, or various power stations, substations, energy resources, and customers of an energy grid, can be modeled by using digital twins object models and ontologies.

**Spatial intelligence graph:** The hierarchical graph of spaces, devices, and people defined in the Digital Twins object model that supports inheritance, filtering, traversing, scalability, and extensibility. You can manage and interact with your spatial graph through the collection of REST APIs that are hosted in Azure.

::: zone target="docs"

### Learn more

- [Azure Digital Twins](/azure/digital-twins/overview)

::: zone-end

::: zone target="chromeless"

### Action

To create Azure Digital Twins:

1. In the left pane, select **Create a resource**.
2. Search for **digital twins**, then select **digital twins**.
3. Select **Create** to start the deployment process.
4. To review existing digital twins, select this button:

::: zone-end

## [Location intelligence](#tab/AzureMaps)

In addition to traditional location capabilities such as nearby, traffic, and routing, the Azure Maps service enables enterprises to create solutions by using real-time location intelligence, powered by world-class mobility technology partners TomTom and Moovit. Easily integrate advanced location and mobility capabilities into your applications with geospatial services.

**Azure Maps Data Service:** Upload and store geospatial data for use with spatial operations or image composition to reduce latency, increase productivity, and enable new scenarios within your applications.

**Spatial operations:** Enhance your location intelligence with a library of common geospatial mathematical calculations, including geofencing, closest point, great circle distance, and buffers.

**Geolocation:** Look up the country/region of an IP address. Customize content and services based on user location, and gain insight on customer geographic distribution.

::: zone target="docs"

### Learn more

- [Azure Maps](/azure/azure-maps/)

::: zone-end

::: zone target="chromeless"

### Action

To use location intelligence:

1. Go to **Azure Maps Accounts**.
2. Select **Create Azure Maps accounts**.

::: zone-end