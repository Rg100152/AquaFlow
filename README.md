# AquaFlow
# 💧 AquaFlow – Smart Water Bill Management & Payment Portal

A premium, enterprise-grade frontend prototype for a digital water utility platform. Built with **HTML5, CSS3, and Vanilla JavaScript**, AquaFlow delivers an ocean‑inspired dark UI, animated water waves, interactive consumption charts, automated bill calculations, and a complete payment‑to‑receipt workflow—all in one responsive, glassmorphism‑driven interface.

![GitHub repo size](https://img.shields.io/github/repo-size/yourusername/aquaflow)
![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/aquaflow)
![License](https://img.shields.io/badge/license-MIT-green)

> **Live Demo:** [https://yourusername.github.io/aquaflow](https://yourusername.github.io/aquaflow) *(replace with your deployed link)*

---

## 📌 Overview

**AquaFlow** reimagines water bill management as a seamless, intelligent digital experience. Consumers can monitor smart meter readings, view real‑time consumption, pay bills, track complaint status, and manage multiple water connections—all from a single, beautifully designed portal.

The platform is a pure frontend prototype, ideal for academic projects, UI/UX showcases, or as a foundation for a full‑stack utility billing system.

---

## 🎯 Project Vision

> **“Every Drop Matters, Every Bill Simplified.”**

AquaFlow empowers citizens to understand and control their water usage through a smart, transparent, and visually engaging digital interface.

---

## 🎨 Design Philosophy

- **Ocean‑Inspired Dark UI** – Deep navy background (`#040B16`) with vibrant blue and cyan accents, evoking water and trust.
- **Premium Glassmorphism** – Semi‑transparent cards with soft blur and subtle borders for a modern, layered look.
- **Animated Water Waves & Bubbles** – A live canvas background simulates gentle ocean waves, reinforcing the aquatic theme.
- **Liquid & Neon Glow Effects** – Buttons, active elements, and chart lines glow with `#00D4FF` and `#00FFA3`.
- **Smooth 60 FPS Animations** – All transitions and charts use `requestAnimationFrame` and CSS hardware acceleration.

---

## 🎨 Color Palette

| Role          | Hex Code  | Usage                                  |
|---------------|-----------|----------------------------------------|
| Primary       | `#0096FF` | Buttons, active states, progress bars  |
| Secondary     | `#00D4FF` | Highlights, graph lines, hover effects |
| Accent        | `#00FFA3` | Success states, call‑to‑action buttons |
| Background    | `#040B16` | Main background                        |
| Cards         | `#111827` | Glass‑morphism base panels             |
| Success       | `#22C55E` | Positive balances, paid status         |
| Warning       | `#F59E0B` | Alerts, leak detection                 |
| Danger        | `#EF4444` | Overdue bills, error messages          |
| Text          | `#FFFFFF` | Primary text                           |

**Typography:** `Montserrat` (headings), `Poppins` (body), `Inter` (UI elements)

---

## 🛠️ Technology Stack

| Category          | Technology                                |
|-------------------|-------------------------------------------|
| **Frontend**      | HTML5, CSS3, Vanilla JavaScript           |
| **Charts**        | Canvas API (custom line charts)           |
| **Animations**    | CSS Keyframes, `requestAnimationFrame`, Intersection Observer |
| **Water Effect**  | Procedural wave animation on `<canvas>`   |
| **No frameworks** | Pure vanilla – no Bootstrap, Tailwind, or React |

---

## ✨ Key Features

- **12+ Interconnected Pages** – Home, Login, Register, Dashboard, Current Bill, Smart Meter, Bill History, Payment, Digital Receipt, Complaints, Profile, and About.
- **Smart Meter Simulation** – Live meter reading display with consumption graphs and a leak detection alert (demo).
- **Automatic Bill Calculation** – Tiered water charges, sewer, maintenance, late fee, and discounts are displayed dynamically.
- **Interactive Analytics** – Canvas‑based charts show daily, weekly, or monthly consumption trends.
- **Payment Flow** – Demo UPI / Card / Net Banking buttons that trigger a success screen and a digital receipt.
- **Digital Receipt** – Printable receipt with transaction ID, QR placeholder, and payment details.
- **Complaint Management** – File complaints (no water, leakage, etc.) and view a timeline of their status.
- **Multi‑Connection UI** – Tabs to switch between home, office, or other connections (UI ready).
- **Animated Water Wave Background** – A full‑screen `<canvas>` that continuously draws gentle ocean waves.
- **Responsive Design** – Fully adapts to desktop, tablet, and mobile.
- **Glassmorphism Dashboard** – Clean, floating cards with blur and hover effects.
- **Performance Optimized** – Lazy canvas rendering, hardware‑accelerated CSS, and minimal DOM reflows.

---

## 📄 Pages & Sections

| Page                | Description |
|---------------------|-------------|
| **Home**            | Hero section, live consumption stats, quick‑access dashboard link |
| **Login**           | Consumer number & password (demo) |
| **Register**        | Registration form with consumer details |
| **Dashboard**       | Current bill, consumption graph, meter reading, next due date |
| **Current Bill**    | Detailed breakdown: previous/current readings, units, charges, total |
| **Smart Meter**     | Live meter reading, 24‑hour usage graph, leak alert |
| **Bill History**    | Searchable table of past bills with paid/pending status |
| **Payment**         | Payment method selection (UPI, Card, Net Banking) |
| **Digital Receipt** | Receipt number, transaction ID, amount, QR placeholder, print button |
| **Complaints**      | Complaint form + timeline tracking |
| **Profile**         | Consumer information display |
| **About**           | (Optional) AquaFlow mission & developer info |

---

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge)
- No server, database, or build tools required.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/aquaflow.git
   cd aquaflow