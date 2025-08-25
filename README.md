# Job Portal Application 🌟

A modern **Job Portal Application** built with **React (Vite)**, **Tailwind CSS**, **Supabase** (database & auth), **Clerk** (authentication), and **Shadcn UI** (beautiful UI components).  

Frontend

## 🚀 Features
- ✅ User Authentication with Clerk  
- ✅ Supabase backend (Jobs, Applications, Companies)  
- ✅ Job Listing, Apply, Save, and Manage Jobs  
- ✅ Responsive UI with Tailwind CSS & Shadcn UI  
- ✅ Protected Routes (only logged-in users can apply/post jobs)  
- ✅ Reusable components (Cards, Buttons, Drawers,Textarea etc.)  

---

## ⚙️ Tech Stack
- **Frontend:** React + Vite, Tailwind CSS, Shadcn UI  
- **Backend / Database:** Supabase  
- **Authentication:** Clerk   

---

## 📦 Installation

Clone the repo:

```bash
git clone https://github.com/your-username/job-portal.git
cd job-portal
````

Install dependencies:

```bash
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root and add:

```env
VITE_SUPABASE_URL=your-supabase-url
VITE_SUPABASE_ANON_KEY=your-supabase-anon-key
VITE_CLERK_PUBLISHABLE_KEY=your-clerk-publishable-key
```

---

## 🖥️ Run Development Server

```bash
npm run dev
```

The app should now be running on:
👉 `http://localhost:5173`

---

## 📁 Project Structure

```
.
├── public/                # Static assets
├── src/
│   ├── api/               # API service files (Supabase fetch)
│   ├── components/        # Reusable components (UI, forms, cards, etc.)
│   ├── data/              # JSON seed data
│   ├── hooks/             # Custom React hooks
│   ├── layouts/           # App layout wrapper
│   ├── lib/               # Utility functions
│   ├── pages/             # All pages (Landing, Jobs, Onboarding, etc.)
│   ├── utils/             # Supabase client setup
│   ├── App.jsx            # Root component
│   └── main.jsx           # App entry point
├── tailwind.config.js     # Tailwind CSS config
├── vite.config.js         # Vite config
└── package.json
```


