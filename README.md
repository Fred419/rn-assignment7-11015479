# rn-assignment7-11015479


React Native Shopping App

This is a React Native shopping app that showcases a product list and a shopping cart functionality. The app fetches product data from an API, displays products in a grid, and allows users to add products to their cart. The cart data is persisted using AsyncStorage.

Features
Home Screen: Displays a list of products fetched from the API.

Product Details Screen: Shows detailed information about a selected product.

Cart Screen: Displays the products added to the cart and allows users to remove items.

Persistent Cart: Uses AsyncStorage to persist cart data between app sessions.

Filter Menu: Allows users to filter products by category (sample filter categories included).

Navigation: Navigate between Home, Product Details, and Cart screens.

Design Choices
User Interface
Grid Layout: The Home screen uses a grid layout to display products, making efficient use of screen space and providing a visually appealing interface.

Product Cards: Each product is displayed as a card with an image, title, category, price, and description. The "Add to Cart" icon is prominently placed to facilitate easy addition to the cart.

Navigation Icons: Included navigation icons to allow users to move between screens easily.

Data Fetching
API Integration: Used axios to fetch product data from a sample API. This demonstrates how to integrate external data sources into the app.

Data Storage
AsyncStorage: Implemented AsyncStorage to persist cart data. This ensures that the cart contents are saved even if the app is closed or the device is restarted.

Implementation Details
Screens and Navigation
Home Screen: Displays a list of products in a grid. Each product can be clicked to navigate to the Product Details screen. A button to view the cart navigates to the Cart screen.
Product Details Screen: Shows detailed information about the selected product, including an option to add the product to the cart.
Cart Screen: Displays the items added to the cart, along with their details and the total price. Users can remove items from the cart.
Adding and Removing Items from Cart
Add to Cart: When a user clicks the "Add to Cart" icon on a product card or the "Add to Basket" button on the Product Details screen, the product is added to the cart. The cart is then saved to AsyncStorage.
Remove from Cart: Users can remove items from the cart by clicking the remove icon. The cart is updated and saved to AsyncStorage.
Persisting Cart Data
Loading Cart: When the app initializes, it loads the cart data from AsyncStorage to maintain the user's cart across sessions.
Saving Cart: Whenever the cart is updated (item added or removed), the new cart state is saved to AsyncStorage.


Conclusion:
This app provides a basic structure for a Shopping application with product listing, detailed product view, and cart functionality. It demonstrates how to fetch data from an API, manage state with React hooks, and persist data using AsyncStorage. The design focuses on a clean and intuitive user experience, with easy navigation and seamless cart management.

![WhatsApp Image 2024-07-12 at 22 13 37_80c613e7](https://github.com/user-attachments/assets/0f04df52-6106-4936-9a47-6d42ed7c6c4a)
![WhatsApp Image 2024-07-12 at 22 13 39_1980245e](https://github.com/user-attachments/assets/4b909c16-1cfe-430b-8556-228494d01a52)
![WhatsApp Image 2024-07-12 at 22 13 37_6dcd9b2d](https://github.com/user-attachments/assets/f52da808-76dd-44f4-8209-05d14b97bf83)
![WhatsApp Image 2024-07-12 at 22 13 37_8d2181ba](https://github.com/user-attachments/assets/f1a869df-3fdf-4c1d-84ad-368db3ff511d)
![WhatsApp Image 2024-07-12 at 22 13 38_5fd239cc](https://github.com/user-attachments/assets/a18fc479-1159-4eb4-a34c-994128138de9)
![WhatsApp Image 2024-07-12 at 22 13 38_ccee9bee](https://github.com/user-attachments/assets/7efe08ea-2667-473c-b24c-eb2b987e10d9)
![WhatsApp Image 2024-07-12 at 22 13 37_80c613e7](https://github.com/user-attachments/assets/38af52d7-d80c-4bb7-aa27-b35b48651a9c)
![WhatsApp Image 2024-07-12 at 22 13 39_9e1a995f](https://github.com/user-attachments/assets/7b7ec326-7412-40bb-b937-aa0160993c0c)












