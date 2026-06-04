# Grindoku-WebApp-
This APP Is to Calculate the Productivity and Etc.>>>>>>>
React Context API is used to share global state like player XP, quests, and workouts across all screens without manual data passing—check out PlayerContext.tsx and WorkoutContext.tsx for details. AsyncStorage helps save data locally on devices when there's no inte rnet, acting as a simple key-value storage system for your phone.

In this setup, everything revolves around reusable components such as GlowCard, XPBar, and StatBar. Once y ou build them, you can use them anywhere in your project. Custom hooks like useColors(), usePlayer(), and useWorkout() provide neat ways to connect to shared logic from any screen, keeping things tidy and organized.

Expo APIs play a role too; for instance, expo-haptics Adds vibration on button taps while expo-linear-gradient offers cool background effects. The combo of expo-camera and react-native-webview enables an AI form check feature, making things more interactive and engaging.

For game design, constants in game.ts handle XP curves, rank thresholds, stat growth, and daily quest creation. It's mostly about setting up rules with numbers and logic. And speaking of tech, MediaPipe, Google’s open-source pose detection tool, works within a WebView to track skeletons in real-time, thanks to your device’s camera.

Stack-wise, we're talking TypeScript, React Native, Expo, AsyncStorage, and MediaPipe all working together.
