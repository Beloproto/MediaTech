# 📰 Tech Blockchain Africa — News Blog

Welcome to the **TechBlockchainAfr** blog — a tech-focused news site sharing insights, events, and updates from across the Francophone tech ecosystem.

This project is built with **Next.js (App Router)**, styled with **Tailwind CSS**, and hosted on **Vercel**.

> 🧪 Currently under development — stay tuned for more!

---

## 🚀 Live Preview

🌐 [blog.techblockchainafr.tech](https://blog.techblockchainafr.tech/)

---

## 🗂 Project Structure

```bash
.
├── app
│   ├── actions
│   │   └── newsletter.ts        # Handles newsletter signup logic
│   ├── blog
│   │   ├── loading.tsx          # Blog section loader
│   │   └── page.tsx             # Blog landing page
│   ├── equipe
│   │   ├── loading.tsx          # Team page loader
│   │   └── page.tsx             # Team info page
│   ├── evenements
│   │   ├── loading.tsx          # Events page loader
│   │   ├── page.tsx             # Events list or overview
│   │   ├── layout.tsx           # Layout specific to events section
│   │   └── globals.css          # Section-specific styles
│   ├── layout.tsx               # Global app layout
│   └── page.tsx                 # Root landing page (homepage)
│
├── components                   # Reusable UI components
├── hooks                        # Custom React hooks
├── lib                          # Utility functions, API clients, etc.
├── public                       # Static assets (logo, OG images, etc.)
├── scripts                      # Automation or setup scripts
├── styles                       # Global CSS or Tailwind config
│
├── README.md
├── components.json              # Component registry (for visual builder?)
├── next.config.mjs              # Next.js config
├── package.json
└── .gitignore
