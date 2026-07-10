# Claude Task: Generate the Missing Section (HTML + CSS Only)

## Objective

Analyze the entire project and generate a new section that perfectly matches the existing website's design, structure, and coding style.

---

## First Step: Analyze the Entire Project

Before generating any code, thoroughly inspect the entire project.

Review:

- Every HTML file
- Every CSS file
- Existing components
- Overall layout
- Design system
- Typography
- Color palette
- Section spacing
- Container width
- Grid and Flex layouts
- Cards
- Buttons
- Forms
- Icons
- Border radius
- Shadows
- Hover effects
- Responsive breakpoints
- Naming conventions
- Existing utility classes

Do **not** create a section that looks different from the rest of the website. It should appear as if it was originally designed with the project.

---

# HTML Generation

Locate the following comments in the HTML:

```html
<!-- messing section -->

<!-- end messing section -->
```

Generate the complete HTML for the new section **only between these comments**.

Do **not** remove or modify the comments.

Do **not** modify any other HTML outside this section.

---

# CSS Generation

Locate the following comments in the stylesheet:

```css
/* start messing section css */

/* end messing section css */
```

Generate all required CSS **only between these comments**.

Do **not** remove or modify the comments.

Do **not** add CSS outside this section.

Reuse existing global variables, typography, spacing, colors, and utility classes whenever possible.

---

# Design Requirements

The section must:

- Match the existing visual language
- Use the same typography
- Follow the same spacing system
- Match border radius
- Match shadows
- Match button styles
- Match hover effects
- Match card design
- Match icon style
- Match animation style using **CSS only**
- Blend naturally with surrounding sections

The new section should feel like it was part of the original design.

---

# Responsive Requirements

The section must be fully responsive.

Support:

- Desktop
- Laptop
- Tablet
- Mobile

Reuse the project's existing breakpoints whenever possible.

Do not introduce a new responsive system unless necessary.

---

# Accessibility

Follow accessibility best practices.

Use:

- Semantic HTML
- Proper heading hierarchy
- Accessible buttons and links
- Descriptive alt text for images
- Sufficient color contrast

---

# Performance

Write clean and optimized code.

- Minimize unnecessary wrappers.
- Reuse existing classes where appropriate.
- Avoid duplicate styles.
- Keep the DOM lightweight.
- Write maintainable CSS.

---

# Restrictions

Do **NOT**:

- Use JavaScript.
- Use jQuery.
- Use any external libraries.
- Use Bootstrap unless the project already uses it.
- Change existing HTML outside the target section.
- Change existing CSS outside the target CSS block.
- Rename existing classes or IDs.
- Remove any comments.

Use **HTML and CSS only**.

---

# Expected Output

Generate only:

1. The HTML code that belongs between:

```html
<!-- messing section -->

<!-- end messing section -->
```

2. The CSS code that belongs between:

```css
/* start messing section css */

/* end messing section css */
```

Do not include explanations, markdown, analysis, or notes. Output only clean, production-ready HTML and CSS.