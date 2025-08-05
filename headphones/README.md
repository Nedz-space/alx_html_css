# 🎧 Headphones Landing Page

A fully responsive marketing landing page for a fictional headphone brand — **Headphones**. Built with semantic **HTML5** and modern **CSS3**, this project follows accessibility best practices and responsive design principles — without relying on any external CSS frameworks or JavaScript.

---

## 📸 Preview

Responsive views:

| Desktop | Tablet | Mobile |
|--------|--------|--------|
| ![Desktop view](./preview_desktop.png) | ![Tablet view](./preview_tablet.png) | ![Mobile view](./preview_mobile.png) |

---

## 🚀 Features

- ✅ Pixel-perfect responsive design (Desktop, Tablet, Mobile)
- ✅ No external libraries or frameworks (pure HTML & CSS)
- ✅ Accessibility-aware semantic markup
- ✅ Mobile layout triggers at `max-width: 480px`
- ✅ Hover & Active States
  - Links: `#FF6565`
  - Buttons: `opacity: 0.9` on hover/active
- ✅ Max content width: `1000px`, centered horizontally

---

## 🧱 Page Structure

The webpage consists of the following sections:

1. **Header**
   - Logo
   - Navigation (`what we do`, `our results`, `contact us`)

2. **Hero Section**
   - Large background image
   - Heading + Subheading
   - Call-to-action button

3. **What We Do**
   - Intro text
   - Four icon blocks describing services

4. **Our Results**
   - Section showcasing four result tiles (with +2%)

5. **Contact Us**
   - Simple contact form (Name, Email, Message)

6. **Footer**
   - Logo
   - Copyright
   - Social media icons

---

## 📐 Layout Notes

- The layout is built using **Flexbox** for alignment and responsiveness.
- A `max-width: 1000px` wrapper is used to center and constrain content.
- Media queries are used to switch to mobile styles at screen widths `<= 480px`.

---

## 🧪 Interactions

| Element | Behavior |
|--------|----------|
| Links | Change color to `#FF6565` on hover and active |
| Button | Reduces `opacity` to `0.9` on hover and active |
| Layout | Switches to mobile version when screen width ≤ 480px |

---

## 💡 How to Run Locally

1. Clone the repo:

   ```bash
   git clone https://github.com/nedz-space/headphones-landing-page.git
   cd headphones-landing-page
