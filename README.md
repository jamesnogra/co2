# 🍋 Citrus Oasis - Modern Landing Page

A sleek, modern, and fully responsive single-page website designed for **Citrus Oasis**, a luxury private sanctuary in Naga, Cebu. This project blends a vibrant Mediterranean aesthetic with the breathtaking coastal beauty of the Philippines, providing an elegant digital experience for prospective guests.

![Status](https://img.shields.io/badge/Status-Production--Ready-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

* **Fully Responsive Design:** Flawless layout across mobile, tablet, and desktop screens using CSS Grid and Flexbox.
* **Masonry Photo Gallery:** A dynamic, Pinterest-style gallery layout using CSS columns to beautifully showcase the property.
* **Smooth Animations:** Subtle fade-in and slide-up effects triggered on scroll using the native `IntersectionObserver` API.
* **Dynamic Navigation:** A transparent navbar that transitions into a solid, shadowed header upon scrolling.
* **Mobile-First UI:** Includes a custom slide-out hamburger menu for mobile users.
* **Elegant Typography:** Pairs the luxury serif font *Cormorant Garamond* with the clean sans-serif *Montserrat*.
* **Zero Dependencies:** Built with pure HTML, CSS, and Vanilla JavaScript. No frameworks or build steps required.

## 🎨 Design System

The color palette is inspired by a "Mediterranean meets Cebu" theme:
* **Deep Slate Blue (`#2C3E50`)**: Primary text and footer background.
* **Terracotta / Citrus Orange (`#E07A5F`)**: Accent colors, buttons, and highlights.
* **Lush Greenery (`#81B29A`)**: Secondary accent for nature elements.
* **Warm Sand (`#F4F1DE`)**: Soft background sections.

## 🚀 Getting Started

Because this is a self-contained single-page application, there is no build process or server setup required.

1. Download the `index.html` file.
2. Double-click the file to open it in your preferred modern web browser (Chrome, Safari, Firefox, Edge).
3. *Optional:* To host it, simply upload the `index.html` file to any static web host (e.g., GitHub Pages, Netlify, Vercel, or traditional cPanel hosting).

## 🛠️ Customization Guide

### Changing Colors
All primary colors are managed via CSS Custom Properties (Variables) at the top of the `<style>` block. Simply update the hex codes in the `:root` selector:

```css
:root {
    --primary: #2C3E50; 
    --secondary: #E07A5F; 
    --accent: #81B29A; 
    --light: #F4F1DE; 
    --white: #FFFFFF;
    --text: #3D405B;
    --bg: #FAFAFA;
}