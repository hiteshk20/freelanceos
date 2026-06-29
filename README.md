# FreelanceOS — Local-First Freelance Workspace & Financial Operations Engine

**FreelanceOS** is an elite, commercial-grade Local-First Single Page Application (SPA) built for independent engineers, architects, and designers. Engineered for complete data sovereignty and zero cloud server reliance, FreelanceOS executes all financial calculations, interactive reporting, procedural audio synthesis, and A4 PDF invoice rendering 100% client-side inside your browser.

---

## 🏛️ Technical Architecture & Core Stack

- **Frontend Core**: React 18 (Functional Components, Strict Hooks Architecture), TypeScript, Vite.
- **Styling & UI Design**: Tailwind CSS featuring developer-esque Linear/Vercel aesthetic, smooth transitions, high contrast, and native Dark/Light Mode toggle.
- **Structured Storage**: **IndexedDB via Dexie.js** for reactive, high-performance structured persistence of Clients, Projects, Tasks, TimeLogs, Invoices, and Workspace Configuration.
- **User Preferences**: **LocalStorage** fallback strictly for Theme preferences and encrypted License verification signatures.
- **Reporting & Telemetry**: **Chart.js** & `react-chartjs-2` for dynamic real-time financial bar charts (Income vs Overhead) and project time allocation pie charts.
- **Client-Side PDF Engine**: **html2pdf.js** compiling editable HTML templates directly into clean A4 PDFs without backend server generation.
- **Acoustic Audio Synthesis**: Procedural **HTML5 Web Audio API** nodes simulating White Noise, Brown Noise Rain, and Cafe Chatter murmurs offline with zero MP3 downloads.
- **Markdown Editor**: Lightweight client-side **marked** parser for rich task card notes and deliverable specifications.

---

## 🔐 Freemium & Premium Licensing System

FreelanceOS features an offline client-side cryptographic license verification module designed for Gumroad distribution. Buyers enter their license key in **Settings & Data Portability**, which decrypts and validates the signature locally or via Gumroad API verification.

### 🍅 Free Starter Tier Features
- Access to the **Kanban Task Board** (Maximum capped at 3 Projects).
- Native HTML5 Drag-and-Drop column & task reordering.
- **Standard Pomodoro Timer** (25m Focus / 5m Short Break / 15m Long Break) with SVG circular visual progress bar.
- Procedural Ambient Audio Soundscape Mixer.

### 💎 Pro VIP Edition Features (Unlocked)
- **Unlimited Projects & Tasks** on the Kanban Board.
- **Interactive Invoice Generator** with Base64 company logo upload, tax calculations, and discount models.
- **Client-Side PDF Export Engine** generating professional A4 invoices instantly.
- **Live Billable Stopwatch** automatically calculating client earnings (`Time * Rate`) and logging directly to IndexedDB under *Unbilled Logs*.
- **Client CRM & Billing Profiles** linking hourly rates and currencies ($, €, £, ¥, ₹, CAD, AUD) to projects.
- **Advanced Financial Chart Analytics** aggregating monthly revenue vs overhead trends.
- **Automated Encrypted JSON Backups** & rigorous schema restore validation.

### 🔑 Instant Demo Unlock Keys
To evaluate the Premium tier immediately without Gumroad purchase receipt verification, enter any of the following demo passkeys in the Settings or Premium Modal:
- `FLOS-PRO-UNLIMITED`
- `FREELANCE-OS-PRO-2026`
- Any standard Gumroad UUID string (e.g. `XXXXXXXX-XXXXXXXX-XXXXXXXX-XXXXXXXX`)

---

## 📦 Core Component Modules

### 1. Telemetry Dashboard & Analytics (Pro)
Displays Total Month Revenue, All-Time Gross Revenue, Tracked Billable Hours, Active Projects ratio, and interactive Chart.js feeds aggregating real IndexedDB sessions.

### 2. Kanban Board & Project Manager (Hybrid)
Sleek column view supporting To Do, In Progress, Review, and Done states. Uses browser native **HTML5 Drag and Drop API** natively without clunky third-party drag libraries. Features priority tags (Low, Medium, High, Urgent) and native Desktop Deadline Reminders (`Notification API`).

### 3. Client CRM & Billing Profiles (Pro)
Manage business relationships, hourly billing rates, billing addresses, and internal accounting notes. View unbilled ledger totals per account with 1-click invoice initiation.

### 4. Time Tracker & Procedural Sound Mixer (Hybrid)
Switch between standard Pomodoro sessions and the Live Billable Stopwatch. The built-in acoustic mixer synthesizes white noise and cafe acoustics procedurally on demand.

### 5. Invoice Generator & PDF Engine (Pro)
Fetches unbilled stopwatch logs for any client, populating itemized descriptions. Edit line items, add custom consulting fees, upload your Base64 agency logo, and download high-resolution A4 PDFs instantly.

### 6. Data Sovereignty & Privacy Module (Free & Pro)
- **Export Backup**: Download your entire IndexedDB database as a formatted JSON archive.
- **Restore Backup**: Rigorously validates incoming JSON schemas to prevent storage corruption.
- **Seed Sample Data**: Populates vivid demo clients, boards, timelogs, and paid invoices.
- **Nuke Danger Zone**: Permanently wipes all LocalStorage and IndexedDB records with a double-confirmation prompt for absolute data privacy.

---

## 🚀 Getting Started & Local Development

```bash
# Install dependencies
npm install

# Start local development server on http://localhost:3000
npm run dev

# Build production bundle
npm run build

# Preview production build
npm run preview
```

---
*Built with absolute precision and zero runtime exceptions by Senior Architects & UI/UX Engineers.*
