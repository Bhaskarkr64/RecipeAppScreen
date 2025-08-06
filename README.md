
# 🍽️ Recipe App

An elegant and user-friendly Android Recipe App to browse, search, and view detailed cooking recipes. Built using Kotlin and Jetpack Compose, it offers a clean UI and seamless user experience.

## ✨ Features

- 🔍 Search recipes by name or category
- 📄 View detailed recipe instructions and ingredients
- 🖼️ Display recipe images
- 🧑‍🍳 Save favorite recipes locally
- 🌙 Light & Dark mode support

## 🚀 Tech Stack

- **Kotlin**
- **Jetpack Compose**
- **MVVM Architecture**
- **Retrofit (API calls)**
- **Coroutines & Flows**
- **Room Database (Favorites)**

## 🏗️ Project Structure

```

com.yourpackage.recipeapp
│
├── ui/               # Compose UI Screens
├── viewmodel/        # ViewModels handling UI logic
├── repository/       # Data fetching (API & Local DB)
├── model/            # Data Models
├── network/          # Retrofit API Service
└── MainActivity.kt   # Entry point

````

## 📲 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Bhaskarkr64/LocationApp.git
````

2. Open in **Android Studio**
3. If using a public API, no API key is needed. Else, add your **API Key** in `local.properties`:

   ```
   RECIPE_API_KEY=your_api_key_here
   ```
4. Run on a physical device or emulator.

## 🛡️ Permissions Required

* INTERNET
* ACCESS\_NETWORK\_STATE

## 📦 Future Enhancements

* Offline recipe caching
* User authentication for custom recipe uploads
* Advanced filters (e.g., Cuisine, Prep Time, Difficulty)
* Shopping list generator from ingredients

```


