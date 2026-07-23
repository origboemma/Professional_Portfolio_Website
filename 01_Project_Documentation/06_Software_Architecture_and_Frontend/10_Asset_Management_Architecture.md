# Professional Portfolio Website

## Document Information

| Item | Details |
|------|---------|
| **Project** | Professional Portfolio Website |
| **Phase** | Phase 6 – Software Architecture & Frontend |
| **Document Title** | Asset Management Architecture |
| **Document Number** | 10 |
| **Version** | 1.0 |
| **Status** | Draft |
| **Prepared By** | Emmanuel Chukwuka Origbo |
| **Last Updated** | 23 July 2026 |

---

# 1. Introduction

The Asset Management Architecture defines how all non-code resources are organised, maintained, optimised, and delivered throughout the Professional Portfolio Website.

Assets include images, icons, project screenshots, downloadable documents, logos, fonts, favicons, videos, and other media that contribute to the presentation and functionality of the application.

A structured asset management strategy improves maintainability, performance, consistency, and scalability.

---

# 2. Purpose

The purpose of this document is to:

- Standardise asset organisation.
- Improve maintainability.
- Optimise application performance.
- Reduce duplication.
- Simplify asset discovery.
- Support responsive media delivery.
- Prepare for future growth.

---

# 3. Asset Management Principles

The asset architecture follows these principles:

- Consistency
- Organisation
- Reusability
- Optimisation
- Accessibility
- Scalability
- Performance

Every asset should have a clearly defined purpose.

---

# 4. Asset Categories

Assets are organised into logical categories.

## Images

Examples:

- Profile photographs
- Hero images
- Background graphics
- Illustrations
- Logos

---

## Project Screenshots

Examples:

- Dashboard screenshots
- Database diagrams
- Power BI reports
- SQL query outputs
- Architecture diagrams

---

## Icons

Examples:

- Navigation icons
- Technology logos
- Social media icons
- UI icons

Lucide React will provide most application icons.

---

## Documents

Examples:

- Résumé (PDF)
- CV
- Case studies
- White papers
- Project documentation

---

## Fonts

Typography assets required by the application.

---

## Favicons

Application branding icons for browsers and devices.

---

## Videos (Future)

Examples:

- Project demonstrations
- Walkthrough videos
- Presentation recordings

---

# 5. Directory Structure

Assets should be organised as follows:

```text
public/
│
├── documents/
│      ├── resume/
│      ├── case-studies/
│      └── reports/
│
├── images/
│      ├── profile/
│      ├── projects/
│      ├── certifications/
│      ├── backgrounds/
│      └── branding/
│
├── icons/
│
├── favicon/
│
├── videos/
│
└── manifest.webmanifest
```

Application-imported assets should be placed in:

```text
src/assets/
│
├── images/
├── illustrations/
├── icons/
├── fonts/
└── animations/
```

---

# 6. Naming Conventions

Assets should use:

- lowercase letters
- hyphens
- descriptive names

Examples:

```
profile-photo.jpg
primemart-dashboard-overview.png
sales-performance-chart.webp
resume-emmanuel-chukwuka-origbo.pdf
github-logo.svg
```

Avoid:

```
IMG001.png
final2.png
new-image.jpg
testfile.png
```

---

# 7. Image Optimisation

Images should be optimised before deployment.

Recommendations include:

- Resize to required dimensions.
- Compress without noticeable quality loss.
- Use modern formats such as WebP where appropriate.
- Avoid unnecessarily large images.
- Generate thumbnails for gallery views.

Optimised assets improve page load speed.

---

# 8. Responsive Images

Images should adapt to different screen sizes.

Recommended practices include:

- Appropriate image dimensions.
- Responsive CSS.
- Lazy loading.
- Multiple resolutions where beneficial.

Users should not download larger images than necessary.

---

# 9. Document Management

Downloadable files should:

- Have descriptive names.
- Include version numbers where appropriate.
- Be reviewed before publication.
- Be stored in the `documents` directory.

Examples include:

- Résumé
- Project reports
- Portfolio documents

---

# 10. Icon Strategy

Icons should:

- Use a consistent visual style.
- Be scalable (SVG where possible).
- Remain accessible.
- Match the overall design system.

Lucide React should be the preferred icon library.

---

# 11. Font Management

Fonts should:

- Minimise download size.
- Support accessibility.
- Maintain readability.
- Include appropriate fallback fonts.

Only required font weights should be loaded.

---

# 12. Accessibility Requirements

Assets should support accessibility.

Examples include:

- Descriptive alternative text for images.
- Meaningful document titles.
- Decorative images marked appropriately.
- Readable PDFs.
- Sufficient contrast for graphical assets.

Accessibility applies to media as well as interface components.

---

# 13. Performance Strategy

Assets should be managed to improve performance.

Recommended practices include:

- Lazy loading images.
- Compressing media.
- Removing unused assets.
- Using SVG where appropriate.
- Minimising duplicate resources.
- Leveraging browser caching.

---

# 14. Version Management

Asset updates should follow version control practices.

Examples:

- Replace outdated screenshots with newer versions.
- Archive deprecated media when necessary.
- Track major asset updates using Git.

Historical versions should remain recoverable through version control.

---

# 15. Security Considerations

Published assets should:

- Exclude confidential information.
- Remove unnecessary metadata where appropriate.
- Avoid exposing personal or sensitive data.
- Be reviewed before release.

Only public-facing resources should be included in production.

---

# 16. Future Scalability

The asset architecture supports future additions including:

- Blog media
- Client resources
- Interactive demonstrations
- Video tutorials
- AI-generated media
- CMS-managed assets

Future resources should integrate without disrupting the existing organisation.

---

# 17. Relationship to Other Documents

This document builds upon:

- Frontend Architecture
- Project Folder Structure
- Styling Architecture

It supports:

- Performance Optimisation
- Build and Deployment
- Logging and Monitoring

---

# 18. Revision History

| Version | Date | Description |
|---------|------|-------------|
| 1.0 | 23 July 2026 | Initial creation of the Asset Management Architecture document. |

---

# 19. Summary

The Asset Management Architecture establishes the standards for organising, naming, optimising, securing, and maintaining all non-code resources used by the Professional Portfolio Website. By defining clear directory structures, optimisation practices, accessibility requirements, and lifecycle management guidelines, it ensures that assets remain efficient, maintainable, and scalable throughout the lifetime of the project.