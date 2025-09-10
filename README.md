# 💰 AI-Powered Expense Tracker  

> Track your expenses, manage your budget, and get **AI-powered insights** to take control of your finances with intelligent automation.  

## 🚀 Overview  

This project is a **next-gen expense tracker** that combines **AI, modern UI/UX, and real-time analytics** to help users make smarter financial decisions.  
From automated expense categorization to personalized insights, this app transforms how you track and understand your money.  

---

## ✨ Features  

### 🤖 AI-Powered Intelligence  
- **Smart Categorization** – AI auto-suggests categories based on descriptions.  
- **Financial Insights** – Personalized recommendations and spending analysis.  
- **Interactive AI Chat** – Ask for explanations and financial advice.  

### 💼 Core Functionality  
- **Expense Tracking** – Add, edit, delete expenses.  
- **Real-time Charts** – Beautiful data visualizations with Chart.js.  
- **Statistics Dashboard** – Clear breakdown of spending patterns.  
- **Expense History** – Full transaction history with search & filters.  

### 🎨 Modern UI/UX  
- **Light & Dark Mode** – Smooth theme switching.  
- **Fully Responsive** – Optimized for all devices.  
- **Beautiful Animations** – Fluid interactions with gradients & blur effects.  

### 🔐 Authentication & Security  
- **Multiple Login Options** – Google, GitHub, Facebook, or email/password.  
- **Clerk Authentication** – Secure sessions with user profiles.  
- **Personalized Dashboards** – Each user sees their own data.  

---

## 🛠️ Tech Stack  

**Frontend**  
- [Next.js 15](https://nextjs.org/) – App Router, React 19 features  
- [React 19](https://react.dev/) – Concurrent rendering  
- [TypeScript](https://www.typescriptlang.org/) – Type safety  
- [Tailwind CSS](https://tailwindcss.com/) – Modern utility-first styling  
- [Chart.js](https://www.chartjs.org/) – Charts & graphs  

**Backend & Database**  
- [Neon](https://neon.tech/) – Serverless PostgreSQL  
- [Prisma](https://www.prisma.io/) – Type-safe ORM  
- Next.js **Server Actions** – Direct server-side execution  

**AI & Authentication**  
- [OpenRouter](https://openrouter.ai/) – AI API without credit cards  
- [Clerk](https://clerk.com/) – Authentication & user management  
- OpenAI-compatible APIs – AI categorization & insights  

---

## ⚙️ Installation  

Clone the repo:  
```bash
git clone https://github.com/your-username/ai-expense-tracker.git
cd ai-expense-tracker

Install dependencies:
npm install

Set up environment variables in .env:
DATABASE_URL="your-neon-database-url"
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your-clerk-key"
CLERK_SECRET_KEY="your-clerk-secret"
OPENROUTER_API_KEY="your-openrouter-key"

Run Prisma migrations:
npx prisma generate
npx prisma db push

Start the development server:
npm run dev

📊 Roadmap
 Add budget planning & savings goals
 Export reports (PDF/CSV)
 Multi-currency support
 Mobile app version (React Native)

🙌 Contributing
Contributions are welcome!
Fork the repo
Create a feature branch (git checkout -b feature-name)
Commit changes (git commit -m "Add feature")
Push to branch and open a PR

📜 License
This project is licensed under the MIT License.

👩‍💻 Author
Created with ❤️ by Archita Jain
