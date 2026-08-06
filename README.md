<h1 align="center">Hi, I'm Carl Janzell 👋</h1>

<p align="center">
  <b>Full-Stack Software Engineer</b> · Production-grade software, whatever the stack.
</p>

<p align="center">
  <a href="https://darkify19.github.io/carl-janzell-portfolio/"><img src="https://img.shields.io/badge/Portfolio-030014?style=for-the-badge&logo=astro&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:carl.oropesa11@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

I build **government-grade HR systems** for the University of the Philippines Los Baños — a constellation of integrated Laravel applications exchanging data over **Apache Kafka**. My through-line isn't a framework, though: I've also shipped a full **Ruby on Rails 8 + GraphQL** API with a **Vue + Vuex** client, plus the **AI agent infrastructure** that helps a small team move like a big one.

Every claim below traces to commit history.

<table>
<tr>
<td align="center"><b>5,021</b><br/><sub>commits shipped</sub></td>
<td align="center"><b>7</b><br/><sub>production repos</sub></td>
<td align="center"><b>500+</b><br/><sub>tagged deploys</sub></td>
<td align="center"><b>346</b><br/><sub>active days</sub></td>
</tr>
</table>

## 🚀 Featured Projects

**[UPLB-TKS — Timekeeping System](https://github.com/orgs/University-of-the-Philippines-Los-Banos/teams/dic)** · *Lead developer · 3,528 / 3,623 commits (97%)*
University-wide timekeeping platform — DTR engine (biometric + manual merge, grace-period undertime, IP-validated clock-in), leave management serving as the ecosystem's canonical balance source over REST, a reusable approval-workflow state machine with per-transition audit logging, Kafka consumers with data-contract enforcement, and RBAC across 30+ models. **531 deploy & version tags** with AI-drafted, human-reviewed changelogs.
`PHP 8.2` `Laravel 11` `Filament 3` `Livewire 3` `MySQL` `Apache Kafka` `PHPUnit 11`

**PerporManTask — Performance Management (IPCR)** · *Sole author · 192 / 192 commits*
Performance-management service deliberately extracted from the timekeeping monolith into its own app, sharing data over Kafka. Semestral rating periods, weighted targets validated to 100%, UP SPMS-compliant PDFs, and a production **human-in-the-loop AI pipeline** that clusters exported task logs into draft reviews with dry-run preview.
`Laravel 12` `Filament 5` `Kafka` `MySQL` `Tailwind CSS 4` `PHPUnit 11`

**DAME UPLB — Department Website + CMS** · *Lead developer · 286 / 293 commits (98%)*
Public site and admin CMS on the newest stack — faculty profiles, academic programs, research areas, and news. Slug-routed public profiles, a post/category CMS with soft deletes, and a Filament 5 admin using delegated Form/Table/Infolist schema classes.
`PHP 8.3` `Laravel 13` `Filament 5` `Livewire 4` `PostgreSQL` `Pest 4`

**UPLB HR Ecosystem — Shared Systems** · *Contributor · 1,005 commits across 4 team repos*
Largest single contributor to **SALN e-filing** (620 / 1,330) — Kafka consumer layer with transactional staging, UUID standardization, and coordinate-mapped PDF generation onto official government forms. Plus a bulk employee-number importer and submission-window controls in the HR system-of-record.
`Laravel 11` `Filament 3` `PostgreSQL` `Kafka` `FPDI/FPDF` `Vue 3`

**samyang — Dating App** · *Solo, full-stack*
Range beyond Laravel: a [Rails 8 GraphQL API](https://github.com/Darkify19/samyang-back) and a [Vue 2 + Vuex SPA](https://github.com/Darkify19/samyang-front) with Apollo, Cloudinary uploads, swipe/match mechanics, and an admin panel.
`Ruby on Rails 8` `GraphQL` `Vue 2` `Vuex` `Apollo`

## 🤖 AI-Native Engineering

I don't just use AI coding tools — I build the infrastructure that makes them effective, treating AI agents as team members that need onboarding docs:

- **190+ agent skill files** — YAML-triggered deep-dives and DRY catalogues of reusable traits/services, so agents work accurately in each codebase
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

- ✉️ **Email:** carl.oropesa11@gmail.com
- 🏢 Currently a dev at [DIC](https://github.com/orgs/University-of-the-Philippines-Los-Banos/teams/dic), UPLB

