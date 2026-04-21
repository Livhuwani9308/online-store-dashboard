# Product Analytics Dashboard

An Angular-based dashboard designed for product analytics, built with a modular architecture and clean coding practices.

**Tech Stack:** Angular • TypeScript • TailwindCSS  
**License:** MIT

---

## 📖 Overview
This project is a **Product Analytics Dashboard** built with Angular 20. It demonstrates how to structure applications using NgModules, which remain common in enterprise environments, even as Angular moves toward standalone components. The goal is to provide a practical example of working with legacy-style modular code while still applying modern development principles.

The dashboard includes **interactive analytics, chart visualizations, and advanced data handling**, all implemented with performance and scalability in mind. It follows SOLID principles to ensure clear separation of concerns and maintainability.

---

## ✨ Features

### Core
- **Analytics Dashboard** — Real-time KPIs and performance metrics  
- **Sortable Data Tables** — Clickable headers with ascending/descending indicators  
- **Search & Filters** — Category-based filtering with debounced input  
- **Charts & Graphs** — Monthly sales trends powered by Chart.js  
- **Pagination** — Server-driven pagination with page details  
- **Theme Toggle** — Dark/light mode with persistence in localStorage  
- **Responsive Layout** — TailwindCSS mobile-first design  

### Advanced
- **Repository Pattern** — Abstracted data access layer  
- **HTTP Interceptors** — Automatic token injection for API calls  
- **Reactive State** — RxJS BehaviorSubjects with async pipes  
- **OnPush Change Detection** — Optimized rendering strategy  
- **Lazy Loading** — Modules loaded only when needed  
- **SOLID Principles** — Maintainable, testable, and extensible architecture  

---

## 🚀 Getting Started

### Requirements
- Node.js ≥ 18.x  
- npm ≥ 9.x  
- Angular CLI ≥ 20.x  

```bash
node --version   # >= 18.x
npm --version    # >= 9.x
ng version       # >= 20.x
