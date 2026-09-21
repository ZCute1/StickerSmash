# CS 262 Assignment 2: Sticker Smash

1. What does the Expo default template add to the minimal blank template (compared to assignment 1)?
Compared to Asignment 1, the Expo default template adds components, constants, hooks and assets/images/. This enables multiple screens and tab navigation.


2. How is the styling of the app widgets specified?
The styling of app widgets is specified by providing references to the images in the assets folder. We use `style` and `StyleSheet.create()` to do this.


3. What does Expo store in the app/ sub-directory?
Expo stores information about and configuration for the app's screens and navigation. For example, `index.tsx` is the home screen,  `about.tsx` is the about screen, `_layout.tsx` controls navigation and `+not-found.tsx` handles invalid routes.


4. What does Expo store in the components/ sub-directory?
Expo stores information about the ui in the components sub-directory. For example. `ThemedText` creates styled text, `ThemedView` creates themed containers, `AppTabs` is responsible for the bottom tab bar, and `button.tsx` allows us to configure buttons and touch gestures.

5. When we `npx expo install` the expo-image-picker, what files are changed in the application?
Running `npx expo install` to add the expo-image-picker, `package.json` and `package-lock.json` are modified to record the information about the installed version and dependencies.

## Screenshots of Sticker Smash Expo App
![Home Screen](assets/images/home.png)
![About Screen](assets/images/about.png)