# MedBook - Accessible Healthcare Appointment System

## Problem Statement
Many patients, particularly seniors and people with disabilities, struggle with complex online booking systems. This project creates an intuitive, accessible interface that simplifies the appointment booking process while maintaining full WCAG 2.1 AA compliance.

## Design Decisions

### Color System
- **Primary Blue (#2563eb)**: Chosen for excellent contrast ratios (4.5:1+)
- **Success Green (#059669)**: Clear visual feedback for positive actions
- **Neutral Grays**: High contrast text (#1f2937) on light background (#f9fafb)
- **Error Red (#dc2626)**: Immediate visual recognition for errors

### Typography Scale
- **Base 16px**: Optimal for readability, especially for elderly users
- **Progressive Scale**: Consistent vertical rhythm with modular scale
- **High Contrast**: Minimum 4.5:1 contrast ratio for all text

### Layout Approach
- **Mobile-First**: Core functionality works on smallest screens
- **Progressive Enhancement**: Advanced layouts for capable devices
- **Flexible Grids**: Responsive without compromising accessibility

## Accessibility Features

### WCAG 2.1 AA Compliance
- ✅ Perceivable: Text alternatives, adaptable content, distinguishable
- ✅ Operable: Keyboard accessible, enough time, navigable
- ✅ Understandable: Readable, predictable, input assistance
- ✅ Robust: Compatible with assistive technologies

### Screen Reader Optimization
- Semantic HTML5 elements
- ARIA landmarks and labels
- Logical heading structure
- Descriptive link text

### Keyboard Navigation
- Visible focus indicators
- Logical tab order
- Skip navigation link
- Accessible form controls

## CSS Methodology

### BEM Naming Convention