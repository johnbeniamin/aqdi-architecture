# DilYDoc (formerly Aqdi / عقدي)

An Arabic-first B2C interactive contract generation platform. DilYDoc helps ordinary Arabic-speaking users generate legally sound contracts through a conversational wizard — no lawyer required.

## The Problem

Existing Arabic legal platforms target lawyers. Ordinary users who need a rental agreement, employment contract, or partnership agreement have no self-service option in Arabic. DilYDoc fills that gap.

## Architecture Highlights

- **Conversational Wizard UI** — guided question flow that builds a contract step by step
- **Clause Variant System** — a single clause stores multiple Arabic legal text variants depending on contract context
- **70+ Contract Taxonomy** — covering the most common civil and commercial contract types in Egyptian law
- **PostgreSQL/MySQL + JSONB Schema** — flexible storage for contract templates and user sessions
- **DomPDF Generation** — produces downloadable Arabic contracts as PDF
- **8 Software Services Contracts** — fully decomposed into the clause variant system (development, SaaS, maintenance/SLA, consulting, licensing, freelancer, web design, mobile app)

## Stack

PHP 8 · MySQL · Material Design (MDC Web) · DomPDF · Vanilla MVC

## Status

🟢 Deployed and live — [dilydoc.com](https://dilydoc.com)

## Author

John Beniamin — [dilycode.com](https://dilycode.com)
