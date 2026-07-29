<div align="center">

# 🌑 Pitch Black Swiss Portfolio

### A stunning, award-worthy portfolio template with Swiss design aesthetics

[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.6-blue?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![Framer Motion](https://img.shields.io/badge/Framer_Motion-11-FF0055?style=for-the-badge&logo=framer)](https://www.framer.com/motion/)
[![Three.js](https://img.shields.io/badge/Three.js-r170-black?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

<p align="center">
  <strong>🎨 Digital Noir Design • 🚀 Smooth Lenis Scroll • 📱 Fully Responsive • ⚡ Light & Dark Harmony</strong>
</p>

[**Live Demo**](https://portfolio-pitch-black-swiss.vercel.app/) • [**Report Bug**](https://github.com/dev-sufyaan/pitch-black-portfolio/issues) • [**Request Feature**](https://github.com/dev-sufyaan/pitch-black-portfolio/issues)

</div>

---

## 📖 Table of Contents

- [✨ Key Features](#-key-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [📂 Project Structure](#-project-structure)
- [🚀 Quick Start](#-quick-start)
- [🧩 Key Components](#-key-components)
- [📄 License](#-license)

---

## ✨ Key Features

- **Film-Grain Noise Overlay:** Subtle CRT/film noise overlay for a highly textured, analog digital noir aesthetic.
- **Lenis Smooth Scroll:** Integrated with `lenis` to deliver ultra-smooth, premium trackpad and mouse scrolling.
- **Kinetic Marquees:** Dynamic, high-performance horizontal looping text with interactive skew properties based on velocity.
- **Custom Adaptive Cursor:** Fluid interactive cursor that scales, morphs, and reacts when hovering over links and magnetic elements.
- **Curtain Reveal Layout:** Elegant overlapping section transitions mimicking theater curtains revealing content underneath on scroll.
- **Bento Grid Layouts:** Clean, responsive Swiss grid systems for showcase skills, tools, and timelines.
- **Typography-First Design:** Features modern grotesque styling using Google Fonts (Inter, Playfair Display, Great Vibes) representing a structured Swiss style.

---

## 🛠️ Tech Stack

- **Framework:** Next.js (App Router)
- **Styling:** Tailwind CSS, PostCSS
- **Animation:** Framer Motion (Motion), Lenis (Smooth scroll)
- **Interactive 3D:** Three.js / React Three Fiber / Drei (for WebGL components)
- **Icons:** React Icons, Tabler Icons React
- **Language:** TypeScript

---

## 📂 Project Structure

```bash
├── app/
│   ├── globals.css         # Styling system & custom font setup
│   ├── layout.tsx          # Root layout featuring Noise, Cursor & Providers
│   └── page.tsx            # Main portfolio layout with curtain reveal structure
├── components/
│   ├── sections/           # Interactive page sections
│   │   ├── hero-section.tsx   # Typography heavy hero landing
│   │   ├── about-section.tsx  # Dynamic pitch & introductory stats
│   │   ├── works-section.tsx  # Video editing portfolio showcase
│   │   ├── process-section.tsx# Horizontal/vertical interactive timeline
│   │   ├── skills-section.tsx # Bento-style skills & tools matrix
│   │   └── footer-section.tsx # Minimalist terminal footer
│   ├── ui/                 # Highly reusable micro-interaction components
│   │   ├── kinetic-marquee.tsx
│   │   ├── magnetic-button.tsx
│   │   ├── encrypted-text.tsx
│   │   ├── focus-cards.tsx
│   │   ├── distortion-image.tsx
│   │   ├── floating-navbar.tsx
│   │   └── sparkles.tsx
│   ├── curtain-reveal-layout.tsx
│   ├── custom-cursor.tsx
│   └── noise-overlay.tsx
├── lib/                    # Helper utilities
└── public/                 # Static assets (fonts, video placeholders)
```

---

## 🚀 Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/dev-sufyaan/pitch-black-portfolio.git
cd pitch-black-portfolio
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run the development server
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.

### 4. Build for Production
```bash
npm run build
npm run start
```

---

## 🧩 Key Components

### 💫 Motion & Interaction
- **[CurtainRevealLayout](file:///Users/divyanshuraj/Documents/Portfolio-Pitch-Black-Swiss/components/curtain-reveal-layout.tsx):** Implements a beautiful scroll reveal transition that unrolls sections over each other.
- **[KineticMarquee](file:///Users/divyanshuraj/Documents/Portfolio-Pitch-Black-Swiss/components/ui/kinetic-marquee.tsx):** Seamlessly loops words horizontally with responsive direction and speed.
- **[MagneticButton](file:///Users/divyanshuraj/Documents/Portfolio-Pitch-Black-Swiss/components/ui/magnetic-button.tsx):** Draws the cursor towards itself using magnetic physics interpolation.
- **[CustomCursor](file:///Users/divyanshuraj/Documents/Portfolio-Pitch-Black-Swiss/components/custom-cursor.tsx):** Tracks cursor position smoothly, adapting style depending on hovered tags.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
