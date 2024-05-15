Product Management Application
Description
This Product Management Application is built using React, Ant Design, and JavaScript. It provides a user-friendly interface for managing products, including features for viewing, adding, editing, and deleting products. The application ensures data persistence using localStorage and provides a responsive design for optimal user experience across various devices.

Features
Product List Page:

Displays a list of products with details including category, name, description, and price.
Provides statistics on the total number of products and unique product categories.
Allows filtering of products based on name, description, and category.
Supports adding, editing, and deleting products.
Assigns different row colors for each product category for better visual distinction.
Add Product Page:

Dedicated form for adding new products with fields for category, name, description, and price.
Form validation to prevent incomplete submissions.
Automatically updates the product list upon successful addition.
Data Persistence:

Product data is stored in localStorage to ensure persistence across page refreshes.
Responsive Design:

Adapts well to different screen sizes, providing a seamless user experience on various devices.
Folder/File Structure
product-management/
├── src/ │ ├── components/ │ │ ├── ProductStatistics.js │ │ ├── ProductTable.js │ │ └── ProductTable.css │ ├── context/ │ │ └── ProductContext.js │ ├── pages/ │ │ ├── AddProduct.js │ │ ├── AddProduct.css │ │ ├── EditProductModal.js │ │ ├── EditProductModal.css │ │ ├── ProductListPage.js │ │ └── ProductListPage.css │ ├── App.js │ ├── App.css │ └── index.js ├── public/ │ ├── index.html │ └── ... ├── package.json ├── README.md └── ...

Libraries Used
React: JavaScript library for building user interfaces.
Ant Design: UI component library for React.
React Router: Library for routing in React applications.
localStorage: Browser's web storage to store data locally.
