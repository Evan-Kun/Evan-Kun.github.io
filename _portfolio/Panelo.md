---
title: "Panelo.ai – AI-Driven Panel-Drawing Management Platform"
excerpt: |
  End-to-end web platform that streamlines precast-engineering workflows.<br/>
  <img src="/images/panelo_dashboard.png" alt="Panelo dashboard preview">
collection: portfolio
date: 2025-04-24        # use the launch or demo date you prefer
link: "https://panelo.ai"   # optional: public URL or demo link
role: "Founder / Lead ML & Full-Stack Engineer"
---

### 🚀 Overview
**Panelo** is a secure, multi-tenant SaaS platform that automates the review, stamping, and document generation pipeline for precast panel drawings.

* **AI-powered metadata extraction** (↑ 90 % efficiency) using OCR + Transformer-based parsers.  
* **Automated PDF stamping & border-note insertion** with PyMuPDF and Laravel queues.  
* Fine-grained **role-based access control** for clients, engineers, and administrators.  

---

### 🛠️ Tech Stack

| Layer | Technologies |
|-------|--------------|
| **Frontend** | Laravel Blade, Livewire, Alpine JS, Tailwind CSS |
| **Backend**  | Laravel 10 (Jetstream), PHP 8.3, REST + GraphQL |
| **AI / ML**  | PyTorch OCR models, OpenAI GPT-4o for metadata QA |
| **Cloud**    | AWS S3 (file storage), EC2 + Ubuntu, RDS MySQL, CloudWatch, Cloudflare |
| **DevOps**   | Docker, GitHub Actions CI/CD, Terraform IaC, SSL & WAF hardening |

---

### 🌟 Key Features & Impact

* **Batch Upload & Instant Preview** – Engineers drag-and-drop multi-page PDFs; pages render in a resizable viewer with live form-filling.  
* **Stamp-All Workflow** – One-click stamping across hundreds of drawings, preventing overlap with dynamic whitespace detection.  
* **Credit-Based Billing** – Company-level token system with Stripe integration; supports free-tier onboarding.  
* **Audit-Ready Logs** – CloudTrail + Laravel Telescope for end-to-end traceability.  
* **>300 active drawings processed** during the pilot phase, cutting manual admin time by **~60 hours/month** for Actech International.

---

### 📸 Gallery
![Upload flow](/images/panelo_upload.png)
![Stamp wizard](/images/panelo_stamp.png)
![Credit dashboard](/images/panelo_credits.png)

---

### 🧩 My Contributions
1. **Architected** the domain-driven data model for projects, drawings, and versions.  
2. **Implemented** AI extraction & stamping micro-services (Python) and queued them via Laravel Horizon.  
3. **Hardened security**—migrated from leaked IAM keys to role-based access with enforced MFA.  
4. **Set up CI/CD pipeline** with GitHub Actions → Docker → EC2 blue-green deploy.  
5. **Led user testing** with three engineering teams, iterating UI/UX based on feedback.

---

> **Status:** Private beta with Actech International (Melbourne, AU).  
> Seeking partners in AEC and manufacturing sectors to expand the platform.
