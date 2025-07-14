# Mama-Baby Store FE

Mama-Baby is an e-commerce platform specializing in high-quality nutritional milk products for pregnant mothers and babies. This project is the frontend, built with ReactJS, Material UI, Redux Toolkit, and other modern libraries.

## Introduction

Mama-Baby aims to support the health and nutrition of pregnant women, infants, and young children through premium milk products and dedicated customer care services.

### Mission

- Ensure the quality of milk products for mothers and babies.
- Provide nutritional consultation and customer support services.
- Deliver a convenient, safe, and fast shopping experience.

## Main Features

### For Customers (Member)

- Register, log in, and manage personal accounts.
- Browse, search, and filter products by age, brand, and category.
- Add products to cart, place orders, pay online (VNPay), and use vouchers.
- View order history, rate products, and collect points for gift redemption.
- Follow promotions and special offers.
- Register to open a store (upgrade to Staff).

### For Store Staff (Staff)

- Manage products, orders, exchanges/returns, vouchers, articles, and product packages.
- View dashboard with revenue, order, refund, and exchange statistics.
- Manage personal store information.

### For Administrators (Admin)

- Manage user accounts and approve store registration requests.
- Manage categories, brands, age groups, and product packages.
- Manage the store system and view overall system statistics.

## Technologies Used

- ReactJS 18
- Material UI 5
- Redux Toolkit
- React Router DOM
- Axios
- Chart.js, react-chartjs-2
- Bootstrap
- Socket.io-client
- VNPay payment integration

## Setup & Run

1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd Mama_Baby_Store_FE
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Start the application:**
   ```bash
   npm start
   ```
   The app will run at [http://localhost:3000](http://localhost:3000)

## Scripts

- `npm start`: Start development server
- `npm run build`: Build for production
- `npm test`: Run tests
- `npm run eject`: Eject CRA configuration

## Additional Information

- The project uses Create React App as the base.
- Connects to backend APIs via files in `src/api/`.
- State management with Redux Toolkit and redux-persist.
- Responsive UI, optimized for both desktop and mobile.

---

For questions or support, please contact the development team.
