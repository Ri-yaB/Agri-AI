# 🌾 AgriAI: Smart Crop Disease Predictor & Treatment Planner

AgriAI is a next-generation agricultural intelligence platform designed to empower farmers with AI-driven diagnostics, real-time weather-aligned treatment planning, and cost-optimized budgeting. Built specifically for the Indian agricultural landscape, it supports multiple regional languages and provides localized insights to improve crop yields and reduce input costs.

---

## 🚀 Key Features

### 1. 🌾 AI Disease Predictor
- **Vision-Powered Analysis**: Uses state-of-the-art AI (Gemini 2.0 Flash) via OpenRouter to analyze crop images for diseases.
- **Detailed Diagnostics**: Provides disease names, confidence scores, possible causes, and professional treatment plans.
- **Home Remedies**: Includes natural, low-cost cures (e.g., Neem oil, Turmeric spray) accessible to rural farmers.

### 2. 🌦️ Smart Treatment Planner
- **Real-Time Weather Sync**: Integrates with OpenWeatherMap API to monitor temperature, humidity, and wind speed.
- **Optimal Spray Windows**: Recommends the best time to apply treatments based on local weather conditions to maximize effectiveness.
- **Irrigation Alerts**: Provides smart alerts for water management during high-evaporation periods.

### 3. 💰 Cost-Optimized Engine
- **Precision Budgeting**: Calculates treatment costs in Rupees (₹) for various Indian crops (Rice, Wheat, Cotton, etc.).
- **Savings Analysis**: Visualizes potential savings achieved through AI-optimized application timing and precision spraying.
- **Custom Crop Support**: Allows farmers to input custom crop types for personalized analysis.

### 4. 📡 Advanced Intelligence
- **Satellite Health Map**: A multispectral visualization of farm health, identifying critical stress areas from a satellite perspective.
- **Community Outbreak Feed**: A live feed of nearby disease alerts to help farmers stay proactive against regional threats.

### 5. 🌍 Multilingual Support
- **Regional Languages**: Full support for **English**, **Hindi (हिन्दी)**, and **Punjabi (ਪੰਜਾਬੀ)**.
- **Voice Interface**: Hands-free voice assistant for easy navigation and command execution.

---

## 🛠️ Tech Stack

- **Frontend**: Next.js 15 (App Router), TypeScript, Vanilla CSS Modules.
- **AI Engine**: OpenRouter API (Gemini 2.0 Flash Vision).
- **Weather API**: OpenWeatherMap API.
- **Design**: Premium Glassmorphism, Dark Mode, and Fluid Animations.

---

## ⚙️ Getting Started

### Prerequisites
- Node.js 18.x or higher
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone (https://github.com/Ri-yaB/Agri-AI.git)
   cd agri-ai
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and add your API keys:
   ```env
   NEXT_PUBLIC_OPENWEATHER_API_KEY=your_openweather_key
   NEXT_PUBLIC_OPENROUTER_API_KEY=your_openrouter_key
   ```

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📸 Screenshots

*(Add screenshots of your stunning UI here!)*

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Empowering the backbone of our nation with intelligence. 🌾🇮🇳**
