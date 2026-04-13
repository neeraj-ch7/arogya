<div align="center">

# 🏥 Arogya

### *Making healthcare smarter, faster, and accessible for everyone*

![Arogya Banner](https://img.shields.io/badge/Arogya-Healthcare%20Platform-brightgreen?style=for-the-badge&logo=heart&logoColor=white)

[![Live Demo](https://img.shields.io/badge/🚀%20Live%20Demo-Visit%20Now-blue?style=for-the-badge)](https://arogya-azure.vercel.app/)
[![MIT License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev/)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

</div>

---

## 📌 Overview

### The Problem

Healthcare today is broken for millions of people — especially those in rural and underserved communities:

- 🔴 **Fragmented Systems** — Medical records scattered across clinics, hospitals, and paper files with no unified access
- 🔴 **Limited Access** — Shortage of doctors and specialists in rural areas forces patients to travel long distances for basic care
- 🔴 **Delayed Diagnosis** — Lack of early screening tools leads to late-stage detection of preventable conditions
- 🔴 **No Continuity of Care** — Patients repeat tests and share histories repeatedly with every new provider
- 🔴 **Mental Health Neglect** — Emotional and psychological wellness is rarely integrated into primary care

### The Solution

**Arogya** is a unified, AI-powered healthcare platform that brings together telemedicine, digital health records, AI diagnostics, and wellness tools into a single accessible system — designed to work for everyone, from urban professionals to rural communities.

> *One platform. Every health need. Anywhere.*

---

## 🚀 Live Demo

🌐 **[https://arogya-azure.vercel.app/](https://arogya-azure.vercel.app/)**

---

## ✨ Key Features

| Feature | Description |
|---|---|
| 🤖 **AI Symptom Checker** | Describe symptoms and get AI-driven early detection insights powered by Google Gemini |
| 👨‍⚕️ **Doctor Consultation** | Connect with verified doctors via telemedicine — no travel required |
| 📁 **Digital Health Records** | Securely store, manage, and share your complete medical history in one place |
| 🪪 **QR Health Passport** | Carry your health identity as a scannable QR code — instant access in emergencies |
| 💊 **Medication Tracker** | Set reminders, track prescriptions, and never miss a dose again |
| 🧠 **Mood & Wellness Tracker** | Daily mental health check-ins and emotional wellness monitoring |
| 🚨 **Emergency Support** | Built-in blood donor network and emergency contact system for critical situations |
| 📊 **Health Dashboard** | A personalized overview of your vitals, appointments, records, and wellness trends |

---

## 🏗️ System Architecture

```
┌──────────────────────────────────────────────────────────────┐
│                        USER                                  │
│              (Patient / Doctor / Admin)                      │
└─────────────────────────┬────────────────────────────────────┘
                          │
                          ▼
┌──────────────────────────────────────────────────────────────┐
│                    FRONTEND                                  │
│              React + Vite + Tailwind CSS                     │
│   [ Symptom Checker | Dashboard | Records | Teleconsult ]    │
└─────────────────────────┬────────────────────────────────────┘
                          │
                          ▼
┌──────────────────────────────────────────────────────────────┐
│                    BACKEND                                   │
│                  Supabase (BaaS)                             │
│       [ Auth | PostgreSQL DB | Storage | Realtime ]         │
└──────────┬──────────────────────────────┬────────────────────┘
           │                              │
           ▼                              ▼
┌─────────────────────┐     ┌────────────────────────────────┐
│    AI ENGINE        │     │        RESPONSE LAYER          │
│  Google Gemini API  │────▶│  Insights | Suggestions |      │
│  (Symptom Analysis) │     │  Diagnosis Reports | Chat      │
└─────────────────────┘     └────────────────────────────────┘
```

---

## 🛠️ Tech Stack

### Frontend
- ⚛️ **React** — Component-based UI framework
- ⚡ **Vite** — Lightning-fast development build tool
- 🎨 **Tailwind CSS** — Utility-first responsive styling

### Backend & Infrastructure
- 🔧 **Supabase** — Open-source Firebase alternative (PostgreSQL + Storage + Realtime)
- 🔐 **Supabase Auth** — Secure user authentication with email, OAuth, and magic links

### AI & Intelligence
- 🤖 **Google Gemini API** — Advanced AI for symptom analysis and health recommendations

### Deployment
- ▲ **Vercel** — Fast, scalable frontend deployment with CI/CD

---

## 🌍 Impact

Arogya is designed with real-world impact in mind:

- ♿ **Accessibility** — Bridges the healthcare gap for rural and underserved populations with internet-first services
- 🔬 **Early Diagnosis** — AI symptom analysis enables proactive care before conditions become critical
- 💰 **Cost Reduction** — Reduces unnecessary clinic visits and repeat diagnostics through unified digital records
- 🌾 **Rural Healthcare** — Brings specialist-level guidance to areas with no physical medical infrastructure
- 🧠 **Mental Wellness** — Normalizes and integrates mental health tracking into everyday healthcare routines

---

## 🔮 Future Scope

We are building Arogya for the future of healthcare:

- 🧬 **Advanced AI** — Upload lab reports and medical scans for AI-powered analysis and second opinions
- 📹 **Full Telemedicine** — Live video consultations with verified doctors and specialists
- 📱 **Mobile Application** — Native iOS and Android apps for on-the-go health management
- ⌚ **Wearable Integration** — Sync data from smartwatches and fitness trackers (Apple Health, Google Fit)
- 🌐 **Regional Language Support** — Multilingual interface to serve India's diverse linguistic communities
- 🏛️ **Government Integration** — Alignment with ABDM (Ayushman Bharat Digital Mission) and NDHM standards

---

## ⚙️ Installation & Setup

Follow these steps to run Arogya locally:

### Prerequisites
- Node.js (v18+)
- npm or yarn
- A Supabase account
- Google Gemini API key

### Steps

**1. Clone the Repository**
```bash
git clone https://github.com/neeraj-ch7/arogya.git
cd arogya
```

**2. Install Dependencies**
```bash
npm install
```

**3. Configure Environment Variables**

Create a `.env` file in the root directory:
```env
VITE_SUPABASE_URL=your_supabase_project_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
VITE_GEMINI_API_KEY=your_google_gemini_api_key
```

**4. Start the Development Server**
```bash
npm run dev
```

**5. Open in Browser**
```
http://localhost:5173
```

---


## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a new branch: `git checkout -b feature/your-feature-name`
3. **Commit** your changes: `git commit -m 'Add: your feature description'`
4. **Push** to the branch: `git push origin feature/your-feature-name`
5. **Open** a Pull Request

Please read our [Contributing Guidelines](CONTRIBUTING.md) and follow the [Code of Conduct](CODE_OF_CONDUCT.md).

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

```
MIT License — free to use, modify, and distribute with attribution.
```

---

## 🙏 Acknowledgements

Arogya stands on the shoulders of global healthcare innovation:

- 🌍 **World Health Organization (WHO)** — Global health standards and telemedicine guidelines
- 🇮🇳 **NDHM / ABDM (India)** — National Digital Health Mission framework and health data standards
- 📚 **Telemedicine Research Community** — Open-source research advancing remote patient care
- 🤖 **Google DeepMind & Gemini Team** — AI tools pushing the boundaries of medical intelligence
- 💙 **Open Source Contributors** — React, Supabase, Tailwind CSS, and the broader developer community

---

<div align="center">

---

### 💚 *"Arogya is not just a platform — it's a step towards making healthcare accessible, affordable, and intelligent for everyone."*

---

**Built with ❤️ for a healthier world**

[![Live Demo](https://img.shields.io/badge/🌐%20Try%20Arogya-Live%20Demo-brightgreen?style=for-the-badge)](https://arogya-azure.vercel.app/)

</div>
