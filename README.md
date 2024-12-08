# ECommerce-site-with-java-Elementary--project
**ECommerce Site with Java (Elementary Project)**

This project implements a basic e-commerce platform using Java. The program simulates user interactions with an e-commerce system, including user registration, product browsing, cart management, and admin functionalities.

### Key Features:
1. **User Management**: 
   - Users can register as either regular users or admins. 
   - Each user has a username, password, and, for non-admin users, a cash balance.
   - The login system allows users to authenticate and access specific features based on their roles.

2. **Product Management**:
   - Admins can add, remove, and manage product stock.
   - Each product has a unique ID, name, price, and available stock, all stored in a product catalog.
   - Products are stored in a file (`products.dat`) and are persisted across sessions.

3. **Shopping Cart System**:
   - Regular users can browse the product catalog, add products to their cart, view their cart, and proceed to checkout.
   - The system checks the user’s available cash before completing the checkout process.
   - The shopping cart and product details are stored for each user to allow a smooth shopping experience.

4. **Admin Features**:
   - Admins have additional privileges like adding or removing products, and updating product stock.
   - Admin functionalities are accessible only to users registered as admins.

5. **Data Persistence**:
   - The system uses serialization to save user and product data into files (`users.dat` and `products.dat`). 
   - On startup, data is loaded back into the application, maintaining consistency across sessions.

6. **Cash Management**:
   - Regular users can deposit or withdraw cash from their accounts.
   - The system ensures users have enough cash to complete their purchases and automatically updates their balance after checkout.

This project demonstrates essential programming concepts such as object-oriented design, file handling, and serialization in Java, offering a simple yet functional e-commerce platform.
