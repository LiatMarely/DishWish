## DishWish - Android App 🍽️  

Welcome to **DishWish**, an intuitive Android application that allows you to organize, store, and explore your favorite recipes efficiently. Manage recipes, upload images, generate grocery lists, and mark recipes as favorites using Firebase and Cloudinary for seamless data management and image hosting.

### 🌟 Features  

✅ **Recipe Storage** – Upload and categorize recipes conveniently with Firebase Realtime Database.  
📷 **Image Upload** – Upload and store recipe images using Cloudinary for smooth image hosting.  
🛒 **Structured Grocery List** – Generate a grocery list based on recipe ingredients with an option to add personal items.  
⭐ **Favorites List** – Save and retrieve your favorite recipes efficiently using their unique Firebase IDs.  
🔍 **Ingredient-Based Recipe Search** – Search recipes by ingredients and categories.  
👤 **User Profile Management** – Update user profile details, including profile picture storage via Firebase Storage.  
🔥 **Firebase Authentication** – Secure user authentication for account management.  

### 🚀 App Flow & Key Screens  

1️⃣ **Login Page** – Allows users to sign in with existing credentials. If the user is new, they can easily register using the "Register" button.  
![image](https://github.com/user-attachments/assets/598c5521-1d68-4f4c-964c-81d3009cb88b)

2️⃣ **Home Page** – Displays existing recipes, including a section for popular recipes.  
![image](https://github.com/user-attachments/assets/83d290d3-a902-4959-b680-58129e555b60)

3️⃣ **Favorite Recipes from the Web** – Users can save their favorite recipes from the internet by adding the recipe name and website URL. 
![image](https://github.com/user-attachments/assets/4a01b62f-4219-41c7-9f0c-9a4c818bc943)

4️⃣ **Add a Recipe** – Users can add new recipes to their saved collection by entering relevant details.
![image](https://github.com/user-attachments/assets/abb04d3f-9703-46ac-bef7-fe3cdecf7e7d)



https://github.com/user-attachments/assets/71a2da4c-1d14-431b-b061-248181e2650a



### 🎯 System Goals  

1️⃣ **Efficient Recipe Management** – Easily search, filter, and manage your recipes with real-time updates.  
2️⃣ **Enhanced User Experience** – A clean and interactive UI for seamless navigation.  
3️⃣ **Seamless Firebase Integration** – Use Firebase Realtime Database for storing user recipes, Firebase Authentication for secure login, and Firebase Storage for profile images.  
4️⃣ **Cloudinary Image Hosting** – Store high-quality recipe images in the cloud for fast retrieval and display.  

### 🛠️ Technologies Used  

- **Java** – For backend logic and app functionality.  
- **XML** – For designing the user interface.  
- **Firebase** – Authentication, Realtime Database, and Cloud Storage.  
- **Cloudinary** – Efficient image hosting and retrieval.  
- **Glide** – For smooth image loading.  
- **RecyclerView & Adapter** – For optimized display of recipe lists.  

### 💡 Getting Started  

To get started with **DishWish**, follow these steps:

1. **Clone the repository**
2. 
   ```bash
   git clone [<YOUR_GITHUB_REPO_URL>](https://github.com/assafmilner/DishWish)
   ```

3. **Open the project in Android Studio**

4. **Set up Firebase**  
   - Create a Firebase Project in the Firebase Console.  
   - Enable Firebase Authentication for user login.  
   - Set up Firebase Realtime Database and import the required structure.  
   - Enable Firebase Storage for user profile images.  

5. **Configure Cloudinary**  
   - Create a Cloudinary account and retrieve your **Cloud Name** and **Upload Preset**.  
   - Update `CLOUDINARY_CLOUD_NAME` and `CLOUDINARY_UPLOAD_PRESET` in `AddRecipeActivity.java`.  

6. **Build and run the application**  

### 🤝 Contributing  

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.  
2. Create a new branch:  
   ```bash
   git checkout -b feature/your-feature-name
   ```  
3. Make your changes.  
4. Commit your changes:  
   ```bash
   git commit -am 'Add feature'
   ```  
5. Push your branch:  
   ```bash
   git push origin feature/your-feature-name
   ```  
6. Open a Pull Request.  

### 📜 License  

This project is licensed under the [MIT License](LICENSE).

### 🎉 Final Words  

🚀 Enjoy exploring and managing your recipes with **DishWish**!  
If you have any questions or suggestions, feel free to open an issue or contact the project maintainer.
