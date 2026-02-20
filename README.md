# Hi there, I'm Shamim Azad! 👋

### 🚀 Sr. Backend Developer | Python, Django, DRF Specialist

Backend developer with 3.5+ years of experience building and optimizing high-performance web applications with Python, Django, and Django REST Framework. Proven expertise in designing scalable APIs, enhancing database performance, and deploying on cloud platforms like AWS. Proficient in leveraging task queues, caching, and containerized deployments to improve system speed and reliability. Committed to writing clean, maintainable code and engineering robust systems for high-traffic production environments.

---

## 💡 Technical Skills

| Category | Key Skills |
| :--- | :--- |
| **Languages** | Python, JavaScript, TypeScript, Java, Solidity |
| **Frameworks** | Django, Django REST Framework (DRF), FastAPI, React |
| **Databases** | PostgreSQL, MySQL, MongoDB, SQLite, SQL Server |
| **Cloud & DevOps** | AWS (EC2, ECS, S3, RDS, SES, Lightsail, Amplify), Docker, Nginx, CI/CD Pipelines |
| **Caching & CDN** | Redis, BunnyCDN, Cloudflare |
| **Payment & Messaging APIs** | Stripe, Paypal, SSLCommerz, Twilio, BulkSMSBD |
| **Push Notifications** | Firebase Cloud Messaging (FCM) |
| **Testing & Documentation** | Pytest, Swagger/OpenAPI (drf-spectacular) |
| **Frontend** | React, Tailwind CSS, Shadcn |
| **Tools** | Git, GitHub, Figma, Asana, SelectPdf |

---

## 💼 Professional Experience

### 🏢 Senior Backend Developer - Interactive Cares (Sep 2024 - Present)
📍 Adabor, Dhaka, Bangladesh

#### 📚 LMS Platform
- Architected and developed a scalable **LMS platform** from scratch using **Django, DRF, and PostgreSQL**, implementing a modular design with apps for `courses`, `classrooms`, `affiliates`, `payments`, `investment`, `notifier`, `offline`, and `users` to support future growth and feature expansion.
- Designed a custom **RBAC system** with a 4-tier permission hierarchy and action-based authorization, enabling fine-grained access control across all API endpoints.
- Developed a **dynamic pricing engine** with stackable discounts (affiliate, coupon, early bird, B2B, mobile app) and real-time commission tracking for the affiliate program.
- Built a **multi-tenant notification system** supporting email (**AWS SES** via django-anymail), SMS (**Twilio, BulkSMSBD**), and **Firebase Cloud Messaging** push notifications with event-driven triggers.
- Integrated **Stripe and SSLCommerz** payment gateways with webhook handling for secure online payments, subscription management, and automated receipt generation.
- Implemented asynchronous task processing using **Celery and Redis** (with celery-singleton and django-celery-results) for background jobs including notifications, reports, and scheduled operations.
- Built an **investment module** to manage and track financial investments within the platform.
- Generated dynamic **QR codes** for course enrollments and event check-ins using the `qrcode` library.
- Migrated the production database from **MySQL to PostgreSQL** with zero downtime and complete data consistency.
- Enhanced API performance through **query optimization, Redis caching, and CDN integration** (BunnyCDN / Cloudflare), reducing average response time by **30%**.
- Implemented a **CI/CD pipeline** for backend services by containerizing with **Docker** and leveraging **AWS ECS** (Fargate / EC2) for scalable deployments, ensuring environment consistency.

#### 📊 CRM Platform
- Architected and developed a full-featured **CRM backend** from scratch using **Django, DRF, and PostgreSQL**, with a clean service-repository architecture across modular apps.
- Built a comprehensive **lead management system** with full CRUD, CSV bulk upload, follow-up scheduling, call logging, notes, and complete lead history tracking.
- Designed and implemented a **hierarchical RBAC system** with role-based permissions, field-level access control, permission inheritance, and custom decorators/mixins for fine-grained API authorization.
- Developed a **purchase and commission module** with agent commission tracking, configurable commission slabs, and purchase history management.
- Built **KPI and finance dashboards** with APIs for conversion analytics, agent performance, source performance, revenue summaries, due aging reports, collection forecasts, and discount usage tracking.
- Implemented a **unified reporting system** with daily activity, team performance, attendance summary, source revenue, and cross-department reports, all with **CSV/Excel export** capabilities.
- Developed a **campaign management module** for marketing campaigns and a **notification system** for in-app alerts with real-time updates.
- Containerized the entire stack with **Docker** using a **blue-green deployment** strategy via **Nginx** load balancer on **AWS EC2** for zero-downtime production releases.
- Configured **Celery workers and Celery Beat** with Redis as the message broker for background task processing and periodic scheduled jobs.
- Integrated **AWS S3** for media storage, **AWS SES** for transactional emails, **BulkSMSBD** for SMS notifications, and **Cloudflare Turnstile** for bot protection.

#### 🧒 Kidz Venture Platform
- Developed a **children's educational platform backend** using **Django, DRF, and PostgreSQL**, with modular apps for `courses`, `users`, `notifier`, and shared `generics`/`utils`.
- Integrated **Stripe and SSLCommerz** payment gateways for course purchases and subscription billing with webhook-based payment verification.
- Built a **notification service** supporting email (**AWS SES**), SMS (**Twilio, BulkSMSBD**), and **Firebase push notifications** for parent/student engagement.
- Implemented **Celery with Redis** for async task processing including enrollment confirmations, scheduled reminders, and report generation.
- Containerized with **Docker** and deployed on **AWS** with CI/CD pipelines via **GitHub Actions** for automated staging and production deployments.

#### 🤖 AI Chatbot for LMS Platform
- Built an **AI-powered chatbot** using **Django and the OpenAI API** with **Server-Sent Events (SSE)** for real-time token-by-token streaming responses.
- Designed a **data scraping and storage system** for LMS content (courses, workshops, locations, FAQs, success stories) using a flexible model with JSON metadata support.
- Implemented **context-aware AI responses** by dynamically fetching and injecting scraped platform data (online/offline courses, pricing, workshop details) into OpenAI prompts for accurate, data-driven conversations.

### 🏢 Software Engineer - Khan Soft Limited (Sep 2022 - Aug 2024)
📍 West Dhanmondi, Dhaka, Bangladesh

- Architected and developed a **blockchain-based cryptocurrency mining platform** using Django and Python, enabling users to mine Bitcoin and other cryptocurrencies through a scalable cloud mining infrastructure.
- Integrated **multi-chain blockchain support** (Bitcoin, Ethereum, BSC, Polygon) by connecting to full nodes, monitoring on-chain transactions, and synchronizing blockchain data with the backend.
- Implemented **cryptocurrency wallet management** with HD wallet generation, multi-signature support, and encrypted private key storage using standard cryptographic libraries.
- Built a **transaction processing engine** optimized for gas efficiency and scalability, featuring batching, automatic retries, and confirmation tracking.
- Developed real-time **on-chain event listeners** using Celery workers to track smart contract events and mining rewards, automatically updating user balances and mining statistics.
- Created **RESTful APIs** for mining stats, user portfolios, transaction history, and worker management, secured with **JWT authentication** and rate limiting.
- Implemented a **transaction monitoring and alerting system** to detect suspicious activities, large withdrawals, and potential security anomalies, sending automated alerts for administrative review.

---

## 🎓 Education

**Bachelor of Science in Computer Science and Engineering**
Bangladesh University of Business and Technology (BUBT) — Mirpur-2, Dhaka, Bangladesh
Graduated: 2022

---

## 📫 Let's Connect

| Platform | Link |
| :--- | :--- |
| **Email** | [shamimazad565@gmail.com](mailto:shamimazad565@gmail.com) |
| **LinkedIn** | [linkedin.com/in/shamim565](https://linkedin.com/in/shamim565) |
| **GitHub** | [github.com/shamim565](https://github.com/shamim565) |

---
*"Code is like poetry—it should be elegant, efficient, and impactful."* 💡
