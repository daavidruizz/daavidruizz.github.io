---
title: My Repositories
description: A collection of my open source projects and contributions
slug: repositories
layout: "page" 
links:
  - title: Telegram Bot
    description: Telegram Bot developed with C++ and TDLib, used for manage and download files, adding ideas.
    website: https://github.com/daavidruizz/TelegramBotCpp
    image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
  - title: rzLogger
    description: Portable, simple, and thread-safe logger for C/C++ projects.
    website: https://github.com/daavidruizz/rzLogger
    image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
  - title: Scripts
    description: Some scripts and apps bash
    image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
    website: https://github.com/daavidruizz/scritps_apps
menu:
    main: 
        weight: 3
        params:
            icon: brand-github
comments: false
---

Welcome to my code portfolio! Here you'll find a selection of my most notable projects, ranging from embedded systems to utility tools.

## PioTGuard Project: IoT Surveillance System

 Final Degree Project - Complete Security Monitoring Solution (UMA)

This comprehensive surveillance system demonstrates end-to-end IoT development, combining embedded systems, server infrastructure, and mobile applications for real-time security monitoring.

**System Overview:**
A complete security monitoring solution designed for restaurants and commercial spaces, offering protection against both external threats and internal risks through intelligent sensor monitoring and real-time video surveillance.

**System Components:**

| Component | Technology Stack | Functionality |
|-----------|------------------|---------------|
| **[ESP32 Sensor Node](https://github.com/daavidruizz/PioTGuard-Sensors)** | C/C++, FreeRTOS, MQTT | Multi-sensor monitoring and data transmission |
| **[Raspberry Pi Server](https://github.com/daavidruizz/PioTGuard_Server)** | Apache, MariaDB, GStreamer, SSL/TLS | Video streaming, recording, and data processing |
| **[Android Mobile App](https://github.com/daavidruizz/PioTGuardApp)** | Java/Kotlin, Android SDK | System configuration, monitoring, and notifications |

**Security Features:**

- **SSL/TLS Encryption** - All communications encrypted
- **Mutual TLS (mTLS)** - Bidirectional authentication between client and server
- **Secure MQTT** - Encrypted sensor data transmission

**Sensor Capabilities:**

- **Presence Detection** - Movement monitoring in specific areas
- **Magnetic Sensors** - Door/window opening control
- **Gas/Smoke Detection** - Early fire and gas leak detection
- **Real-time Video** - Continuous streaming with event-triggered recording

**Mobile Features:**

- Real-time system monitoring and configuration
- Event history with associated video recordings
- Push notifications for anomaly detection
- Secure authenticated access

**[Download Complete Documentation (PDF)](https://github.com/daavidruizz/PioTGuard-Sensors/blob/main/TFG_PIOTGUARD.pdf)**

**Technologies Used:** Raspberry Pi, ESP32, Android, MQTT, Apache, SSL/TLS, mTLS, GStreamer, MariaDB, IoT, FreeRTOS

---

## Other Projects: