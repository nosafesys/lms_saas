# Learning Platform SaaS – Built with Next.js, Supabase & Stripe

Kickstart your journey in building modern SaaS applications by exploring this comprehensive, production-ready LMS project. This repository contains the source code for a full-featured Learning Management System that combines real-time data, subscriptions, AI voice tutors, and a clean, responsive UI.

---

## 📚 Overview

This project demonstrates how to develop a SaaS learning platform from scratch. With secure authentication, robust billing, voice AI integration, and a scalable tech stack, it serves as an ideal foundation for your own commercial or personal projects.

Use this as a guide to learn, extend, or launch your next big idea.

---

## 🛠️ Tech Stack

- **Next.js** – React framework with server-side rendering, static site generation, and API routes.
- **Supabase** – Open-source backend with real-time subscriptions, authentication, and PostgreSQL database.
- **Clerk** – Handles user authentication and billing with pre-built UI and admin tools.
- **Stripe** – Manages subscription payments securely.
- **Tailwind CSS & shadcn/ui** – For a modern, customizable design system.
- **Sentry** – Application monitoring for errors and performance.
- **Vapi** – Integrates conversational voice agents for interactive tutoring.
- **TypeScript & Zod** – Strong typing and schema validation for safer code.

---

## 🚀 Features

- 🎙 **AI Voice Tutors** – Practice subjects with conversational, voice-enabled AI.
- 🔐 **Authentication** – User sign-up, sign-in, and OAuth through Clerk.
- 💳 **Subscriptions & Payments** – Flexible plans and billing via Stripe.
- ⭐ **Bookmarks & History** – Keep track of favorite tutors and revisit past sessions.
- 🛠 **Create a Tutor** – Set up your own AI tutor with custom subjects and styles.
- 📱 **Responsive UI** – Fully optimized across mobile, tablet, and desktop.
- ⚡ **Real-Time Data** – Backed by Supabase for instant updates.
- 🔍 **Powerful Search** – Quickly locate tutors using filters and search.
- 🔄 **Modular Codebase** – Reusable components designed for scalability.

---

## ⚡ Getting Started

### Prerequisites

Make sure you have installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [Git](https://git-scm.com/)

---

### Clone the Repository

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

---

### Install Dependencies

```bash
npm install
```

---

### Configure Environment Variables

Create a `.env` file in the root directory and add your credentials:

```env
# Sentry
SENTRY_AUTH_TOKEN=

# Vapi
NEXT_PUBLIC_VAPI_WEB_TOKEN=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

# Supabase
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
```

Replace these with your actual keys from Supabase, Clerk, Sentry, and Vapi.

---

### Run the Application

```bash
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) to see it running.
