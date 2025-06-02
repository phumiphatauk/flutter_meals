# 🍳 Flutter Meals

A beautiful and feature-rich recipe app built with Flutter and Riverpod. Discover delicious meals, save your favorites, and filter recipes based on your dietary preferences!

## ✨ Features

- 🍽️ **Recipe Categories** - Browse 10 diverse meal categories with beautiful gradient cards
- ⭐ **Favorites System** - Save and manage your favorite recipes with animated toggles
- 🔍 **Smart Filtering** - Filter meals by dietary preferences (Gluten-free, Lactose-free, Vegetarian, Vegan)
- 📱 **Tab Navigation** - Easy switching between Categories and Favorites
- 🎨 **Beautiful UI** - Dark theme with custom colors and Google Fonts (Lato)
- ✨ **Smooth Animations** - Hero transitions, slide animations, and rotation effects
- 📖 **Detailed Recipes** - Complete ingredient lists and step-by-step cooking instructions
- 🎯 **Intuitive Design** - Card-based layout with meal complexity, duration, and affordability indicators
- 🌟 **Modern State Management** - Powered by Riverpod for reactive and scalable state management
- 📱 **Cross-Platform** - Runs seamlessly on iOS, Android, Web, macOS, Windows, and Linux

## 🗂️ Meal Categories

The app features 10 delicious categories, each with its unique color theme:

| Category | Color | Description |
|----------|-------|-------------|
| 🇮🇹 **Italian** | Purple | Classic Italian dishes |
| ⚡ **Quick & Easy** | Red | Fast meals for busy days |
| 🍔 **Hamburgers** | Orange | Delicious burger variations |
| 🇩🇪 **German** | Amber | Traditional German cuisine |
| 🥗 **Light & Lovely** | Blue | Healthy and light meals |
| 🌶️ **Exotic** | Green | International exotic flavors |
| 🥞 **Breakfast** | Light Blue | Morning meal favorites |
| 🥢 **Asian** | Light Green | Asian-inspired dishes |
| 🇫🇷 **French** | Pink | Elegant French cuisine |
| ☀️ **Summer** | Teal | Fresh summer recipes |

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (v3.8.0 or higher)
- Dart SDK (compatible with Flutter version)
- A device or emulator to run the app

### 📥 Installation

1. Clone this repository:
```bash
git clone https://github.com/phumiphatauk/flutter_meals.git
```

2. Navigate to the project directory:
```bash
cd flutter_meals
```

3. Install dependencies:
```bash
flutter pub get
```

4. Run the app:
```bash
flutter run
```

## 🎮 How to Use

### Browse Categories
1. **Explore Categories**: View 10 meal categories on the home screen
2. **Select Category**: Tap any category to see available meals
3. **View Meals**: Browse through filtered meals in a scrollable list

### Manage Favorites
1. **Add to Favorites**: Tap the star icon on any meal detail page
2. **View Favorites**: Use the bottom navigation to switch to the Favorites tab
3. **Remove Favorites**: Tap the star again to remove from favorites

### Apply Filters
1. **Open Drawer**: Tap the menu icon in the app bar
2. **Select Filters**: Choose "Filters" from the drawer menu
3. **Set Preferences**: Toggle dietary filters (Gluten-free, Lactose-free, Vegetarian, Vegan)
4. **Apply**: Filters automatically update available meals

### Recipe Details
1. **Select Meal**: Tap any meal card to view details
2. **View Ingredients**: See complete ingredient list
3. **Follow Steps**: Read step-by-step cooking instructions
4. **Check Info**: View duration, complexity, and affordability

## 📱 Supported Platforms

- ✅ Android
- ✅ iOS  
- ✅ Web
- ✅ Windows
- ✅ macOS
- ✅ Linux

## 📦 Dependencies

```yaml
dependencies:
  flutter: sdk
  cupertino_icons: ^1.0.8        # iOS-style icons
  google_fonts: ^6.2.1           # Beautiful typography (Lato font)
  transparent_image: ^2.0.1       # Smooth image loading
  flutter_riverpod: ^2.6.1       # Reactive state management

dev_dependencies:
  flutter_test: sdk
  flutter_lints: ^5.0.0          # Code quality and style linting
```

## 🏗️ Project Structure

```
lib/
├── main.dart                    # App entry point and theme configuration
├── data/
│   └── dummy_data.dart         # Sample categories and meals data
├── models/
│   ├── category.dart           # Category data model
│   └── meal.dart               # Meal data model with enums
├── providers/
│   ├── favorites_provider.dart # Favorites state management
│   ├── filters_provider.dart   # Filters state management
│   └── meals_provider.dart     # Meals data provider
├── screens/
│   ├── categories.dart         # Categories grid screen
│   ├── filters.dart            # Dietary filters screen
│   ├── meal_details.dart       # Recipe details screen
│   ├── meals.dart              # Meals list screen
│   └── tabs.dart               # Main tab navigation
└── widgets/
    ├── category_grid_item.dart  # Category card widget
    ├── main_drawer.dart         # Navigation drawer
    ├── meal_item.dart           # Meal card widget
    └── meal_item_trait.dart     # Meal info traits (duration, complexity)
```

## 🎨 Design Features

- **Dark Theme**: Elegant dark theme with warm brown/orange accent colors
- **Google Fonts**: Beautiful Lato typography throughout the app
- **Gradient Cards**: Eye-catching gradient backgrounds for categories
- **Hero Animations**: Smooth image transitions between screens
- **Card Design**: Material Design 3 cards with rounded corners and elevation
- **Color Coding**: Each category has its distinctive color
- **Responsive Layout**: Adapts to different screen sizes

## 🔧 Technical Features

- **Riverpod State Management**: Reactive and scalable state management
- **Provider Pattern**: Clean separation of business logic and UI
- **Hero Transitions**: Smooth navigation animations
- **Custom Animations**: Slide transitions and rotation effects
- **Enum-based Models**: Type-safe complexity and affordability levels
- **Filter Logic**: Efficient meal filtering based on dietary preferences
- **Tab Navigation**: Bottom navigation between Categories and Favorites
- **Drawer Navigation**: Side menu for accessing filters

## 🍽️ Sample Recipes

The app includes 10 diverse recipes such as:

- **Spaghetti with Tomato Sauce** - Quick Italian classic
- **Classic Hamburger** - American comfort food
- **Wiener Schnitzel** - Traditional German cuisine
- **Creamy Indian Chicken Curry** - Exotic Asian flavors
- **Chocolate Souffle** - Elegant French dessert
- **Pancakes** - Perfect breakfast option
- **Asparagus Salad** - Light and healthy choice

Each recipe includes:
- **Difficulty Level**: Simple, Challenging, or Hard
- **Affordability**: Affordable, Pricey, or Luxurious
- **Duration**: Cooking time in minutes
- **Dietary Info**: Gluten-free, Lactose-free, Vegetarian, Vegan flags
- **Ingredients**: Complete list with measurements
- **Instructions**: Step-by-step cooking guide

## 🎯 State Management

The app uses **Riverpod** for state management with three main providers:

- **`mealsProvider`**: Provides the list of available meals
- **`favoriteMealsProvider`**: Manages user's favorite meals
- **`filtersProvider`**: Handles dietary filter preferences
- **`filteredMealsProvider`**: Computed provider that filters meals based on active filters

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/phumiphatauk/flutter_meals/issues).

### How to Contribute
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🌟 Future Enhancements

- 🔍 **Search Functionality** - Search recipes by name or ingredients
- 📝 **Custom Recipes** - Allow users to add their own recipes
- ⏱️ **Cooking Timer** - Built-in timer for cooking steps
- 🛒 **Shopping List** - Generate shopping lists from recipes
- 👥 **User Profiles** - Personal recipe collections
- 📸 **Photo Upload** - Add custom recipe photos
- 🌐 **Recipe Sharing** - Share recipes with friends

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Flutter team for the amazing framework
- Riverpod team for excellent state management
- Google Fonts for beautiful typography
- Material Design for design principles
- Community contributors and recipe inspirations

## 📧 Contact

Project Link: [https://github.com/phumiphatauk/flutter_meals](https://github.com/phumiphatauk/flutter_meals)
