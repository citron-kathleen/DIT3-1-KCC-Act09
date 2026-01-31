Project Overview

- This project is a Pure UI Chat Application inspired by the Omegle conversation interface. It demonstrates the transition from a Login screen to a dynamic Chat screen within a single Activity using Kotlin and XML.
- The project was specifically configured to resolve JVM Target compatibility issues to ensure a successful build on the current development environment.

Features
- Dual-Screen Toggle: Implements a seamless transition between the Login (Start Chatting) and Chat interfaces using view visibility management.

- Omegle-Inspired UI: Features a classic blue-and-white theme with distinct chat bubble styles.

- Dynamic Chat Bubbles: Includes left-aligned bubbles for the "Stranger" and right-aligned blue bubbles for "You" to simulate a real conversation.

- Interactive Messaging: A functional "Send" button that programmatically adds new text bubbles to the chat container.

Running the App

- Open the project in Android Studio.

- Select the appropriate Virtual Device (e.g., Medium Phone API 36).

- Click the Run button to compile and install the APK.

- Click "Start Chatting" to exit the Login screen and enter the Chat interface.

Chat Screen

- The Chat Screen consists of a Blue Header for branding, a ScrollView to handle multiple messages, and a Bottom Input Bar containing an EditText for typing and a Button for sending.

Sample Conversation

- Stranger: "oh cool! What games?"

- You: "mostly fps games and some rpgs"

- You: "oh awesome! what's your favorite?"

Notes
- The application currently manages chat data through Local UI state without a persistent backend.

The initial build failure caused by the JVM 21 error was resolved by downgrading the Kotlin target to 1.8 in the Gradle settings.

The previous "Network Explorer" placeholder was successfully replaced by the Chat UI after performing a "Clean and Rebuild" of the project.
