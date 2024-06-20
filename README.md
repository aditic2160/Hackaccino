# Hackaccino
markdownCopy# Interactive Solar System in A-Frame

This project is an interactive 3D solar system created using A-Frame. It allows users to explore a visually rich representation of our solar system in their web browser.

## Prerequisites

Before you begin, ensure you have met the following requirements:
* You have installed the latest version of [Node.js and npm](https://nodejs.org/en/download/)
* You have a Windows/Linux/Mac machine with a modern web browser installed (Chrome, Firefox, Safari, or Edge)

## Setting Up and Running the Project

To get this project running locally on your computer, follow these steps:

1. Download the project files:
   - Save the HTML file as `index.html` in a new folder on your computer.

2. Open a command prompt or terminal:
   - On Windows: Press `Win + R`, type `cmd`, and press Enter.
   - On Mac: Press `Cmd + Space`, type `Terminal`, and press Enter.
   - On Linux: Use your distribution's application menu to open a terminal.

3. Navigate to the project folder:
cd path/to/your/project/folder
CopyReplace `path/to/your/project/folder` with the actual path where you saved the `index.html` file.

4. Install a simple HTTP server:
npm install -g http-server
CopyThis command installs the `http-server` package globally on your system.

5. Start the server:
http-server
CopyThis command starts a local web server.

6. Open your web browser and go to:
http://localhost:8080
CopyYou should now see the interactive solar system in your browser!

## Using the Solar System

- Use your mouse to look around the scene.
- Use the WASD keys to move through the scene.
- Click on any planet or the Sun to see information about it.

## Troubleshooting

- If you see a blank screen or errors in the browser console, make sure all the files are in the correct location and that you're accessing the page through `http://localhost:8080` and not directly opening the HTML file.
- If you have issues installing `http-server`, make sure Node.js and npm are correctly installed and that you're running the command prompt or terminal with appropriate permissions.

## Additional Information

This project uses A-Frame version 1.2.0. For more information about A-Frame, visit [https://aframe.io/](https://aframe.io/).

Enjoy exploring the solar system!
