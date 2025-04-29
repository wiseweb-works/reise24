# Reise24 – Modern Travel Management Platform

**Reise24** is a feature-rich, fullstack travel management application built using the latest **React Router 7**, integrated with **Syncfusion UI components**, **Appwrite backend services**, and **Stripe** for secure payment processing. It delivers a smooth, interactive, and responsive user experience for booking, managing, and visualizing travel-related data.

---

## ✨ Features

- 🧭 **Server-driven routing** with React Router 7
- 🧩 **Modular, component-rich UI** using Syncfusion
- 💳 **Payment integration** with Stripe
- ☁️ **Backendless architecture** powered by Appwrite
- 📈 **Advanced charts, grids, and maps**
- 🕵️‍♀️ **Bot detection** and smart user tracking (via `isbot` & Sentry)
- 🎉 **Interactive UX enhancements** with canvas-confetti
- 🌍 **Timezone-aware date handling** via Day.js
- ⚡ Built with **Vite** for instant development feedback

---

## 🧱 Tech Stack

| Layer       | Tools / Libraries                                       |
| ----------- | ------------------------------------------------------- |
| Frontend    | React 19, React Router 7, Tailwind CSS 4                |
| UI          | Syncfusion React Components                             |
| Backend API | Appwrite (headless CMS, authentication, database, etc.) |
| Payments    | Stripe                                                  |
| Monitoring  | Sentry with profiling                                   |
| Utilities   | Day.js, isbot, clsx, canvas-confetti                    |
| Dev Tools   | Vite, TypeScript, ESLint, React Router DevTools         |

---

## 📦 Installation

```bash
git clone https://github.com/wiseweb-works/reise24.git
cd reise24
pnpm install
```

### Development

```bash
pnpm run dev
```

### Build

```bash
pnpm run build
```

### Type Check

```bash
pnpm run typecheck
```

### Start (Production Serve)

```bash
pnpm run start
```

---

## 🔐 Environment Setup

Create and configure an `.env` file from the sample `.env.example` file:

```
# Syncfusion
VITE_SYNCFUSION_LICENSE_KEY=

# Appwrite
VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_API_KEY=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_USERS_COLLECTION_ID=
VITE_APPWRITE_TRIPS_COLLECTION_ID=
VITE_APPWRITE_API_ENDPOINT=

# Gemini
GEMINI_API_KEY=

# Unsplash
UNSPLASH_ACCESS_KEY=

# Stripe
STRIPE_SECRET_KEY=
```

---

## 📚 Learnings & Highlights

- Implemented advanced server-side routing with full React Router SSR.
- Built reusable, dynamic UI with enterprise-grade Syncfusion components.
- Integrated Appwrite as a backendless solution for auth and storage.
- Managed real-time payment flows securely with Stripe.
- Tuned performance with Vite and TypeScript’s strict mode.

---

## 🧠 Useful Resources

- [React Router Docs](https://reactrouter.com/en/main)
- [Syncfusion React UI](https://www.syncfusion.com/react-components)
- [Appwrite](https://appwrite.io/)
- [Stripe Docs](https://stripe.com/docs)
- [Sentry Profiling](https://docs.sentry.io/performance/profiling/)
- [Vite](https://vitejs.dev/)

---

## 📸 Screenshots / Demo

### Admin Pages

|            Sign-In Page            |              Admin Dashboard               |
| :--------------------------------: | :----------------------------------------: |
| ![](./images/sign-in.png?raw=true) | ![](./images/admin_dashboard.png?raw=true) |

|              All Trips               |            Create Trips with AI            |
| :----------------------------------: | :----------------------------------------: |
| ![](./images/all_trips.png?raw=true) | ![](./images/create_trips_ai.png?raw=true) |

### User Pages

|              Homepage               |           Trip Details & Buy            |
| :---------------------------------: | :-------------------------------------: |
| ![](./images/homepage.png?raw=true) | ![](./images/trip_details.png?raw=true) |

|     Successful Purchasing with Stripe     |
| :---------------------------------------: |
| ![](./images/successful_buy.png?raw=true) |

---

## 📜 License

MIT © [Abdullah Koyuncu](https://github.com/wiseweb-works)
