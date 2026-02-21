# Website Builds Portfolio (WordPress • Booking • Forms • Analytics)

A structured portfolio of two WordPress website builds, focused on:
- clean site structure and page management
- booking / enquiry workflows
- plugin integrations (forms, appointments, memberships, analytics)
- practical reporting using built-in dashboards and analytics summaries

This repository keeps **screenshots and supporting documentation** organised per website for easy review.

---

## Contents
- [Repo layout](#repo-layout)
- [Sites](#sites)
  - [nagmaenfield.co.uk](#nagmaenfieldcouk)
  - [richchotel.com](#richchotelcom)
- [Common build themes](#common-build-themes)
- [Notes](#notes)

---

## Repo layout

```text
docs/                         → shared notes/checklists (security, SEO, analytics)
nagmaenfield.co.uk/           → site-specific README + assets
richchotel.com/               → site-specific README + assets
```
---

Each site folder contains:

README.md → full overview, features, integrations, screenshot index

assets/ → screenshot evidence (filenames preserved)

assets/docs/ → optional space for exports/config notes (if added)

Sites
nagmaenfield.co.uk

Focus: business website management, page structure, plugin ecosystem, appointment scheduling, membership roles, and recruitment/application workflow.

Open: nagmaenfield.co.uk/README.md

richchotel.com

Focus: hotel booking workflow (room setup → pricing → checkout rules), payment configuration, customer email integration, and website analytics reporting.

Open: richchotel.com/README.md

Common build themes

Across both sites, the work demonstrates:

Information architecture: clear page structure + consistent navigation

Operational workflows: bookings/appointments, enquiries, and user actions

Plugin governance: selecting, installing, and managing plugins for specific outcomes

Analytics & performance monitoring: traffic/engagement reporting and site insight tracking

Delivery documentation: screenshot evidence + structured write-ups for reproducibility

Notes

Screenshots are stored with original filenames to keep traceability.

No credentials, keys, or sensitive settings should be added to this repo.

Where exports are included, place them inside each site’s assets/docs/ folder.


---

```md
# Shared Documentation

This folder holds reusable documentation that applies across the website builds in this repository.

## Recommended files
- `security-maintenance-checklist.md`  
  Practical checklist for updates, backups, plugin review, access control, and monitoring.

- `analytics-seo-notes.md`  
  Notes on analytics reporting, baseline KPIs, and SEO hygiene (indexing, metadata, performance checks).

## What NOT to store here
- passwords, API keys, SMTP credentials
- payment wallet numbers, private details, secret tokens
- full database exports that contain real customer data
