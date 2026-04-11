# grocTrac — TODO

**Type:** Crowdsourced Grocery Price Comparison App  
**Stack:** Python/FastAPI (backend), Next.js/React (frontend), PostgreSQL + PostGIS  
**Status:** Specification only — no code implemented

---

## Actions To Take

- [ ] **Initialize project with chosen tech stack** — Create `apps/api` (FastAPI + Python) and `apps/web` (Next.js) with `requirements.txt`, `package.json`, Docker Compose for PostgreSQL + PostGIS, and `.env.example`
- [ ] **Design and create database schema** — Write PostgreSQL migrations for Users, Receipts, PriceRecords, Stores, and Store_Locations tables; enable PostGIS extension for geolocation queries
- [ ] **Implement receipt upload and OCR pipeline** — Build API endpoint for image upload; integrate OCR (Tesseract or a cloud vision API); parse receipt items and prices into structured records
- [ ] **Create authentication system** — Implement user registration/login with JWT tokens and role-based access (contributor, viewer, admin) using NextAuth.js or FastAPI + python-jose
- [ ] **Scaffold core price comparison UI** — Build Next.js pages for product price search, store results grid, trending price chart, and a store locator map with real data
