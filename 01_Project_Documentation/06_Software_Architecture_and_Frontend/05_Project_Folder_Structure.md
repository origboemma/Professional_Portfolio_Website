# Professional Portfolio Website

## Document Information

| Item | Details |
|------|---------|
| **Project** | Professional Portfolio Website |
| **Phase** | Phase 6 – Software Architecture & Frontend |
| **Document Title** | Project Folder Structure |
| **Document Number** | 05 |
| **Version** | 1.0 |
| **Status** | Draft |
| **Prepared By** | Emmanuel Chukwuka Origbo |
| **Last Updated** | 23 July 2026 |

---

# 1. Introduction

The Project Folder Structure defines the physical organisation of the Professional Portfolio Website.

A consistent directory structure improves maintainability, discoverability, scalability, and collaboration by ensuring that project files are organised logically and predictably.

This document establishes the directory conventions that will be followed throughout the implementation of the application.

---

# 2. Purpose

The purpose of this document is to:

- Define the project directory structure.
- Standardise file organisation.
- Separate concerns.
- Improve maintainability.
- Support scalability.
- Reduce duplication.
- Simplify onboarding for future contributors.

---

# 3. Folder Structure Principles

The project structure is based on the following principles:

- Separation of concerns.
- Modular organisation.
- Reusability.
- Predictability.
- Scalability.
- Simplicity.
- Consistency.

Every folder should have a clearly defined responsibility.

---

# 4. Root Directory Structure

The project root is organised as follows:

```text
Professional_Portfolio_Website/
│
├── .github/
├── public/
├── src/
├── docs/
├── scripts/
├── tests/
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── README.md
└── vite.config.js
```

---

# 5. Public Directory

The `public` directory contains static files served directly by the web server.

Typical contents include:

```text
public/
│
├── favicon/
├── images/
├── documents/
├── robots.txt
├── sitemap.xml
└── manifest.webmanifest
```

Examples:

- Résumé (PDF)
- Project documents
- Logos
- Open Graph images
- Favicons

---

# 6. Source Directory

The `src` directory contains the application source code.

```text
src/
│
├── assets/
├── components/
├── config/
├── contexts/
├── data/
├── hooks/
├── layouts/
├── pages/
├── routes/
├── services/
├── styles/
├── types/
├── utils/
├── App.jsx
├── main.jsx
└── index.css
```

Each subdirectory has a specific responsibility.

---

# 7. Directory Responsibilities

## assets/

Stores application assets imported into the React application.

Examples:

- Images
- Icons
- Fonts
- Illustrations
- Project screenshots

---

## components/

Contains reusable UI components.

Examples:

- Buttons
- Cards
- Navigation
- Footer
- Hero
- Timeline
- Skill Card
- Project Card

---

## config/

Contains application configuration.

Examples:

- Navigation configuration
- Social links
- Metadata
- Theme configuration
- Site settings

---

## contexts/

Contains React Context providers.

Examples:

- Theme context
- Future authentication context
- Global application state

---

## data/

Contains structured application data.

Examples:

- Projects
- Skills
- Certifications
- Experience
- Education

---

## hooks/

Contains reusable custom React hooks.

Examples:

- useTheme
- useScrollPosition
- useMediaQuery
- useLocalStorage

---

## layouts/

Contains reusable page layouts.

Examples:

- Main layout
- Page layout
- Project layout

---

## pages/

Contains top-level pages.

Examples:

- Home
- About
- Skills
- Projects
- Contact

Pages compose layouts and reusable components.

---

## routes/

Contains routing configuration.

Examples:

- Route definitions
- Protected routes (future)
- Route helpers

---

## services/

Contains service-layer logic.

Examples:

- API services
- Future CMS integration
- Analytics services

---

## styles/

Contains global styling resources.

Examples:

- Global CSS
- Tailwind customisations
- Variables
- Utility styles

---

## types/

Reserved for future TypeScript adoption.

Examples:

- Interfaces
- Type definitions
- Shared models

---

## utils/

Contains reusable utility functions.

Examples:

- Formatters
- Validators
- Constants
- Helper functions

---

# 8. Supporting Directories

## docs/

Stores supplementary documentation that supports development but is separate from the main project documentation.

Examples:

- API notes
- Design references
- Developer guides

---

## scripts/

Contains automation scripts.

Examples:

- Build scripts
- Maintenance scripts
- Data generation scripts

---

## tests/

Contains automated tests.

Examples:

- Unit tests
- Integration tests
- End-to-end tests

---

# 9. Naming Conventions

The following conventions apply:

| Item | Convention |
|------|------------|
| Folders | lowercase |
| React Components | PascalCase |
| Hooks | camelCase beginning with `use` |
| Utility Functions | camelCase |
| CSS Files | kebab-case or aligned with project conventions |
| Images | kebab-case |
| Configuration Files | lowercase |

Naming should remain consistent throughout the project.

---

# 10. Organisational Rules

The following rules govern file organisation:

- One responsibility per folder.
- Avoid duplicate components.
- Shared code belongs in shared directories.
- Keep pages lightweight.
- Separate configuration from implementation.
- Separate assets from source code.
- Avoid deeply nested directory structures unless clearly justified.

---

# 11. Scalability Strategy

The structure supports future additions such as:

- Blog
- Dashboard
- Authentication
- Backend APIs
- Client Portal
- CMS Integration
- AI Features

New features should fit naturally into the existing structure without requiring significant reorganisation.

---

# 12. Relationship to Other Documents

This document supports:

- Frontend Architecture
- Component Architecture
- Routing Architecture
- State Management Strategy
- Asset Management Architecture
- Build and Deployment

It defines the physical structure that implements the logical architecture.

---

# 13. Revision History

| Version | Date | Description |
|---------|------|-------------|
| 1.0 | 23 July 2026 | Initial creation of the Project Folder Structure document. |

---

# 14. Summary

The Project Folder Structure document establishes the physical organisation of the Professional Portfolio Website. By defining directory responsibilities, naming conventions, organisational rules, and scalability guidelines, it provides a consistent foundation for implementation and future growth. The structure is designed to support modular development, encourage reuse, simplify maintenance, and accommodate future enhancements without major restructuring.