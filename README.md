# rn-assignment2-11015431-1129884

Here's a README file for the provided React Native code snippet using Expo:

My React Native App
This is a simple React Native application built using Expo. The app displays a text message with the name "Emmanuel Akuffo" in a styled view. It also utilizes the StatusBar component from Expo to handle the status bar's appearance.

Table of Contents
Installation
Usage
Code Overview
Dependencies
License
Installation
To run this project on your local machine, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/my-react-native-app.git
cd my-react-native-app
Install the dependencies:
Make sure you have npm or yarn installed, then run:

bash
Copy code
npm install
# or
yarn install
Start the development server:

bash
Copy code
npm start
# or
yarn start
Usage
Once the development server is running, you can use the Expo Go app on your mobile device to scan the QR code displayed in the terminal or browser. This will open the app on your device for testing.

Alternatively, you can run the app on an Android or iOS emulator using:

bash
Copy code
npm run android
# or
npm run ios
Code Overview
App Component
The main component of the app is defined in App.js. Here is a brief overview of the code:

javascript
Copy code
import { StatusBar } from 'expo-status-bar';
import { StyleSheet, Text, View } from 'react-native';

export default function App() {
  return (
    <View style={styles.container}>
      <Text>My name is <b>Emmanuel Akuffo</b></Text>
      <StatusBar style="auto" />
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: 'blue',
    alignItems: 'center',
    justifyContent: 'center',
    fontSize: '24',
  },
});
Description of the Task
Import Statements:

StatusBar from expo-status-bar: Manages the status bar's style and appearance.
StyleSheet, Text, View from react-native: Core React Native components for styling and layout.
App Function:

Returns a View component styled using styles.container.
Displays a Text component with the message "My name is Emmanuel Akuffo".
Includes the StatusBar component to ensure the status bar adapts to the app's style.
Styles:

Defined using StyleSheet.create to manage the styles for the container. The container is set to take up the full screen (flex: 1), with a blue background color, centered content (alignItems and justifyContent), and a font size of 24.
Dependencies
expo
react-native
expo-status-bar
Ensure you have these dependencies installed in your project.
