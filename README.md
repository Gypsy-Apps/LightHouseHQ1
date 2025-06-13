# LighthouseHQ

LighthouseHQ is a streamlined web-based admin platform designed to help property managers, campground operators, and small teams track tasks, properties, expenses, and documents—all in one place.

## ✨ Features

- 🔐 Supabase Authentication (email/password)
- ✅ Task management (with RLS protection)
- 🏘 Property tracking
- 💰 Expense logging
- 📄 Document uploads (coming soon)
- 📊 Reports dashboard
- 🧠 Built using React + Supabase + Bolt.new

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/LighthouseHQ.git
   cd LighthouseHQ
Install dependencies:

bash
Copy
Edit
npm install
Set up .env:

Create a .env file in the root with your Supabase credentials:

env
Copy
Edit
VITE_SUPABASE_URL=your-supabase-url
VITE_SUPABASE_ANON_KEY=your-anon-key
Run locally:

bash
Copy
Edit
npm run dev
🛡 Security
This project uses Row-Level Security (RLS) in Supabase. Only authenticated users can view or add tasks related to their own user ID.

🧙 Built With
React

Supabase

Bolt.new

TailwindCSS

📂 Project Structure
css
Copy
Edit
src/
├── components/    → Shared UI and logic components (Auth, Task Dialog, etc.)
├── pages/         → Main views (Dashboard, Tasks, Reports)
├── supabaseClient.js
├── App.jsx
└── index.css
📦 Deployment
Can be deployed to Vercel, Netlify, or your own hosting.

Built with 💡 by Joyce Berkner

yaml
Copy
Edit

---

### 🛠 `.gitignore`

Here’s a recommended `.gitignore` so you don’t accidentally push sensitive or bloated files:

```gitignore
# Environment variables
.env

# Build output
dist/
.vite/
*.log

# Dependencies
node_modules/

# System files
.DS_Store

