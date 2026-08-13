# Supreme Scholar System Engine

Educational mission & level progression system.

**Levels:** Foundation → Mortal → Scholar → Adept → Master → Transcendent → Supreme

## Tech Stack
- Next.js 15 (App Router)
- Supabase (Auth + Database)
- Tailwind CSS + Framer Motion
- Vercel ready

## Setup Steps

### 1. Create Supabase Project
1. Go to [supabase.com](https://supabase.com) → New Project
2. Copy **Project URL** and **anon public key**

### 2. Run Database Schema
1. In Supabase Dashboard → SQL Editor
2. Paste the entire content of `supabase-schema.sql`
3. Run it

### 3. Local Setup
```bash
cp .env.example .env.local
# Edit .env.local and put your Supabase URL + anon key

npm install
npm run dev
```

### 4. Deploy to Vercel
1. Push this repo to GitHub
2. Import in Vercel
3. Add Environment Variables:
   - `NEXT_PUBLIC_SUPABASE_URL`
   - `NEXT_PUBLIC_SUPABASE_ANON_KEY`
4. Deploy

### 5. Auth Settings (Supabase)
- Authentication → Providers → Email (enable)
- Optionally enable Google etc.

## Features
- Public multi-user auth (anyone can sign up)
- Left side live Level + XP progress panel
- Educational Missions / Exams / Steps / Deadlines
- Difficulty based XP (Easy 25 · Medium 60 · Hard 120 · Boss 250)
- Beautiful dark gold theme with glassmorphism
