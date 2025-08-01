# 🔦 LiComm (Demo) — Light Communication with ESP32

LiComm is an experimental **Li-Fi (Light Fidelity)** system using two ESP32 boards. It enables data transfer using a **laser** as a transmitter and a **solar panel** as a receiver — no WiFi or RF needed.

> ⚠️ **Note:** This is just **demo code** to prove the concept. A complete, easy-to-use **Arduino Library** named `LiCom` is under development and will be released soon.

---

## 📡 Overview

This setup enables simple one-way light communication using:

- **Transmitter ESP32:** Sends messages via laser pulses.
- **Receiver ESP32:** Detects light changes using a solar panel and reconstructs the original message.

---

## 🔧 Features

- 📲 **Bluetooth input** to enter messages from any smartphone.
- 💡 **Laser-based transmission** for visible light data transfer.
- ☀️ **Solar panel-based reception** (no special photodiodes needed).
- ⚙️ **Auto threshold calibration** to adjust for ambient light.
- 🧠 **Bit-level encoding/decoding** with timing control.
- 🧪 Works reliably at low speeds with clear line of sight.

---

## 🧰 Hardware Requirements

| Component           | Description                            |
|--------------------|----------------------------------------|
| 2× ESP32 boards     | One for transmission, one for reception |
| Laser module        | Connected to transmitter ESP32 (GPIO 2) |
| Small solar panel   | Connected to receiver ESP32 (GPIO 32)   |
| Bluetooth terminal app | To send messages from mobile         |
| Jumper wires        | For basic connections                   |

