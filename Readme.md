# React Native - The Movie App

The movie app is a movie browsing app that builds completely on [**React Native**](https://reactnative.dev/) and [**Expo**](https://expo.io).

## Screenshot

![screenshots of the movie app](/screenshot/movie_ui_design.png)

## Dependencies

- [React Navigation](https://reactnavigation.org/)
- [Axios](https://axios-http.com/)
- [Expo App Loading](https://docs.expo.io/versions/latest/sdk/app-loading/)
- [Expo Font](https://docs.expo.io/versions/latest/sdk/font/)
- [Expo Status Bar](https://docs.expo.io/versions/latest/sdk/status-bar/)

## Setup instructions

### 1. Clone Repository

```sh
# Clone the movie app
git clone https://github.com/ameenfarook/the_movie_app.git
```

### 2. Install all dependencies

```sh
# navigate to app directory
cd the_movie_app

npm install
```

### 3. Configuration

Add TMDB API-KEY inside package.json / projectConfig.apiKey

```sh
# add tmdb api-key here
"projectConfig": {
    "apiKey": "<put the api key from tmdb here>"
  }
```

### 4. Start the app

```sh
# using expo-cli
expo start

# using npm
npm start
```

## Dependencies Installation Details:

This is a react native clone for movie app.

Library used in the application:
1. react-navigation/native : https://www.npmjs.com/package/@react-navigation/native
Installation Command : npm i @react-navigation/native
Description: React Native integration for React Navigation.

2. react-navigation/stack : https://www.npmjs.com/package/@react-navigation/stack
Installation Command : npm i @react-navigation/stack
Description: React Native integration for React Navigation.

3. expo-font : https://www.npmjs.com/package/expo-font
Installation Command : npm i expo-font
Description: Load fonts at runtime and use them in React Native components.

1. expo-app-loading : https://www.npmjs.com/package/expo-app-loading
Installation Command : npm i expo-app-loading
Description: expo-app-loading is deprecated in favor of expo-splash-screen: use SplashScreen.preventAutoHideAsync() and SplashScreen.hideAsync() instead. Learn more.
A React component that tells expo-splash-screen to remain visible if it is the first and only component rendered in your app. This can be useful while download and cache fonts, logos, icon images and other assets that you want to be sure the user has on their device for an optimal experience before rendering and they start using the app. You can alternatively use expo-splash-screen APIs directly - expo-app-loading just wraps them.

2. expo-linear-gradient : https://www.npmjs.com/package/expo-linear-gradient
Installation Command : npm i expo-linear-gradient
Description: Provides a React component that renders a gradient view.


14. react-native-gesture-handler : https://www.npmjs.com/package/react-native-gesture-handler
Installation Command : npm i react-native-gesture-handler
Description: Declarative API exposing platform native touch and gesture system to React Native.

15. react-native-screens : https://www.npmjs.com/package/react-native-screens
Installation Command : npm i react-native-screens
Description: This project aims to expose native navigation container components to React Native. It is not designed to be used as a standalone library but rather as a dependency of a full-featured navigation library.

13. Below library for running this project in web: 
npx expo install react-native-web@~0.18.9 react-dom@18.1.0 @expo/webpack-config@^0.17.2

    
// npm start -- --reset-cache

Note : Your project may not work correctly until you install the correct versions of the packages:
npx expo install react-native-reanimated@~2.12.0 react-native-safe-area-context@4.4.1    
npx expo install react-native-gesture-handler@~2.8.0 react-native-screens@~3.18.0




