# 🌆 Bengaluru Urban Pulse

**A real-time smart dashboard for Bengaluru's urban resilience.**  
Tracking floods, monitoring lakes, and predicting the future of urban chaos — one API call at a time.

---

![Bengaluru Urban Pulse](https://img.shields.io/badge/Status-Active-brightgreen)  
![License](https://img.shields.io/github/license/chandrahas-k/bengaluru-urban-pulse)

## 🚀 What is Urban Pulse?

**Bengaluru Urban Pulse** is a full-stack web platform built to:

- Predict flooding based on real-time weather data 🌧️
- Monitor lake health, track encroachments via satellite data 🛰️
- Visualize urban heat islands and planning patterns 🏙️
- Connect citizens with actionable alerts 🚨
- Provide live dashboards for researchers and civic bodies

Built as part of our final-year major project under KSCST 48th Series Sponsorship 💡

---

## 🧠 Tech Stack

| Layer       | Tech Used                                    |
|------------|-----------------------------------------------|
| Frontend    | React.js, Tailwind CSS, Mapbox GL, Recharts  |
| Backend     | FastAPI (Python), RESTful APIs               |
| Database    | Supabase (PostgreSQL), Edge Functions        |
| APIs        | OpenWeatherMap, NASA Earthdata, Mapbox       |
| Deployment  | Vercel (Frontend), Lightsail/Backend (prev.) |
| Tools       | Git, GitHub, Nginx, JSON, Pandas, GeoJSON    |

---

## 🛰️ Features

- 📡 **Real-time flood prediction** using rainfall + terrain data  
- 🌊 **Lake monitoring dashboard** — health, encroachment alerts  
- 🗺️ **Satellite imagery comparisons** from NASA for historical change detection  
- 🧠 **AI-powered land use forecasts** (planned)  
- 🔒 **Authentication + data storage** via Supabase  
- 📊 **Visual analytics** via React + Mapbox + Recharts

---

## 🛠️ How It Works

1. User hits the dashboard on `urbanpulse.vercel.app` (example)
2. React frontend fetches:
   - Weather data (OpenWeatherMap)
   - Satellite layers (NASA)
   - Real-time lake stats (mock/actual API)
3. Backend (FastAPI) runs prediction models (flood risk, encroachment likelihood)
4. Mapbox renders interactive overlays (heatmaps, lake outlines, rainfall)
5. Output is shown as **insightful charts, alerts, and geovisuals**

---

## ⚡ Getting Started (Dev Mode)

```bash
# Clone this repo
# Frontend
cd frontend
npm install
npm run dev

# Backend (FastAPI)
cd backend
pip install -r requirements.txt
uvicorn main:app --reload

🎓 Project Info
📍 Developed by final-year B.E. students, MVJ College of Engineering

🎖️ Sponsored under KSCST 48th Series (2024–25)

🌐 Designed for Bengaluru’s civic planning, research & public safety

💌 Contact
📧 kchandrahas863@gmail.com

![WhatsApp Image 2025-05-27 at 12 32 11_2e8c9e50](https://github.com/user-attachments/assets/5826c608-1d56-4326-99e2-73c398b63bbb)
![WhatsApp Image 2025-05-27 at 12 32 42_f41f6e5e](https://github.com/user-attachments/assets/89757672-226d-42e1-80c3-3cd6fba3b614)
![WhatsApp Image 2025-05-27 at 12 34 10_8b8987ef](https://github.com/user-attachments/assets/6fd26d10-1747-4185-a32c-004090ee507b)
![WhatsApp Image 2025-05-27 at 12 35 01_10cb6668](https://github.com/user-attachments/assets/df0441ab-30ad-4af6-b139-1385da072d71)
![WhatsApp Image 2025-05-27 at 12 35 54_3eada79e](https://github.com/user-attachments/assets/6ca3f5e5-ba5f-4d88-9b54-19f79afe48ee)
![WhatsApp Image 2025-05-27 at 12 36 21_3b28bf6b](https://github.com/user-attachments/assets/3601195b-0f23-4f70-9ae4-1b488d791828)
![WhatsApp Image 2025-05-27 at 12 37 37_3ccdc15a](https://github.com/user-attachments/assets/f599aa07-8ced-4a96-88d5-bbde38c2f65a)
![WhatsApp Image 2025-05-27 at 12 39 33_0128d4ea](https://github.com/user-attachments/assets/052250d4-8c3d-4037-8dae-b42155fd9680)
![WhatsApp Image 2025-05-27 at 12 41 52_8294c7af](https://github.com/user-attachments/assets/5598c568-a824-4da2-a7f4-40e549530d9f)
![WhatsApp Image 2025-05-27 at 12 43 30_b4671009](https://github.com/user-attachments/assets/52c6f787-34aa-46b3-9b96-910256f23ddb)
![WhatsApp Image 2025-05-27 at 12 46 41_ebd19c64](https://github.com/user-attachments/assets/2f2f66b0-ee92-4768-9f0b-72b73195ce86)
![WhatsApp Image 2025-05-27 at 12 47 25_ab5f7897](https://github.com/user-attachments/assets/add815e5-5d24-4d46-b513-aea2d57daca1)
![WhatsApp Image 2025-05-27 at 12 47 39_abd6b2d3](https://github.com/user-attachments/assets/8f73424c-0bbb-47d6-b23d-bf80809219b8)
![WhatsApp Image 2025-05-27 at 12 48 49_d1b08255](https://github.com/user-attachments/assets/b7b8cf5b-aa68-4d5d-b3a5-a5c33f7b57ff)

#🌟 Star This Repo
If this helped you, inspired you, or saved you from a flood —
⭐ Give us a star and help others discover it too!

#🤝 Contributing
We welcome contributions! Just fork, code, and PR.
Make sure to open an issue first for significant changes.

