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
<td align="center"><b>795</b><br/><sub>tagged prod deploys</sub></td>
<td align="center"><b>8</b><br/><sub>production systems</sub></td>
<td align="center"><b>2</b><br/><sub>full stacks — Laravel & Rails</sub></td>
</tr>
</table>

## 🚀 Featured Projects

**UPLB-TKS — Timekeeping System** · *Lead developer · primary author*
The backbone of timekeeping for 4,000+ UPLB personnel — DTR engine (biometric + manual merge, grace-period undertime, IP-validated clock-in), leave management serving as the ecosystem's canonical balance source over REST, a reusable approval-workflow state machine with per-transition audit logging, Kafka consumers with data-contract enforcement, and RBAC across 30+ models. Ships behind a real pipeline: **431 tagged production deploys** with AI-drafted, human-reviewed changelogs. Also carries Portal SSO, Google One Tap, Calendar-driven work-location tagging, and a guest/demo tenant that lets the system be shown to a room without exposing a real employee's record.
> **Real production usage** *(180 days to 22 Sep 2026)*: **224,490** attendance punches logged, **79.9%** captured directly by the system rather than keyed in by a timekeeper — **96.1%** over the trailing 7 days; **1,486** active personnel in a trailing 30-day window; **567** personnel timing in on an average working day. Traffic, on a shorter 44-day window to the same date: **183,765** page views and **10,369** logins, peaking at **238** concurrent users at the 8 AM clock-in rush.
`PHP 8.2` `Laravel 11` `Filament 3` `Livewire 3` `MySQL` `Apache Kafka` `PHPUnit 11`

**PerporManTask — Performance Management (IPCR)** · *Sole author*
A performance-management service deliberately carved out of the timekeeping monolith into its own app, sharing data over Kafka. Semestral rating periods, weighted targets validated to 100%, UP SPMS-compliant PDFs, and a production **human-in-the-loop AI pipeline** that clusters exported task logs into draft reviews with dry-run preview.
`Laravel 12` `Filament 5` `Kafka` `MySQL` `Tailwind CSS 4` `PHPUnit 11`

**UPLB Kiosk — Offline-First Attendance Terminal** · *Lead developer · primary author*
Shared walk-up terminals for personnel without a desk — the channel behind **20.1%** of all punches in the 180 days to 22 Sep 2026, and 1,200+ a day by late September. Offline-first punching with local storage and replay, a device token mirrored across cookie and localStorage so one kiosk stays one row, cooldown/rescan suppression against double punches, and CIDR-aware network validation resolved by range specificity.
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
Range beyond Laravel, and the one project you can read end to end: a [Rails 8 GraphQL API](https://github.com/Darkify19/samyang-back) and a [Vue 2 + Vuex SPA](https://github.com/Darkify19/samyang-front) with Apollo, Cloudinary uploads, swipe/match mechanics, and an admin panel.
`Ruby on Rails 8` `GraphQL` `Vue 2` `Vuex` `Apollo`

**filament-page-builder — Filament Plugin** · *Author (public source)*
A drag-and-drop page builder for [Filament](https://filamentphp.com): nested layout canvas, document outline, token style inspector, inline text editing, undo/redo — persisting to the same JSON column the form editor writes, so neither surface owns the content. [Source](https://github.com/carljanzell/filament-page-builder) · [Docs](https://carljanzell.github.io/filament-page-builder/)
`Laravel` `Filament` `Alpine.js` `Tailwind CSS`

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
- 📍 Based in Los Baños, Philippines · Full-Stack Developer (Senior ICT Assistant) at UPLB

<sub>Open to software-engineering roles where systems thinking, event-driven architecture, and an AI-native workflow matter more than any single framework.</sub>
