# JOOLDI Smart Urban Locker 🚀

**JOOLDI** is an infrastructure ecosystem designed to optimize high-demand urban spaces. The brand name is a tribute to its founder, Joaquín Olivieri Díaz, and reflects a commitment to sustainable urban engineering. This repository contains the technical specifications, structural design, and management logic for our smart storage system tailored for urban parking environments. 🏙️

## Project Description 🛠️
High-density modular infrastructure for the secure storage of urban micromobility, optimized for bicycles and electric scooters with high-security mechanical access systems. 🛡️

## User Experience (JOOLDI App) 📱
The **JOOLDI** app acts as the ecosystem's control center, allowing users to:
- **Smart Localization**: Real-time discovery of the nearest storage station or charging point. 📍
- **Availability**: Check real-time occupancy of lockers and bays before arriving. 🟢
- **Access Management**: View the exact location of the assigned locker and receive security notifications. 🔐


## User Experience (JOOLDI App) 📱
The **JOOLDI** app acts as the ecosystem's control center, allowing users to:
- **Smart Localization**: Real-time discovery of the nearest storage station or charging point. 📍
- **Availability**: Check real-time occupancy of lockers and bays before arriving. 🟢
- **Access Management**: View the exact location of the assigned locker and receive security notifications. 🔐

- ### 💳 Agentic Payment & Transaction Infrastructure
The system features a payment module integrated with **Mercado Pago (Production Credentials)** and automated by **Gemini**, enabling a frictionless monetization cycle for urban micromobility:

* **Dynamic Plans:** Automated management of charging time tariffs stored in scalable databases (`30 min / $50`, `1 hr / $90`, `2 hr / $160`).
* **Order Lifecycle:** Instant payment preference creation via API (`charging_orders`) ensuring full transaction traceability at the totem.
* **Webhooks & Async Confirmation:** Real-time payment validation that authorizes power delivery and autonomously updates node availability status.

### 🧠 Cognitive Engine & Orchestration via Gemini API
The platform's operational core implements direct calls to advanced models via the **Gemini API**, agentically processing urban environment variables to optimize totem services:

* **Real-Time Data Interpretation:** The `/app-api/charging/interpret` endpoint processes traffic flows, urban availability, and micromobility patterns using the **Gemini API** to make automated deployment decisions.
* **End-to-End Automation:** All business logic, from plan structuring to charging state management, operates natively via calls to the **Gemini API**, guaranteeing a fluid and decentralized response.
* **Synchronized Transactional Infrastructure:** The artificial intelligence not only analyzes the environment through the **Gemini API** but also securely communicates with production payment gateways to validate payment preferences and confirmation webhooks without human intervention.


## Ecosystem Components 🧩
- **J-O-O-L-D-I Urban Smart Bay**: High-security open bay for bicycles. 🚲
- **J-O-O-L-D-I Smart Urban Scooters**: High-density storage modules featuring industrial sliding drawers. 🛴

## Technical Specifications ⚙️
- **Security**: High-security mechanical locking system (individual physical key per user). 🔑
- **Ergonomics**: Horizontal storage at waist height to prevent heavy lifting. 🧘‍♂️
- **Materiality**: Industrial steel structure with high-density polymer protection to prevent vehicle wear or scratches. 🏗️
- **Modularity**: Scalable design adaptable to long, finite spaces in urban parking lots. 📏



## Brand Philosophy 💡
The name **JOOLDI** fuses the identity of its creator, Joaquín Olivieri Díaz, reflecting a personal commitment to engineering sustainable and efficient urban solutions in Uruguay. 🇺🇾

## License 📄
Copyright (c) 2026 Joaquín Olivieri Díaz. All rights reserved.
