
# Palm Heights × H&M HOME Collaboration Website

**Live Website:** https://el-shayah-task.vercel.app/

**Figma Design:** https://www.figma.com/design/nUdsMBxLEjqdmZiSQYeQfX/Ganna-Mohamed---Elshayah-Task?node-id=0-1&t=1FGbAr2wQhpLQEmN-1

---

## Design Concept

The design was inspired by **magazine spread layouts**, aiming for an editorial and elegant aesthetic:

* **Layout**

  * 12-column grid system on web, aligned to an **8-point grid** with minimal gaps (starting from 8px).
  * Bold titles and structured grids to mimic high-end fashion magazines.

* **Typography**

  * **Lora** → Elegant, slim, and refined for headlines (stylish, fashion-forward “رشيق” look).
  * **Inter** → Modern, readable, and versatile for body text.

* **Icons & Aesthetics**

  * Sharp, slim icon set reflecting **H&M brand aesthetics**.
  * **Beige and warm tones** introduced to highlight Palm Heights’ identity and create a balanced, luxurious mood.

---

## Code Implementation

The codebase focuses on responsiveness, maintainability, and scalability:

* **CSS Grid Layouts** → Used for consistent alignment and to recreate the magazine-style structure.
* **Responsive Design**

  * Two dedicated CSS files:

    * `styles.css` → Laptop & larger screens.
    * `mobile.css` → Mobile devices.
  * **rem units** for spacing and typography → scalable for future tablet or breakpoint adjustments.
* **CSS Variables** → Centralized color palette for easier maintenance.
* **jQuery Slider** → Added in the product section for smooth navigation, fully responsive on mobile.

---

## Project Structure

```
project-root/
│── index.html
│── css/
│   ├── styles.css
│   ├── mobile.css
│── assets/
```
