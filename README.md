# “Designing for Conversion”

**45 Minutes Total**
**Pairs (2 students per team)**

---

# 🎯 Learning Goals

By the end of this activity, pairs should be able to:

1. Apply CSS fundamentals (selectors, box model, flexbox)
2. Improve visual hierarchy of a product page
3. Connect layout decisions to business metrics
4. Explain at least one technical decision strategically

---

# 🎞 SLIDE 1 – Activity Introduction

## You Are the Front-End Team

A mid-sized e-commerce company hired you.

They say:

> “Our product page looks plain.
> Our Add-to-Cart rate is low.
> Improve it.”

You may NOT change the HTML structure.

You may ONLY use CSS.

---

# Pair Roles (Important)

Each pair assigns roles:

### Builder

* Writes CSS
* Implements changes

### Strategist

* Justifies decisions
* Connects layout to business metrics
* Prepares for mini reflection

They may switch halfway if desired. This ensures both tech + management engagement.

---

# 🟦 The Challenge Structure

---

# 🟢 Layer 1 – Required

All pairs must complete:

### 1. Center the product card

* Horizontally centered on page
* Balanced spacing

### 2. Use Flexbox

* Image and text side by side (desktop view)

### 3. Improve spacing

* Proper margin and padding
* Clear separation between sections

### 4. Style the button

* Distinct color
* Adequate padding
* Rounded corners

---

### Business Reflection Prompt

Pairs must answer in 2–3 sentences:

> What user behavior are you trying to influence with your button styling?

Examples:

* Increase click visibility
* Improve perceived trust
* Reduce hesitation

---

# Layer 2 – Intermediate

After completing Layer 1:

### 5. Add Hover Effect

* Button changes color on hover
* Optional subtle scale transform

### 6. Improve Typography

* Adjust font size hierarchy
* Make price visually dominant

### 7. Make It Responsive

* Stack image above text on small screens

Hint:
Use media query:

```css
@media (max-width: 768px) {
  /* your rules */
}
```

---

### Business Reflection Prompt (Layer 2)

> Why is mobile responsiveness critical for e-commerce revenue?

Expected:

* Majority of traffic is mobile
* Poor mobile UX increases bounce rate

---

# Layer 3 – Advanced (Hi, MIS people. Your challenge is to bypass this stage) (Optional)

### 8. Refactor CSS

* Remove duplicate styles
* Use reusable classes
* Improve structure

### 9. Inspect with DevTools

* Check box model
* Check computed styles

### 10. Answer This:

> What CSS changes could trigger layout recalculation (reflow)?

Guide toward:

* Changing width
* Changing display
* Changing font size

---

# 🟦 Guide Questions

### 🔵 Technical

* Why did you choose that spacing?
* Why flexbox instead of margin hacks?
* Why that color contrast?

### 💼 Business

* Which metric improves because of this change?
* What happens if the CTA blends into the background?
* How does spacing affect perceived brand quality?

Push them to think beyond “it looks nice.”

---

# 🎞 SLIDE – Mini Presentation Prompt

Each pair answers, in 3-5 sentences:

1. What visual change had the biggest impact?
2. What business metric were you targeting?
3. What technical concept enabled that change?

---
