# Muhamad Rizky Setiawan

Full-stack developer from Bogor, Indonesia. I build web apps, CLI tools,
and small AI agents — usually with Laravel, Next.js, or Python, depending
on what the job actually needs.

## About me

I work mostly on the web side of things: product backends, dashboards,
and the occasional developer tool. I care about clean structure, small
features that ship, and not over-engineering the boring parts. When I'm
not shipping product code I'm poking at agent frameworks and writing
small utilities that save me an hour a week.

## Tech stack

**Backend**
- PHP — Laravel 11/12/13, Breeze
- TypeScript / Node.js — NestJS 11, Express 5
- Python — CLIs, small scripts, automation

**Frontend**
- Next.js 16 (App Router) + React 19 + TypeScript
- Tailwind CSS v4, Radix UI, TanStack Query / Table
- Framer Motion, Alpine.js, Blade

**Database & data**
- MySQL, PostgreSQL, SQLite
- Prisma 8 (RC), Eloquent

**Auth & integrations**
- Laravel Breeze, Passport (Google OAuth / JWT), Argon2
- Resend (transactional email), Upstash Redis (rate limiting)
- Google Gemini API

**Tooling**
- pnpm workspaces, Vite, Turborepo
- Pest, PHPUnit, Jest
- GitHub Actions, Docker, Git

## Featured projects

### Avunel — a multi-agent AI assistant
Python CLI for orchestrating AI agents with skills, plugins, scheduled
jobs, and conversation memory. Cross-platform (bash, fish, PowerShell).
[github.com/mhmdrzkyystiawnn/avunel-agent](https://github.com/mhmdrzkyystiawnn/avunel-agent)

### Faktura — invoicing monorepo
A NestJS 11 + Prisma 8 API and a Next.js 16 web client, wired together
in a pnpm monorepo. Argon2 + Google OAuth (Passport) for auth, Radix
UI + TanStack on the front, Resend for transactional email. Built to
ship serverless on Neon.
[github.com/mhmdrzkyystiawnn/faktura](https://github.com/mhmdrzkyystiawnn/faktura)

### Library Connect — school library booking system
A Laravel 12 app for a single school: students browse the catalog and
book books, an admin approves bookings, tracks loans, and records
late-return fines. Stock is enforced server-side; admin can set a
different approved duration than the one the student asked for.
[github.com/mhmdrzkyystiawnn/library-connect](https://github.com/mhmdrzkyystiawnn/library-connect)

### Portfolio site (this site)
Next.js 16 with App Router, all content lives in JSON files at build
time, so adding a project is a single commit. The contact form uses
Resend and Upstash Redis for per-IP rate limiting.
[github.com/mhmdrzkyystiawnn/portofolio](https://github.com/mhmdrzkyystiawnn/portofolio)

### PKL Jurnal Generator
A Python tool that reads today's git log + diff across multiple
projects, sends the relevant code to Gemini, and appends a daily
summary to a weekly journal file. Skips re-generation on the same
day to save API calls, with a `--force` flag when needed.
[github.com/mhmdrzkyystiawnn/tools-ai-recap-work-summary](https://github.com/mhmdrzkyystiawnn/tools-ai-recap-work-summary)

### Cleaning Service — booking platform
Laravel 13 + Breeze web app for a cleaning service business: public
landing and catalog, customer-side booking flow, and an admin panel
for packages, bookings, and FAQ.
[github.com/mhmdrzkyystiawnn/cleaning-service](https://github.com/mhmdrzkyystiawnn/cleaning-service)

## Other work

I also work on internal / internship projects (facility management,
metering, patrol, etc.) — these are not public and are owned together
with the rest of the team, so I won't list them here.

## Contact

- GitHub: [@mhmdrzkyystiawnn](https://github.com/mhmdrzkyystiawnn)
- Location: Bogor, Indonesia
