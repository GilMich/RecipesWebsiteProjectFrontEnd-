# Recipes Website 🍲

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

**Recipes Website** is a Vue.js-based recipe platform where users can browse recipes, save favorites, and manage their accounts. The platform offers a modern, responsive interface, integrating external APIs to deliver fresh and dynamic content.

## 📸 Demo

![Alt text](./screenshots/main page user)
 <!-- Optional: Add images or GIFs to showcase the app -->

## 🚀 Features

- **Recipe Discovery:** Browse various recipes sourced from the Spoonacular API.
- **User Authentication:** Secure registration and login system for users to manage their favorite recipes.
- **Favorites System:** Users can save, view, and remove their favorite recipes.
- **Recipe Submission:** Contribute your own recipes through an intuitive modal form.
- **Responsive Design:** Fully responsive interface for desktop, tablet, and mobile devices.
- **Dark Mode:** Clean and visually appealing dark theme.

## 🛠️ Technologies Used

- **Vue.js 3** - Front-end framework for building user interfaces.
- **Vue Router** - For navigation between different app pages.
- **Axios** - To handle API requests for recipe data and user interactions.
- **BootstrapVue** - For responsive UI components.
- **Spoonacular API** - Used to fetch real-time recipe data.
- **LocalStorage** - To manage user session and preferences.

## 🔧 Installation and Setup

To run this project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/recipes-website-frontend.git
    cd recipes-website-frontend
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Create a `.env` file** with your Spoonacular API key:

    ```plaintext
    VUE_APP_SPOONACULAR_API_KEY=your_api_key
    ```

4. **Run the development server:**

    ```bash
    npm run serve
    ```

    The app will be available at `http://localhost:8080`.

## 📂 Project Structure

📦src ┣ 📂assets ┣ 📂components ┣ 📂pages ┣ 📂services ┗ 📂store


- `components/` - Reusable Vue components like `RecipePreview.vue` and `LoginPage.vue`.
- `pages/` - Main application pages like `HomePage.vue`, `FavoritesPage.vue`.
- `services/` - API interaction and business logic.
- `store/` - Vuex store for state management.

## 🌐 Live Demo

Check out the live demo: [Demo Link](https://your-demo-link.com)

## 📈 Future Improvements

- **Recipe Reviews**: Users can leave reviews and ratings on recipes.
- **Advanced Search**: Filters for dietary preferences such as gluten-free or vegan options.
- **User Profiles**: Users can personalize profiles with preferences and dietary restrictions.

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute, feel free to check out the [issues page](#).

---


