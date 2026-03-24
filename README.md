# 🌾 KhetMitra — Ultimate Smart Farm Portal

**KhetMitra** is a high-tech, precision agriculture dashboard designed to empower modern farmers. It combines real-time weather telemetry, IoT-style soil monitoring, market analytics, and government scheme discovery into a single, elegant "Dark-Mode" interface.

---

## 🌟 Project Overview
KhetMitra bridges the gap between traditional farming and data-driven agriculture. By providing a "command center" view of the farm, it helps farmers make scientific decisions about irrigation, pest control, and crop sales.

### 🚀 [Live Demo Link - Insert Your Link Here]

---

## 💎 Key Benefits

*   **Precision Farming:** No more guessing. Monitor Nitrogen, pH, and Moisture levels to apply fertilizers and water only when needed.
*   **Financial Security:** Integrated **AI Scheme Finder** helps farmers discover government subsidies and loans (like KCC) they are eligible for based on their land size and income.
*   **Market Intelligence:** Real-time APMC (Mandi) price tracking ensures farmers sell their produce at the highest possible profit, avoiding middleman exploitation.
*   **Risk Reduction:** Early warning system for pests and extreme weather prevents total crop failure.

---

## 📡 Highlighted Feature: Live Tracking & Telemetry

The "Heart" of KhetMitra is its **Live Tracking System**, which provides real-time situational awareness:

1.  **Dynamic Weather Sync:** Using the **Open-Meteo API**, the app tracks live temperature, wind, and sky conditions based on the farmer's specific GPS coordinates.
2.  **Interactive Bank & KCC Locator:** Built with **Leaflet.js**, the portal tracks the farmer's location and maps out the nearest banking hubs and Kisan Credit Card centers with turn-by-turn direction capabilities.
3.  **Real-Time Market Pulse:** Tracks price fluctuations (Up/Down percentages) for major crops like Wheat, Onion, and Tomato, updated via live data feeds.
4.  **Satellite Health Simulation:** Provides a "Field-by-Field" health status, flagging specific areas (e.g., "Field B") for pest risks or irrigation needs.

---

## 🛠 How It Works (The Logic)

1.  **User Onboarding:** The farmer creates a profile detailing their State, Land Size (Acres), and Primary Crop.
2.  **Data Aggregation:** 
    *   **Weather:** Fetched via REST API for local accuracy.
    *   **Soil:** Simulates IoT sensor data to show NPK (Nitrogen, Phosphorus, Potassium) health.
    *   **Maps:** Renders interactive layers using OpenStreetMap.
3.  **Decision Support:** The "Action Plan" section translates complex data into simple daily tasks (e.g., *"Spray Field B today"*).
4.  **Local Persistence:** Uses `localStorage` to save user data, ensuring the farm profile remains active even after closing the browser.

---

## 💻 Tech Stack

*   **HTML5:** Semantic structure for high performance.
*   **CSS3:** Custom variables, Glassmorphism UI, and Responsive Grid layout.
*   **JavaScript (ES6+):** Async/Await for API calls and DOM manipulation.
*   **Leaflet.js:** For high-performance interactive mapping.
*   **Open-Meteo API:** For real-time meteorological data.
*   **Google Fonts:** Playfair Display (Headers) and Space Mono (Data).

---

## ⚙️ Installation & Usage

Since KhetMitra is a "Pure-Web" application, it requires **zero installation**.

1.  **Clone the Repo:**
    ```bash
    git clone https://github.com/your-username/KhetMitra.git
    ```
2.  **Run it:**
    Open `index.html` in any modern browser (Chrome, Safari, Edge).

3.  **Demo Access:**
    *   **Mobile:** `9999999999`
    *   **Password:** `1234`

---

## 🗺️ Future Roadmap
- [ ] Integration with real LoRaWAN Soil Sensors.
- [ ] Multi-language support (Hindi, Marathi, Punjabi, etc.).
- [ ] AI Image Upload for Pest Identification (using TensorFlow.js).
- [ ] Direct-to-Consumer (D2C) marketplace for farm produce.

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

---
**Developed with ❤️ for the Global Agricultural Community.**
