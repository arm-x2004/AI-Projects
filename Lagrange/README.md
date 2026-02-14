# 🛰️ Lagrange Protocol Simulator: Deep Space Network

This is a specialized simulation implementing **Lagrange Interpolation** to solve data loss issues in deep-space communications.



## 🌌 The Problem & Solution
In space, solar radiation causes "Packet Loss." If you send a message as raw bits, a single missing bit can ruin the whole message. 

**This project uses a different approach:**
* It encodes your message into a **Mathematical Polynomial Curve**.
* It sends several points (packets) along that curve.
* As long as the receiver (Mars Rover) catches at least 3 points, it can use the **Lagrange Algorithm** to reconstruct the entire original curve and "read" the message back.

## 🚀 Features
* **Interactive Transmission:** Set the "Solar Interference" level to see packets explode in flight.
* **Math Visualization:** Real-time graphing of the encoded polynomial on the Earth station.
* **Lagrange Reconstruction:** Watch the Mars Rover trace the missing path using surviving data points.

## 🛠️ Built With
* **HTML5 Canvas:** For high-performance space animations.
* **Vanilla JavaScript:** Implementing the Lagrange math formula from scratch.
* **CSS3:** Custom "Galactic" dark theme.

---
*Note: This is a hobby project created to explore the intersection of physics, math, and web development.*
