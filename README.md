
An AI-powered scalable full-stack car marketplace.
Built with Next.js, Shadcn/UI, and Supabase, VehiQL enables users to search, list, and manage cars with advanced features like AI-powered search, secure authentication, and real-time data sync.

🔗 Live Demo: https://vehiqle.vercel.app/
Features

AI-powered car search using Google Gemini Flash for smart query handling.

Secure Authentication with Clerk (OAuth, email/password, and more).

Real-time data sync & file storage powered by Supabase.

Type-safe database interactions with Prisma ORM.

Advanced security layer via Arcjet.

Modern UI with Shadcn/UI + Tailwind CSS.

Scalable architecture, built for growth.
Tech Stack

Frontend: Next.js, React, Shadcn/UI, Tailwind CSS
Backend: Next.js API Routes, Supabase
Database: PostgreSQL (via Supabase + Prisma ORM)
Authentication: Clerk
Security: Arcjet
AI Integration: Google Gemini Flash

### Make sure to create a `.env` file with following variables -

```
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=

ARCJET_KEY=
```
