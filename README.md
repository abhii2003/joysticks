# Joystick Controller HTML and JavaScript Readme

This repository contains an HTML and JavaScript implementation for creating virtual joysticks that can be used for various applications, such as gaming or remote control interfaces. The code is designed to allow users to interact with the virtual joysticks using both mouse and touch input.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Code Explanation](#code-explanation)
- [Contributing](#contributing)


## Introduction
The provided HTML and JavaScript code creates two virtual joysticks, each with its own X and Y value indicators. These joysticks are fully customizable in terms of appearance and can be integrated into web applications for various purposes.
There are two joysticks, one joystick does not reset on release while the other does.

## Features
- **Two Joysticks**: The code creates two virtual joysticks with distinct styles and behavior.
- **Mouse and Touch Interaction**: The joysticks can be interacted with using both mouse and touch input on mobile devices.
- **Dynamic Value Updates**: The X and Y values of each joystick are dynamically updated as the user drags the joystick's stick.
- **Customizable Styling**: The appearance of the joysticks can be easily customized by modifying the CSS styles.

## Usage
To use the virtual joysticks in your web application, follow these steps:

1. Copy the HTML code from the provided `index.html` file and paste it into your web page where you want the joysticks to appear.

2. Customize the styles of the joysticks by modifying the CSS styles defined in the `<style>` section of the HTML. You can change colors, sizes, and positions to match your design preferences.

3. The JavaScript code provided in the `<script>` section handles the functionality of the joysticks, including user interaction and value updates. You can leave this code as is or make adjustments as needed for your specific use case.

4. Add any additional logic to your web application that responds to the joystick values. You can access the X and Y values of each joystick by referencing the `positions` array in the JavaScript code.

5. Test your web application to ensure that the virtual joysticks work as expected on both desktop and mobile devices.

## Code Explanation
The JavaScript code provided in the `<script>` section of the HTML file is responsible for the behavior of the virtual joysticks. Here's a brief overview of the key functions and their roles:

- `initializeJoystick(index)`: Initializes each joystick element and sets up event listeners for mouse and touch interactions.

- `startDragging(event, stick, index)`: Handles the start of joystick dragging, marking it as active.

- `stopDragging(event, stick, index)`: Handles the end of joystick dragging, resetting the joystick position and updating values.

- `moveStick(event, stick, xValue, yValue, index)`: Updates the position of the joystick's stick and calculates X and Y values based on user input.

- `resetStickPosition(stick)`: Resets the joystick's stick to the center position.

- `updateValues(xValue, yValue, index)`: Updates the displayed X and Y values for each joystick.

Please refer to the comments in the code for more detailed explanations of each function.

## Contributing
Contributions to this codebase are welcome. If you have ideas for improvements or new features, please open an issue or submit a pull request.

