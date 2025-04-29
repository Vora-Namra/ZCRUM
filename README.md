# 🧩 Jira-like Project Management Tool

A robust and modern project management platform inspired by Jira — built with **Next.js**, **Clerk**, **ShadCN**, **NeonDB**, **Prisma**, and **PostgreSQL**.

## 🚀 Features

### 🛠️ Organization & User Management
- Admins can **create and manage organizations**
- Admins can **invite members** to join the organization via **email invitation**
- Members can **accept invites** and collaborate within the organization

### 📁 Project & Task Management
- Admins can **create multiple projects** under a single organization
- Projects include **task/issue creation**, tracking, and collaboration
- Tasks can be **assigned to members**
- Members can **update task progress** (e.g., Todo → In Progress → Done)
- Admins can **monitor real-time updates**

### 🌀 Sprint Support
- Admins can **create and manage sprints** to organize work into structured cycles
- Sprint progress can be tracked via the task board

### 💡 Tech Stack

| Tech        | Description                              |
|-------------|------------------------------------------|
| Next.js     | React framework for full-stack app       |
| Clerk       | Authentication and user management       |
| ShadCN UI   | UI components built with Tailwind CSS     |
| Prisma      | Type-safe database ORM                   |
| NeonDB      | Serverless Postgres hosting              |
| PostgreSQL  | Relational database                      |

## 🧪 Local Development

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

npm i 

### Make sure to create a `.env` file with following variables -


DATABASE_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

npm run dev

```