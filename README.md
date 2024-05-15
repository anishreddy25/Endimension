# Product Management Application

## Description
This Product Management Application is built using React, Ant Design, and JavaScript. It provides a user-friendly interface for managing products, including features for viewing, adding, editing, and deleting products. The application ensures data persistence using `localStorage` and provides a responsive design for optimal user experience across various devices.

## Features
- **Product List Page**: 
  - Displays a list of products with details including category, name, description, and price.
  - Provides statistics on the total number of products and unique product categories.
  - Allows filtering of products based on name, description, and category.
  - Supports adding, editing, and deleting products.
  - Assigns different row colors for each product category for better visual distinction.

- **Add Product Page**: 
  - Dedicated form for adding new products with fields for category, name, description, and price.
  - Form validation to prevent incomplete submissions.
  - Automatically updates the product list upon successful addition.

- **Data Persistence**: 
  - Product data is stored in `localStorage` to ensure persistence across page refreshes.

- **Responsive Design**: 
  - Adapts well to different screen sizes, providing a seamless user experience on various devices.

## Folder/File Structure
### Components
- **ProductForm.js**: Component for adding and editing products.
- **ProductList.js**: Component for displaying the list of products with filtering options.
- **CustomButton.js**: Custom styled button using Ant Design.

### Contexts
- **ProductContext.js**: Context for managing product state (add, edit, delete).

### Styles
- **index.less**: Main stylesheet for the application.
- **CustomButton.less**: Custom styles for the button component.



## Libraries Used
- [React](https://reactjs.org/)
- [Ant Design](https://ant.design/)
- [Less](http://lesscss.org/)
- [craco](https://github.com/gsoft-inc/craco) for customizing Create React App configuration

## Installation and Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/anishreddy25/Endimension.git
2. Install the dependencies:
    sh
    npm install
3. Start the development server:
    sh
    npm start   
4. Open your browser and navigate to:
    arduino
    http://localhost:3000     

## Usage
 -> Navigate to the Product List page to view and manage products.
 -> Click on "Add Product" to add a new product.
 -> Use the edit button in the product table to update product details.
 -> Use the delete button in the product table to remove a product.
 -> The product list is automatically updated and persisted in localStorage.
