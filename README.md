# Medha Sarothi (মেধা সারথি)

**Education management for Bangladesh: one workspace for schools, coaching centers, independent teachers and students.**

🌐 **Live:** [www.medhasarothi.com](https://www.medhasarothi.com)

> 🔒 This repository is a public overview only. The application's source code is kept private for the security of the schools and students who use it.

---

## What it does

| For organizations and teachers | For students |
|---|---|
| Academic years, classes, batches and NCTB subjects, set up through a guided wizard | A personal portal for attendance, fees, results and progress |
| Student admission by invitation link, join request or student ID | Join several teachers or organizations from one account |
| Teacher logins with roles, permissions and class/batch/subject scope | An AI doubt solver whose answers follow the NCTB books |
| Attendance, exams, results with merit positions, and reports | Notices and notifications from every teacher in one place |
| Fees, discounts and payment tracking | |
| A question bank by NCTB 2026 chapter and topic, with images and math formulas | |
| A question-paper builder in Bangladesh board format (MCQ and creative), exported to PDF | |
| SMS and notices to students and guardians | |

The interface is fully bilingual (English / বাংলা) and works on mobile.

## Engineering highlights

- **Multi-tenant architecture.** Organizations and independent teachers each get an isolated workspace, and one teacher can belong to an organization while also running a private space.
- **Security by design.** PostgreSQL row-level security on every tenant table, server-side HttpOnly cookie sessions and per-request scoped database clients. Permissions are enforced in the database, not just in the UI.
- **AI layer.** Separate provider, prompt-routing and credit-control modules for question generation and student doubt solving.
- **Scale of the codebase.** 560+ commits, 140+ database migrations and 160+ test files, built and maintained by a single developer.

## Tech stack

`TypeScript` · `React` · `TanStack Start` · `TanStack Query` · `Supabase (PostgreSQL, Auth, Storage, RLS)` · `Drizzle` · `Tailwind CSS` · `Radix UI` · `i18next` · `KaTeX` · `jsPDF` · `Zod` · `Vercel`

## Author

**Saurov Kumer**, founder and sole developer · [LinkedIn](https://www.linkedin.com/in/saurov-kumer/) · [GitHub](https://github.com/SaurovKumer)

For a demo or a walkthrough of the code, contact me on LinkedIn.
