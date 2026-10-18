<h1 align="center">Hi, I'm Carl Janzell 👋</h1>

<p align="center">
  <b>Full-Stack Software Engineer</b> · I build systems people depend on.
</p>

<p align="center">
  <a href="https://darkify19.github.io/carl-janzell-portfolio/"><img src="https://img.shields.io/badge/Portfolio-030014?style=for-the-badge&logo=astro&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/carl-janzell-764399179/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:carl.oropesa11@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

I build the backbone of a university's HR operations — a constellation of integrated **Laravel** applications serving **4,000+ personnel** at the University of the Philippines Los Baños, exchanging data over **Apache Kafka** and replacing the paper-based processes behind time, leave, performance reviews, and government-compliance forms. My through-line isn't a framework, though: I've also shipped a full **Ruby on Rails 8 + GraphQL** API with a **Vue + Vuex** client, plus the **AI agent infrastructure** that helps a small team move like a big one.

<table>
<tr>
<td align="center"><b>4,000+</b><br/><sub>personnel served</sub></td>
<td align="center"><b>661</b><br/><sub>production deploys of my code,<br/>8 Apr to 1 Oct 2026</sub></td>
<td align="center"><b>8</b><br/><sub>production systems</sub></td>
<td align="center"><b>2</b><br/><sub>full stacks — Laravel & Rails</sub></td>
</tr>
</table>

## 🚀 Featured Projects

**UPLB-TKS — Timekeeping System** · *Lead developer · primary author*
The backbone of timekeeping for 4,000+ UPLB personnel — DTR engine (biometric + manual merge, grace-period undertime), leave management serving as the ecosystem's canonical balance source over REST, a reusable approval-workflow state machine with per-transition audit logging, Kafka consumers with data-contract enforcement, and RBAC across 30+ models. Ships behind a real pipeline: **441 tagged production deploys** from 8 Apr to 24 Sep 2026, with AI-drafted, human-reviewed changelogs. Also carries Portal SSO, Google One Tap, Calendar-driven work-location tagging, and a guest/demo tenant that lets the system be shown to a room without exposing a real employee's record. Recent work: a push reminder to personnel still clocked in at shift end, and VL/SL/SPL balances computed from HR's imported leave workbook, with each person's Leave Card PDF a click away from the Personnel list.
> **Real production usage** *(180 days to 13 Oct 2026)*: **273,195** attendance punches logged, **79.4%** captured directly by the system rather than keyed in by a timekeeper — **96.8%** over the trailing 7 days; **1,586** active personnel in a trailing 30-day window; **1,138** personnel timing in on 13 Oct alone. Traffic, on a shorter 65-day window to the same date: **293,334** page views and **18,406** logins, **921** unique users on an average working day, and **264** concurrent users at the 8 AM clock-in rush on 13 Oct.
`PHP 8.2` `Laravel 12` `Filament 3` `Livewire 3` `MySQL` `Apache Kafka` `PHPUnit 11`

**PerporManTask — Performance Management (IPCR)** · *Lead developer · primary author*
A performance-management service deliberately carved out of the timekeeping monolith into its own app, sharing data over Kafka. Semestral rating periods, weighted targets validated to 100%, UP SPMS-compliant PDFs, and a production **human-in-the-loop AI pipeline** that clusters exported task logs into draft reviews with dry-run preview. **685** people signed in between 23 Jul and 14 Oct 2026.
`Laravel 12` `Filament 5` `Kafka` `MySQL` `Tailwind CSS 4` `PHPUnit 11`

**UPLB Kiosk — Offline-First Attendance Terminal** · *Lead developer · primary author*
Shared walk-up terminals for personnel without a desk — the channel behind **22.8%** of all punches in the 180 days to 13 Oct 2026, and more than a third of the punches from 1 to 13 Oct. Offline-first punching with local storage and replay, a device token mirrored across cookie and localStorage so one kiosk stays one row, and cooldown/rescan suppression against double punches.
`PHP 8.2` `Laravel 12` `Filament 4` `Livewire` `Tailwind CSS 4` `Vite 7`

**UPLB Payroll Control System** · *Core contributor · holiday-pay entitlement + delivery pipeline*
An audit-first payroll app — integer-centavo computation, effective-dated authorities, segregation of duties, immutable hashed register snapshots — that names its own go-live gates rather than implying sign-off it doesn't have. I own the holiday-pay entitlement vertical (effective-dated authority, resolver returning a verdict value object, policies, Filament resource) and the delivery pipeline.
`Laravel 13` `Filament 5` `PostgreSQL` `Livewire` `GitHub Actions`

**DAME UPLB — Department Website + CMS** · *Lead developer*
Public site and admin CMS on the newest stack — faculty profiles, academic programs, research areas, and news. Slug-routed public profiles, a post/category CMS with soft deletes, and a Filament 5 admin using delegated Form/Table/Infolist schema classes.
`PHP 8.3` `Laravel 13` `Filament 5` `Livewire 4` `PostgreSQL` `Pest 4`

**UPLB HR Ecosystem — Shared Systems** · *Core contributor · 4 shared team repos*
Largest single contributor to **SALN e-filing** — Kafka consumer layer with transactional staging, UUID standardization, and coordinate-mapped PDF generation onto official government forms. Plus a bulk employee-number importer and submission-window controls in the HR system-of-record.
`Laravel 11` `Filament 3` `PostgreSQL` `Kafka` `FPDI/FPDF` `Vue 3`

**samyang — Dating App** · *Solo, full-stack (public source)*
Range beyond Laravel: a [Rails 8 GraphQL API](https://github.com/Darkify19/samyang-back) and a [Vue 2 + Vuex SPA](https://github.com/Darkify19/samyang-front) with Apollo, Cloudinary uploads, swipe/match mechanics, and an admin panel.
`Ruby on Rails 8` `GraphQL` `Vue 2` `Vuex` `Apollo`

**filament-page-builder — Filament Plugin** · *Author and maintainer (open source, MIT)*
A drag-and-drop page builder I maintain for the Filament community, listed in the [official Filament plugin directory](https://filamentphp.com/plugins/carl-janzell-page-builder). You lay a page out on a canvas and it saves to the same JSON column the form editor writes, so neither surface owns the content. One Composer command installs the right release for Filament 3, 4 or 5, and it runs the page editor on the DAME website. [Source](https://github.com/Darkify19/filament-page-builder) · [Docs](https://darkify19.github.io/filament-page-builder/) · [Packagist](https://packagist.org/packages/carljanzell/filament-page-builder)
`Laravel` `Filament 3–5` `Livewire` `Alpine.js` `Pest`

**filament-insights — Filament Plugin** · *Author and maintainer (open source, MIT)*
Admin-built stats and chart dashboards on any Filament resource, with no data-source classes: each dashboard reads the resource's own table query, so a chart counts exactly the records its viewer could see in that table. One codebase supports Filament 3, 4 and 5, with version floors set past known security advisories, a Pest suite on a Testbench panel run in CI, and a GitHub release cut for every tag. [Source](https://github.com/Darkify19/filament-insights) · [Packagist](https://packagist.org/packages/carljanzell/filament-insights)
`Laravel` `Filament 3–5` `Livewire` `anime.js` `Pest`

## 🤖 AI-Native Engineering

I don't just use AI coding tools — I build the infrastructure that makes them effective, treating AI agents as team members that need onboarding docs:

- **Agent skill libraries** — YAML-triggered deep-dives and DRY catalogues of reusable traits/services, so agents work accurately in each codebase
- **Executable specifications** — self-contained spec docs a fresh agent can run, with explicit "do not invent" guardrails
- **AI features in production** — an IPCR drafting flow and an AI changelog generator, both behind human-review gates and guarded by tests

## 🛠️ Tech Stack

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)
![Livewire](https://img.shields.io/badge/Livewire-4E56A6?style=flat&logo=livewire&logoColor=white)
![Ruby on Rails](https://img.shields.io/badge/Rails-CC0000?style=flat&logo=rubyonrails&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-BC52EE?style=flat&logo=astro&logoColor=white)
<br/>
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat&logo=rabbitmq&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white)
<br/>
![PHPUnit](https://img.shields.io/badge/PHPUnit-3776AB?style=flat&logo=php&logoColor=white)
![Pest](https://img.shields.io/badge/Pest-6C5CE7?style=flat&logo=pest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**Depth:** RBAC (Shield + Spatie) · Approval workflows · PDF generation (DomPDF / FPDI) · PII encryption · Gov-compliance forms · Event-driven architecture

## 📫 Connect

- 🌌 **Portfolio:** [darkify19.github.io/carl-janzell-portfolio](https://darkify19.github.io/carl-janzell-portfolio/)
- 💼 **LinkedIn:** [carl-janzell](https://www.linkedin.com/in/carl-janzell-764399179/)
- ✉️ **Email:** carl.oropesa11@gmail.com
- 📍 Based in Calamba, Philippines · Full-Stack Developer (Senior ICT Assistant) at UPLB

<sub>Open to software-engineering roles where systems thinking, event-driven architecture, and an AI-native workflow matter more than any single framework.</sub>
