# E-commerce App - SMART SHOP
Smart Shop is a modern Flutter-based e-commerce app featuring product browsing, cart, and wishlist management.
It uses Provider for state management and integrates a RESTful API for real-time product data.
It also supports theme toggling, user authentication, and persistent login using SharedPreferences for a seamless shopping experience.

## Project Demo
Click the link to watch a short demo video of the Smart Shop app - https://drive.google.com/file/d/1QGO3MHBpnHQvjmJpMxZzcTUPdWeL3zqR/view?usp=sharing

## Features
1. **Login Screen :**
The Login Screen in Smart Shop provides a user-friendly interface with validated `TextFormField`s for email and password input. It uses `SharedPreferences` to securely store login status and navigate users directly to the home screen on successful login, enhancing the app's usability and persistence.
![WhatsApp Image 2025-07-20 at 22 35 42_5c756c98](https://github.com/user-attachments/assets/90bccf24-a6f7-42a2-b4bb-72afbc8f207f)

**Register Screen :**
The Register Screen in Smart Shop allows new users to create an account with validated name, email, and password fields. Upon successful registration, it saves the login state using `SharedPreferences` and seamlessly redirects users to the Home Screen for immediate access.
![WhatsApp Image 2025-07-20 at 22 35 42_3f921e38](https://github.com/user-attachments/assets/595ef047-0096-4d41-82d0-1afa58758692)

2. **Home Page :**
The Home Screen of Smart Shop showcases trending products, special discounts, and a dynamic product list fetched from the FakeStore API. It features a responsive layout with a navigation drawer, custom widgets like `ProductCard`, `DiscountCard`, and `TrendingCard`, providing users with an engaging shopping experience.
![WhatsApp Image 2025-07-20 at 22 36 19_e7b86ee1](https://github.com/user-attachments/assets/d28d819e-2e50-4ac3-b3d4-ea43b1b06895)
![WhatsApp Image 2025-07-20 at 22 36 21_808b37dc](https://github.com/user-attachments/assets/9b890edc-1b88-4786-89c0-f5d6cab7cf72)
![WhatsApp Image 2025-07-20 at 22 36 21_77384b39](https://github.com/user-attachments/assets/37467a88-f572-4d4f-bdaf-366bac927696)
![WhatsApp Image 2025-07-20 at 22 36 20_7e57622b](https://github.com/user-attachments/assets/307a97a0-87c2-4155-ab04-649352469d16)
![WhatsApp Image 2025-07-20 at 22 36 18_f0965408](https://github.com/user-attachments/assets/3ba7b1bf-cd03-4afe-ab18-bb09de59d3e7)
![WhatsApp Image 2025-07-20 at 22 36 20_12948ce4](https://github.com/user-attachments/assets/0e5a2598-ef70-4d1e-8063-af0b208d34d8)

3. **Cart Page :**
The Cart Page in Smart Shop displays all products added by the user for purchase, showing item details, quantity, and total cost. It allows users to review, remove items, and proceed to checkout, offering a smooth and interactive shopping experience.
![WhatsApp Image 2025-07-20 at 22 36 21_808b37dc](https://github.com/user-attachments/assets/5b3e8ad8-d2d8-4808-966a-87fa1aec34b5)

4. **Theme Switch :**
Dark Mode and Light Mode in Smart Shop enhance user experience by offering two visually distinct themes. Light Mode provides a bright, clean interface ideal for daytime use, while Dark Mode delivers a low-light friendly design that reduces eye strain—both seamlessly switchable using the built-in theme toggle feature.
Light Mode :
![WhatsApp Image 2025-07-20 at 22 36 21_77384b39](https://github.com/user-attachments/assets/3cbf857e-c574-4c44-a796-cc98a0b32d72)
Dark Mode :
![WhatsApp Image 2025-07-20 at 22 36 20_7e57622b](https://github.com/user-attachments/assets/2dc12fe0-df66-4a22-a210-62f8312912ed)

5.**Drawer Navigation :**
The Drawer Navigation in Smart Shop provides quick access to key sections like Home, Profile, Cart, Favourites, and Logout. It's implemented using a `DrawerWidget`, ensuring intuitive and smooth navigation throughout the app with just a swipe or tap.
![WhatsApp Image 2025-07-20 at 22 36 19_76977655](https://github.com/user-attachments/assets/0031b5f7-77f8-44af-a7bb-c58709b889bf)

6. **Logout :**
The **Logout** feature in Smart Shop securely signs the user out by clearing the saved login state from `SharedPreferences`. It then redirects the user back to the Login Screen, ensuring a clean session and protecting user data.
![WhatsApp Image 2025-07-20 at 22 36 22_df293e0b](https://github.com/user-attachments/assets/e9bbad7c-d6a0-43cb-ba6a-f791ad950975)
