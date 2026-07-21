# Day 51 – Product Discovery & Sprint Planning (Capstone)

## ABTalks 60 Days Claude Challenge

Today marked the beginning of the 10-day Capstone Project. Instead of jumping directly into development, the focus was on discovering a meaningful product idea, validating its feasibility, defining the MVP, and creating a complete execution roadmap.

---

# Project

## InternTrust

**Tagline:**
AI-Powered Internship Discovery Platform for CS Students

InternTrust is a full-stack web platform designed to help Computer Science students at Integral University discover internship opportunities they can actually trust and that actually fit their skills.
The platform combines AI-assisted legitimacy analysis with personalized internship recommendations to reduce the time students spend searching through unreliable job posts.

---

# Project Summary

"InternTrust" is a web platform built for CS students at Integral University to discover internship opportunities they can actually trust and that actually fit them. Students create a lightweight profile (skills, experience level, preferences), and can browse a feed of internship postings sourced from two places: real postings seeded by you for the demo, and postings manually submitted by other users. Every posting gets an AI-generated first-pass legitimacy score (flagging red flags like no verifiable company presence, upfront payment requests, vague descriptions, or too-good-to-be-true promises), with the option for users to manually flag/verify postings as a future enhancement. Listings are also ranked/filtered by fit against the student's profile, so instead of scrolling through noisy WhatsApp groups and random sites, students see a curated, trust-scored, personally relevant list. V1.0 will be a fully deployed, working full-stack product (frontend + backend + AI scoring + live URL) — narrowly scoped to CS students at your university for a tight, believable demo, but designed so it could expand to other domains and colleges later. Success on Day 10 means a live, polished, publicly accessible product where a real student could sign up, build a profile, submit or browse postings, and see AI-scored, relevance-ranked results — with no glaring bugs during a live demo.

---

# Problem Statement

Students often find internships through:

- WhatsApp Groups
- Telegram Channels
- LinkedIn Posts
- Random Job Portals

These sources frequently contain:

- Scam internships
- Fake companies
- Upfront payment requests
- Poorly described roles
- Outdated opportunities
- Irrelevant postings

Students waste significant time verifying whether an internship is genuine.

---

# Proposed Solution

InternTrust allows students to:

- Create a personalized profile
- Select skills and interests
- Browse internship opportunities
- Submit internship postings
- Receive AI-generated legitimacy scores
- View internship recommendations ranked by profile relevance

The AI identifies common warning signs such as:

- Missing company information
- Unrealistic promises
- Upfront payment requests
- Vague job descriptions
- Suspicious posting patterns

---

# Technology Stack

## Frontend

- React
- Vite
- Tailwind CSS

## Backend

- Node.js
- Express.js

## Database

- MongoDB Atlas

## Authentication

- JWT Authentication

## AI

- Gemini API

## Deployment

- Vercel
- Render
- MongoDB Atlas

---

# V1.0 Scope

### Included

- User Authentication
- Student Profiles
- Internship Feed
- Internship Submission
- AI Legitimacy Analysis
- Personalized Ranking
- Search & Filtering
- Responsive UI
- Live Deployment

---

### Excluded

- Company Dashboards
- Payment Features
- Email Notifications
- Admin Analytics
- Community Verification
- Resume Builder
- Mobile Application

---

# Day 10 Success Criteria

A live production-ready application where users can:

- Register and login
- Build their profile
- Browse internships
- Submit internship opportunities
- View AI trust scores
- Receive relevance-ranked recommendations

The application should be fully deployed and suitable for a live demo.

---

# Deliverables Generated

✅ Product Requirements Document (PRD)
✅ Implementation Blueprint (Days 2–10)
✅ Project Pitch Deck

---

# Key Learnings

- Product discovery is more valuable than immediately writing code.
- Clearly defining MVP boundaries prevents scope creep.
- AI should solve a real user problem rather than being added for novelty.
- Sprint planning simplifies execution over multiple days.
- A strong PRD significantly reduces ambiguity during development.

---
