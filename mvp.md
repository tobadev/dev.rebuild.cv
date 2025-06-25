# MVP – dev.rebuild.cv

This document outlines the **Minimum Viable Product (MVP)** scope for `rebuild.cv`. The goal is to ship a usable, fast, and AI-assisted CV builder for early adopters — primarily students and young professionals.

---

## 🧩 MVP Structure

- **Phase 1: Core Functionality**
- **Phase 2: Polished Product**
- **Phase 3: Growth Drivers**

---

## ✅ Phase 1: Core Functionality

> 🚀 Goal: Get users to create, edit, and download a CV with minimal effort.

### Features
- [ ] **User Auth**
  - Email + password or magic link (Clerk)
- [ ] **Dashboard**
  - View existing CVs
  - Create new CV
  - Delete CV
- [ ] **CV Editor**
  - Markdown-based editor or form-based
  - Auto-formatting into sections (e.g. Experience, Education, Skills)
  - Live preview
- [ ] **AI Assistant**
  - Suggest content for sections (e.g. rewrite bullet point, fill gaps)
  - Initial prompt options for students with no experience
- [ ] **PDF Export**
  - Download CV as PDF in default layout

---

## 🎯 Phase 2: Polished Product

> 🧪 Goal: Improve usability, support templates, cover letters, and introduce autosave.

### Features
- [ ] **Autosave & Local Drafts**
- [ ] **CV Templates**
  - Minimal / Modern / Professional (1-column and 2-column)
- [ ] **Cover Letter Builder**
  - Optional AI-assisted generator
- [ ] **Mobile Responsiveness**
- [ ] **User Profile Settings**
  - Name, photo, email settings

---

## 📈 Phase 3: Growth Drivers

> 🔁 Goal: Retention, virality, and conversion funnel

### Features
- [ ] **AI Chat Assistant**
  - "Ask CV Assistant anything"
- [ ] **CV Analytics**
  - Track downloads, views (for hosted CV links)
- [ ] **Shareable Link**
  - `rebuild.cv/u/username`
- [ ] **Referral Program**
  - Invite friends = unlock premium templates
- [ ] **Educational Pricing Tier**
  - Free for students w/ .edu or .ac email

---

## ⚙️ Tech Stack Overview

| Layer       | Tech                       |
|-------------|----------------------------|
| Frontend    | Next.js (App Router)       |
| UI          | shadcn/ui, Tailwind CSS    |
| Auth        | Clerk / NextAuth           |
| Backend     | Edge Functions (Vercel)    |
| Database    | PlanetScale / Supabase     |
| AI          | OpenAI API + Jina AI       |
| Export      | react-pdf or Puppeteer     |
| Hosting     | Vercel                     |

---

## 🔖 Notes

- This MVP is scoped to **ship in 14 days** with basic features.
- AI Assistant should support **cold start prompts** like:
  - "I’m a student with no experience"
  - "I did an internship in marketing"
  - "I need a CV for a tech job"

---

