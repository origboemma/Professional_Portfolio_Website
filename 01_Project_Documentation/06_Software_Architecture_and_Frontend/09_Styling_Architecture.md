# Professional Portfolio Website

## Document Information

| Item | Details |
|------|---------|
| **Project** | Professional Portfolio Website |
| **Phase** | Phase 6 – Software Architecture & Frontend |
| **Document Title** | Styling Architecture |
| **Document Number** | 09 |
| **Version** | 1.0 |
| **Status** | Draft |
| **Prepared By** | Emmanuel Chukwuka Origbo |
| **Last Updated** | 23 July 2026 |

---

# 1. Introduction

The Styling Architecture defines the visual implementation strategy for the Professional Portfolio Website.

It establishes the standards governing colours, typography, spacing, layouts, responsive design, dark mode, animations, reusable styles, and accessibility. The objective is to ensure that every page and component presents a consistent, professional, and maintainable user interface.

---

# 2. Purpose

The purpose of this document is to:

- Standardise visual design.
- Establish a reusable design system.
- Promote consistency across the application.
- Improve maintainability.
- Support responsive design.
- Ensure accessibility.
- Simplify future expansion.

---

# 3. Styling Philosophy

The styling strategy follows these principles:

- Consistency
- Simplicity
- Reusability
- Accessibility
- Responsiveness
- Maintainability
- Performance

Visual decisions should support usability rather than decoration.

---

# 4. Styling Technology Stack

The application uses:

| Technology | Purpose |
|------------|---------|
| Tailwind CSS | Utility-first styling framework |
| CSS Variables | Design tokens |
| CSS Modules (optional) | Component-specific styles where necessary |
| Global CSS | Base styles and resets |
| Lucide React | Icon library |

Tailwind CSS serves as the primary styling solution throughout the application.

---

# 5. Design System

The application uses a centralised design system.

The design system defines:

- Colour palette
- Typography
- Spacing
- Borders
- Shadows
- Border radius
- Icons
- Buttons
- Cards
- Forms
- Animations

All UI components should follow these standards.

---

# 6. Colour System

The colour system should support:

- Professional appearance
- High contrast
- Accessibility
- Light mode
- Dark mode

## Primary Colours

- Primary
- Primary Hover
- Primary Active

---

## Secondary Colours

- Secondary
- Secondary Hover

---

## Neutral Colours

- Background
- Surface
- Border
- Divider
- Text Primary
- Text Secondary

---

## Semantic Colours

- Success
- Warning
- Error
- Information

Semantic colours should be used consistently throughout the application.

---

# 7. Typography

Typography should establish a clear visual hierarchy.

The typography system includes:

- Display
- Heading 1
- Heading 2
- Heading 3
- Heading 4
- Body Large
- Body
- Small Text
- Caption

Typography should remain consistent across all pages.

---

# 8. Spacing System

Spacing should follow a consistent scale.

Examples:

- Extra Small
- Small
- Medium
- Large
- Extra Large

Layouts should rely on predefined spacing values rather than arbitrary measurements.

---

# 9. Responsive Design Strategy

The application supports:

- Mobile
- Tablet
- Laptop
- Desktop
- Large displays

Responsive behaviour should be implemented using Tailwind's breakpoint system.

Layouts should adapt gracefully across all supported screen sizes.

---

# 10. Layout Guidelines

Layouts should:

- Use consistent container widths.
- Maintain predictable spacing.
- Align content consistently.
- Avoid unnecessary complexity.
- Prioritise readability.

A consistent layout improves navigation and usability.

---

# 11. Component Styling

Reusable components should define:

- Normal state
- Hover state
- Focus state
- Active state
- Disabled state

Every interactive component should provide clear visual feedback.

---

# 12. Dark Mode Strategy

The application supports both:

- Light Mode
- Dark Mode

The selected theme should:

- Persist across sessions.
- Maintain sufficient colour contrast.
- Apply consistently across all pages.

Dark mode should use the same design tokens rather than separate styles where practical.

---

# 13. Animation Guidelines

Animations should:

- Be subtle.
- Support usability.
- Avoid distraction.
- Respect reduced motion preferences.

Examples include:

- Button transitions
- Card hover effects
- Navigation animations
- Page transitions
- Fade-in effects

Animations should enhance, not dominate, the user experience.

---

# 14. Accessibility Requirements

The styling system should support:

- WCAG-compliant colour contrast.
- Visible keyboard focus.
- Readable font sizes.
- Adequate spacing.
- Scalable text.
- Reduced motion preferences.

Accessibility must be considered a core design requirement.

---

# 15. Performance Considerations

Styling should be optimised by:

- Removing unused styles.
- Using reusable utility classes.
- Minimising custom CSS.
- Optimising fonts.
- Compressing images.
- Avoiding unnecessary animations.

Performance contributes directly to user experience.

---

# 16. Naming Conventions

Styling conventions include:

| Item | Convention |
|------|------------|
| CSS Variables | kebab-case |
| Tailwind Classes | Utility-first |
| Component Classes | Semantic and descriptive |
| Assets | kebab-case |

Consistency improves maintainability.

---

# 17. Future Scalability

The styling architecture supports future additions including:

- Blog layouts
- Dashboard interface
- Client portal
- CMS-driven pages
- Additional themes
- Multilingual layouts

Future enhancements should integrate without disrupting the existing design system.

---

# 18. Relationship to Other Documents

This document builds upon:

- Software Architecture
- Frontend Architecture
- Component Architecture
- State Management Strategy

It supports:

- Asset Management Architecture
- Testing Strategy
- Build and Deployment

---

# 19. Revision History

| Version | Date | Description |
|---------|------|-------------|
| 1.0 | 23 July 2026 | Initial creation of the Styling Architecture document. |

---

# 20. Summary

The Styling Architecture establishes the visual foundation of the Professional Portfolio Website. By defining a consistent design system, colour palette, typography, spacing, responsive strategy, accessibility standards, and performance guidelines, it ensures that every page and component delivers a cohesive, professional, and user-centred experience while remaining maintainable and scalable.