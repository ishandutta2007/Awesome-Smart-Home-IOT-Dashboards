# Awesome-Smart-Home-IOT-Dashboards

# Top Smart Home & IoT Dashboards Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Self-Hosted Home Automation, Local-First IoT Dashboards, MQTT/Zigbee/Matter Control & Telemetry Visualization*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted IoT platforms** and **open-source GitHub projects** for **Smart Home & IoT Dashboards**. These tools enable homeowners, embedded engineers, makers, and home-labbers to monitor sensor telemetry, build touch-friendly wall-mounted control panels, automate Zigbee/Z-Wave/Matter/ESPHome devices, and visualize real-time industrial or residential IoT metrics without cloud dependency.

**Examples** include Home Assistant, ThingsBoard Community Edition, Node-RED Dashboard, Grafana, OpenHAB, Domoticz, Gladier / Gladys Assistant, ioBroker, MagicMirror², Freeboard, adamoberley/habirddashboard, Home Assistant Cloud (Nabu Casa), Blynk, Adafruit IO, Arduino Cloud, Ubidots, Datacake, Losant, Particle Cloud, and Tuya Developer Platform.

**Open-source emphasis**: This list heavily expands on active open-source smart home hubs, custom Lovelace/wall-tablet dashboards, MQTT/Node-RED flow dashboards, and self-hosted IoT telemetry stacks — ideal for privacy-focused homeowners, embedded developers, and home-lab enthusiasts building local-first automation systems.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Home Assistant Cloud (Nabu Casa)](https://nabucasa.com)**  
  Official cloud companion service for Home Assistant providing zero-config encrypted remote dashboard access, Google Assistant/Alexa voice bridges, and WebRTC relay without port forwarding.

- **[ThingsBoard Cloud](https://thingsboard.io)**  
  Enterprise cloud IoT platform offering drag-and-drop real-time telemetry dashboards, rule chains, alarm management, and MQTT/CoAP/HTTP device provisioning.

- **[Blynk](https://blynk.io)**  
  Low-code IoT cloud platform featuring mobile and web drag-and-drop dashboards, OTA firmware updates, and native libraries for ESP32, Arduino, and Raspberry Pi.

- **[Adafruit IO](https://adafruit.com)**  
  Maker-friendly cloud data logging and visual dashboard service supporting MQTT feeds, triggers, webhooks, and CircuitPython/Arduino hardware integrations.

- **[Arduino Cloud](https://arduino.cc)**  
  Integrated online IDE, device manager, and customizable IoT dashboard builder with mobile companion apps and over-the-air sketch deployment.

- **[Ubidots](https://ubidots.com)**  
  Cloud IoT application enablement platform designed for sensor data visualization, synthetic metrics, alerts, and white-label industrial dashboards.

- **[Datacake](https://datacake.co)**  
  Low-code multi-protocol IoT platform featuring instant LoRaWAN, MQTT, and cellular payload decoders alongside shareable public/private dashboards.

- **[Losant](https://losant.com)**  
  Enterprise cloud IoT platform combining edge compute, visual workflow engines, digital twins, and customizable end-user dashboards.

- **[Particle Cloud](https://particle.io)**  
  Integrated edge-to-cloud IoT device management, cellular/Wi-Fi connectivity, fleet OTA updates, and telemetry console.

- **[Tuya Developer Platform](https://tuya.com)**  
  Commercial IoT PaaS and smart-home device cloud ecosystem powering OEM Wi-Fi/Zigbee/Matter hardware and companion mobile control apps.


## Open-Source GitHub Projects

- **[Home Assistant (home-assistant/core)](https://github.com)**  
  The premier open-source, local-first home automation platform featuring a highly customizable Lovelace dashboard engine, 3,000+ integrations, Matter/Thread/Zigbee support, and voice assist.

- **[habirddashboard (adamoberley/habirddashboard)](https://github.com)**  
  Open-source companion dashboard for Home Assistant designed for wall-mounted tablets and kiosks with clean entity cards, responsive layouts, and streamlined smart-home controls.

- **[ThingsBoard Community Edition (thingsboard/thingsboard)](https://github.com)**  
  Open-source IoT platform for data collection, processing, visualization, and device management with rich customizable widgets, maps, and rule engines.

- **[Node-RED & FlowFuse Dashboard 2.0 (FlowFuse/node-red-dashboard)](https://github.com)**  
  Low-code, event-driven visual programming tool paired with a modern Vue-based dashboard builder for wiring MQTT brokers, hardware GPIO, and APIs into interactive control panels.

- **[openHAB (openhab/openhab-core)](https://github.com)**  
  Vendor- and technology-agnostic open-source smart home automation server written in Java featuring responsive MainUI, HABPanel wall dashboards, and semantic home modeling.

- **[Grafana (grafana/grafana)](https://github.com)**  
  Industry-standard open-source observability and time-series visualization platform widely used alongside InfluxDB/Prometheus/TimescaleDB for high-density IoT and energy dashboards.

- **[Domoticz (domoticz/domoticz)](https://github.com)**  
  Lightweight, fast open-source home automation system written in C++ optimized for low-power hardware like Raspberry Pi with customizable web floorplans.

- **[ioBroker (ioBroker/ioBroker.js-controller)](https://github.com)**  
  Modular, Node.js-based open-source smart home integration platform featuring `vis` drag-and-drop visualization editors and hundreds of protocol adapters.

- **[Gladys Assistant (GladysAssistant/Gladys)](https://github.com)**  
  Privacy-first, lightweight open-source smart home server built with Node.js and Preact offering a clean, zero-YAML dashboard out of the box.

- **[MagicMirror² (MagicMirrorOrg/MagicMirror)](https://github.com)**  
  Popular open-source modular smart mirror and ambient information display platform with hundreds of community modules for calendars, transit, weather, and Home Assistant status.

- **[Freeboard (Freeboard/freeboard)](https://github.com)**  
  Lightweight, open-source real-time JSON/WebSocket/MQTT dashboard builder ideal for embedding clean IoT status widgets in static web interfaces.

- **[ESPHome (esphome/esphome)](https://github.com)**  
  Open-source system to control ESP8266/ESP32/RP2040 microcontrollers via simple YAML configuration files with native Home Assistant API and local web dashboards.

- **[Zigbee2MQTT (Koenkk/zigbee2mqtt)](https://github.com)**  
  Open-source bridge that connects thousands of Zigbee smart home devices directly to local MQTT brokers with a built-in web UI for network maps and OTA updates.

### Additional Strong Open-Source Options

- **[Mushroom Cards (piitaya/lovelace-mushroom)](https://github.com)** & **[Bubble Card (Clooos/Bubble-Card)](https://github.com)** — Minimalist, mobile-first open-source UI card suites that transform Home Assistant dashboards into modern control panels.
- **[Eclipse Mosquitto (eclipse-mosquitto/mosquitto)](https://github.com)** & **[EMQX (emqx/emqx)](https://github.com)** — Open-source MQTT message brokers forming the real-time nervous system of local IoT dashboards.
- **[Frigate NVR (blakeblackshear/frigate)](https://github.com)** — Open-source local AI NVR with real-time object detection and low-latency WebRTC camera feeds built for smart home dashboards.
- **[Homepage (gethomepage/homepage)](https://github.com)** & **[Homarr (homarr-labs/homarr)](https://github.com)** — Sleek, self-hosted service dashboards with native widgets for Home Assistant, Pi-hole, AdGuard Home, and Proxmox.
- **[Tasmota (arendst/Tasmota)](https://github.com)** — Alternative open-source firmware for ESP-based smart plugs, switches, and sensors freeing devices from proprietary Tuya/vendor clouds.
- **[OpenMower / BirdNET-Pi / Local-Tuya](https://github.com)** — Open-source local-control integration allowing Home Assistant to control Tuya Wi-Fi devices entirely over LAN without cloud round-trips.

**Frameworks for building custom systems**: Combine **Home Assistant** + **Zigbee2MQTT** + **ESPHome** + **Mosquitto** for local-first device control, enhance the UI with **habirddashboard** or **Mushroom Cards** on a wall tablet, and pipe long-term sensor telemetry into **InfluxDB + Grafana** for historical analytics.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Smart home hubs and IoT dashboards control physical switches, locks, cameras, and appliances; isolate IoT devices on a dedicated VLAN without unrestricted WAN access, and secure remote dashboard endpoints with WireGuard/Tailscale or strong 2FA.
- Flashing custom firmware (`ESPHome`, `Tasmota`) onto mains-powered smart plugs or relays requires disconnecting devices from AC mains during programming and following electrical safety standards.

---

**Made for smart home builders, embedded developers, home-labbers, and open-source enthusiasts.**  
Let's make smart homes and IoT dashboards local-first, private, reliable, and open to everyone.
