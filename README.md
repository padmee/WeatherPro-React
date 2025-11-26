<div align="center">

  ⭐<img width="1872" height="891" alt="image" src="https://github.com/user-attachments/assets/32d5c806-f6d9-4f95-930a-f482041cfbaf" />⭐
 

  # 🌦️ WeatherPRO
  ### A Next-Gen Weather Dashboard Experience

  <p>
    <img src="https://img.shields.io/badge/React-18-blue?logo=react&style=for-the-badge" />
    <img src="https://img.shields.io/badge/Vite-Fast-purple?logo=vite&style=for-the-badge" />
    <img src="https://img.shields.io/badge/Tailwind-CSS-38B2AC?logo=tailwind-css&style=for-the-badge" />
    <img src="https://img.shields.io/badge/React_Query-TanStack-red?logo=react-query&style=for-the-badge" />
  </p>

  <p>
    WeatherPRO is a high-performance, fully responsive weather application featuring a modern <b>Glassmorphism UI</b> and <b>Neon Aesthetics</b>. Built to demonstrate advanced Frontend concepts including client-side caching, geolocation services, and complex state management.
  </p>
</div>

---

## 📸 Gallery

| **Desktop View (Sunny Theme)** | **Mobile View (Dark/Rainy)** |
|:---:|:---:|
| ⭐<img width="1872" height="891" alt="image" src="https://github.com/user-attachments/assets/87fd6bd9-f7a2-44b3-85fa-260dd7a73ae5" />⭐ | ⭐<img width="384" height="754" alt="image" src="https://github.com/user-attachments/assets/b41e2ec4-8459-4c63-b0b6-eace3576610a" />⭐ |

---

## ✨ Key Features

### 🎨 User Interface (UI/UX)
- **Glassmorphism Design:** Advanced usage of backdrop-blur, gradients, and semi-transparent layers.
- **Dynamic Themes:** The UI theme (colors, shadows, glows) automatically adapts based on weather conditions (Sunny, Cloudy, Rainy, Snowy).
- **Smooth Animations:** Custom CSS animations for floating elements, neon pulses, and seamless transitions.
- **Fully Responsive:** Optimized for all screen sizes (Mobile, Tablet, Desktop).

### ⚙️ Functionality & Logic
- **Smart Geolocation:** Automatically detects user coordinates and converts them to accurate city names (Reverse Geocoding).
- **Real-time Search:** Intelligent city search algorithm that sorts results by population to find the most relevant city.
- **Comprehensive Data:**
  - Current weather conditions (Temp, Humidity, Wind).
  - **24-Hour Hourly Forecast** (Horizontal scroll).
  - **7-Day Daily Forecast**.
- **Favorites System:** Save/Remove favorite cities using `LocalStorage` for persistent access.
- **Unit Toggle:** Instant switch between Celsius (°C) and Fahrenheit (°F).

### 🚀 Performance
- **Optimized Caching:** Implemented **TanStack Query (React Query)** to cache API responses, reducing server requests and loading times.
- **Error Handling:** Professional error management with user-friendly toast notifications (React-Toastify).

---

## 🛠️ Tech Stack

- **Core:** [React.js](https://react.dev/) (bootstrapped with [Vite](https://vitejs.dev/))
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **State Management & Data Fetching:** [TanStack Query](https://tanstack.com/query/latest)
- **API:** [Open-Meteo](https://open-meteo.com/) (Free, No API Key required)
- **HTTP Client:** [Axios](https://axios-http.com/)
- **Icons:** [React Icons](https://react-icons.github.io/react-icons/) (Feather & Weather Icons)
- **Notifications:** [React Toastify](https://fkhadra.github.io/react-toastify/)
- **Typography:** Vazirmatn (Persian) & Inter (English)

---

## 📂 Project Structure

A clean and modular folder structure was maintained for scalability:

```text
src/
├── api/                # API configuration & endpoints (Open-Meteo logic)
├── components/         # Reusable UI components (ForecastList, HourlyForecast, etc.)
├── utils/              # Helper functions (Icon mappers, Date formatters)
├── App.jsx             # Main application logic & layout
├── main.jsx            # Entry point & QueryProvider setup
└── index.css           # Global styles & Custom Tailwind animations
🚀 How to Run Locally
Clone the repository:
code
Bash
git clone https://github.com/YOUR-USERNAME/WeatherPro.git
Navigate to the project directory:
code
Bash
cd WeatherPro
Install dependencies:
code
Bash
npm install
Start the development server:
code
Bash
npm run dev
Open your browser at http://localhost:5173.
