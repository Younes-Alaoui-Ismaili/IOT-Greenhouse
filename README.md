# IoT-Based Smart Mini Greenhouse

## Overview
The **IoT-Based Smart Mini Greenhouse** is developed and maintained by **IoT-Experts** as part of a professional contract under Canadian law. This project adheres to advanced software architectural principles, highlighting our expertise in scalable IoT solutions tailored for agricultural applications.

The greenhouse system features a distributed architecture, combining event-driven and modular design approaches. Independent subsystems share real-time data using MQTT and RESTful APIs to ensure robustness, scalability, and ease of maintenance.

This document provides an overview of the project's features, architectural highlights, setup instructions, and contribution guidelines.

---

## Key Features

### 1. **Environmental Monitoring**
- **CO2 Sensors (MQ-135):** Monitor carbon dioxide levels to optimize photosynthesis.
- **UV Radiation Measurement:** Maintain and adjust UV exposure for healthy plant growth.
- **Temperature and Humidity Sensors (DHT22):** Ensure stable climate control.
- **Soil Moisture Sensors:** Dynamically regulate watering schedules.
- **Light Sensors (BH1750):** Ensure plants receive optimal light intensity.

### 2. **Energy Efficiency**
- **Solar Panels:** Reduce reliance on traditional energy sources.
- **Battery System:** Ensure uninterrupted operation with adaptive load balancing.

### 3. **Water Management**
- **Automated Irrigation:** Dynamically adjust watering schedules based on soil moisture.
- **Rainwater Harvesting:** Collect and utilize rainwater for sustainability.

### 4. **Data Analytics**
- **AI-Based Insights:** Predict plant growth trends, detect anomalies, and optimize conditions.
- **Real-Time Alerts:** Notify users of environmental deviations via mobile and web platforms.

### 5. **Scalability**
- **Modular Design:** Seamlessly integrate additional modules or greenhouses.
- **Centralized Platform:** Manage multiple greenhouses through a unified dashboard.

### 6. **Security**
- **Encrypted Communication:** Secure data transfers with TLS protocols.
- **Role-Based Access Control:** Implement granular permissions for enhanced security.

### 7. **Remote Control and Automation**
- **Mobile & Web Interfaces:** Access real-time data and control the greenhouse remotely.
- **Automated Responses:** AI-driven automation adjusts environmental conditions based on thresholds.

---

## Architectural Highlights
- **Event-Driven Architecture:** Real-time updates across sensors and actuators.
- **Modular Microservices:** Independent modules simplify maintenance and scalability.
- **Cloud Integration:** Real-time dashboards and remote control through platforms like Blynk™.

---

## Installation and Setup

### Architectural Style
This project employs a hybrid architectural style combining event-driven architecture, client-server models, and modular microservices to ensure:
- Real-time data synchronization via MQTT.
- Scalability through independent microservices.
- Secure remote monitoring using IoT platforms like Blynk™.

### Hardware Requirements
- **NodeMCU ESP8266:** Microcontroller for IoT communication.
- **DHT22:** High-accuracy temperature and humidity sensor.
- **BH1750:** Light sensor with wide lux range.
- **Hygrometer:** Soil moisture sensor for precise irrigation control.
- **MQ-135:** CO2 sensor for air quality monitoring.
- **Solar Panels & Battery:** Optional but recommended for sustainability.

### Software Requirements
- **Node-RED:** Flow-based visual programming tool.
- **MQTT:** Lightweight messaging protocol.
- **Blynk™:** IoT platform for dashboards and real-time monitoring.

### Steps to Install
1. Connect and configure hardware components as per the provided manual.
2. Install Node-RED and required nodes for dashboard and data processing.
3. Deploy the provided Node-RED flow to automate processes and visualize data.
4. Link the setup with the Blynk™ platform for remote monitoring and alerts.

### Node-RED JSON Flow
The Node-RED JSON flow includes:
- Integration of CO2, temperature, humidity, soil moisture, and light sensors.
- Automated irrigation triggered by soil moisture levels.
- Real-time visualization with gauges and charts.
- MQTT-based communication for seamless data exchange.

---

## Usage
- Monitor environmental data via dashboards.
- Use predictive analytics for data-driven adjustments.
- Access historical data to optimize resource efficiency.
- Leverage AI-driven automation for reduced manual intervention.

---

## Contribution

### Professional Workflow
This project is governed by Canadian contractual law and managed under IoT-Experts' professional standards.

#### Submitting Changes
- Submit issues or changes via GitHub with detailed documentation.
- Include a pull request outlining the purpose and scope of modifications.

#### Project Management
- Tasks and milestones are tracked using tools like Jira or Trello.
- Contributors must log progress and adhere to project timelines.

#### Approval Process
- External contributions require prior written approval.
- All contributions must comply with intellectual property and confidentiality clauses.

For collaboration or inquiries, contact IoT-Experts directly. Contributions are subject to rigorous testing and professional standards.

---

## License
This project is licensed under a custom proprietary license. Contact IoT-Experts for detailed terms and restrictions.

---

## Flow Node-RED
Below is an overview of the Node-RED flow used for this project:

![Flow Node-RED](./node-red-flow-screenshot.PNG)

