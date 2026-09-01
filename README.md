# fake-amazon-static
A lightweight, responsive e-commerce web interface designed to simulate dynamic product search and filtering using vanilla JavaScript. This is my first project implementing JavaScript arrays and objects to power a live, responsive search bar.

##  Key Features

* **Dynamic Client-Side Search:** Utilizes JavaScript array methods (`filter`, `map`, `includes`) to evaluate the product database in real time as you type.
* **Smart Filtering:** Accurately isolates matching items (e.g., typing `"socks"` narrows the catalog down to exclusively show sock products) while dynamically hiding non-relevant items off-screen.
* **Typo & Empty State Handling:** Gracefully handles typos or unmatched queries by instantly clearing the view or hiding products when no results match the input.
* **Array-Based Data Structure:** Stores and manages product attributes—such as titles, categories, pricing, and image paths—inside structured JavaScript objects and arrays.

##  Tech Stack

* **HTML5:** Semantic page layout and structure for product cards and search inputs.
* **CSS3:** Responsive styling replicating an e-commerce catalog grid and managing visibility states.
* **JavaScript (ES6+):** DOM manipulation, event listeners, string parsing, array iteration, and dynamic UI rendering.

##  Getting Started

To run this project locally, simply clone the repository and open `index.html` in your browser:

```bash
git clone [https://github.com/your-username/fake-amazon-static.git](https://github.com/your-username/fake-amazon-static.git)
cd fake-amazon-static
# Open index.html in your preferred browser
