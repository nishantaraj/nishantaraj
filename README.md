<img src="Assets/Banners/github-banner.png" alt="Nishanta Raj. AI Product, Automation, Strategy" width="100%">

# Nishanta Raj

**Head of AI Product Automations & Strategy at Learn with Leaders** · Bhubaneswar, India

I design the operating system of an EdTech company: one trusted database for every program, books that read per program, payments that reconcile themselves, and reports the founders receive each morning without anyone building them.

---

## What I own

| Remit | What it means in practice |
|---|---|
| **Data and backend architecture** | One central database in place of a sheet per program. Incoming data lands first and is validated before it is trusted. Role-based access, consent and audit built in, not bolted on |
| **Financial streamlining and reporting** | Multi-currency books designed around programs, advance fees held as a liability until delivered, one program code shared by the books, the database and the reports |
| **Process design** | Taking an unwritten habit, writing the rule, building the tool, and getting people to use it |
| **Product** | Applications, custom checkout, an admin portal, a learner portal and LMS, an affiliate platform. Built with Lovable on React and Supabase |
| **Automation and AI** | Daily reports and staged reminders that run on their own. Lead agents that have to pass safety tests, a shadow run and a pilot before they send anything |

## How the organisation changed

| Before | After |
|---|---|
| A sheet per program, the same school spelled several ways | One database with explicit links between people, organisations, applications and payments |
| Payment links matched to students by hand | Checkout that carries a program code, a webhook, and a reconciliation job that flags what it cannot match |
| Finance reconciled program by program | One coded taxonomy across the books, the database and the reports |
| Reports built by hand | A daily founder snapshot and a weekly financial report that arrive on their own |
| A gap after a student paid | A learner portal and LMS reading from the same database |

The full picture is in [Operating model, before and after](https://github.com/nishantaraaj-prog/case-studies/blob/main/01-Organisation-Reshaped/Operating-Model-Before-And-After.md).

## Selected work

Write-ups live in [case-studies](https://github.com/nishantaraaj-prog/case-studies). The company's code, data and figures stay with the company, so each one covers the problem, the design and the trade-offs.

| Area | Read |
|---|---|
| Organisation | [Operating model, before and after](https://github.com/nishantaraaj-prog/case-studies/blob/main/01-Organisation-Reshaped/Operating-Model-Before-And-After.md) |
| Data and backend | [Unified data architecture](https://github.com/nishantaraaj-prog/case-studies/blob/main/02-Data-And-Backend/Unified-Data-Architecture.md) · [Backend design principles](https://github.com/nishantaraaj-prog/case-studies/blob/main/02-Data-And-Backend/Backend-Design-Principles.md) |
| Finance | [Financial streamlining and reporting](https://github.com/nishantaraaj-prog/case-studies/blob/main/03-Finance/Financial-Streamlining-And-Reporting.md) · [Programme code convention](https://github.com/nishantaraaj-prog/case-studies/blob/main/03-Finance/Programme-Code-Convention.md) |
| Product | [Application-to-payment journey](https://github.com/nishantaraaj-prog/case-studies/blob/main/04-Product/Application-To-Payment-Journey.md) · [LMS and portals](https://github.com/nishantaraaj-prog/case-studies/blob/main/04-Product/LMS-And-Portals.md) · [Lovable build portfolio](https://github.com/nishantaraaj-prog/case-studies/blob/main/04-Product/Lovable-Build-Portfolio.md) |
| Automation and AI | [AI lead agents and reporting](https://github.com/nishantaraaj-prog/case-studies/blob/main/05-Automation-And-AI/AI-Lead-Agents-And-Reporting.md) · [Daily automations with Apps Script](https://github.com/nishantaraaj-prog/case-studies/blob/main/05-Automation-And-AI/Daily-Automations-With-Apps-Script.md) |
| Process design | [Building processes from scratch](https://github.com/nishantaraaj-prog/case-studies/blob/main/06-Process-Design/Building-Processes-From-Scratch.md) |

## Runnable code

Original code with invented data, written from scratch to show the patterns. None of it is the company's implementation.

| Repository | What it shows |
|---|---|
| [supabase-backend-patterns](https://github.com/nishantaraaj-prog/supabase-backend-patterns) | Landing layer, money in minor units, consent, time-limited grants and row-level security, with tests that run on real Postgres |
| [programme-finance-reporting](https://github.com/nishantaraaj-prog/programme-finance-reporting) | Programme-coded profit and loss with deferred revenue and multiple currencies |
| [payment-reconciliation-template](https://github.com/nishantaraaj-prog/payment-reconciliation-template) | Matching payments to applications, safe to re-run |
| [apps-script-daily-ops-toolkit](https://github.com/nishantaraaj-prog/apps-script-daily-ops-toolkit) | Daily snapshot, staged reminders, duplicate-safe CSV import |

## How I work

1. Map the manual process end to end.
2. Get the data into one trusted place.
3. Put money through it with identifiers that survive.
4. Make the reports read from it.
5. Automate the follow-up last, and measure each stage so it can be questioned.

I keep a person in the loop wherever a wrong call is expensive, and I would rather report a modest number I can defend than a big one I cannot.

## Toolkit

| Area | Tools |
|---|---|
| Product | Lovable, React, TypeScript, Tailwind |
| Data and backend | Supabase (Postgres, Edge Functions, row-level security) |
| Finance | Xero, multi-currency, tracking categories |
| Payments | Stripe, Razorpay |
| Email and messaging | Resend, WATI (WhatsApp) |
| Automation | n8n, Google Apps Script |
| AI | Claude, ChatGPT, Google AI Studio |
| Analysis | Python, SQL, Google Sheets |

## Earlier

At Excelerate I built internal tools that took most of the manual work out of an internship operation.

## Connect

[LinkedIn](https://www.linkedin.com/in/nishantaraj/)
