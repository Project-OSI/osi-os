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
##  Roadmap

This roadmap outlines the planned development milestones for OSI OS. Timelines are indicative and may shift based on field feedback and contributor input.

### Alpha – Core Functionality (Q4 2025)
- [x] Offline operation with customized ChirpStack Gateway OS (Raspberry Pi)
- [ ] Integration of KIWI Agriculture Sensor by TEKTELIC (soil moisture, temp, humidity)
- [ ] Integration of STREGA Smart Valve for automated irrigation control
- [ ] Local database (SQLite) for storing sensor and environmental data
- [ ] Node-RED flows for basic scheduling, threshold logic, and actuator control
- [ ] Web dashboard for  soil monitoring and trigger-based scheduling
- [ ] Basic alerting system (e.g., dry soil warning, device disconnect)
- [ ] Documentation: Hardware setup, wiring guide, image flashing, troubleshooting

### Beta – Field-Ready Release (Q2 2026)
- [ ] Multi user and role-based access (farmer, technician, superuser)
- [ ] Modular plugin system to support additional sensors and control devices
- [ ] Backup and export functionality for sensor logs and schedules
- [ ] On-device diagnostics UI (LoRa signal, battery status, system health)
- [ ] Sensor calibration and alerting functions in UI

### 🚀 v1.0 – Community Release (Q4 2026)
- [ ] Stable OS image with one-click installer
- [ ] Configurable irrigation routines per crop
- [ ] Multilingual dashboard (starting with English, French, Arabic, Swahili)
- [ ] Contribution workflow for plugin submissions and bug reports
- [ ] Training package for local technicians and partners


## Repository Structure
```plaintext
osi-os/
│
├── README.md               → Project overview and setup instructions
├── LICENSE                 → MIT License
├── .gitignore              → Ignore rules
│
├── docs/                   → Guides, diagrams, and system architecture
├── src/                    → Node-RED flows and plugin modules
├── os-image/               → Build scripts and flashing instructions
├── dashboard/              → Dashboard configurations
└── tools/                  → Utility scripts for logs, diagnostics, etc.
