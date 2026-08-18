# Li-Fi Communication System

## 📌 Overview

This project implements a **Li-Fi (Light Fidelity) based optical wireless communication system** using an Arduino. Unlike conventional wireless communication systems that use radio frequency signals, Li-Fi uses **visible light from an LED to transmit digital data**.

The system demonstrates the complete process of **data transmission, optical signal detection, decoding, and message display** using low-cost embedded hardware.

## ⚙️ Working Principle

The transmitter converts the input message into digital data and controls an LED to generate corresponding light pulses. These rapid variations in LED intensity represent the transmitted binary information.

At the receiver, an **LDR (Light Dependent Resistor)** detects the changes in incident light and produces corresponding electrical signals. The Arduino processes these signals, reconstructs the transmitted data, and displays the decoded message on a **16×2 LCD**.

```text
Input Message
      ↓
Arduino Transmitter
      ↓
Digital Data Encoding
      ↓
LED → Light Pulses
      ↓
      ✨
      ↓
LDR Receiver
      ↓
Signal Detection & Decoding
      ↓
Arduino
      ↓
16×2 LCD
      ↓
Received Message
```

## 🔧 Hardware Components

* Arduino
* LED
* LDR Sensor
* 16×2 LCD Display
* Resistors
* Connecting Wires
* Breadboard

## 💻 Software & Technologies

* **Arduino IDE**
* **Embedded C/C++**
* Digital Signal Processing
* Visible Light Communication (VLC)
* Optical Wireless Communication

## 🚀 Key Features

* Wireless data transmission using visible light
* Digital signal encoding and decoding
* LDR-based optical signal detection
* Real-time message reception
* LCD-based output display
* Low-cost embedded implementation

## 🎯 Applications

Li-Fi technology can be explored for applications such as **indoor wireless communication, secure short-range communication, IoT systems, and environments where RF communication is restricted or undesirable**.

## 📚 Learning Outcomes

This project provides practical experience with **embedded-system programming, sensor interfacing, digital communication, optical signal transmission, and real-time data decoding**.
