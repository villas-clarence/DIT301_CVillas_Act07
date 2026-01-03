# AdvancedUINavApp

A social-style Android app demonstrating modular UI with Fragments, Bottom Navigation, and Tabbed Layout.

## Project Structure

### Fragments
- **HomeFragment**: Main home screen with welcome message
- **ProfileFragment**: Profile section with two tabs (Info and Gallery)
- **SettingsFragment**: Settings section with various options

### Features
- Bottom Navigation Bar for switching between fragments
- TabLayout in ProfileFragment with two tabs (Info and Gallery)
- Responsive design supporting both portrait and landscape orientations
- Adaptive UI using ConstraintLayout for larger screens (sw600dp)
- Material Design 3 components

## Building and Running

1. Open the project in Android Studio
2. Sync Gradle files
3. Run the app on an emulator or physical device

## Responsive Design

- **Portrait Mode**: Standard layout with bottom navigation
- **Landscape Mode**: Optimized layout for wider screens
- **Tablet (sw600dp)**: Larger padding and text for better readability

## Technologies Used

- Jetpack Compose for UI
- Fragment API for modular screens
- Material Design 3
- ConstraintLayout for adaptive layouts
- Kotlin

## Reflection

### What I Learned About Fragments and Navigation
- Fragments provide modular, reusable UI components
- BottomNavigationView enables seamless navigation between sections
- Fragment transactions manage the back stack automatically

### Adaptive UI Implementation
- Used ConstraintLayout with guidelines for responsive design
- Resource qualifiers (sw600dp) for tablet-specific layouts
- Configuration changes handled gracefully with savedInstanceState

### Challenges and Solutions
- **Challenge**: Combining Bottom Navigation with Tabs
  - **Solution**: Used nested fragments with proper lifecycle management
- **Challenge**: Screen orientation changes
  - **Solution**: Implemented proper state preservation and resource qualifiers
