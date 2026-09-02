# Health-Tracker

## Project Overview

Purpose of this Health-Tracker is to

- Personally keep track of your personal health
- Get AI-powered health recommendations
- Track your health improvements
- Monitor your meals intake
- better yourself

## Features
- Interactive Plant — a visual plant that grows and reflects your real life health progress
- AI Health Assistant — powered by Google Gemini, gives personalized advice or answer health related questions
- Calorie & Meal Tracking — log daily meals and monitor calorie intake
- Habit Tracking — track drinking habits and other lifestyle factors
- Health Dashboard — visualize your progress with charts and trends
- Weight Management — get recommendations for maintaining, losing, or managing weight
- Health Profile — store medical history, family conditions, and blood test results

## Tech Stack
- Frontend/Backend — Nuxt 4, Vue, TypeScript
- Database — PostgreSQL (Supabase)
- ORM — Prisma
- AI — Google Gemini API
- Authentication — Clerk
- Styling — Tailwind CSS
- Deployment — Vercel
evelopment 


## Setup Development Enviorment

Make sure that you have Visual Studio Code, git, Node.js, npm or pnpm installed. 
Git Bash as your terminal works too.

### Installation

Make pnpm as your packet manager
```bash
npm install -g pnpm
```

Install the repo
```bash
git clone https://github.com/bienbun/Health-Tracker.git
cd Health-Tracker
```

Install dependencies
```bash
pnpm install
```

Set up environment variables
```bash
cp .env.example .env
```

Set up the database
```bash
pnpm prisma migrate dev
```

Run the app
```bash
pnpm run dev
```

## Environment Variables

Create a `.env` file in the root of your project and add the following:

```
DATABASE_URL=your_supabase_postgresql_url
GEMINI_API_KEY=your_gemini_api_key
CLERK_SECRET_KEY=your_clerk_secret_key
CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
NUXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

Hope you enjoy the webapp :D