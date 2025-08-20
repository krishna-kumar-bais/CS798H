<!-- https://uber-customer.onrender.com-->
<!-- https://driver-ui.onrender.com -->

# 🚖 Uber Priority Ride System

This project implements a ride-hailing system with **priority ride support**, designed to simulate both **Customer** and **Driver** perspectives. It integrates real-time route visualization using **Leaflet maps**, ride request/accept flows, OTP-based verification, and fare adjustments for priority rides.

---

## 🌐 Deployed Links
- **Customer UI:** [Open Demo](https://krishna-kumar-bais.github.io/Customer-UI/)  
- **Driver UI:** [Open Demo](https://krishna-kumar-bais.github.io/Driver-UI/)

---

## 🔎 Project Overview
The system introduces a **Priority Ride** option intended for urgent travel needs such as medical or emergency trips.  

Key highlights:
- **Customer side:** Book rides, toggle priority mode (+25% fare), view ETAs, and start rides with OTP validation.  
- **Driver side:** Accept incoming ride requests, view flagged priority rides, navigate using the integrated map, and complete rides.  
- **Maps integration:** Interactive routing and location visualization powered by **Leaflet.js**.  

This setup provides an end-to-end demonstration of how priority-based ride systems can operate, including differentiated pricing and priority handling for drivers.

---

## ⚙️ Features
### 🧍 Customer UI
- Select pickup and drop-off locations.
- Option to request a **Priority Ride** (with fare adjustment).
- Ride suggestions sorted by fastest ETA.
- OTP-based verification for ride initiation.
- Route preview displayed on map.

### 🚗 Driver UI
- Receive and accept ride requests.
- Priority rides visually highlighted to drivers.
- View passenger details, fare (with priority markup), and OTP.
- Integrated **Leaflet map** for navigation and route details.

### 🌍 Shared Components
- Dynamic **map rendering** and route tracing.
- Clear UI separation for customers and drivers.
- Consistent design and ride flow across both portals.

---

## 🧩 Tech Stack
- **Frontend:** HTML, CSS, JavaScript  
- **Mapping & Routing:** Leaflet.js  
- **Deployment:** GitHub Pages (for demo links)  
- **Data:** JSON / client-side state for simulating ride flows  

---

## ▶️ Running Locally
> Recommended: run over a local server for maps and AJAX to function properly.

1. Clone the repository:
   ```bash
   git clone https://github.com/krishna-kumar-bais/CS798H.git
   cd CS798H/Project-Uber\ Priority\ Ride\ System
