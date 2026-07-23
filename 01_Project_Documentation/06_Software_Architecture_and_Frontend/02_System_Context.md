# Professional Portfolio Website

## Document Information

| Item | Details |
|------|---------|
| **Project** | Professional Portfolio Website |
| **Phase** | Phase 6 – Software Architecture & Frontend |
| **Document Title** | System Context |
| **Document Number** | 02 |
| **Version** | 1.0 |
| **Status** | Draft |
| **Prepared By** | Emmanuel Chukwuka Origbo |
| **Last Updated** | 23 July 2026 |

---

# 1. Introduction

The System Context document defines the operational environment of the Professional Portfolio Website.

It identifies the users, external services, supporting platforms, and organisational boundaries that interact with the application. It establishes what is considered part of the system, what lies outside the system, and how information flows between them.

Understanding the system context ensures that architectural decisions are made with a clear understanding of the application's environment and dependencies.

---

# 2. Purpose

The purpose of this document is to:

- Define the system boundary.
- Identify all user groups.
- Identify external systems and services.
- Describe interactions between the application and external platforms.
- Provide a high-level operational view of the website.
- Support architectural planning and future integration.

---

# 3. System Overview

The Professional Portfolio Website is a responsive web application that showcases Emmanuel Chukwuka Origbo's professional profile, software engineering projects, data analytics portfolio, certifications, technical skills, education, and consulting services.

The website serves as a central professional platform for recruiters, clients, collaborators, employers, and academic stakeholders.

Initially, the website will operate as a static frontend application hosted on GitHub Pages, with the architecture designed to support future backend services without requiring major redesign.

---

# 4. System Boundary

The system boundary defines which elements belong to the application and which exist outside its control.

## Inside the System

The following are managed directly by the application:

- Homepage
- About section
- Professional profile
- Skills section
- Portfolio projects
- Project detail pages
- Certifications
- Education
- Contact page
- Navigation
- Responsive layouts
- User interface components
- Static project data
- Website assets
- Configuration files

---

## Outside the System

The following are external services or platforms:

- GitHub
- GitHub Pages
- LinkedIn
- Email provider
- Web browser
- Search engines
- Future backend APIs
- Analytics platforms
- Social media platforms

These systems interact with the website but remain independently managed.

---

# 5. Primary Users

The website is intended for several categories of users.

## Recruiters

Recruiters evaluate professional experience, projects, skills, and qualifications.

Typical objectives:

- Review portfolio.
- Download résumé.
- Evaluate technical capability.
- Initiate contact.

---

## Employers

Potential employers assess suitability for employment opportunities.

Typical objectives:

- Review experience.
- Examine completed projects.
- Assess technical competencies.
- Contact the candidate.

---

## Consulting Clients

Business owners and organisations evaluate consulting capabilities.

Typical objectives:

- Review services.
- Examine case studies.
- Assess technical expertise.
- Request consultation.

---

## Academic Stakeholders

Lecturers, supervisors, and academic reviewers may evaluate the portfolio.

Typical objectives:

- Review academic projects.
- Assess software engineering practices.
- Examine documentation standards.

---

## Professional Network

Professional colleagues and collaborators may explore the website to understand current work, technical interests, and opportunities for collaboration.

---

# 6. External Systems

The website interacts with several external systems.

## GitHub

Purpose:

- Repository hosting.
- Source code.
- Project documentation.

Interaction:

Users may navigate from the portfolio website to GitHub repositories.

---

## GitHub Pages

Purpose:

- Website hosting.

Interaction:

Delivers the production version of the website.

---

## LinkedIn

Purpose:

Professional networking.

Interaction:

Visitors may navigate to the LinkedIn profile.

---

## Email Service

Purpose:

Professional communication.

Interaction:

Visitors may initiate contact using the published email address or contact form (future enhancement).

---

## Search Engines

Purpose:

Website discovery.

Interaction:

Index public pages to improve visibility.

---

# 7. External Dependencies

The application depends on:

- React
- Vite
- Tailwind CSS
- React Router
- npm packages
- GitHub
- GitHub Pages
- Modern web browsers

These dependencies should be monitored and updated regularly.

---

# 8. Information Flow

Information primarily flows in one direction.

Examples include:

- User requests website pages.
- Website delivers content.
- User opens project details.
- User follows external links.
- User downloads résumé.
- User initiates contact.

Future versions may support bidirectional communication through backend services and APIs.

---

# 9. Assumptions

The architecture assumes:

- Users have internet access.
- Modern browsers are available.
- JavaScript is enabled.
- GitHub Pages remains available.
- External platforms remain operational.

Future backend integrations should minimise disruption if assumptions change.

---

# 10. Constraints

Current constraints include:

- Static frontend architecture.
- No backend database.
- No user authentication.
- No server-side rendering.
- No persistent user accounts.

These constraints are intentional for Version 1 and may be revisited in future releases.

---

# 11. Relationship to Other Documents

This document supports:

- Software Architecture
- Application Architecture
- Frontend Architecture
- Routing Architecture
- Data Flow Architecture
- Build and Deployment

It provides the environmental context for the overall system architecture.

---

# 12. Revision History

| Version | Date | Description |
|---------|------|-------------|
| 1.0 | 23 July 2026 | Initial creation of the System Context document. |

---

# 13. Summary

The System Context document defines the operational environment of the Professional Portfolio Website by identifying its users, external systems, dependencies, assumptions, and system boundaries. It provides the high-level perspective required to ensure that architectural decisions remain aligned with the application's intended operating environment and future growth.