# 📘 **Error Detection Visualizer**

### *Interactive Teaching Tool for : Parity · Checksum · CRC*
An interactive visual tool demonstrating Parity, Checksum, and CRC error-detection techniques. Includes bit-level transmission view, error simulation, and sender/receiver decoding for teaching data communication concepts. Source code is private; repo contains documentation and demo link.

---

## 🚀 **Live Demo**

🔗 **[https://errordetection-visualizer.netlify.app/](https://errordetection-visualizer.netlify.app/)**

> *(Only minified/obfuscated build deployed — source code is private.)*

---

## 🧾 **Overview**

**Error Detection Visualizer** is a fully interactive, browser-based tool designed for teaching **Error Detection Techniques** in computer networks and digital communication.

It visually demonstrates:

* **Parity Bit (Even Parity)**
* **16-bit Internet Checksum**
* **CRC (Configurable polynomial)**
* **Message corruption**
* **Bit errors slipping undetected**
* **Receiver-side error checking**

This repository contains **documentation and screenshots only**.
The **full readable source code is private** for academic and security reasons.

---

## ✨ **Features**

### 🔹 Sender-Side Visuals

* ASCII → Binary conversion
* Parity calculation
* Checksum computation
* CRC remainder generation
* Full frame construction (payload + redundancy)

### 🔹 Error Simulation Tools

* Random bit flip
* Manual bit toggle
* Character-level corruption
* Same-weight pair flips (checksum bypass)
* Undetected 2-bit checksum errors
* CRC detection demo

### 🔹 Receiver-Side Analysis

* Parity checking per character
* Checksum recomputation and comparison
* CRC long division + zero remainder checking
* Highlighted error detection
* Reconstructed message view
* Detects corrupted characters (  shown for broken bytes)

### 🔹 Teaching / Instructor Mode

* Advanced diagnostics
* Edit received message
* Step-by-step explanations
* Useful for classroom demonstrations

---

## 📂 **Repository Structure**

```
error-detection-visualizer/
│
├── docs/
│   ├── screenshots/
│   │     screenshot 1.png
│   │     screenshot 2.png
│   │     screenshot 3.png
│   │     screenshot 4.png
│   ├── documentation.pdf
│   ├── architecture-overview.png
│   └── feature-list.txt
│
└── README.md
```

**Note:** The actual tool’s code (HTML + JS logic) is not included.

---

## 🎓 **Educational Purpose**

This tool was built to demonstrate:

* Why parity detects only odd-bit errors
* Why checksum sometimes fails
* How two-bit errors can keep checksum unchanged
* Why CRC is the strongest in real-world network protocols
* How single-bit corruption transforms ASCII characters

Designed for teaching sessions at **NIAT** on the topic:

> **Applications in Computing — Error Detection Techniques**

---

## 🛠 **Technology Stack**

* HTML5
* CSS3
* JavaScript (with obfuscation)
* Netlify (deployment)
* Offline-ready architecture

---

## 🔒 **Code Privacy Policy**

To prevent misuse or copying by students:

* The full source code is **not** uploaded
* Only an obfuscated/minified version is deployed
* GitHub contains documentation, not code
* Architecture diagrams and screenshots serve as proof of development

---

## 👨‍💻 **Author**

**Rishabh Shukla**

Error Detection Teaching Project — NIAT


## 📝 **License**

This project’s build and documentation are copyrighted.
Source code remains private.

