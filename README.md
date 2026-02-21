# Designing for Conversion

**Project Link:**
[https://github.com/knee-rel/css_work](https://github.com/knee-rel/css_work)

---

# Learning Goals

By the end of this activity, pairs should be able to:

* Apply CSS fundamentals (selectors, box model, flexbox)
* Improve the visual hierarchy of a product page
* Connect layout decisions to business metrics
* Explain at least one technical decision strategically

---

## Generative AI Policy

The use of Generative AI to augment work is tolerated **as long as there is clear understanding of the design decisions suggested by AI**.

* There are **no deductions** for using AI.
* However, you **must honestly identify** AI assistance.

### Requirement

Create a file named:

```
AIUsage.md
```

Inside, briefly state:

* Which parts were AI-assisted
* What you modified or verified yourself

---

# Activity Introduction

## You Are the Front-End Team

A mid-sized e-commerce company hired you.

They say:

> “Our product page looks plain.
> Our Add-to-Cart rate is low.
> Improve it.”

---

## Constraint

You may **NOT**:

* Change the HTML structure

You may **ONLY**:

* Use CSS

---

# Challenge Structure

---

## Layer 1 – Required

All pairs must complete the following.

---

### Task 1: Center the Product Card

* Horizontally centered on the page
* Balanced spacing

---

### Task 2: Use Flexbox

* Image and text side-by-side (desktop view)

---

### Task 3: Improve Spacing

* Proper margin and padding
* Clear separation between sections

---

### Task 4: Style the Button

* Distinct color
* Adequate padding
* Rounded corners

---

# Layer 2 – Intermediate

Proceed after completing Layer 1.

---

### Task 5: Add Hover Effect

* Button changes color on hover
* Optional subtle scale transform

---

### Task 6: Improve Typography

* Adjust font size hierarchy
* Make price visually dominant

---

### Task 7: Make It Responsive

On small screens:

* Stack the image above the text

Use:

```css
@media (max-width: 768px) {
  /* your rules */
}
```

---

# Layer 3 – Advanced

**(Optional for Non-MIS, Required for MIS)**

---

## Task 8: Refactor CSS

* Remove duplicate styles
* Use reusable classes
* Improve structure

---

## Refactor Requirements

### 1. Remove Obvious Duplication

Focus on:

* Repeated spacing values
* Repeated colors
* Repeated border-radius or shadows

---

### 2. Ensure Selectors are Reusable

Focus on:

* Using class selectors for components
* Avoid overly specific selectors
* Avoid `!important`

Ask yourself:

> If there were 30 product cards instead of 3, would my CSS still work cleanly?

---

### 3. Basic File Organization

Requirements:

* Related rules are grouped together
* Hover states are near their base styles
* Media query is placed at the bottom

---

# Guide Questions for Reflection

Answer all questions. Be specific and connect your technical choices to user behavior and business impact.

---

## Technical Reflection

### Layout and Structure

What key layout problem were you solving, and why was Flexbox the most appropriate solution for this product grid and card layout?

---

### Visual Hierarchy and Spacing

Which single CSS change most improved readability or scannability (spacing, typography, or price emphasis)? Explain how it affects user attention.

---

### Interaction Design

How does your button styling and hover effect communicate that the element is clickable? What risk would occur if the CTA were less visually distinct?

---

### Responsiveness and Robustness

What specifically changes at the mobile breakpoint, and how does your solution ensure the layout still works if more products are added?

---

### For MIS Only

What specifically changes at the mobile breakpoint, and how does your solution ensure the layout still works if more products are added?

---

## Business Reflection

### Conversion Impact

Which user behavior were you primarily trying to influence (for example: faster scanning, increased trust, more clicks)? Explain how your design supports this.

---

### Revenue and Risk Thinking

If the Add-to-Cart rate did not improve after your redesign, what would you test or change first, and why?

---

# Response Guidelines

* Your full reflection should be **300–400 words**
* Format your submission using:

  * **Font:** Times New Roman
  * **Size:** 11 pt
  * **Line spacing:** 1.15

---
