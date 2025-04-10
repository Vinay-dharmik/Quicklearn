
# 📚 Quick Learner

An intelligent short-course platform built with **Next.js 13**, **MongoDB**, and **TailwindCSS**.  
It tracks users' progress on YouTube-based courses, provides interactive tests, and auto-generates certificates upon successful completion.

---

## 🚀 Features

- 🎥 YouTube video tracking per course
- 🧠 Test-based course completion
- 🧾 Certificate generation as downloadable PDF
- 🔐 User authentication (Login/Signup)
- 💾 MongoDB database for courses, users, and progress
- 🌐 Fully routed (no 404 errors), production-ready
- 📱 Mobile responsive design
- 🔒 Free HTTPS deployment with Vercel

---

## 🛠️ Tech Stack

| Frontend     | Backend        | Database     | Deployment           |
|--------------|----------------|--------------|-----------------------|
| Next.js 13+  | Node.js API    | MongoDB Atlas| Vercel (SSL + Domain)|
| TailwindCSS  | JWT Auth       | Mongoose     |                       |

---

## 🧪 Local Setup Instructions

1. **Clone the Repo**
   ```bash
   git clone https://github.com/your-username/quick-learner.git
   cd quick-learner
   ```

2. **Install Dependencies**
   ```bash
   # With npm
   npm install

   # Or with pnpm (recommended)
   pnpm install
   ```

3. **Add Environment Variables**
   Create a `.env.local` file:
   ```
   MONGODB_URI=your_mongodb_connection_string
   NEXT_PUBLIC_YOUTUBE_API_KEY=your_youtube_api_key
   JWT_SECRET=your_random_jwt_secret
   ```

4. **Run the Dev Server**
   ```bash
   npm run dev
   # or
   pnpm dev
   ```

5. Open your browser at `http://localhost:3000`

---

## 📁 Folder Structure

```
.
├── app/                # Frontend pages
│   ├── layout.tsx
│   └── page.tsx
├── pages/api/          # API routes (Next.js)
├── lib/                # MongoDB connection and utilities
├── public/             # Static files and certificates
├── styles/             # Tailwind and globals
└── README.md
```

---

## 📜 License

MIT License

---

## 🤝 Contributions

Pull requests are welcome! For major changes, open an issue first to discuss what you’d like to change or improve.
