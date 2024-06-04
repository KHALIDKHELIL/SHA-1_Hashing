SHA-1 Hash Calculator
Description

This project is a graphical user interface (GUI) application that calculates the SHA-1 hash for a given input string. The application is built using Java and Swing for the GUI components. It provides functionalities to compute, copy, and clear the SHA-1 hash, as well as a dark mode toggle for better user experience.
Features

    Input field: Allows users to input the string they want to hash.
    Hash button: Computes the SHA-1 hash of the input string.
    Copy button: Copies the computed SHA-1 hash to the clipboard.
    Clear button: Clears both the input field and the result area.
    Exit button: Closes the application.
    How It Works button: Displays a dialog explaining how the SHA-1 algorithm works and how to use the application.
    Dark Mode: Toggles between light and dark modes for the GUI.

Installation

To run this application, ensure you have Java Development Kit (JDK) installed on your system. You can download it from Oracle's official website.

    Clone this repository:

git clone https://github.com/yourusername/SHA1HashCalculator.git

Navigate to the project directory:

cd SHA1HashCalculator

Compile the Java files:

javac SHA1HashGUI.java

Run the application:

    java SHA1HashGUI

Usage

    Enter the text: Type or paste the text you want to hash into the input field.
    Hash the text: Click the "Hash" button to compute the SHA-1 hash of the input text.
    Copy the hash: Click the "Copy" button to copy the computed hash to your clipboard.
    Clear fields: Click the "Clear" button to clear both the input and result fields.
    Exit the application: Click the "Exit" button to close the application.
    How It Works: Click the "How It Works" button to learn more about the SHA-1 algorithm and the usage of the application.
    Toggle Dark Mode: Check or uncheck the "Dark Mode" checkbox to switch between dark and light themes.

Code Structure

    SHA1HashGUI: The main class that sets up the GUI and handles all user interactions.
    initialize(): Sets up the main frame and all the GUI components.
    createButton(): Helper method to create buttons with consistent styling and action listeners.
    calculateSHA1(): Computes the SHA-1 hash for a given input string.
    showHowItWorks(): Displays a dialog explaining the SHA-1 algorithm and how to use the application.
    showAlert(): Displays informational messages to the user.
    toggleDarkMode(): Toggles the application between dark and light modes.
    toggleComponentDarkMode(): Applies dark or light mode to all components recursively.

Screenshots

(Include screenshots of the application in light mode and dark mode here)
Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss any changes or enhancements.
License

This project is licensed under the MIT License. See the LICENSE file for more details.
Acknowledgements

    The SHA-1 hashing algorithm is implemented using the MessageDigest class from Java's java.security package.
    Swing framework is used for creating the GUI.
