# SimpleStatus

## 📖 Project Description

**SimpleStatus** is a lightweight SaaS for creating public status pages.
Designed for indie devs, small startups, and teams that want to keep users informed without the cost and complexity of tools like Statuspage.io.

* Runs automated **HTTP/TCP health checks** on services.
* Opens **incidents automatically** when checks fail, or lets you post them manually.
* Provides a clean, branded **public page** to show uptime history.
* Sends **notifications** (Slack, email, webhook).

---

## 🚀 Features

* **Status Pages** – Create branded pages for your services.
* **Health Checks** – Automated HTTP/TCP checks with configurable intervals.
* **Incidents** – Auto-opened or manual posting.
* **Notifications** – Slack, email (SES), generic webhooks.
* **Multi-Tenant** – Each org gets isolated status pages and services.
* **Public Pages** – Share uptime and incident history with customers.
* **Affordable** – Transparent pricing with free tier.

---

## 🛠️ Tech Stack

* **Backend:** Go (Gin)
* **Frontend:** React + Tailwind
* **Database:** Postgres
* **Infrastructure:** Docker, Terraform, AWS (ECS, RDS, ALB, SES)
* **Payments:** Stripe

---

## 📦 Getting Started (Local Dev)

### Prerequisites

* Go 1.22+
* Node.js 20+
* Docker & Docker Compose
* Postgres

### Clone & Setup

```bash
git clone https://github.com/yourusername/simplestatus.git
cd simplestatus
```

### Backend

```bash
cd services/api
go run main.go
```

### Frontend

```bash
cd apps/dashboard
npm install
npm run dev
```

Visit: `http://localhost:3000`

---



---

