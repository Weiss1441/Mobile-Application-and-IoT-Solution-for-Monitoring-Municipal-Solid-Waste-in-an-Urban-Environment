# SmartWaste: Intelligent Waste Monitoring System

## Brief Description

SmartWaste is a comprehensive software and hardware solution designed to automate municipal waste collection. The system integrates IoT devices for real-time measurement of waste container fill levels, a cloud server for data collection and analysis, and a mobile application for monitoring and logistics management.

## Problem Statement

The traditional approach to solid municipal waste collection relies on fixed schedules and routes. This leads to two primary issues:

1. Overflow of containers prior to the scheduled arrival of garbage trucks, degrading sanitary and environmental conditions.

2. Inefficient use of resources (fuel, time, equipment wear) when collecting half-empty bins.

Currently, there is an absence of a unified digital platform capable of providing real-time data for dynamic route adjustments.

## Target Users

* **Municipal Services & Environmental Agencies:** For monitoring sanitary conditions and generating reports.

* **Regional Waste Operators & Dispatchers:** For tracking statistics, planning, and optimizing collection routes.

* **Garbage Truck Drivers:** Utilizing the mobile application to navigate to priority collection points.

## Expected Outcomes

* A functional prototype of an IoT device capable of autonomously transmitting data over a wireless network.

* A fully deployed server infrastructure featuring a database and REST/MQTT APIs.

* A completed mobile application for iOS and Android with an interactive user interface.

* A unified, integrated system successfully tested on a pilot dataset, demonstrating confirmed data transmission with minimal delay.

## Project Scope & Current Development Status

**In Scope:**
Hardware node development (microcontroller + sonar), data transmission configuration via MQTT/HTTP, database design, backend service development, creation of a mobile application and monitoring dashboard, and end-to-end testing on 1-3 devices.

**Current Status (Pre-defense):**

* Analysis and design phase completed.

* Architecture, database schema, and UI mockups drafted.

* IoT component selection and preliminary testing initiated.

## Team Members and Responsibilities

* **Nurym Muratov** – IoT Subsystem Developer

  * Hardware architecture and sensor integration.

  * Embedded software development and network protocol implementation.

* **Dinmukhammed Baltabay** – Mobile Application Developer

  * UI/UX design and cross-platform mobile client development.

  * Geolocation and push notification features.

* **Miras Aliyev** – Backend & Analytics Developer

  * Database design and API development.

  * Real-time data processing and web dashboard creation.

* **Supervisor:** Akerke Akanova

## Selected Technologies

* **IoT Hardware:** ESP32, Ultrasonic Sensor (HC-SR04/JSN-SR04T), C/C++.

* **Mobile App:** Flutter / Dart (cross-platform).

* **Backend:** Python (FastAPI) or Node.js, PostgreSQL, MQTT broker (e.g., Mosquitto).

* **Protocols:** MQTT, REST API.

## Project Links

* **Issue Tracker (YouTrack):** \[Link to YouTrack Project\]

* **Project Documentation:** \[Link to Docs/Diagrams\]

* **UI Mockups / Prototype:** \ https://www.figma.com/design/lfBwxZg5EPVAZkzUur6LGe/SMA?node-id=0-1&t=wgl1BGNu7e87YclG-1

## Setup, Execution, and Testing Instructions

*Detailed setup, execution, and testing instructions will be added here as soon as the first runnable full-stack prototype is committed to the main branch.*
