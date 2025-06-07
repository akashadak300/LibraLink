# 📚 LibraLink – University Library Management System

A full-stack, production-grade University Library Management System with a responsive Admin Panel, automated email workflows, real-time analytics, and a modern UI/UX. Built for scalability, performance, and a seamless library experience.

---

## 🚀 Features

- 🔐 **Authentication & RBAC** – Secure login, signup, and role-based access control using NextAuth
- 📖 **Library Dashboard** – Advanced filtering, search, pagination, and dynamic book details
- 📥 **Borrowing Workflow** – Email reminders, borrow receipts in PDF, due-date tracking
- 📬 **Automated Emails** – Onboarding, inactivity emails, and notifications via Resend
- 📊 **Admin Analytics** – Insights into users, books, and borrow activity
- 🧾 **Profile Management** – View borrow history, manage account, download receipts
- 🛠 **Admin Tools** – Book management, user control, and role updates with audit logs
- ⚡ **Optimized Backend** – Redis-based caching, rate-limiting, and DDoS protection

---

## 🛠 Tech Stack

| Frontend        | Backend           | Infrastructure & Utilities    |
|-----------------|-------------------|-------------------------------|
| Next.js         | PostgreSQL        | Upstash Redis (caching, queue) |
| TypeScript      | Drizzle ORM       | ImageKit (media CDN)         |
| Tailwind CSS    | NextAuth (Auth)   | Resend (email service)       |

---

## 📦 Getting Started

### ✅ Prerequisites

- Node.js & npm
- Git
- PostgreSQL (via Neon or local)
- Resend, Upstash, and ImageKit accounts

### ⚙️ Installation

```bash
# 1. Clone the repository
git clone https://github.com/akashadak300/LibraLink.git
cd libralink

# 2. Install dependencies
npm install

# 3. Configure environment variables
cp .env.example .env
# Fill in actual keys for DATABASE_URL, IMAGEKIT, UPSTASH, RESEND, etc.

# 4. Run the development server
npm run dev

# Visit the app at
http://localhost:3000
