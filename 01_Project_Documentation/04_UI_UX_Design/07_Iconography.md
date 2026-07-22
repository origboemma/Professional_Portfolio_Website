# Professional Portfolio Website

## Document Information

| Item | Details |
|------|---------|
| **Project** | Professional Portfolio Website |
| **Phase** | Phase 3 – UI/UX Design |
| **Document Title** | Iconography |
| **Document Number** | 07 |
| **Version** | 1.0 |
| **Status** | Draft |
| **Prepared By** | Emmanuel Chukwuka Origbo |
| **Last Updated** | 22 July 2026 |

---

# 1. Purpose

This document defines the iconography standards for the Professional Portfolio Website.

Icons are visual communication tools that improve navigation, reinforce meaning, reduce cognitive load, and enhance the overall user experience.

The objective is to ensure that icon usage remains consistent, accessible, and aligned with the website's professional identity.

---

# 2. Icon Philosophy

Icons should:

- Improve understanding.
- Support navigation.
- Reinforce interface actions.
- Complement text rather than replace it.
- Maintain visual consistency.
- Remain simple and recognisable.

Icons should clarify information, not decorate the interface unnecessarily.

---

# 3. Icon Library

The project will adopt a single primary icon library.

Preferred library:

- Lucide React

Alternative libraries (only if necessary):

- Heroicons
- Phosphor Icons
- Tabler Icons

Using multiple icon libraries within the same interface should be avoided unless there is a compelling reason.

---

# 4. Icon Categories

Icons will be grouped into the following categories:

| Category | Examples |
|----------|----------|
| Navigation | Home, Menu, Back, Search |
| Contact | Email, Phone, Location |
| Social | GitHub, LinkedIn, X, YouTube |
| Projects | Database, Dashboard, Code, Server |
| Skills | Python, SQL, Cloud, Analytics |
| Actions | Download, View, Edit, Share |
| Status | Success, Warning, Error, Information |
| Interface | Settings, Theme, Notifications |

---

# 5. Icon Usage Guidelines

Icons should:

- Accompany important actions.
- Support navigation.
- Improve content scanning.
- Reinforce labels.

Icons should not replace clear text unless the meaning is universally understood.

---

# 6. Icon Sizing

Recommended sizes include:

| Size | Typical Use |
|------|-------------|
| Small | Inline text and metadata |
| Medium | Buttons and navigation |
| Large | Feature highlights |
| Extra Large | Hero illustrations or section highlights |

Consistent sizing should be maintained throughout the website.

---

# 7. Icon Styling

Icons should follow the Design System.

Guidelines include:

- Consistent stroke width.
- Consistent corner style.
- Consistent visual weight.
- Consistent alignment.
- Consistent spacing.

Icons should visually match one another regardless of their purpose.

---

# 8. Colour Usage

Icons should inherit colours from the design token system.

Typical mappings include:

- Primary colour for key actions.
- Neutral colour for supporting content.
- Success colour for confirmations.
- Warning colour for cautionary information.
- Error colour for validation messages.

Hard-coded colours should be avoided.

---

# 9. Accessibility

Icons should support accessibility by ensuring:

- Decorative icons are hidden from assistive technologies.
- Functional icons include accessible labels.
- Interactive icons remain keyboard accessible.
- Icons are not the sole means of conveying important information.

Accessibility should always take priority over appearance.

---

# 10. Responsive Behaviour

Icons should scale appropriately across:

- Desktop
- Laptop
- Tablet
- Mobile

Spacing and alignment should remain consistent on all screen sizes.

---

# 11. Frontend Implementation

Icons should be:

- Imported as reusable React components.
- Wrapped where appropriate in shared UI components.
- Styled using design tokens.
- Documented for reuse.

Avoid embedding SVG markup directly into individual pages unless there is a specific technical requirement.

---

# 12. Relationship to Other Documents

This document builds upon:

- Brand Strategy
- Design System
- Colour Implementation
- Typography Implementation
- Component Library

It provides the standards for icon implementation during frontend development.

---

# 13. Revision History

| Version | Date | Description |
|---------|------|-------------|
| 1.0 | 22 July 2026 | Initial creation of the Iconography document. |

---

# 14. Summary

The Iconography document establishes consistent standards for selecting, styling, and implementing icons throughout the Professional Portfolio Website. By defining icon libraries, usage guidelines, accessibility requirements, and implementation practices, it supports a cohesive, intuitive, and maintainable user interface.