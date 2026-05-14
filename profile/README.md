

<div align="center">

  <img 
    src="https://github.com/user-attachments/assets/8a3052b2-0616-4b7d-804b-a52f5666ff4d"
    alt="Preview 1"
    width="800"
    style="border-radius: 16px; margin-bottom: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);"
  />

  <br/>

  <img 
    src="https://github.com/user-attachments/assets/34301458-39a4-45c6-82ff-54e2f4d553b5"
    alt="Preview 2"
    width="800"
    style="border-radius: 16px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);"
  />

</div>




# 🌱♻️ PILAH YUK!!

### *Smart Waste Classification & Gamified Recycling Platform*

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-16-black?style=for-the-badge\&logo=next.js)
![React](https://img.shields.io/badge/React-19-61dafb?style=for-the-badge\&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=for-the-badge\&logo=typescript)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169e1?style=for-the-badge\&logo=postgresql)
![Prisma](https://img.shields.io/badge/Prisma-2d3748?style=for-the-badge\&logo=prisma)
![GSAP](https://img.shields.io/badge/GSAP-88ce02?style=for-the-badge\&logo=greensock)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38bdf8?style=for-the-badge\&logo=tailwindcss)

### 🚀 AI-Powered Recycling Platform with Gamification

*"Ubah kebiasaan memilah sampah menjadi pengalaman yang modern, interaktif, dan berdampak bagi lingkungan."*

</div>

---

# 📖 Tentang Project

**Pilah Yuk!!** adalah platform berbasis web yang membantu pengguna memilah sampah menggunakan teknologi Artificial Intelligence (AI) serta sistem gamifikasi modern untuk meningkatkan kesadaran lingkungan.

Pengguna cukup mengupload foto sampah, lalu AI akan mengidentifikasi jenis sampah secara otomatis dan memberikan poin berdasarkan kategori sampah tersebut.

Project ini dikembangkan sebagai bagian dari:

> 🎓 **Capstone Project DBS UNTIRTA 2026**

---

# ✨ Main Features

## 🤖 AI Waste Classification

Deteksi otomatis jenis sampah menggunakan AI.

### Kategori Sampah:

* Plastik
* Kertas
* Logam
* Kaca
* Organik

### Contoh:

```bash
Upload Foto → AI Detection → Plastik → +10 Poin
```

---

## 🏆 Gamification System

Sistem reward untuk meningkatkan motivasi pengguna.

### Features:

* ⭐ Point System
* 🏅 Badge & Achievement
* 🔥 Daily / Weekly Challenge
* 🥇 Leaderboard
* 📈 User Level Progress

---

## 📊 Dashboard Analytics

Dashboard interaktif untuk melihat:

* Total poin
* Progress level
* Statistik sampah
* Badge
* Riwayat aktivitas

---

## 🔐 Authentication

Sistem login modern menggunakan:

* Google Authentication
* Email & Password Authentication

---

## 🎨 Modern UI/UX

Menggunakan:

* Minimalist design
* Responsive layout
* GSAP animation
* Green environment theme

---

# 🧠 AI Architecture

## CNN (Convolutional Neural Network)

Digunakan untuk klasifikasi gambar sampah.

### Workflow:

```bash
User Upload Image
        ↓
Image Preprocessing
        ↓
CNN Model Prediction
        ↓
Waste Classification
        ↓
Point Calculation
```

---

# 🛠️ Tech Stack

# 🌐 Frontend

| Technology   | Function           |
| ------------ | ------------------ |
| Next.js 16   | Frontend Framework |
| React        | UI Library         |
| TypeScript   | Type Safety        |
| Tailwind CSS | Styling            |
| GSAP         | Animation          |

---

# ⚙️ Backend

| Technology            | Function       |
| --------------------- | -------------- |
| Next.js Route Handler | API Backend    |
| Prisma 7              | ORM            |
| PostgreSQL            | Database       |
| NextAuth/Auth.js      | Authentication |

---

# 🤖 AI / Machine Learning

| Technology | Function             |
| ---------- | -------------------- |
| TensorFlow | AI Training          |
| PyTorch    | Deep Learning        |
| CNN        | Image Classification |
| BPNN       | Neural Network       |

---

# 🗄️ Database Structure

## User

```prisma
model User {
  id        String
  name      String
  email     String
  points    Int
  level     Int
}
```

---

## Recycling Log

```prisma
model RecyclingLog {
  id          String
  userId      String
  wasteType   String
  points      Int
  imageUrl    String
}
```

---

# 📂 Project Structure

```bash
src/
│
├── app/
│   ├── dashboard/
│   ├── admin/
│   ├── login/
│   ├── register/
│   └── api/
│
├── components/
│   ├── landing/
│   ├── dashboard/
│   ├── login/
│   ├── sidebar/
│   └── ui/
│
├── prisma/
├── lib/
├── hooks/
├── data/
├── types/
└── utils/
```

---

# 🚀 Installation

# 1️⃣ Clone Repository

```bash
git clone https://github.com/DBSUNTIRTA2026/pilah-yuk.git
```

---

# 2️⃣ Masuk ke Folder Project

```bash
cd pilah-yuk
```

---

# 3️⃣ Install Dependencies

```bash
npm install
```

---

# 4️⃣ Setup Environment Variables

Buat file `.env`

```env
DATABASE_URL=""
NEXTAUTH_SECRET=""
NEXTAUTH_URL="http://localhost:3000"

GOOGLE_CLIENT_ID=""
GOOGLE_CLIENT_SECRET=""
```

---

# 5️⃣ Prisma Migration

```bash
npx prisma migrate dev
```

---

# 6️⃣ Run Development Server

```bash
npm run dev
```

---

# 🎥 Animation System

Website menggunakan **GSAP** untuk:

* Scroll Trigger Animation
* Floating Elements
* Interactive Card
* Smooth Transition
* Modern Landing Page Motion

---

# 📱 Responsive Design

Website fully responsive:

* 💻 Desktop
* 📱 Mobile
* 📲 Tablet

---

# 🎯 Main Objective

Meningkatkan kesadaran masyarakat terhadap pentingnya pemilahan sampah melalui teknologi AI dan sistem gamifikasi yang interaktif.

---

# 👨‍💻 Team Division

## Frontend Developer

* Landing Page
* Dashboard
* Responsive UI
* GSAP Animation

## Backend Developer

* API
* Authentication
* Database
* Point System

## AI Engineer

* Dataset
* CNN/BPNN Training
* AI Inference
* Image Classification

---

# 🌍 Environmental Impact

Dengan Pilah Yuk!! pengguna tidak hanya membuang sampah, tetapi juga:

* belajar memilah sampah
* memahami dampak lingkungan
* membangun kebiasaan positif
* berkontribusi terhadap sustainability

---

# 🔥 Future Features

* 📷 Real-time Camera Detection
* 📍 Smart Recycling Location
* 🏪 Reward Marketplace
* 🤝 Community Challenge
* 📊 AI Impact Analytics

---

# 📸 Preview

```bash
Landing Page
↓
Upload Sampah
↓
AI Classification
↓
Get Points
↓
Leaderboard & Badge
```

---

# 🏆 DBS UNTIRTA 2026

### Capstone Project

<div align="center">

## ♻️ PILAH YUK!!

### *Small Action, Big Impact.*

</div>
