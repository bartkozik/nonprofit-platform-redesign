# Nonprofit Platform Redesign

**Portfolio case study:** Frontend contributions to a private project. This repository contains a project overview only; implementation code, internal links and client data are not included.

## 📌 Project Overview

A platform helping nonprofit organizations manage their presence, fundraising activities and supporter-facing content. My work in 2026 focused on translating desktop and mobile designs into reusable React interfaces across organization dashboards, fundraising, help and blog sections.

## 👨‍💻 My Role

I contributed frontend implementation and refinement, working from Figma designs and incorporating code review feedback.

- Built responsive views for fundraising lists and creation flows, organization panels, help categories and articles, and blog content.
- Extended the shared UI layer with reusable component variants, tabs and chips instead of duplicating controls for each screen.
- Used common SCSS typography and layout mixins to keep new views consistent with the existing design system.
- Separated page composition, filtering, routing and presentation into focused components and hooks.
- Maintained Polish and English interface messages, including ICU placeholders and accessible labels.
- Implemented explicit empty states and reusable navigation helpers for different organization contexts.

## 🛠️ Tech Stack

- **React + TypeScript** — component development and typed view models
- **SCSS Modules** — component styles, shared mixins and responsive layouts
- **i18next + ICU messages** — localized interface copy
- **Figma** — desktop and mobile design references
- **Vite** — frontend build tooling

## 🧠 Selected Technical Decisions

### Shared components with clear responsibilities

Blog pages share a common grid and configurable content rather than separate, duplicated implementations. Filtering lives in a dedicated hook, while individual cards handle presentation. Fundraising views separate list, empty and creation states.

### Consistent design system implementation

Existing tabs, chips, typography and layout utilities provide a common foundation. I extended these patterns when needed and removed local styling that duplicated shared components.

### Localization within UI behavior

Search reuses normalization helpers for case and diacritics. Labels and dynamic messages remain in translation resources, including accessible descriptions for progress indicators.

## 🔍 What This Project Demonstrates

Design-to-code implementation, reusable React components, modern SCSS, responsive UI, internationalization and maintainable frontend structure.

---

[Back to my profile](https://github.com/bartkozik)
