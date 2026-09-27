# TechMeetup Landing Page

A fully responsive, single-page event landing page built to demonstrate fundamental UI design and layout techniques using Bootstrap 5. 

Instead of relying on pre-built complex components (like Navbars or Cards), this project is meticulously crafted from scratch using Bootstrap's core grid system, flexbox capabilities, and utility classes.

## 🚀 Live Demo
*(You can add your GitHub Pages or Vercel live link here later)*

## 🛠️ Technologies & Tools
* **HTML5** (Semantic structuring)
* **CSS3** (Custom object-fit adjustments)
* **Bootstrap 5.3** (Layout and Styling)
* **Bootstrap Icons** (Typography and Visuals)

## 💡 Key Features & Concepts Applied

This project serves as a practical implementation of the following Bootstrap concepts:

* **Button & Button Groups:** Styled interactive elements using `btn`, `btn-primary`, `btn-outline-primary`, and combined them seamlessly using `btn-group` in the header.
* **Grid System & Gutters:** Built a responsive speaker section using `row-cols-*` logic and controlled vertical/horizontal spacing with `gy-4` and `g-4` gutters.
* **Flexbox Layouts:** Used `d-flex`, `justify-content-between`, and `align-items-center` for perfect alignment in the header, alerts, and footer.
* **Responsive Visibility:** Implemented display utilities (`d-none`, `d-md-table-cell`) to hide specific table columns on mobile devices to prevent horizontal scrolling, while keeping them visible on larger screens.
* **Positioning:** Utilized `position-fixed` with `z-3` for a sticky header, and `position-absolute` paired with `translate-middle` for perfect centering in the hero section.
* **Spacing & Borders:** Applied comprehensive margin/padding utilities (`p-4`, `my-5`) and customized element boundaries using `border`, `border-primary`, and `rounded-circle`.
* **Alert Components:** Integrated a prominent `alert-warning` box to emphasize urgent information.

## 📱 Responsiveness
The layout adapts seamlessly across all devices:
* **Mobile (<768px):** Single-column grid for speakers, simplified event schedule table (hidden columns), stacked footer.
* **Tablet (768px - 992px):** Two-column grid for speakers, fully visible event schedule table.
* **Desktop (>992px):** Four-column grid layout for optimal screen usage.
