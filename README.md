Hikari — Lighting Store
--
Hikari is a fictional online store for lamps and lighting products. It was developed as part of my Web Design and Development technician program at Da Vinci School.
The project focuses on structured business logic implementation, including conditional discount rules, installment calculations based on selected payment methods and persistent state management using LocalStorage. The architecture emphasizes separation of concerns, predictable state updates, and modular JavaScript design using ES6 classes.

Technologies Used
- HTML5 
- CSS3 
- JavaScript (ES6+) —  no frameworks or external libraries

How to Run Locally
No installation or dependencies needed. Just download the files and open index.html in your browser.

What I Learned
This project was a great exercise to solidify several JavaScript concepts:
- OOP with classes: modeled products and cart items using classes (Product, CartItem), which made the code much cleaner and easier to maintain.
- DOM manipulation: practiced creating, inserting and replacing elements dynamically without relying on any framework.
- LocalStorage persistence: implemented cart saving and recovery between sessions, including applied discount logic.
- Form validation: the checkout flow includes card number, CVV and expiry date validation using the browser's native API.
Native <dialog> element: used the built-in HTML element instead of recreating modals with divs, which simplified open/close handling significantly.


📁 Project Structure
hikari/
├── index.html
├── style.css
├── app.js
└── img/
    └── (product images)

Made with argentinian mate🧉 and way too many hours wondering why the cart wasn't updating.

NOTES: some variable names and comments in the code are in Spanish, as this project was built while studying in a Spanish-speaking environment. Product images were sourced from https://www.caprichotm.com for educational purposes only. This is a non-commercial practice project and is not affiliated with or endorsed by Capricho in any way.
