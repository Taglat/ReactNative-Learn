1. Create your first app
npx create-expo-app . --template blank
npx expo install react-dom react-native-web @expo/metro-runtime
npx expo start

2. Build a screen
In this tutorial, learn how to use React Native components such as Image, Pressable, and Vector icons to build a screen.

npx expo install @expo/vector-icons

3. Use an image picker
In this tutorial, learn how to use Expo Image Picker.
npx expo install expo-image-picker

4. Create a modal
In this tutorial, learn how to create a modal from React Native to select an image.

5. Add gestures
npx expo install react-native-gesture-handler react-native-reanimated
https://docs.swmansion.com/react-native-gesture-handler/docs/gestures/tap-gesture

6. Take a screenshot
npx expo install react-native-view-shot expo-media-library
The react-native-view-shot and expo-media-library work only on Android and iOS, however, we'd like our app to work on the web as well.

7. Handle platform differences
npm install dom-to-image

8. Configure status bar, splash screen and app icon