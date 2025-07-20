# 🚀 Deepak Nethaji - Portfolio

> **Aspiring Data Analyst & Full Stack Developer | AI & Data Science Enthusiast**

A modern, interactive portfolio website showcasing Deepak Nethaji's skills, experience, and projects. Built with the latest technologies, featuring 3D animations, vivid cyan accents, and seamless user experience.

![Status](https://img.shields.io/badge/Status-Live-brightgreen)
![React](https://img.shields.io/badge/React-18.3.1-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-5.5.3-blue)
![Vite](https://img.shields.io/badge/Vite-5.4.1-purple)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4.11-cyan)
![Three.js](https://img.shields.io/badge/Three.js-3D-orange)
![EmailJS](https://img.shields.io/badge/EmailJS-Integrated-blueviolet)

---

## ✨ Features

- **Modern UI**: Glassmorphism, dark mode, vivid cyan accents
- **3D Animations**: Interactive models with Three.js & React Three Fiber
- **Responsive**: Mobile-first, pixel-perfect on all devices
- **Scroll & Hover Effects**: Smooth reveal and interactive transitions
- **Contact & Email**: EmailJS-powered contact form/modal
- **CV Management**: Download and preview CV in-app
- **Project & Experience Timeline**: Real-world projects, GitHub links
- **Skills & Tools**: Categorized, visually rich, always up-to-date
- **Certifications**: Modal viewer for certificates
- **SEO & Performance**: Optimized for speed and discoverability

---

## 🏗️ Tech Stack

### **Core**
- **React 18** (with hooks)
- **TypeScript 5**
- **Vite** (blazing fast dev/build)
- **Tailwind CSS 3** (utility-first styling)
- **shadcn/ui** & **Radix UI** (accessible, beautiful components)
- **Lucide React** (modern icons)

### **3D & Animation**
- **Three.js**
- **React Three Fiber**
- **React Three Drei**
- **Custom ScrollReveal**

### **Data & Backend**
- **EmailJS** (contact form integration)
- **React Query** (data fetching/caching)
- **PYODBC** (Python DB connectivity, project experience)

### **Other Tools**
- **ESLint** (linting)
- **PostCSS & Autoprefixer**
- **React Router** (routing)

---

## 🛠️ Skills & Tools

### **Languages**
- Java ☕, Python 🐍, C ©️, C++ 🔧, JavaScript ⚡

### **Frontend**
- React ⚛️, HTML5 🌐, CSS3 🎨, Tailwind CSS 💨

### **Backend**
- Spring Boot 🌱, Flask 🧪, JWT 🔐

### **Databases**
- MySQL 🗄️, PostgreSQL 🐘, Firebase 🔥, **PYODBC 🔌**

### **Data Science / ML**
- Pandas 🐼, NumPy 📊, Matplotlib 📈, Scikit-Learn 🤖, Jupyter 📓, Power BI !(https://img.shields.io/badge/Power%20BI-yellow), Tableau 📋, Excel

### **Cloud & DevOps**
- AWS ☁️, GitHub Actions 🔄, Linux 🐧

### **Testing & Automation**
- Postman 📮, JUnit ✅

### **Utilities & Platforms**
- GitHub 🐙, VS Code 💻, Git 📝

### **Design & Docs**
- Figma 🎨, Markdown 📝

---

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/deepak-portfolio.git
   cd deepak-portfolio
   ```
2. **Install dependencies**
   ```bash
   npm install
   ```
3. **Start development server**
   ```bash
   npm run dev
   ```
4. **Open your browser**
   Navigate to the port shown in terminal (e.g., http://localhost:8081)

---

## 📁 Project Structure

```
deepak-portfolio/
├── public/                        # Static assets
│   ├── resume.png                 # CV/Resume image
│   ├── excel.png                  # Excel logo for skills
│   ├── Zealous.png                # Certificate image
│   ├── certificate.png            # Certificate image
│   ├── favicon.svg                # Site favicon
│   └── robots.txt                 # SEO robots file
│
├── src/
│   ├── App.tsx                    # Main app component
│   ├── App.css                    # App-level styles
│   ├── index.css                  # Global styles
│   ├── main.tsx                   # App entry point
│   ├── vite-env.d.ts              # Vite TypeScript env types
│   │
│   ├── components/                # All React components
│   │   ├── 3d/                    # 3D models and scenes
│   │   │   ├── ContactRobot.tsx
│   │   │   ├── ContactScene3D.tsx
│   │   │   ├── RobotModel.tsx
│   │   │   └── Scene3D.tsx
│   │   ├── sections/              # Main page sections
│   │   │   ├── ContactSection.tsx
│   │   │   ├── ExperienceSection.tsx
│   │   │   ├── HeroSection.tsx
│   │   │   ├── SkillsSection.tsx
│   │   │   └── SummarySection.tsx
│   │   ├── ui/                    # UI primitives (shadcn/ui, Radix, custom)
│   │   │   ├── (many .tsx files: dialog, button, card, table, etc.)
│   │   ├── CertificateModal.tsx   # Modal for certificates
│   │   ├── EmailModal.tsx         # Modal for email/contact
│   │   ├── ErrorBoundary.tsx      # Error boundary component
│   │   ├── NavigationTabs.tsx     # Tab navigation
│   │   ├── ScrollingBackground.tsx# Animated background
│   │   └── ScrollReveal.tsx       # Scroll animation wrapper
│   │
│   ├── hooks/                     # Custom React hooks
│   │   ├── use-mobile.tsx
│   │   ├── use-toast.ts
│   │   └── useScrollReveal.tsx
│   │
│   ├── lib/                       # Utility functions
│   │   └── utils.ts
│   │
│   ├── pages/                     # Page-level components
│   │   ├── Index.tsx
│   │   └── NotFound.tsx
│
├── dist/                          # Production build output (auto-generated)
│
├── package.json                   # Project dependencies and scripts
├── package-lock.json              # Dependency lock file
├── tailwind.config.ts             # Tailwind CSS configuration
├── vite.config.ts                 # Vite build tool configuration
├── tsconfig.json                  # TypeScript configuration
├── tsconfig.app.json              # App-specific TS config
├── tsconfig.node.json             # Node-specific TS config
├── postcss.config.js              # PostCSS configuration
├── eslint.config.js               # ESLint configuration
├── index.html                     # HTML entry point
└── .gitignore                     # Git ignore rules
```

This structure gives a clear, professional overview of your project for your README. If you want to highlight or explain any specific folders or files, let me know!

---

## 🎨 Design System
- **Accent Color**: Vivid Cyan (`#00ffff`)
- **Background**: Dark gradients, light grey modals
- **Typography**: Times New Roman, bold headings
- **Animations**: Scroll reveal, hover, 3D

---

## 📧 Contact & CV
- **EmailJS**: Direct email from contact modal
- **CV**: Download and preview (PDF/image)
- **Social Links**: LinkedIn, GitHub, Phone

---

## 🏆 Achievements & Certifications
- Modal viewer for certificates (light grey background, black title)
- All certificates accessible from Experience section

---

## 📝 License
MIT License. See [LICENSE](LICENSE) for details.

---

## 👨‍💻 About
**Deepak Nethaji** — B.Tech AI & Data Science | Data Analyst & Full Stack Developer | Passionate about building data-driven, AI-powered solutions.

- **LinkedIn**: [Deepak Nethaji](https://www.linkedin.com/in/deepak-nethaji-349a8a235/)
- **GitHub**: [DeepakNS003](https://github.com/DeepakNS003)
- **Email**: deepaknethaji01@gmail.com
- **Location**: Salem, Tamil Nadu, India

---

<div align="center">
  <p>Made with ❤️ by Deepak Nethaji</p>
  <p>© 2024 Deepak Nethaji. All rights reserved.</p>
</div>
