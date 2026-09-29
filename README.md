# GJU Global

### Connecting students with international opportunities, resources, and experiences.

**GJU Global** is a student-developed digital platform designed to bring international opportunities and exchange-related resources for German Jordanian University students into one centralized experience.

The project explores how students can more easily discover opportunities, prepare for studying abroad, access relevant resources, learn from other students' experiences, and stay connected throughout their international journey.

---

## The Problem

Preparing for an international experience involves much more than choosing a destination.

Students often need to navigate information about exchange programs, universities, applications, documents, deadlines, preparation, cultural differences, and life abroad — while much of this information may be distributed across different sources.

At the same time, valuable knowledge from students who have already gone through the experience can be difficult to access.

---

## Our Solution

We designed and developed **GJU Global** as a centralized platform for the international student journey.

The platform brings together opportunities, resources, preparation tools, student experiences, and community features within one digital environment.

Rather than focusing only on finding an exchange opportunity, GJU Global is designed around the broader journey:

**Explore → Prepare → Apply → Go Abroad → Connect → Share**

The goal is to make international opportunities more **accessible, organized, and student-centered**.

---

## Tech Stack

GJU Global is built as a **full-stack TypeScript web application**.

### Frontend

- **React 18**
- **TypeScript**
- **Vite**
- **Tailwind CSS**
- **shadcn/ui**
- **Radix UI**
- **TanStack Query**
- **React Hook Form**
- **Wouter**
- **Framer Motion**
- **Recharts**
- **Leaflet / React Leaflet**

### Backend

- **Node.js**
- **Express.js**
- **TypeScript**
- **REST APIs**
- **Zod** for schema validation

### Data & Authentication

- **PostgreSQL**
- **Drizzle ORM**
- **Drizzle Kit**
- **OpenID Connect**
- **Passport.js**
- Session-based authentication
- Role-based access control

### Development & Tooling

- **Git & GitHub** — version control and collaboration
- **Replit** — development and prototyping
- **Vite** — frontend tooling
- **esbuild** — production server bundling
- **TypeScript** — end-to-end type safety

---

## High-Level Architecture

GJU Global follows a modular full-stack architecture with shared TypeScript schemas across the application.

```text
                     ┌─────────────────────┐
                     │      Students       │
                     │   & Platform Users  │
                     └──────────┬──────────┘
                                │
                                ▼
                     ┌─────────────────────┐
                     │    React Web App    │
                     │                     │
                     │  TypeScript + Vite  │
                     └──────────┬──────────┘
                                │
                                ▼
                     ┌─────────────────────┐
                     │      REST API       │
                     │                     │
                     │  Node.js + Express  │
                     └──────────┬──────────┘
                                │
                    ┌───────────┴───────────┐
                    ▼                       ▼
          ┌──────────────────┐    ┌──────────────────┐
          │    Data Layer    │    │ Authentication   │
          │                  │    │ & Authorization  │
          │   PostgreSQL     │    │                  │
          │   Drizzle ORM    │    │   OIDC + RBAC    │
          └──────────────────┘    └──────────────────┘
```

The frontend and backend share structured TypeScript schemas to maintain consistency across the platform.

---

## Key Engineering Areas

Development of GJU Global involved work across both **product development and full-stack engineering**, including:

- Designing a multi-section student platform
- Building responsive and reusable React interfaces
- Developing REST API services
- Designing and managing structured application data
- Implementing authentication and role-based access
- Building interactive geographic experiences
- Creating forms and schema-based validation
- Developing student-facing and administrative experiences
- Building moderation workflows
- Creating data visualization and progress-tracking interfaces
- Connecting frontend experiences with backend services
- Designing for different stages of the international student journey

---

## Current Status

### 🚧 Functional Full-Stack Prototype

GJU Global has progressed into a functional full-stack platform demonstrating how the international student experience can be brought together within one digital environment.

The current prototype includes the core frontend experience, backend services, structured data layer, authentication, user-specific functionality, and administrative capabilities.

The project continues to evolve through feature development, interface improvements, and technical iteration.

---

## Team

GJU Global is a **student-led project developed at the German Jordanian University**.

### [Ban Y. Tarawneh](https://www.linkedin.com/in/ban-tarawneh/?isSelfProfile=true)

### [Karmel Qawasmi](https://www.linkedin.com/in/karmel-qawasmi-40b70b197/)



---

## About This Project

GJU Global was created to explore how technology can improve the way students discover and navigate international opportunities.

The project combines **software engineering, product design, international mobility, and student experience** within a single platform.

This GitHub organization serves as a public technical and product showcase. Development repositories and implementation details are maintained separately.

> **Disclaimer:** GJU Global is a student-developed project and is not an official digital service or platform of the German Jordanian University.

---

<p align="center">
  <b>International Mobility • Full-Stack Development • Student Experience • GJU</b>
</p>
