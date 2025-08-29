# Niyantran Coffee - Git Readme

This project contains a fully client-side mock coffee website built with Tailwind CSS. It includes: Home, About, Menu, Cart (Chart), Checkout (with Juspay mock API), and Contact pages.

Key features implemented:
- Full-width, responsive layout using Tailwind CSS classes (no fixed-width containers).
- Menu with default items and image placeholders using the required src syntax.
- About page with founders GSR and MBR.
- Cart functionality stored in localStorage with a live cart count badge in the header.
- Checkout page with a Juspay mock API flow (no real charges).
- All pages are linked with relative paths.
- Image containers have defined sizes with overflow-hidden; all images use w-full h-full object-cover.
- INR currency formatting.

How to run locally:
1) Save all .html files in the same folder.
2) Open index.html in a browser.
3) Navigate to Menu, add items to cart, view Cart, then go to Checkout to simulate payment via Juspay mock API.

Notes:
- This is a frontend mock for demonstration only. No real payments are processed.
- You can customize menu items by editing the content in menu.html or the index homepage teaser.
