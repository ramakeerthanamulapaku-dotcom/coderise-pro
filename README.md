# CodeRise AI 🚀

> **Master coding. Build a career. One hour a day.**

CodeRise AI is an AI-powered learning platform built for college students who are struggling with coding and digital skills. Instead of boring lectures or confusing YouTube videos, CodeRise AI teaches through **AI-animated video lessons**, a **24/7 AI mentor**, daily assignments, and real-world projects — all structured into just **one focused hour per day**.

---

## 🌍 The Problem We're Solving

Millions of college students across India and beyond are:

- Failing programming labs they don't understand
- Wasting hours on YouTube tutorials that lead nowhere
- Graduating without a single real project to show recruiters
- Unable to afford ₹30,000–₹50,000 bootcamps or coaching institutes

**CodeRise AI changes that — starting at just ₹299/month.**

---

## ✨ What Makes CodeRise AI Different

| Feature | Traditional Courses | CodeRise AI |
|---|---|---|
| Lectures | Human-recorded, boring | AI-animated, visual |
| Mentor | Unavailable / expensive | AI mentor, 24/7, free |
| Pace | Fixed for everyone | Adapts to you |
| Projects | Optional extras | Built into every course |
| Price | ₹10,000–₹50,000 | Starting ₹0 |

---

## 🎯 Core Features

### 🎬 AI-Animated Video Lessons
Every concept is taught through **AI-generated animated videos** — no slides, no recordings, no boring lectures. Visual, practical, and built around real-world examples that actually stick.

### 🤖 24/7 AI Mentor — "Rize"
Stuck at 2 AM before an exam? Rize is always online. Ask anything in plain language and get an explanation tailored to how *you* think — with code examples, analogies, and patient follow-ups until you get it.

### 📋 Daily Assignments + Instant Feedback
After every lesson, you get a small assignment. Submit it and receive **line-by-line AI code review** in seconds — what works, what to fix, and how to improve.

### 🛠️ Real Project Building
Every month ends with a real, deployable project. Build a portfolio website, a calculator app, or an AI chatbot — things you can actually show to recruiters.

### ⏱️ 1-Hour Daily Structure
Designed for busy college students:

```
0:00 – 0:15  →  Watch AI-animated lesson
0:15 – 0:30  →  Practice code in-browser
0:30 – 0:50  →  Complete daily assignment
0:50 – 1:00  →  Review progress + plan tomorrow
```

### 📜 Verified Certificates
Earn verifiable certificates you can share on LinkedIn and add to your résumé — backed by real project work, not just watching videos.

---

## 💰 Pricing

| Plan | Monthly | Yearly | Best For |
|---|---|---|---|
| **Explorer** | ₹0 | ₹0 | Try before committing |
| **Pro Student** | ₹299 | ₹179/mo | Most students — full access |
| **Career Elite** | ₹599 | ₹359/mo | Job hunting & internships |

> 🎓 `.edu` email gets an additional **20% off**  
> 💳 UPI, cards & EMI accepted  
> 🏫 Group plans available for colleges and NGOs  
> ✅ All paid plans include a **7-day free trial** — no credit card needed

---

## 🗂️ Course Catalogue (Sample)

- **HTML, CSS & JavaScript — Zero to Functional** *(42 AI lessons · 3 weeks · Beginner)*
- **Python for Absolute Beginners** *(38 AI lessons · 4 weeks · Beginner)*
- **Introduction to AI & Machine Learning** *(50 AI lessons · 5 weeks · Intermediate)*
- **React & Frontend Development** *(Coming soon)*
- **Data Structures & Algorithms for Interviews** *(Coming soon)*
- **Full-Stack Web Development** *(Coming soon)*

---

## 🧰 Tech Stack

```
Frontend      →  HTML5, CSS3, Vanilla JS  (landing page)
Platform      →  React + Next.js          (app)
AI Mentor     →  Claude API (Anthropic)
Video Engine  →  AI-generated animations  (proprietary pipeline)
Auth          →  Clerk / Firebase Auth
Database      →  PostgreSQL + Supabase
Payments      →  Razorpay (UPI, cards, EMI)
Hosting       →  Vercel + AWS
```

---

## 📁 Project Structure

```
coderise-ai/
├── public/
│   └── assets/             # Images, icons, fonts
├── src/
│   ├── components/         # Reusable UI components
│   ├── pages/              # Next.js pages
│   ├── features/
│   │   ├── courses/        # Course player & progress
│   │   ├── mentor/         # AI mentor chat interface
│   │   ├── assignments/    # Assignment submission & review
│   │   └── projects/       # Project builder & portfolio
│   ├── api/                # API routes
│   ├── lib/                # Utility functions
│   └── styles/             # Global styles & theme
├── landing/
│   └── coderise-pro.html   # Standalone landing page
├── docs/                   # Documentation
├── .env.example
├── package.json
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js v18+
- npm or yarn
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/your-org/coderise-ai.git

# Navigate into the project
cd coderise-ai

# Install dependencies
npm install

# Copy environment variables
cp .env.example .env.local

# Fill in your environment variables
# (See Environment Variables section below)

# Run the development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## ⚙️ Environment Variables

Create a `.env.local` file with the following:

```env
# Anthropic (AI Mentor)
ANTHROPIC_API_KEY=your_anthropic_api_key

# Database
DATABASE_URL=your_supabase_postgres_url
SUPABASE_ANON_KEY=your_supabase_anon_key

# Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
CLERK_SECRET_KEY=your_clerk_secret

# Payments
RAZORPAY_KEY_ID=your_razorpay_key
RAZORPAY_KEY_SECRET=your_razorpay_secret

# App
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

---

## 🗺️ Roadmap

- [x] Landing page with pricing
- [x] AI mentor chat (Rize)
- [x] Course player with AI-animated videos
- [x] Assignment submission & AI feedback
- [ ] In-browser code editor (Monaco)
- [ ] Mobile app (React Native)
- [ ] Offline video downloads
- [ ] GitHub portfolio auto-builder
- [ ] AI mock interview module
- [ ] Multi-language support (Hindi, Telugu, Tamil...)
- [ ] College group & institution dashboard

---

## 🤝 Contributing

We welcome contributions from the community!

```bash
# Fork the repo and create a feature branch
git checkout -b feature/your-feature-name

# Make your changes, then commit
git commit -m "feat: add your feature description"

# Push and open a Pull Request
git push origin feature/your-feature-name
```

Please read our [CONTRIBUTING.md](./CONTRIBUTING.md) before submitting a PR.

---

## 📊 Impact Goals

> CodeRise AI is built with a social mission — not just a business one.

- 🎯 **1 million** students reached by 2027
- 🌍 Available in **10+ Indian languages** by 2026
- 🏫 Partner with **500+ colleges** for group access
- 💼 Help **100,000 students** land their first job or internship
- 🆓 Keep a **genuinely useful free tier** — always

---

## 📬 Contact & Support

| Channel | Link |
|---|---|
| Website | [www.coderise.ai](https://www.coderise.ai) |
| Email | team@coderise.ai |
| Twitter / X | [@CodeRiseAI](https://twitter.com/CodeRiseAI) |
| LinkedIn | [CodeRise AI](https://linkedin.com/company/coderise-ai) |
| Support | support@coderise.ai |

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.

---

<div align="center">

**Built with ❤️ for every student who was told coding is too hard.**

*CodeRise AI — Stop struggling with code. Start building.*

</div>
