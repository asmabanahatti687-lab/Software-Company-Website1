# 🚀 TechNova – Modern Software & Digital Solutions Frontend

TechNova is a fully responsive, enterprise-grade frontend application for a modern software engineering and digital transformation company. Built with **HTML5**, **CSS3**, and modular **vanilla JavaScript**, it features a complete single-page interactive application architecture (SPA) with full page navigation, live form validation, dynamic data engines, client-side authentication, and dark mode support.

---

## 🌐 Live Demo & Repository

*   **Live Demo:** [https://your-deployed-url.com](https://your-deployed-url.com) *(Replace with your Netlify, Vercel, or GitHub Pages link)*
*   **GitHub Repository:** `https://github.com/your-username/technova-website.git`

---

## ✨ Key Features & Functionality

*   **1. Multi-Page Experience & Routing:**
    *   10 complete interactive site views: Home, About Us, Services, Portfolio, Blog/News, Careers, Contact, Login, Register, and Protected Dashboard.
    *   Smooth page transitions and mobile-first responsive navigation with dropdown menus and mobile drawer menu.
*   **2. Dynamic Data & Portfolio Marketplace:**
    *   Categorized project showcase featuring real-time filter chips (Web, Mobile, Cloud, AI, Cybersecurity).
    *   Interactive modal views displaying client details, technologies used, and project metrics.
*   **3. Interactive Blog Engine:**
    *   Search and filter tech articles and industry insights by category (Cloud, AI, Engineering, Design).
    *   Interactive article bookmarking and reading-time estimations.
*   **4. Career & Job Application Portal:**
    *   Explore active job openings (Software Engineers, Cloud Architects, AI Researchers, QA Specialists).
    *   Interactive multi-field job application modal with file upload simulation and immediate confirmation.
*   **5. Contact & Location Finder:**
    *   Interactive office location selector (San Francisco, New York, London, Bangalore) with simulated dynamic interactive map rendering.
    *   Contact query logging with local storage persistence.
*   **6. Security & Authentication Engine:**
    *   Client-side authentication with Web Crypto API (`SHA-256`) password hashing.
    *   Show/Hide password toggles, "Remember Me" toggle, and strict validation checks.
    *   5-attempt failed login security lockout with dynamic 5-minute countdown lock state.
    *   Protected Dashboard view requiring login state, complete with a 15-minute idle auto-logout manager.
*   **7. Real-Time Form Validation System:**
    *   Live validation across Contact, Careers, Newsletter, Login, and Register forms.
    *   Strict input rules: Name (letters only, min 3 chars), Email (RFC-compliant format), Phone (10 digits), Password (min 8 chars with uppercase, lowercase, number, and special character).
    *   Visual indicators: Inline red error messages and borders for invalid inputs; green borders and ticks for valid fields.
*   **8. Customer Testimonials & FAQ Accordion:**
    *   Interactive testimonial carousel with auto-play and manual navigation.
    *   Accessible collapsible FAQ accordion with search capability.
*   **9. Dark / Light Mode Support:**
    *   Persistent light and dark theme toggling stored in `localStorage`.

---

## 🛠️ Technology Stack

*   **HTML5** (Semantic markup, ARIA accessibility standards, Content Security Policy tags)
*   **CSS3** (Custom properties/variables, Flexbox, Grid, keyframe animations, mobile-first design)
*   **JavaScript (ES6+)** (Vanilla DOM manipulation, state management, event delegation)
*   **Font Awesome (v6.4.0)** (Iconography)
*   **Google Fonts** (Inter & Poppins typography)
*   **Web Crypto API** (Client-side SHA-256 password hashing)
*   **LocalStorage API** (Theme persistence, auth session tracking, job applications, contact submissions)

---

## 📁 Project Structure

```text
technova-website/
│
├── index.html          # Main HTML entry point (contains all views & templates)
├── css/
│   └── style.css       # Enterprise CSS variables, utility classes, theme rules
└── js/
    ├── data.js         # Centralized data store (Services, Portfolio, Blog, Careers, Team)
    ├── auth.js         # Auth state, SHA-256 encryption, security lockout, auto-logout
    └── script.js       # App router, dynamic DOM rendering, live validation, interactions
