# ⚡ ProWeb Pulse: Mastering PWA Fundamentals (Cine Seek Application)

This repository details the successful transformation of a Next.js-based movie application, **Cine Seek**, into a high-performance **Progressive Web App (PWA)**. The project focuses on implementing core PWA features—**offline access**, **installability**, and **improved performance**—using the Next.js framework and the `@ducanh2912/next-pwa` package.

## ✨ Key Features & Concepts

This project demonstrates mastery of the following PWA and Next.js concepts:

* **Service Worker Implementation:** Configuration and deployment of a service worker for enabling offline caching and background sync capabilities.
* **Web App Manifest:** Creation and linking of `manifest.json` to provide app metadata for seamless mobile installation (Add to Home Screen).
* **Offline Caching:** Setup of proper caching strategies to allow users to browse previously viewed movie details without an internet connection.
* **Next.js Integration:** Seamless integration of PWA tooling within the Next.js framework using `next.config.mjs` and `pages/_document.tsx`.
* **Real-World Application:** Emulates the architectural pattern used by major media platforms (e.g., Spotify Lite, Netflix) for cross-platform, app-like experiences.

## 🚀 Getting Started

Follow these steps to set up and run the Cine Seek PWA application locally.

### Prerequisites

* **Node.js** (LTS version)
* **npm** or **yarn**
* **Git**

### Installation and Local Run

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/Musakalamz/alx-pwa-0x01.git](https://github.com/Musakalamz/alx-pwa-0x01.git) alx-movie-app
    cd alx-movie-app
    ```

2.  **Install Dependencies**
    Install all required packages, including `next`, `react`, and the PWA-specific dependencies.
    ```bash
    npm install
    # Ensure next-pwa and webpack are installed:
    # npm i @ducanh2912/next-pwa
    # npm i -D webpack
    ```

3.  **Run the Development Server**
    ```bash
    npm run dev
    ```
    The application will be accessible at `http://localhost:3000` (or the default Next.js port). Use **Chrome DevTools (Application tab)** to verify the Service Worker registration and Manifest loading. 

## 📝 Project Implementation Details

| Task | Objective | Files/Configuration |
| :--- | :--- | :--- |
| **0. Install Dependencies** | Setup the PWA package. | `package.json` |
| **1. Configure PWA in Next.js** | Integrate `next-pwa` with Next.js build process. | `next.config.mjs` |
| **2. Create Web App Manifest** | Define PWA install metadata and icons. | `public/manifest.json`, `public/icons/` |
| **3. Link the Manifest** | Ensure the browser recognizes the manifest file. | `pages/_document.tsx` |
| **4. Test and Deploy** | Verify PWA functionality and deploy to Vercel. | Deployed URL: `https://alx-pwa-0x01-phi-murex.vercel.app/` |

## 🛠️ Tools and Libraries

* **Next.js:** The core React framework used for server-side rendering.
* **@ducanh2912/next-pwa:** Next.js plugin to easily add PWA features.
* **Webpack:** Used by Next.js for module bundling.
* **Vercel:** Deployment platform for live testing and accessibility.

## 🌐 Live Demonstration

The application is deployed and available for testing on:
[https://alx-pwa-0x01-phi-murex.vercel.app/](https://alx-pwa-0x01-phi-murex.vercel.app/)

Feel free to test the **install prompt** and **offline experience** on a mobile device or a desktop Chrome browser.

## 👤 Author

* **Musa Ogunsolu** (GitHub: [Musakalamz](https://github.com/Musakalamz))
* **LinkedIn:** [Musa Ogunsolu](https://www.linkedin.com/in/musa-ogunsolu)

---

## ⚖️ License

* **ALX** - This project is for educational purposes as part of the ALX curriculum.
