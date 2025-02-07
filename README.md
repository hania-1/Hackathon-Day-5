# 🛒 E-Commerce Marketplace - Testing & Error Handling

## 📌 Overview
This project is an **E-Commerce Marketplace** with a focus on **error handling, fallback UI, and testing** to ensure a smooth user experience.

## ✅ Features Implemented
- **Error Handling & Fallback UI**
  - If user searches for a non-existent product → `No relevant product found`
  - If cart is empty → `Your cart is empty`
  - If wishlist is empty → `No product in wishlist`
  - If API request fails → Show error message instead of breaking the UI
- **Functional Testing**
  - Cypress & React Testing Library used for feature validation
- **Performance Optimization**
  - Lazy loading, optimized images, and Lighthouse testing
- **Cross-Browser Compatibility**
  - Tested on Chrome, Firefox, Edge, and Mobile Devices

## 📂 Folder Structure
/src /components - ProductList.jsx - Cart.jsx - Wishlist.jsx /tests - functionalTests.cy.js - errorHandling.test.js /public - images (optimized)

## 🛠 Installation & Running
```sh
git clone https://github.com/your-repo-name
cd your-project
npm install
npm run dev

🚀 Testing Guide
Run Cypress tests:
npx cypress open
Run Jest tests:
npm test

📝 Test Cases
Test Case ID	Scenario	Expected Result	Actual Result	Status
TC001	User searches for an unavailable product	"No relevant product found" message appears	✅ Works as expected	✅ Passed
TC002	Cart is empty	"Your cart is empty" message appears	✅ Works as expected	✅ Passed
TC003	Wishlist is empty	"No product in wishlist" message appears	✅ Works as expected	✅ Passed
TC004	Add product to cart	Product appears in cart	✅ Works as expected	✅ Passed
TC005	Remove product from cart	Cart updates correctly	✅ Works as expected	✅ Passed
TC006	API fails to fetch products	"Error loading products" message appears	✅ Works as expected	✅ Passed

📜 License
This project is licensed under the MIT License.
