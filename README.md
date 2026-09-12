# TechSwap Android App

* Developed TechSwap, an Android based student electronics marketplace using Kotlin, Java, XML, and Firebase to enable secure peer-to-peer buying and selling of electronics.
* Implemented role-based control (Buyer, Seller, Admin) with secure authentication, full listing management (CRUD), and admin moderation features.
* Designed and built core e-commerce functionality including product search, filtering, shopping cart, checkout, and order confirmation to support a complete user transaction flow.

# Documentation

While designing and developing TechSwap, we kept detailed documentation of the requirements of our app and how we planned to design it. Below is a summary of the key portions of our documentation:

1. **Problem TechSwap Solves** TechSwap is an Android based electronics marketplace designed for students who want to buy and sell new or pre-owned electronics. The application was created to provide a more organized and secure environment for student to student transactions and reduce problems such as scame, misleading listings, and unrelaible trading experiences.

2. **App Requirement and Technologies**
TechSwap was designed to support three main user roles: Buyer, Seller, and Admin. The system includes user authentication, role based access control, electronic listings, listing management, shopping cart functionality, checkout, and administrative moderation. The application was developed in Android Studion using Kotlin, Java, XML and Firebase service used for authentication and data storage.

3. **Features Implemented**
    1. `Login/Registration Page` - Allows users to create an account and security log in using their credentials. The application provides different access depending on whether the user is a Buyer, Seller, or Admin.
    2. `Electronics Listings Page` - Displays available electronics with information such as the product name, image, brand/model, price, condition, and availability. Users can select a product to view additional details.
    3. `Search Bar` - A search feature was designed to allow buyers to search for electronics by product name. However, the final version of the application did not fully complete the home-screen search functionality 
    4. `Filtering Feature` - Allows users to narrow the displayed listings by product category. 
    5. `Seller Listing Management` - Sellers can create new electronic listings and enter information such as the product name, price, condition, description, and images.  
    6. `Admin Dashboard` - Provides administrators with tools to review users and product listings. Admins can view pending, approved, and rejected items and mange the status of listings within the marketplace
    7. `Shopping Cart` - Allows buyers to add electronics to their cart, view selected items and prices, remove products, and proceed to checkout. 
    8. `Checkout/Payment` - Provides a mock checkout process where buyers can review their order and enter sample payment information. No real financial transitions are processed by TechSwap.
    9. `Order Confirmation` -  Displays information after a successful checkout, including the order confirmation number, purchased items, total amount, and an option to return to the home page.
    
4. **UML Diagrams**
We created several UML diagrams to visually represent the structure and flow of TechSwap and show how different parts of the application interact. These included diagrams for login and registration, seller listings, the listing lifecycle, search and filtering, admin interactions, shopping cart components and the checkout process.

These diagrams helped us plan how users, application components, and database operations would connect before and during development. 

5. **Test Cases**
We created test cases to verify that TechSwap's functionality met our system requirements and behaved as expected. testing covered registration, login, electronic listings, search/filtering, seller listing management, the admin dashboard, shopping cart, checkout/payment, and order confirmation. The tests included both valid scenarios and invalid/error scenarios to help identify problems with functionality and input validation.

6. **Application Screenshots**
Our documentation contains screenshots of the actual TechSwap application to demonstrate the user interface and the different features devloped. Screenshots include the splash screen, login and registration screens, home page, category filtering, item details, seller dashboard, create listing page, profile page, shopping cart, checkout, order confirmation, admin dashboard, and listing/user management screens.

7. **Code Snippets**
The documentation also includes slected source code snippets to demonstrate the logic behind important parts of the application. The included code focuses on the Login Activity, Seller Listings Activity, and Admin Activity, showing jow major application features were implemented and connected to the backend.

8. **Database**
TechSwap uses Firebase as its primary backend because it integrates well with Android applications, is relatively easy to manage, and provides services suitable for student projects.

We used Firebase Firestore for user information and Firebase Realtime Database for information such as product categories, listings, listing statuses, the admin key, and banner information. Product images themselves were stored using Cloudinary, while the Cloudinary image URLS were saved in Firebase Realtime Database. 

# **Hands-on Test**

Using the instructions below, you can test out this app yourself.

Check out the app by downloading "app-debug.apk" file under docs and run the app on Android Studio!
