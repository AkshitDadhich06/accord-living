# 🏢 Accord Living

> A modern, real-time Society Management Platform for Admins, Residents & Security

![Live Demo](https://img.shields.io/badge/LIVE%20DEMO-accord--living.vercel.app-brightgreen)
![React](https://img.shields.io/badge/React-18-blue)
![Firebase](https://img.shields.io/badge/Firebase-Firestore-orange)
![Vercel](https://img.shields.io/badge/Deployed-Vercel-black)
![Hackathon](https://img.shields.io/badge/RECKON%207.0-Top%2010%20Finalist-gold)

---

## 📖 Overview

Accord Living is a full-featured, multi-tenant society management web application that connects **Admins, Residents, and Security personnel** on a single real-time platform.

Built with React + Firebase, it handles everything from onboarding & billing to visitor management and emergency alerts — all with live Firestore subscriptions so every update reflects instantly across all portals.

🔗 **Live Demo:** [https://accord-living.vercel.app](https://accord-living.vercel.app)

---

## 🚀 Features

### 🛡️ Admin Portal
- **Real-time KPI Dashboard** — live stats for flats, residents, billing, complaints, attendance & emergencies
- **Onboarding Wizard** — bulk flat creation, resident credential generation, flat assignment & staff onboarding
- **Resident Management** — create/edit residents with flat mapping and credential-aware flows
- **Bill Management** — generate bills for all or individual flats, track collection progress, view payment records
- **Complaint Management** — search/filter, status updates, metrics (pending / in-progress / resolved)
- **Notices & Events** — create and manage announcements with real-time list updates
- **Attendance Logs** — real-time staff attendance with GPS and photo proof
- **Visitor Records** — search/filter, CSV/Excel export, blacklist management
- **Emergency Contact Management** — manage contacts added by resident SOS
- **Admin Settings** — society profile, payment preferences, admin users, notification preferences & full CSV exports

### 🏠 Resident Portal
- Dashboard — dues, payments, complaints, announcements, activity feed & weather integration
- **My Bills** — view bills, record payments, generate invoices & see payment history
- **Complaints** — submit complaints and track live status updates
- **Documents** — view and download society documents directly
- **Emergency SOS** — one-tap call to admin-managed emergency contacts
- **Visitor Pre-Approval** — create and manage pre-approvals, view QR codes, download approval PDFs

### 🔒 Security Portal
- Dashboard — summaries for visitors, deliveries, attendance & active alerts
- **Pre-Approved Visitors** — scan QR code/mobile, allow/deny with time-window validation
- **Staff Attendance** — GPS capture, reverse geocode, camera photo proof
- **Emergency Alerts** — live active and history feed with acknowledge/resolve actions

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React 18, React Router |
| Build Tool | Vite |
| Backend / Auth | Firebase Authentication |
| Database | Cloud Firestore (real-time) |
| Hosting | Vercel |
| UI | Custom component library with dark mode support |

---

## 🏆 Hackathon

Built for **RECKON 7.0 — National Hackathon** | 🥈 **Top 10 Finalist among 100+ national teams**

Delivered as a fully working prototype under 24 hours.

---

## ⚙️ Getting Started

### Prerequisites
- Node.js 18+
- A Firebase project with Firestore and Authentication enabled

### Installation

\```bash
git clone https://github.com/AkshitDadhich06/accord-living.git
cd accord-living
npm install
npm run dev
\```

### Environment Setup

\```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
VITE_FIREBASE_APP_ID=your_app_id
\```

---

## 📄 License

This project is open source and available under the MIT License.
