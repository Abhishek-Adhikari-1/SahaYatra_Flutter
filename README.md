# SahaYatra Flutter (Mobile App)

SahaYatra (सहयात्रा - "Journey Together") is a comprehensive school bus tracking mobile application built with Flutter. It serves two distinct user roles through a unified codebase: **Parents** and **Drivers**.

For **Parents**, it provides peace of mind by offering real-time live tracking of their child's bus, automated push notifications for bus arrivals, and strict privacy controls ensuring they only see buses assigned to their children.
For **Drivers**, it acts as a digital cockpit to start trips, navigate routes, and manage the student boarding/drop-off manifest without paper.

## Key Features
- **Dual-Role Architecture:** Seamless login and UI switching for Parents and Drivers.
- **Live Map Tracking:** Real-time bus movement using MapLibre GL with smooth marker animations.
- **Smart Notifications:** Firebase Cloud Messaging (FCM) integration for milestone alerts (Bus Approaching, Arrived, Boarded, Dropped Off).
- **Digital Manifest (Driver):** One-tap UI to mark students as boarded, absent, or dropped off.
- **Privacy-First (Parent):** Client-side and server-side enforcement ensuring parents only see their child's assigned route.

## Tech Stack
- **Framework:** Flutter (Dart)
- **Maps:** MapLibre GL Flutter
- **Real-time:** Server-Sent Events (SSE)
- **Notifications:** Firebase Cloud Messaging (FCM)

### Part of the SahaYatra Ecosystem
- 💻 [Admin Dashboard (Next.js)](https://github.com/Abhishek-Adhikari-1/SahaYatra_Web.git)
- ⚙️ [Backend API (Bun)](https://github.com/Abhishek-Adhikari-1/SahaYatra_Backend.git)