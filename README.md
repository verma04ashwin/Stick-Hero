# Stick Hero Clone - JavaFX

This project is a clone of the popular mobile game **Stick Hero** built using **JavaFX** for the graphical user interface (GUI). The game involves helping a stick figure cross platforms by drawing bridges made of sticks. The length of the stick determines whether the stick figure successfully reaches the next platform. This README provides an overview of the project structure, libraries used, and how to run the game.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Game Instructions](#game-instructions)
- [Running the Game](#running-the-game)
- [Customization](#customization)
- [Credits](#credits)

## Project Overview

This game replicates the core mechanics of **Stick Hero** where the player must draw sticks of varying lengths to help the character jump between platforms. It uses **JavaFX** for the graphical interface and **XML Loader** for scene management.

## Features
- **Smooth Game Flow:** Players control the length of the stick to bridge the gaps between platforms.
- **Randomized Platforms:** Platform positions change dynamically, making each level unique.
- **Simple UI:** A straightforward, easy-to-use interface made with JavaFX.
- **Sound Effects:** Audio for stick drawing, jumping, and falling.
- **Game Over Screen:** Displays when the player fails to bridge a gap.
- **Progression:** Players level up as they successfully jump between more platforms.

## Technologies Used

- **JavaFX:** For creating the game UI, rendering graphics, and handling user input.
- **FXML (XML Loader):** For loading the game scenes and separating logic from UI design.
- **Java:** The core programming language used to implement the game's logic and functionality.

### JavaFX

**JavaFX** provides the foundation for the graphical user interface. It allows us to create windows, buttons, and other interactive elements. In this project, JavaFX is used for:
- Drawing the game elements (stick figure, platforms, and bridges).
- Handling animation and transitions (stick length change, platform movement).
- Managing the game scene (start screen, gameplay, game over screen).

### XML Loader (FXML)

**FXML** is used for defining the structure of the game's scenes. It separates the visual layout from the logic of the game, making it easier to manage complex scenes and UI elements.

The XML files define the layout of each screen (such as the start screen, gameplay screen, and game over screen), while the game logic (e.g., the movement of platforms, creation of sticks) is written in Java classes. The **FXMLLoader** class is used to load and display the scene defined in the XML files.

## Game Instructions

1. **Start the Game:** Upon launching the game, you'll be presented with a title screen. Click on "Start" to begin.
2. **Draw the Stick:** To bridge the gap between two platforms, click and drag the mouse to draw a stick. The length of the stick will determine the distance the character will travel.
3. **Cross the Platforms:** The stick figure will attempt to cross the platform. If the stick is too short or too long, the character will fall and the game will end.
4. **Game Over:** If you fail to make a successful jump, a "Game Over" screen will appear with the option to restart the game.
5. **Winning the Level:** Each successful jump will add to your score. When you reach a certain threshold, you level up.

## Running the Game

### Prerequisites

- **Java JDK:** You need Java 8 or higher to run the game.
- **JavaFX SDK:** Ensure you have the JavaFX SDK set up for your development environment (IDE or command line).

### Steps to Run

1. Clone or download the repository to your local machine.
2. Ensure you have **JavaFX** set up correctly in your IDE (e.g., IntelliJ IDEA, Eclipse).
3. Open the project folder in your IDE.
4. Build the project and run the `Main.java` class to start the game.

Alternatively, you can compile and run the project from the command line:

```bash
javac -cp "path_to_javafx_sdk/lib/*" -d bin src/*.java
java -cp "path_to_javafx_sdk/lib/*:bin" Main
```
## Customization

You can modify and extend the game by adding:

- **New levels:** Customize platform positions or add obstacles.
- **Different themes:** Change the background and stick figure design.
- **Additional sounds:** Add background music or different sound effects.

## Credits

- **JavaFX:** Provides the graphical interface for the game.
- **FXML:** Used to structure and load the UI elements.
- **OpenGameArt:** Some art assets used in the game are sourced from free resources.

