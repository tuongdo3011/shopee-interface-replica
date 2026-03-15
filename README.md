# Shopee Interface Replica

## 📌 Project Overview
This project is a frontend exercise focused on replicating the landing page interface of Shopee using HTML and CSS. The primary goal was to apply layout techniques, manage CSS architecture, and ensure the UI matches the original design's structure and styling.

## 🛠 Technologies & Techniques
* **HTML5 & CSS3**: Used for semantic structure and styling of the interface.
* **CSS Variables**: Implemented via the `:root` selector to manage global values such as the primary Shopee brand color, text colors, and header dimensions for maintainable code.
* **Flexbox**: Utilized as the primary tool for aligning elements within the navigation bar and product lists.
* **BEM Methodology**: Adopted the `Block__Element--Modifier` naming convention for CSS classes to ensure clear and scalable code.
* **Grid System**: Built a custom grid layout (e.g., `.grid`, `.grid__row`) to handle the column structure for product displays.
* **Icon Library**: Integrated **FontAwesome 7.1.0** to display vector icons across the UI.

## 📂 Project Structure
```text
.
├── icons/
│   └── fontawesome-free-7.1.0-web/  # Integrated icon library
├── img/                             # Optimized product & UI images
├── .gitignore                       # Clean repository (ignored .DS_Store)
├── base.css                         # Global resets, variables, and grid system
├── main.css                         # Feature-specific styles (Header, Footer, Product)
├── index.html                       # Main entry point
└── README.md
```
🏗 Installation
1. Clone the repository:
```Bash
git clone https://github.com/tuongdo3011/shopee-interface-replica.git
```
2. Open index.html in your preferred browser.
