# OSI OS – Open Smart Irrigation Operating System

**OSI OS** is an open-source operating system for Raspberry Pi, designed to power LoRaWAN-based smart irrigation hubs. Built on ChirpStack Gateway OS and developed within the Node-RED environment, OSI OS enables fully offline irrigation scheduling and real-time sensor monitoring—ideal for deployment in resource-constrained agricultural settings.

## Key Features
- **LoRaWAN Integration**  
  Supports long-range, low-power communication between sensors and actuators.

- **Node-RED Visual Programming**  
  Intuitive, event-based interface suitable for quick, beginner-friendly adaptation.

- **Local Data Processing**  
  100% offline operation with on-device storage and scheduling logic.

- **Farmer-Friendly Dashboard**  
  Web-based UI accessible via local Wi-Fi

- **Modular Plugin System**  
  Easily extend the system to support new sensors or actuators.

## Repository Structure
```plaintext
osi-os/
│
├── README.md               → Project overview and setup instructions
├── LICENSE                 → MIT License
├── .gitignore              → Ignore rules for OS image and system files
│
├── docs/                   → Guides, diagrams, and system architecture
├── src/                    → Node-RED flows and plugin modules
├── os-image/               → Build scripts and flashing instructions
├── dashboard/              → Dashboard configurations
└── tools/                  → Utility scripts for logs, diagnostics, etc.
