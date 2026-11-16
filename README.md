# HOMEHUB – Intelligent Smart Home Automation System

### One Command. Complete Control. Smarter Living.

HOMEHUB is an intelligent, scene-based Smart Home Automation System developed to simplify the management and control of connected home devices through a centralised interface. The project focuses on automation, device management, sensor-based interactions, energy optimisation and multi-brand device integration using established Object-Oriented Software Design Patterns.

Unlike conventional home automation interfaces that require users to operate individual appliances separately, HOMEHUB introduces a scene-based approach in which multiple devices can perform coordinated actions through a single command. The system allows users to create and activate predefined scenes such as Movie Night, Sleep Mode, Leaving Home and Energy Saver, providing a more convenient and organised smart-home experience.

## Problem Statement

Managing multiple household devices independently can become inconvenient and inefficient. Users often need to control lighting, temperature, security systems and entertainment devices separately. Additionally, integrating devices from different manufacturers and managing their individual behaviours can introduce architectural complexity.

HOMEHUB addresses these challenges by providing a unified control architecture that combines scene-based automation, centralised device management, sensor-driven responses and energy-monitoring capabilities.

## Project Objectives

- Develop a centralised interface for managing smart-home devices.
- Implement scene-based automation for coordinated device operations.
- Demonstrate reusable and maintainable software architecture.
- Simulate intelligent responses through motion, smoke and temperature sensors.
- Support multi-brand device integration through adapter-based architecture.
- Introduce undo functionality for device operations and scene execution.
- Demonstrate energy optimisation through simulated ECO mode.
- Apply multiple Software Design Patterns to solve recurring software design problems.

## Key Features

### 1. Scene-Based Automation
HOMEHUB provides predefined automation scenes:

- **Movie Night:** Dims the lights, switches on the television, adjusts the thermostat and closes the curtains.
- **Sleep Mode:** Switches off main lights, adjusts bedroom lighting, changes the thermostat and activates security.
- **Leaving Home:** Turns off unnecessary appliances, closes curtains and locks the smart lock.
- **Energy Saver:** Moves idle devices into ECO mode and reduces simulated energy consumption.

### 2. Smart Device Management
Provides individual controls for smart lights, smart locks, thermostats, televisions and curtains. Users can adjust brightness, temperature, device power and operating states through an interactive dashboard.

### 3. Sensor-Based Automation
Simulates motion, smoke and temperature sensors. Sensor events notify registered components and can trigger predefined automation rules.

### 4. Energy Monitoring
Displays simulated power consumption, daily energy usage, estimated electricity costs and device-wise consumption. ECO mode demonstrates how reducing unnecessary device activity can optimise energy usage.

### 5. Command Execution and Undo
Supports individual device commands and scene-level operations. Users can reverse previous actions and restore earlier device states.

### 6. Multi-Brand Device Integration
Demonstrates a unified device interface using simulated vendor adapters for Samsung and LG devices, reducing dependency on manufacturer-specific operations.

### 7. Automation Rules
Supports rule-based and schedule-based automation strategies for responding to sensor events and predefined conditions.

### 8. Notifications and Activity History
Maintains a simulated activity timeline of scene activations, device operations, sensor events, automation triggers and undo actions.

## Software Design Patterns Implemented

HOMEHUB demonstrates nine Software Design Patterns:

| Design Pattern | Application |
|---|---|
| Command | Encapsulates device operations into independent objects with execute and undo functionality. |
| Composite | Combines multiple commands into scenes that can be executed or reversed as a group. |
| State | Manages device behaviour through On, Off and Eco states. |
| Observer | Enables sensors to notify registered observers about changes and events. |
| Adapter | Integrates vendor-specific devices through a common SmartDevice interface. |
| Facade | Provides a simplified interface for controlling the smart-home system. |
| Factory | Creates appropriate smart-device objects based on device type. |
| Singleton | Maintains a centralised SmartHub instance. |
| Strategy | Supports interchangeable rule-based and schedule-based automation approaches. |

## System Architecture

The system follows a modular, object-oriented architecture consisting of:

- **User Management:** Represents users and their associated homes.
- **Home and Room Management:** Organises devices into individual rooms.
- **Device Management:** Handles device operations and state transitions.
- **Scene Management:** Coordinates multiple commands through composite scenes.
- **Central Smart Hub:** Manages connected devices and command history.
- **Sensor Management:** Processes simulated sensor events.
- **Automation Management:** Evaluates conditions and executes automation strategies.
- **Energy Monitoring:** Tracks simulated consumption and estimated costs.
- **Notification Management:** Displays system events and alerts.

The architecture is documented through a UML Class Diagram created using StarUML.

## Technology Stack

**Frontend**
- React.js
- JavaScript
- Vite
- Tailwind CSS
- Lucide React
- Recharts

**Development and Design Tools**
- Visual Studio Code
- Antigravity
- StarUML
- Git and GitHub

## Project Scope and Implementation

HOMEHUB is developed as an interactive frontend demonstration prototype. Device operations, sensor readings, notifications, automation events and energy statistics are simulated using local application state and mock data.

The prototype does not require physical IoT hardware, live vendor APIs, a backend server, cloud infrastructure or a database. Its primary purpose is to demonstrate the functionality and architectural application of Software Design Patterns through an interactive software model.

## Future Enhancements

Potential future developments include:

- Integration with actual IoT devices and smart-home platforms.
- Real-time sensor monitoring using hardware modules.
- Voice-controlled automation.
- Machine-learning-based energy optimisation.
- Cloud-based device synchronisation.
- Mobile application integration.
- Advanced scheduling and personalised automation.
- Real-time energy consumption analytics.

## Expected Outcome

HOMEHUB demonstrates how multiple Software Design Patterns can work together to create a modular, extensible and maintainable smart-home automation system. By combining scene-based control, simulated intelligent automation, sensor interactions and energy awareness, the project presents a practical application of object-oriented software engineering principles.

## Project Information

**Project Name:** HOMEHUB  
**Project Category:** Smart Home Automation  
**Domain:** Software Engineering and Design Patterns  
**Development Type:** Interactive Frontend Prototype  
**Institution:** BGS College of Engineering and Technology  
**Department:** Computer Science and Design Engineering  
**Event:** PATTERNXTHON 2026

---

**HOMEHUB – Automate. Optimise. Experience Smarter Living.**
