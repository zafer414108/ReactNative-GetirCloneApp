# React Native Getir Clone App

It looks like you've set up a basic structure for your React Native app with navigation and Redux integration. Here are a few things to consider and potential improvements:

# Styles:

You have a styles object, but it's not currently being used. If you don't need it, you can remove it.
If you plan to use styles, make sure to apply them to your components as needed.
# NavigationContainer:

Make sure you have installed the react-navigation/native and react-navigation/stack packages if you're using Stack Navigator. If you're using a different navigator, adjust the import accordingly.
# Redux Integration:

Ensure that your Redux store (store) is configured correctly in the src/redux/store file.
Confirm that the Redux Provider is properly wrapping your application to provide the store to all components.
# LogBox:

Ignoring all logs might make debugging more challenging. Consider ignoring specific logs only when necessary. Ignoring all logs can hide potential issues.
# Component Naming:

Ensure that your RootNavigator component is correctly implemented and located in the specified path ('./src/navigators/RootNavigator').
# TypeScript Usage:

If you're using TypeScript (based on the JSX.Element type in the function signature), make sure you have TypeScript properly configured and use it consistently across your project.
Commented-out Code:

Remove any commented-out code that is not needed. It helps to keep your codebase clean and easy to understand.

# Screenn gif
![ezgif com-speed (3)](https://github.com/zafer414108/ReactNative-GetirCloneApp/assets/147662873/7b8823c5-f726-4afe-abf9-4038af83f59a)

