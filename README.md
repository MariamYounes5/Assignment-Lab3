# Studio - Component Library, Form Validation & Dynamic Data Table

A responsive, accessible web project built with modern CSS features, custom components, client-side form validation, and dynamic JavaScript data manipulation.

## Features Implemented

### 1. Registration Form Validation (`validation.html`):
- **Real-time Client-Side Validation:** Prevents default submission on invalid entries.
- **Detailed Error Feedback:** Field-specific error messages displayed inline directly below inputs.
- **Validation Rules:**
  - Full Name: Required field.
  - Email: Verified against a standard regular expression (Regex) pattern.
  - Password & Confirm Password: Minimum length of 8 characters and strict matching check.
  - Age: Numeric verification within an acceptable range (18–100).

### 2. Dynamic Data Table (`data.html`):
- **DOM Generation:** Safely builds table rows and cells using `document.createElement` and `textContent` to prevent XSS vulnerabilities.
- **Live Search / Filter:** Filters table records in real-time on input without reloads.
- **Column Sorting:**
  - Text Sorting: Uses `localeCompare` for alphabetical name sorting.
  - Numeric Sorting: Standard numerical comparison for age sorting.

### 3. Responsive Layout & Breakpoints (`styles.css`):
- **1 Column** on Mobile screens (< 600px).
- **2 Columns** on Tablet screens (600px - 1023px).
- **3 Columns** on Desktop screens (1024px+).

### 4. Component Library (`components.html`):
- Pure CSS Modal using `:target`.
- Custom alert boxes and accessible form elements.

### 5. Accessibility & Dark Mode:
- Automatic Dark Mode support via `@media (prefers-color-scheme: dark)`.
- WCAG AA compliant text and surface contrast.