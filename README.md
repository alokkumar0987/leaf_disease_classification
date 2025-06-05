# 🌾 किसान मित्र (KisanMitra) – Empowering Farmers with AI & Direct Crop Selling

## 🧑‍💼 Project Overview

**KisanMitra** is a farmer-first digital platform designed to eliminate middlemen, enable direct crop selling, use AI for crop disease detection, and promote eco-friendly agricultural practices. The goal is to create a self-reliant ecosystem for farmers where they can earn better, grow better, and live better.

---

## 🔍 Problem Statement

Despite India being an agrarian economy:

- ❌ Farmers earn only 30–40% of the market price due to **middlemen**.
- ❌ No structured **crop loss tracking** system exists.
- ❌ Limited awareness of **organic & eco-friendly solutions**.
- ❌ Uncontrolled use of **chemical fertilizers and pesticides**.
- ❌ No direct way to **connect buyers and farmers** locally.

---

## ✅ Project Goals

1. **📦 Sell Crops Directly**: Connect farmers to buyers (within 10 km) without any middleman.
2. **📉 Crop Loss Graph & Insights**: Show farmers how crop loss happens year by year with data and visual charts.
3. **🤖 AI-Based Disease Detection**: Let farmers upload leaf images and get instant diagnosis.
4. **🌱 Eco-Friendly Farming Practices**: Promote natural solutions (Neem oil, compost, bio-pesticides).
5. **📢 Precautionary Alerts**: AI-driven early warnings based on climate, soil, and image analysis.

---

## 📊 Sample Crop Loss Chart (Past 5 Years)

| Year | Wheat Loss (tonnes) | Rice Loss (tonnes) | Maize Loss (tonnes) | Major Cause              |
|------|---------------------|--------------------|----------------------|--------------------------|
| 2020 | 1200                | 1800               | 800                  | Drought + Price Crash    |
| 2021 | 1000                | 1500               | 1000                 | Leaf Disease             |
| 2022 | 1300                | 1600               | 900                  | Pest Attack + Delay      |
| 2023 | 900                 | 1400               | 700                  | Natural Disaster         |
| 2024 | 1100                | 1700               | 850                  | Mandi Strike + Infection |

> ⚠️ *Note:* Crop loss data currently entered manually. IMD rainfall data sync pending – working on automated ingestion. Some years have overlapping region info due to inconsistent district codes.

---

## 🤖 AI Disease Detection – How It Works

- **Step 1**: Farmer uploads a crop leaf image.
- **Step 2**: AI model predicts disease name (e.g., "Leaf Blight", "Powdery Mildew").
- **Step 3**: User receives:
  - Disease severity (Mild / Moderate / Severe)
  - Chemical Treatment option
  - Organic Solution alternative
- **Fallback**: Gemini API used for symptom-based input if image is unclear.

> ❗*Error Note:* Onion and sugarcane currently unsupported due to missing class labels. Dataset extension in progress.

---

## 🌍 Eco-Friendly Farming Solutions

| Problem              | Organic Solution                     | Description                              |
|----------------------|--------------------------------------|------------------------------------------|
| Pest Attacks         | नीम तेल छिड़काव (Neem Oil Spray)      | Natural pest repellent                   |
| Fungal Leaf Infections | छाछ + बेकिंग सोडा छिड़काव              | Organic anti-fungal solution             |
| Soil Infertility     | वर्मी कम्पोस्ट (Vermi Compost)        | Boosts natural fertility                 |
| Water Wastage        | ड्रिप सिंचाई (Drip Irrigation)        | Saves 40–60% water                       |

> 📌 Precautionary articles and videos in Hindi & English available in the mobile app.

---

## 📦 Crop Selling Without Middlemen

- Farmers list crops (e.g., गेहूं, धान, सरसों) with quantity & expected price.
- Local buyers see listings within 10 km using geolocation.
- Buyers can call or request pickup directly from the farm.
- Payment proof and digital transaction receipts stored.

> 🚧 *Coming Soon:* Crop insurance integration and buyer rating system.

---

## 📲 Tech Stack

- **Frontend**: Streamlit (Demo), Kotlin (Android App)
- **Backend**: FastAPI
- **AI Model**: EfficientNet (for classification), Gemini API fallback
- **Database**: MySQL (disease data, buyer-farmer listing)
- **Cloud**: Oracle Free VM (scalable up to 1000 users)

---

## 🔐 Data Privacy & Farmer Safety

- OTP-based login only
- No sharing of mobile numbers without consent
- No data sold to third-party vendors

---

## 📈 KPIs (Key Performance Indicators)

| Metric                        | Target |
|------------------------------|--------|
| Farmers Onboarded            | 10,000 |
| Crops Sold Directly          | 5,000  |
| Leaf Disease Reports Scanned | 50,000 |
| Pesticide Alternatives Used  | 75,000 |

---

## 🚧 Known Issues / Errors (Transparency)

- [ ] Crop loss chart mismatch for Rewa district in 2022
- [ ] Some disease outputs show “NoneType” due to image background noise
- [ ] Chatbot breaks after 3 questions — needs memory token fix
- [ ] No support for offline mode yet — planned for v1.3
- [ ] Hindi voiceover delay in organic video tutorials

---

## 🤝 Team Vision

> "हमारा किसान, हमारा भविष्य" – We aim to give power, pricing, and protection back to the hands that grow our food.

This is not just a tech solution — it's a mission to create a **self-sustaining, data-driven, environment-friendly ecosystem** for Indian farmers.

---

## 📬 Contact & Support

- 📞 Helpline: 1800-8899-456  
- 📧 Email: support@kisanmitrapp.in  
- 🌐 Website: [www.kisanmitrapp.in](https://www.kisanmitrapp.in)  
- 🧑‍🌾 Support Languages: Hindi, English (local dialects soon)

---
