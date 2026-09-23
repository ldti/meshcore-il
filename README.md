# MeshCore IL 📡

Community guide for configuring MeshCore devices with our shared custom frequency and network settings.

## Welcome to MeshCore IL 🇮🇱

This guide explains how to set up your device to join the MeshCore IL community mesh network. MeshCore is an alternative mesh routing protocol that offers efficient communication over LoRa radios.

### ⚠️ Disclaimer
This guide is provided for community use only, for community educational purposes only.
The authors and maintainers are not responsible for any device damage, interference, or legal issues arising from the use of these settings.
Always follow local regulations and use devices responsibly.
Participation in any shared network (like WhatsApp groups) is voluntary, and users should exercise caution and avoid sharing personal information.

---

### 🔍 What Is MeshCore?
MeshCore is an open-source mesh networking protocol that allows devices to communicate over long distances without cellular or internet service. It features efficient routing and is often used for reliable repeater networks and community grids.

---

### 🛠 Getting Started

**1. Flash Your Device**
Use the **MeshCore Flasher** to install the appropriate firmware:
[https://meshcore.io/flasher](https://meshcore.io/flasher)

It is important to choose the correct firmware for your use case:

*   **Companion Firmware:** Use this for portable devices or trackers that need to pair with a mobile phone (via Bluetooth). It is designed for mobile use and interaction with the MeshCore app.
*   **Repeater Firmware:** Use this for stationary devices. This firmware turns your hardware into a node that extends the range of the network and relays messages between other devices.

**2. Configure Radio Settings**
Once flashed, go to your device settings and apply the **Custom** radio settings below.

---

### ⚙️ Configuration Summary

Please ensure your device matches these exact parameters to join the network:

| Parameter | Setting |
| :--- | :--- |
| **Region** | **Custom** |
| **Frequency** | **917.525 MHz** |
| **Bandwidth** | **62.5 kHz** |
| **Spreading Factor** | **8** |
| **Coding Rate** | **5** |

**Repeater Note:** If your device is unable to detect existing repeaters, consider deploying a repeater in a high-elevation location to ensure it can receive advertisements from other network nodes.

---

### 📦 Recommended Mesh Devices for Starters

MeshCore runs on similar hardware to Meshtastic. Here are some popular choices:

*   **Seeed Wio Tracker L1** - Includes OLED, GPS, and joystick. Very power efficient.
*   **Heltec WiFi LoRa 32 V4** - Compact and updated board layout.
*   **Lilygo T-echo** - Compact e-ink display device, ESP32-C3 based, excellent battery life.

**Tips for beginners:**
1.  Ensure your region is set to **Custom** and the frequency is exactly **917.525 MHz**.
2.  Pair your device with the MeshCore app for configuration.

---

### 📢 Connect

Join the MeshCore IL community for support, updates, and discussions:

[**Join MeshCore IL WhatsApp Group**](https://chat.whatsapp.com/H57uPbyIYE5D1miPTFXRjT?s=cl&p=a&ilr=1)
