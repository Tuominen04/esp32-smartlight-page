# ESP32 SmartLight Starter

A beginner-friendly and extensible smart lighting controller built on the ESP-IDF framework. This project combines BLE setup, WiFi connectivity, HTTP-based control, and OTA updates to demonstrate modern IoT practices in an educational and hands-on way.

This repository contains the public-facing documentation and licensing information for the `esp32-smartlight-starter` project. The actual source code and firmware are available under commercial license only.

<br/>

> ⚠️ **This project is designed for educational and prototype purposes only. It is not certified for commercial or safety-critical use.**


---

## ✨ Features

* **BLE Setup** – Configure WiFi credentials using BLE
* **WiFi Connectivity** – Connect to 2.4GHz networks
* **REST API** – HTTP server for light control and status
* **OTA Updates** – Update firmware over WiFi
* **NVS Storage** – Store WiFi credentials and metadata
* **Modular Codebase** – Easy to extend and test
* **Unit & System Tests** – Test your implementation on real hardware

---

## 📷 Architecture Diagram

```
┌─────────────────┐    ┌──────────────────┐    ┌─────────────────┐
│   Mobile App    │◄──►│  ESP32 Device    │◄──►│  WiFi Network   │
│  (BLE Client)   │    │                  │    │                 │
└─────────────────┘    │  ┌─────────────┐ │    └─────────────────┘
                       │  │ BLE Manager │ │              │
                       │  └─────────────┘ │              │
                       │  ┌─────────────┐ │              ▼
                       │  │WiFi Manager │ │    ┌─────────────────┐
                       │  └─────────────┘ │    │  HTTP Client    │
                       │  ┌─────────────┐ │    │ (OTA Updates)   │
                       │  │HTTP Server  │ │    └─────────────────┘
                       │  └─────────────┘ │
                       │  ┌─────────────┐ │
                       │  │GPIO Control │ │
                       │  └─────────────┘ │
                       └──────────────────┘
```
---

## 🔐 Licensing & Legal Info

This project is **commercially licensed** with restrictions. It is intended for internal and educational use only unless you purchase a commercial or source license.

### 📄 Important Documents (see `licenses/`)

* [LICENSE.md](/LICENSE.md) – Commercial license terms
* [EULA.md](licenses/EULA.md) – End User License Agreement
* [DISCLAIMER.md](licenses/DISCLAIMER.md) – Electrical safety and intended use
* [PRIVACY.md](licenses/PRIVACY.md) – Data handling and user rights
* [SALES\_TERMS.md](licenses/SALES_TERMS.md) – Licensing tiers, pricing
* [THIRD\_PARTY\_LICENSES.md](licenses/THIRD_PARTY_LICENSES.md) – ESP-IDF and open-source attributions

### ❗ Not for Life-Critical Use

This project is not certified for medical, life safety, or critical infrastructure applications.

---

## 💬 Support & Feedback

* Contact: [arttutuominen10@gmail.com](mailto:arttutuominen10@gmail.com)
* ESP-IDF resources: [Espressif Docs](https://docs.espressif.com/projects/esp-idf/en/latest/)

---

## 📢 Commercial Use

To purchase a commercial or source code license and gain access to the private repository:

1. Visit the [Buy Page](https://yourstore.gumroad.com/l/smartlight)
2. Provide your GitHub username during checkout
3. You'll receive private repository access within 24 hours

*© 2025 Arttu Tuominen. All rights reserved.*
