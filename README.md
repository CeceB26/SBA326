

# Chat Booking Hero Layout

Bootstrap + Custom CSS Project

## Project Overview

This project recreates a responsive hero section featuring a chat booking interface mockup. The layout was built using **Bootstrap 5 utilities and components wherever possible**, with custom CSS used only for decorative elements that Bootstrap cannot generate (such as the purple background blob and phone mock styling).

The design includes:

* A responsive hero card
* A layered purple background shape
* A phone mockup with chat UI
* Responsive text alignment and layout behavior
* Clean Bootstrap spacing and typography utilities

---

## Technologies Used

* **HTML5**
* **Bootstrap 5.3**
* **CSS3**
* Responsive Design Principles

---

## Bootstrap Usage

Bootstrap utilities and components were used for:

### Layout

* `container`
* `row`
* `col-*`
* `d-flex`
* `justify-content-*`
* `align-items-*`
* Responsive column stacking

### Spacing

* `p-*`
* `m-*`
* `g-*`
* `gap-*`

### Typography

* `fw-bold`
* `text-secondary`
* `text-center`
* `text-lg-end`
* `small`

### Components Used

* `card`
* `input-group`
* `btn`
* `form-control`

Bootstrap handles the majority of structural styling and responsiveness.

---

## Custom CSS

Custom CSS was only used for elements that Bootstrap cannot provide:

* `.purple-blob` (decorative background shape)
* `.soft-circle` (background accent)
* `.phone-shell` (phone mockup styling)
* `.phone-notch`
* Gradient backgrounds for booking cards

All custom CSS is valid and limited to visual enhancements that are not achievable through Bootstrap utilities alone.

---

## Responsiveness

The layout is fully responsive:

* On small screens, elements stack vertically.
* On larger screens, the phone and text display side-by-side.
* The phone overlaps the purple background by approximately 10% on desktop view.
* Text alignment adjusts using responsive Bootstrap utilities.

Tested using browser DevTools in mobile and desktop views.

---

## File Structure

```
project-folder/
│
├── index.html
├── styles.css
└── images/
    ├── avatar.jpg
    ├── dog1.jpg
    ├── dog2.jpg
    └── dog3.jpg
```

---

## How to Run

1. Download or clone the project.
2. Open `index.html` in a browser.
3. Ensure `styles.css` is linked properly.
4. Make sure images are inside the `/images` folder.

No additional dependencies or installations required.

---

## Notes

* Bootstrap was prioritized for layout and spacing to meet assignment requirements.
* Custom CSS was minimized and used only where necessary.
* The project maintains clean separation between structure (HTML), framework styling (Bootstrap), and custom design elements (CSS).

