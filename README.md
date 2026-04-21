🛍️ Uomo — React E-Commerce App
A fully functional fashion e-commerce web app built with React and Context API — one of my core personal portfolio projects. Uomo covers the complete shopping experience from browsing to cart management, with clean component architecture and global state handled entirely through React's built-in Context API.

🔗 Live Demo: https://gobikrishnan-33.github.io/uomo-ecommerce/


📸 Preview

<img width="1433" height="849" alt="Screenshot 2026-04-21 at 1 38 28 PM" src="https://github.com/user-attachments/assets/f1a32834-0be6-4e98-9290-4ca2bafa4ac1" />


🎯 About This Project
Uomo is a personal project built to strengthen my React skills and demonstrate real-world frontend development — component design, state management with Context API, routing, and responsive UI — without relying on any third-party state library.

🛠️ Tech Stack
TechnologyPurposeReact (CRA)UI framework and component architectureReact Context APIGlobal state — cart, wishlist, filtersReact RouterMulti-page navigation and routingCSS3Responsive styling and layoutJavaScript (ES6+)Logic, filtering, data handling

✨ Features

🗂️ Product Listing & Filtering — Browse products with dynamic filter controls (category, price, etc.)
📄 Product Detail Page — Individual product pages with image, description, and add-to-cart action
🛒 Shopping Cart — Add/remove items, update quantities, view cart total
❤️ Wishlist — Save favourite products and manage them separately
🌐 Multi-page Navigation — React Router for seamless page transitions
📱 Responsive Design — Works across desktop and mobile viewports


📂 Project Structure
uomo-ecommerce/
├── public/
├── src/
│   ├── components/       # Reusable UI components (Navbar, ProductCard, etc.)
│   ├── context/          # React Context — CartContext, WishlistContext
│   ├── pages/            # Page components (Home, Products, ProductDetail, Cart)
│   ├── data/             # Product data
│   └── App.js            # Root component with routing
├── package.json
└── README.md

🚀 Getting Started
View Live
👉 https://gobikrishnan-33.github.io/uomo-ecommerce/
Run Locally
bash# Clone the repository
git clone https://github.com/gobikrishnan-33/uomo-ecommerce.git

cd uomo-ecommerce

# Install dependencies
npm install

# Start the development server
npm start
Open http://localhost:3000 in your browser.

💡 Key Takeaways / What I Learned

Structuring a multi-page React app with React Router from scratch
Managing shared global state (cart + wishlist) cleanly using Context API
Building reusable components — product cards, filters, nav, cart drawer
Implementing dynamic filtering logic in React without external libraries
Deploying a React app to GitHub Pages with gh-pages


🗺️ Roadmap / Future Improvements

 Add Redux Toolkit for more scalable state management
 Integrate a real backend / mock API (JSON Server or Supabase)
 Add user authentication (login/signup)
 Add checkout flow with order summary
 Improve mobile UI and add skeleton loaders


👨‍💻 Author
Gobikrishnan M — Frontend Developer
📎 LinkedIn | 💻 GitHub

📄 License
This is a personal portfolio project. Feel free to explore the code for learning purposes.
