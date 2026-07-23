# Professional Portfolio Website

## Document Information

| Item | Details |
|------|---------|
| **Project** | Professional Portfolio Website |
| **Phase** | Phase 6 – Software Architecture & Frontend |
| **Document Title** | Testing Strategy |
| **Document Number** | 15 |
| **Version** | 1.0 |
| **Status** | Draft |
| **Prepared By** | Emmanuel Chukwuka Origbo |
| **Last Updated** | 23 July 2026 |

---

# 1. Introduction

The Testing Strategy defines the quality assurance approach for the Professional Portfolio Website.

It establishes how testing activities are planned, executed, documented, and maintained throughout the software development lifecycle to ensure the application meets functional and non-functional requirements.

Testing is integrated into every phase of development rather than being treated as a final activity.

---

# 2. Purpose

The purpose of this document is to:

- Define the testing approach.
- Improve software quality.
- Detect defects early.
- Verify business requirements.
- Validate user experience.
- Support maintainability.
- Reduce production issues.

---

# 3. Testing Objectives

The testing process aims to:

- Verify functional correctness.
- Validate user interface behaviour.
- Confirm responsive design.
- Ensure accessibility compliance.
- Measure performance.
- Verify browser compatibility.
- Improve application reliability.

Testing should provide confidence that the software behaves as intended.

---

# 4. Testing Principles

The project follows these principles:

- Test early.
- Test continuously.
- Automate where practical.
- Focus on business value.
- Verify expected behaviour.
- Prevent regression.
- Document findings.

Testing is a continuous quality activity.

---

# 5. Testing Levels

The application will be verified using multiple testing levels.

## Unit Testing

Purpose:

Verify individual components, utilities, and helper functions.

Examples:

- Utility functions
- React hooks
- Data formatting functions

---

## Integration Testing

Purpose:

Verify interactions between components.

Examples:

- Navigation
- Page layouts
- Theme switching
- Contact form behaviour

---

## System Testing

Purpose:

Verify the complete application.

Examples:

- Complete navigation flow
- Project browsing
- Downloadable résumé
- External links

---

## User Acceptance Testing (UAT)

Purpose:

Confirm that the website satisfies stakeholder expectations.

Evaluation areas include:

- Ease of navigation
- Professional appearance
- Information quality
- Overall usability

---

# 6. Functional Testing

Functional testing verifies:

- Navigation menu
- Theme switching
- Routing
- Contact links
- Project pages
- Downloadable documents
- Forms
- Interactive components

Every feature should perform according to its requirements.

---

# 7. Responsive Testing

The website should be tested on:

- Mobile phones
- Tablets
- Laptops
- Desktop displays
- Large monitors

Layouts should remain readable and functional across all supported screen sizes.

---

# 8. Browser Compatibility Testing

Supported browsers include:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

Critical functionality should remain consistent across supported browsers.

---

# 9. Accessibility Testing

Accessibility verification includes:

- Keyboard navigation.
- Screen reader compatibility.
- Colour contrast.
- Focus indicators.
- Heading hierarchy.
- Alternative text.
- Form accessibility.

Testing should align with WCAG 2.2 Level AA.

---

# 10. Performance Testing

Performance evaluation includes:

- Lighthouse audits.
- Core Web Vitals.
- Loading speed.
- Bundle size.
- Image optimisation.
- Rendering performance.

Performance should remain within defined project targets.

---

# 11. Security Testing

Although Version 1 is a frontend application, testing should verify:

- Safe external links.
- Secure handling of downloadable files.
- Absence of exposed secrets.
- Dependency vulnerabilities.
- Browser security best practices.

Security testing should be repeated before major releases.

---

# 12. Test Environment

Testing should be performed in:

- Local development environment.
- Production preview build.
- GitHub Pages deployment.

Each environment should reflect the intended user experience.

---

# 13. Test Data Management

Testing should use:

- Representative project data.
- Valid URLs.
- Sample downloadable documents.
- Realistic screenshots.

Test data should not contain confidential information.

---

# 14. Defect Management

Each defect should include:

- Unique identifier.
- Description.
- Severity.
- Priority.
- Steps to reproduce.
- Expected behaviour.
- Actual behaviour.
- Resolution status.

Defects should be tracked until resolved.

---

# 15. Acceptance Criteria

A feature is considered complete when:

- Functional requirements are satisfied.
- No critical defects remain.
- Accessibility requirements are met.
- Performance targets are achieved.
- Documentation is updated.
- Code review is completed.

Completion should be based on quality rather than speed.

---

# 16. Regression Testing

Regression testing should be performed after:

- New features.
- Refactoring.
- Dependency updates.
- Major design changes.

Previously working functionality should remain unaffected.

---

# 17. Future Automation

Future automated testing may include:

- Unit testing.
- Integration testing.
- End-to-end testing.
- Accessibility audits.
- Performance monitoring.

Automation should expand as the project grows.

---

# 18. Relationship to Other Documents

This document builds upon:

- Coding Standards
- Accessibility Architecture
- Performance Optimization
- Security Considerations

It supports:

- Build and Deployment
- Continuous Integration
- Maintenance

---

# 19. Revision History

| Version | Date | Description |
|---------|------|-------------|
| 1.0 | 23 July 2026 | Initial creation of the Testing Strategy document. |

---

# 20. Summary

The Testing Strategy defines the framework for verifying the quality, reliability, accessibility, performance, and maintainability of the Professional Portfolio Website. By incorporating structured testing throughout the software development lifecycle, the project reduces defects, improves confidence in each release, and supports the delivery of a robust and professional application.