
# Fanvue Automation Platform — AI Creator Management

Fanvue Automation is an internal AI-powered content management system designed to generate, review, schedule, and manage visual content for a virtual creator persona named **Lila**.

The platform is built as a scalable SaaS-style dashboard with future integration for AI generation pipelines (RunPod / ComfyUI) and automation workflows.

---

## 🚀 Project Overview

This system is designed to handle the full lifecycle of AI-generated content:

* Image generation (future AI pipeline integration)
* Video generation (multi-scene workflows via RunPod API)
* Content review and approval system
* Scheduling and content planning
* Character consistency management
* Media library organization

---

## 🧠 Core Concept

Instead of a simple generation tool, Fanvue Automation acts as a:

> **Central operating system for AI content creation and distribution**

It allows the operator to:

* Generate content
* Review outputs
* Maintain character consistency
* Schedule posts
* Prepare content for external platforms

---

## 🏗️ Tech Stack

* Next.js 15 (App Router)
* TypeScript
* Tailwind CSS
* Firebase Authentication
* Firestore Database
* Firebase Storage
* Vercel (Deployment)

---

## 📁 Project Structure

```
src/
├── app/
│   ├── (dashboard)/
│   │   ├── dashboard/
│   │   ├── content/
│   │   ├── review/
│   │   ├── scheduling/
│   │   ├── character/
│   │   └── settings/
│   ├── login/
│   └── layout.tsx
│
├── components/
├── services/
├── firebase/
├── hooks/
├── types/
└── lib/
```

---

## 🔥 Core Features

### 📊 Dashboard

* Overview of system activity
* Generated images/videos stats
* Pending reviews
* Scheduled content
* Active generation jobs

### 🎨 Content Generation (Future Integration)

* Image generation interface
* Video generation with multi-scene prompts
* RunPod API integration (planned)

### 🗂 Content Library

* Media storage (images/videos)
* Filtering by status (pending, approved, rejected)
* Organized asset management

### 🧾 Review System

* Approve / Reject content
* Regenerate workflows
* Content validation before publishing

### 📅 Scheduling System

* Weekly content calendar
* Post scheduling logic
* Campaign planning (daily + weekly content flow)

### 🧍 Character Manager

* Maintain consistent AI persona (Lila)
* Reference images
* Style and identity settings
* Location and outfit consistency

---

## 🔐 Supabase Architecture

### Authentication

* Admin-only login system
* Protected routes

### Supabase Collections

* users
* characters
* images
* videos
* review_queue
* scheduled_posts
* generation_jobs
* settings

### Storage Buckets

* reference-images
* generated-images
* generated-videos
* character-assets

---

## ⚙️ Architecture Philosophy

* Service-layer-based Firebase access
* Strict separation of UI and business logic
* Scalable modular folder structure
* Future-proof for AI pipeline integration
* Internal tool (not public SaaS)

---

## 🔄 Future Integration Plan

Phase 1:

* UI + mock data dashboard system

Phase 2:

* RunPod API integration (image/video generation)

Phase 3:

* Automation system (posting + scheduling)

---

## 🧪 Current Status

* Project architecture completed
* Next.js 15 structure implemented
* Firebase setup defined
* UI pages under development
* AI pipeline integration pending

---

## 📌 Notes

This project is currently in **UI + system design phase**.
All generation features are mocked until backend AI pipeline integration is completed.

---

## 👤 Purpose

Built as an internal AI content production system for managing a virtual creator workflow efficiently and at scale.
