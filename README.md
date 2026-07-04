# Willow: AI Companion

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square" alt="License: MIT">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen.svg?style=flat-square" alt="Status: Active">
  <img src="https://img.shields.io/badge/Hardware-XIAO_ESP32--S3-blue.svg?style=flat-square" alt="Hardware: XIAO ESP32-S3">
</p>

Willow is an interactive AI companion powered by the **Seeed Studio XIAO ESP32-S3**. Designed as a high-fidelity, expressive desktop companion, Willow features a crisp **0.96" SSD1306 OLED (Full White)** display, clear audio output via the **MAX98357A I2S Amplifier**, and precision voice capture through the **INMP441 MEMS Omnidirectional Microphone**. Willow is activated hands-free with the wake word **"Hey,Willow"**, enabling natural, low-friction voice interaction.

---

## Features

- **Voice Activation:** Always-listening wake word detection — simply say **"Hey,Willow"** to begin an interaction, no button press required.
- **Expressive Interface:** Dynamic facial animations rendered on a high-contrast white OLED display.
- **Audio Capability:** Powered by a 3W 4Ω speaker for clear, resonant AI vocal feedback.
- **Voice Recognition:** High-precision audio capture using a professional-grade INMP441 MEMS microphone.
- **Compact & Modular:** Built on the powerful ESP32-S3 architecture, optimized for custom enclosures.

---

## Hardware Requirements

| Component | Specification |
|---|---|
| Microcontroller | Seeed Studio XIAO ESP32-S3 |
| Display | 0.96" SSD1306 OLED (Full White) |
| Audio Output | MAX98357A I2S Amplifier + 4Ω 3W Speaker |
| Audio Input | INMP441 MEMS Omnidirectional Microphone |

---

## Wake Word Configuration

Willow uses **"Hey,Willow"** as its default wake word for hands-free activation.

- The device continuously listens for the wake phrase in a low-power state.
- Upon detection, Willow transitions to active listening mode, indicated by a facial animation change on the OLED display.
- Wake word sensitivity can be adjusted in the firmware configuration to reduce false triggers in noisy environments.

---

## Installation (Quick Flash)

To install the firmware without setting up a full development environment:

1. Navigate to the [Robonavigators ESP Flasher](https://robonavigators.github.io/flash.html).
2. Select **"Willow: AI Companion"** from the firmware menu.
3. Connect your XIAO ESP32-S3 via USB.
4. Select the appropriate COM/Serial port in the browser interface.
5. Click **Upload** to flash the firmware.